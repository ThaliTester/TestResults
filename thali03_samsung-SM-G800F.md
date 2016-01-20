#### Test 564496606be5677_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,E/Watchdog( 2421): !@Sync 9
V/AlarmManager( 2421): waitForAlarm result :8
V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/AndroidRuntime( 7304): 
D/AndroidRuntime( 7304): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7304): CheckJNI is OFF
D/AndroidRuntime( 7304): setted country_code = Poland
D/AndroidRuntime( 7304): setted countryiso_code = PL
D/AndroidRuntime( 7304): setted sales_code = PLS
D/AndroidRuntime( 7304): readGMSProperty: start
D/AndroidRuntime( 7304): readGMSProperty: already setted!!
D/AndroidRuntime( 7304): readGMSProperty: end
D/AndroidRuntime( 7304): addProductProperty: start
D/dalvikvm( 7304): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7304): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7304): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7304): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7304): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7304): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7304): failed to load memtrack module: -2
D/dalvikvm( 7304): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7304): Calling main entry com.android.commands.am.Am
D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SELinux ( 7331): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7331):  
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7304): Shutting down VM
D/dalvikvm( 7304): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7331): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7331):  
I/SELinux ( 7331):  
I/SELinux ( 7331): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7331): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7331): >>>>> Normal User
E/dalvikvm( 7331): >>>>> com.test.thalitest [ userId:0 | appId:10641 ]
E/SELinux ( 7331): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7331): in addTimaSignatureService
D/TimaKeyStoreProvider( 7331): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7331): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4170): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4170): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7331): GC_CONCURRENT freed 2996K, 30% free 9572K/13568K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7331): Binding Chromium to the background looper Looper (main, tid 1) {4224d3e0}
I/chromium( 7331): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7331): Initializing chromium process, renderers=0
W/chromium( 7331): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7331): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7331): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7331): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7331): Mali API Version : 401
I/Mali    ( 7331): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 7331): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7331): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7331): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7331): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x0008
D/StatusBarManagerService( 2421): tr p:7331,o:f
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
W/dalvikvm( 7331): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7331): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7331): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7331): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7331): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7331): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7331): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7331): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7331): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7331): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7331): CordovaWebView is running on device made by: samsung
D/StatusBarManagerService( 2421): semi p:7331,o:f
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7331): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7331): Enabling debug mode 0
W/AwContents( 7331): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/AwContents( 7331): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 7331): showStatusIcon on inactive InputConnection
D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
D/JsMessageQueue( 7331): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7331): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42245978
D/dalvikvm( 7331): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42245978
D/jxcore_app_log( 7331): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2031444736
I/chromium( 7331): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 7331): GC_CONCURRENT freed 1303K, 17% free 11343K/13640K, paused 2ms+2ms, total 26ms
D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 7331): GC_CONCURRENT freed 1720K, 16% free 15140K/17880K, paused 1ms+3ms, total 42ms
D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7331): GC_FOR_ALLOC freed 5745K, 29% free 16766K/23544K, paused 49ms, total 49ms
,D/dalvikvm( 7331): GC_CONCURRENT freed 6775K, 31% free 18146K/25952K, paused 2ms+12ms, total 78ms
,D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 59ms
,D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 63ms
,D/dalvikvm( 7331): GC_FOR_ALLOC freed 1030K, 31% free 17991K/25952K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7331): Grow heap (frag case) to 22.056MB for 3688532-byte allocation
,D/dalvikvm( 7331): GC_FOR_ALLOC freed 2439K, 36% free 19154K/29556K, paused 54ms, total 54ms
,W/jxcore-log( 7331): Initializing JXcore engine
,W/jxcore-log( 7331): JXcore engine is ready
,W/jxcore-log( 7331): Starting JXcore engine
,W/jxcore-log( 7331): Platform android
W/jxcore-log( 7331): 
,W/jxcore-log( 7331): Process ARCH arm
W/jxcore-log( 7331): 
,I/PowerManagerService( 2421): [PWL] Off : 225s ago
,I/jxcore-log( 7331): JXcore Cordova bridge is ready!
I/jxcore-log( 7331): 
,W/jxcore-log( 7331): JXcore engine is started
,I/jxcore-log( 7331): Toggling radios to true
I/jxcore-log( 7331): 
,D/BluetoothAdapter( 7331): enable(): BT is already enabled..!
,I/WifiManager( 7331): packageName : com.test.thalitest
,I/WifiManager( 7331): setWifiEnabled : true
,I/WifiService( 2421): setWifiEnabled: true pid=7331, uid=10641
,W/WifiService( 2421): Failed getting userId using ActivityManagerNative
W/WifiService( 2421): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7331, uid=10641 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2421): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager( 2421): Permission Denial: getCurrentUser() from pid=7331, uid=10641 requires android.permission.INTERACT_ACROSS_USERS
I/WifiService( 2421): disconnect: pid=7331, uid=10641
I/jxcore-log( 7331): Radios toggled
I/jxcore-log( 7331): 
I/wpa_supplicant( 3976): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7331): My device name is: samsung-SM-G800F
I/jxcore-log( 7331): 
,I/wpa_supplicant( 3976): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3976): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3976): First Scan Start
W/Settings( 2421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3976): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2421): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/ConnectivityService( 2421): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2421): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2421): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2421): net.tcp.delack.default not found in system default properties
I/wpa_supplicant( 3976): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3976): Skip scan - already scanning
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2421): Attempting to switch to mobile
D/ConnectivityService( 2421): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7379):  
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2421): route cmd failed: 
W/NetworkManagementService( 2421): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2421): '
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2421): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2421): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
E/WifiStateMachine( 2421): Error! unhandled message{ when=-79ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2421): Error! unhandled message{ when=-78ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,I/SELinux ( 7379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7379):  
I/SELinux ( 7379):  
I/SELinux ( 7379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7379): >>>>> Normal User
,E/dalvikvm( 7379): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-16ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7379): in addTimaSignatureService
,D/NetUtils( 2421): android_net_utils_resetConnections in env=0x78704948 clazz=0x62300001 iface=wlan0 mask=0x3
,D/TimaKeyStoreProvider( 7379): Cannot add TimaSignature Service, License check Failed
,D/ConnectivityService( 2421): resetConnections(wlan0, 3)
D/ActivityThread( 7379): Added TimaKesytore provider
,V/NativeCrypto( 2851): Read error: ssl=0x7460b278: I/O error during system call, Connection timed out
,V/NativeCrypto( 2851): SSL shutdown failed: ssl=0x7460b278: I/O error during system call, Broken pipe
,D/dalvikvm( 7379): GC_CONCURRENT freed 2993K, 30% free 9576K/13568K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 7379): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 7379): WAIT_FOR_CONCURRENT_GC blocked 1ms
,E/SPPClientService( 5559): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5559): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5559): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5559): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5559): [b] ResponseMap empty
,I/System.out( 7379): Inside WakeupProvider
,I/System.out( 7379): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2421): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): updateIfacesLocked()
V/NetworkStats( 2421): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7379): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7379): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7379): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 32ms
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2830): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2421): Killing 6189:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7379): initQueue()
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2830): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2421): updateDataUsageMap
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2421): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6640): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6640): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6640): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6640): noConnectivity : true
,I/DBG_DM  ( 4754): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7408): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7408):  
,I/SELinux ( 7408): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7408):  
I/SELinux ( 7408):  
,I/SELinux ( 7408): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7408): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7408): >>>>> Normal User
,E/dalvikvm( 7408): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7408): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/wpa_supplicant( 3976): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 3976): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/TimaKeyStoreProvider( 7408): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7408): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7408): Added TimaKesytore provider
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3976): Associated with C0.AA.48
I/wpa_supplicant( 3976): freq(2412) increment count 2
,I/wpa_supplicant( 3976): meet head of list.
,D/dalvikvm( 7408): GC_CONCURRENT freed 2997K, 30% free 9570K/13564K, paused 5ms+1ms, total 31ms
,D/dalvikvm( 7408): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3976): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3976): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2421): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2421): Killing 6258:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
,D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,I/SELinux ( 7422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7422):  
,I/SELinux ( 7422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7422):  
I/SELinux ( 7422):  
,I/SELinux ( 7422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7422): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7422): >>>>> Normal User
,E/dalvikvm( 7422): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7422): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7422): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7422): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7422): Added TimaKesytore provider
,D/dalvikvm( 7422): GC_CONCURRENT freed 3001K, 30% free 9568K/13564K, paused 3ms+1ms, total 69ms
,D/dalvikvm( 7422): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dhcpcd  ( 7434): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7434): bssid match
,I/ActivityManager( 2421): Killing 6342:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7441): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7441):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 10% free 9505K/10548K, paused 2ms+3ms, total 29ms
,I/SELinux ( 7441): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7441):  
I/SELinux ( 7441):  
,I/SELinux ( 7441): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7441): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7441): >>>>> Normal User
,E/dalvikvm( 7441): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7441): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9505K/10548K, paused 2ms+3ms, total 27ms
,D/TimaKeyStoreProvider( 7441): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7441): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7441): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9505K/10548K, paused 2ms+3ms, total 26ms
,D/dalvikvm( 7441): GC_CONCURRENT freed 2998K, 30% free 9575K/13572K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7441): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/KLMS-2.3.201 : ( 7441): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7441): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453288747957
,I/KLMS-2.3.201 : ( 7441): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2421): Killing 6362:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7453): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7453):  
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7453): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7453):  
I/SELinux ( 7453):  
,I/SELinux ( 7453): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7453): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7453): >>>>> Normal User
,E/dalvikvm( 7453): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7453): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7453): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7453): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7453): Added TimaKesytore provider
,D/dalvikvm( 7453): GC_CONCURRENT freed 3008K, 30% free 9568K/13572K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7453): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/SO_AGENT( 7453): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7453): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5825): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5825): [BDLM] already registered in spp
,I/SA      ( 5825): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5825): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5825): [OR] == isSIMCardReady false ==
,I/SA      ( 5825): [SCU] == networkStateCheck == false
,I/SA      ( 5825): [OR] onReceive END
I/ActivityManager( 2421): Killing 6401:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7465): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7465):  
,I/SELinux ( 7465): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7465):  
I/SELinux ( 7465):  
,I/SELinux ( 7465): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7465): >>>>> Normal User
,E/dalvikvm( 7465): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7465): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7465): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7465): Added TimaKesytore provider
,D/dalvikvm( 7465): GC_CONCURRENT freed 2994K, 30% free 9573K/13564K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/sCloudBackupApp( 7465): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7465): Other Intent
I/ActivityManager( 2421): Killing 5610:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7478):  
,I/SELinux ( 7478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7478):  
I/SELinux ( 7478):  
,I/SELinux ( 7478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7478): >>>>> Normal User
,E/dalvikvm( 7478): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7478): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7478): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7478): Added TimaKesytore provider
,D/dalvikvm( 7478): GC_CONCURRENT freed 2998K, 30% free 9573K/13568K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7478): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7478): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/com.samsung.app( 7478): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5361): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7478): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5361): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7478): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5361): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2421): Killing 6314:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5888): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5888): getCountryCode(): countryCode = PL
,D/Headlines( 5888): Breath.onCreate
,D/Headlines( 5888): Breath timer started. interval : 30000
,I/SELinux ( 7490): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7490):  
,V/AlarmManager( 2421): waitForAlarm result :8
D/Headlines( 5888): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5888): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5888): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5888): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5888): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5888): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5888): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7490): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7490):  
I/SELinux ( 7490):  
,I/SELinux ( 7490): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7490): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7490): >>>>> Normal User
,E/dalvikvm( 7490): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7490): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7490): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7490): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7490): Added TimaKesytore provider
,D/dalvikvm( 7490): GC_CONCURRENT freed 2995K, 30% free 9575K/13568K, paused 5ms+3ms, total 40ms
,D/dalvikvm( 7490): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,V/WebViewChromium( 7490): Binding Chromium to the background looper Looper (main, tid 1) {4224a1d0}
I/chromium( 7490): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7490): Initializing chromium process, renderers=0
,W/chromium( 7490): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7490): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7490): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7490): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7490): Mali API Version : 401
,I/Mali    ( 7490): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7490): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7490): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
,D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2421): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/NSApplication( 7490): Starting up...
,D/WifiStateMachine( 2421): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2421): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,D/ConnectivityService( 2421): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2421): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2421): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/ConnectivityService( 2421): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2421): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2421): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,I/iu.Environment( 5956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5163): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42259c48
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SELinux ( 7561): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7561):  
V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/SELinux ( 7561): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7561):  
I/SELinux ( 7561):  
,I/SELinux ( 7561): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7561): >>>>> Normal User
,E/dalvikvm( 7561): >>>>> com.android.email [ userId:0 | appId:10157 ]
V/NetworkStats( 2421): updateIfacesLocked()
,V/NetworkStats( 2421): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
E/SELinux ( 7561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 28ms
,D/TimaKeyStoreProvider( 7561): in addTimaSignatureService
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7561): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7561): Added TimaKesytore provider
,D/dalvikvm( 7561): GC_CONCURRENT freed 2988K, 30% free 9588K/13572K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 7561): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/SELinux ( 7584): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7584):  
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/SELinux ( 7584): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7584):  
I/SELinux ( 7584):  
,I/SELinux ( 7584): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7584): >>>>> Normal User
E/dalvikvm( 7584): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2421): Killing 6338:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7584): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7584): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7584): Added TimaKesytore provider
,I/SELinux ( 7597): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7597):  
,I/ActivityManager( 2421): Killing 6001:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7597): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7597):  
I/SELinux ( 7597):  
,I/SELinux ( 7597): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7597): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7597): >>>>> Normal User
,E/dalvikvm( 7597): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7597): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2421): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/dalvikvm( 7584): GC_CONCURRENT freed 3002K, 30% free 9568K/13568K, paused 4ms+2ms, total 28ms
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/TimaKeyStoreProvider( 7597): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7597): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7597): Added TimaKesytore provider
,D/BadgeProvider( 7584): onCreate
,D/BadgeProvider( 7584): DatabaseHelper
,I/DBG_DM  ( 4754): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/BadgeProvider( 7584): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7584): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7584): sendNotify, [notify] : null
D/BadgeProvider( 7584): update, [uri] : content://com.sec.badge/apps/1
,D/Launcher.Model( 2779): reloadBadges entered.
D/BadgeProvider( 7584): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7584): update, [UpdateCount] : 1
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7597): GC_CONCURRENT freed 3006K, 30% free 9568K/13572K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7597): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
E/SPPClientService( 5559): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5559): [SystemStateMoniter] Current Time : 298549
,E/SPPClientService( 5559): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5559): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5559): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5559): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5888): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5888): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5888): Breath 1780 latestRequest time : 1453288748690 current time : 1453288750470
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5559): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5559): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5559): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5559): [a] [ConnectionManager] Connection is already disconnected.
D/PowerManagerService( 2421): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5559): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6640): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6640): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6640): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 7441): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7441): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453288750822
,I/KLMS-2.3.201 : ( 7441): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7453): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3432): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3432): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7453): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3432): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3432): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7620): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7620):  
D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 20
,I/GallerySearchProvider( 3561): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,W/WifiP2pStateTracker( 2421): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2421): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2421):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2421): updateSourceRoutes : no source routing conditions
,I/SELinux ( 7620): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7620):  
I/SELinux ( 7620):  
,I/SELinux ( 7620): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7620): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7620): >>>>> Normal User
,E/dalvikvm( 7620): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7620): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7620): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7620): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7620): Added TimaKesytore provider
,I/dalvikvm( 7422): Total arena pages for JIT: 11
,I/dalvikvm( 7422): Total arena pages for JIT: 12
I/dalvikvm( 7422): Total arena pages for JIT: 13
I/dalvikvm( 7422): Total arena pages for JIT: 14
I/dalvikvm( 7422): Total arena pages for JIT: 15
,I/dalvikvm( 7422): Total arena pages for JIT: 16
,I/dalvikvm( 7422): Total arena pages for JIT: 17
,D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/dalvikvm( 7620): GC_CONCURRENT freed 2912K, 29% free 9569K/13460K, paused 2ms+1ms, total 21ms
,I/SA      ( 5825): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5825): [BDLM] already registered in spp
I/SA      ( 5825): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5825): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5825): [OR] == isSIMCardReady false ==
,I/SA      ( 5825): [SCU] == networkStateCheck == true
,I/SA      ( 5825): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5825): isChinaCountryCode : false
,I/SA      ( 5825): [OR] == networkStateCheck true ==
,I/SA      ( 5825): [OR] GetMyCountryZoneTask
,I/SA      ( 5825): [OR] onReceive END
,I/SA      ( 5825): [SRS] prepareGetMyCountryZone
,I/SA      ( 5825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5825): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7465): Other Intent
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7478): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/dalvikvm( 2421): GC_EXPLICIT freed 3913K, 72% free 25370K/89532K, paused 15ms+21ms, total 279ms
,I/SA      ( 5825): [TPMU] GetMccFromDB : null
I/SA      ( 5825): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5825): [TPM] isNoProxy(default) : true
,I/SA      ( 5825): [RC New] Execute method=[GET] start
,D/Headlines( 5888): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5888): getCountryCode(): countryCode = PL
,D/Headlines( 5888): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5888): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5888): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5888): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5888): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5888): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5888): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7638): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7638):  
,I/System.out( 7422): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/SELinux ( 7638): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7638):  
I/SELinux ( 7638):  
,I/SELinux ( 7638): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7638): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7638): >>>>> Normal User
,E/dalvikvm( 7638): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SELinux ( 7638): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/System.out( 7422): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7422): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/TimaKeyStoreProvider( 7638): in addTimaSignatureService
,V/QuickConnect[1.1][2] ( 5163): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42259c48
,D/TimaKeyStoreProvider( 7638): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7638): Added TimaKesytore provider
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
,D/dalvikvm( 7638): GC_CONCURRENT freed 3002K, 30% free 9569K/13572K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7638): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,V/KVNProvider( 7638): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7638): getFindoCursor query string : 
E/SPPClientService( 5559): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5559): [SystemStateMoniter] Current Time : 299632
,E/SPPClientService( 5559): [SystemStateMoniter] No Connect : false
,V/KVNProvider( 7638): getTagSearchCursor() tagSearchCursor count : 0
D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,I/ActivityManager( 2421): Killing 6277:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/dalvikvm( 5559): GC_CONCURRENT freed 2037K, 23% free 10436K/13548K, paused 4ms+3ms, total 44ms
,D/dalvikvm( 5559): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/System.out( 7422): AsyncTask #1 calls detatch()
,W/System.err( 7422): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7422): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7422): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7422): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7422): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7422): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7422): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7422): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7422): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7422): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7422): Caused by: java.lang.NullPointerException
W/System.err( 7422): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7422): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7422): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7422): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7422): 	... 8 more
,I/ActivityManager( 2421): Killing 6176:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SA      ( 5825): [RC New] [v2liruge] api execute + 1062
,I/SA      ( 5825): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5825): AsyncTask #2 calls detatch()
,I/SA      ( 5825): [TPMU] getNetworkMcc : 
,I/SA      ( 5825): [SCU] saveMccToPreferece Start
,I/SA      ( 5825): [SCU] RegionMCC : 260
,I/SA      ( 5825): [SSP] query invoked
I/SA      ( 5825): [TPMU] GetMccFromDB : null
,I/SA      ( 5825): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5825): [SCU] saveMccToPreferece End
I/SA      ( 5825): [RC New] executeRequest [v2liruge] end. 1090
,I/SA      ( 5825): [RC New] Execute end
I/SA      ( 5825): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5825): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/SPPClientService( 5559): [b] __InitReply__
,E/WifiStateMachine( 2421): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager( 2421): Killing 6211:com.google.android.music:main/u0a125 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2421): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2421) eventTime = 302227
D/PowerManagerService( 2421): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421 (0x0)
D/PowerManagerService( 2421): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2421, ws=WorkSource{1000}) (elapsedTime=3475)
,I/GAV2    ( 7490): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6640): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6640): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6640): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6640): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6640): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6640): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6640): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6640): [ensureRegistration] - No Samsung account
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7331): 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/CaptivePortalTracker( 2421): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2421): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE
,D/CaptivePortalTracker( 2421): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2421): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2421): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2421): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 0
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE
,I/jxcore-log( 7331): Test app app.js loaded
I/jxcore-log( 7331): 
,I/dalvikvm( 7331): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7331): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7331): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7331): BLE advertisement is supported
I/jxcore-log( 7331): 
,I/chromium( 7331): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,I/jxcore-log( 7331): --= Surplus to requirements =--
I/jxcore-log( 7331): 
I/jxcore-log( 7331): ****TEST TOOK:  ms ****
I/jxcore-log( 7331): 
,I/jxcore-log( 7331): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7331): 
,D/AndroidRuntime( 7669): 
D/AndroidRuntime( 7669): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7669): CheckJNI is OFF
,D/AndroidRuntime( 7669): setted country_code = Poland
,D/AndroidRuntime( 7669): setted countryiso_code = PL
D/AndroidRuntime( 7669): setted sales_code = PLS
D/AndroidRuntime( 7669): readGMSProperty: start
,D/AndroidRuntime( 7669): readGMSProperty: already setted!!
D/AndroidRuntime( 7669): readGMSProperty: end
,D/AndroidRuntime( 7669): addProductProperty: start
,D/dalvikvm( 7669): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7669): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7669): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7669): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7669): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7669): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7669): failed to load memtrack module: -2
,D/dalvikvm( 7669): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7669): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2421): START PACKAGE DELETE: observer{1114996952}
D/PackageManager( 2421): pkg{<packageName>}
D/PackageManager( 2421): user{0}
,D/PackageManager( 2421): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager( 2421): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2421): deletePackageX- pkg:com.test.thalitest, userId:0
,D/PackageManager( 2421): !@killApplicatoin: 10641, uninstall pkg
,I/ActivityManager( 2421): Killing 7331:com.test.thalitest/u0a641 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2421): WIN DEATH: Window{42f6c2f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2421): Skipping PackageSetting{42c9cc78 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2421): setPackageStoppedState - Execution time: 119 ms
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10641, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6800): GC_EXPLICIT freed 160K, 28% free 9960K/13788K, paused 3ms+4ms, total 49ms
,D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10641, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/DBG_DM  ( 4754): [3.19.140541][Line:408][onResume] 
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,I/DBG_DM  ( 4754): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4754): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4754): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4754): [3.19.140541][Line:418][onResume] Postpone Count : 30
,D/dalvikvm( 2953): GC_EXPLICIT freed 1471K, 27% free 10036K/13568K, paused 7ms+5ms, total 104ms
,I/DBG_DM  ( 4754): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/dalvikvm( 6452): GC_EXPLICIT freed 2531K, 28% free 9886K/13568K, paused 4ms+8ms, total 120ms
,E/SamsungIME( 2985): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5163): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/InputReader( 2421): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4754): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/SELinux ( 7680): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7680):  
,W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 4754): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/SELinux ( 7680): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7680):  
I/SELinux ( 7680):  
,I/SELinux ( 7680): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7680): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7680): >>>>> Normal User
,E/dalvikvm( 7680): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7680): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 3276): GC_EXPLICIT freed 2166K, 21% free 12436K/15596K, paused 18ms+9ms, total 226ms
,D/TimaKeyStoreProvider( 7680): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7680): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7680): Added TimaKesytore provider
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2421): GC_EXPLICIT freed 2067K, 73% free 25028K/89532K, paused 12ms+26ms, total 283ms
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4754): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
,I/DBG_DM  ( 4754): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4754): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4754): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4754): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4754): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4754): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/StatusBarManagerService( 2421): semi p:4754,o:t
D/Activity( 4754): setTransGradationMode to true
D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/RegisteredServicesCache( 2757): empty dynamic service
I/DBG_DM  ( 4754): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "sms"
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/RCPManagerService( 2421): PackageReceiver onReceive()
,I/HarmonyEASService( 2421): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/dalvikvm( 7680): GC_CONCURRENT freed 3000K, 30% free 9568K/13564K, paused 4ms+1ms, total 49ms
,D/dalvikvm( 7680): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7680): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mms"
,D/elm:14132( 7680): ELMEngine.ELMEngine( context ).
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7680): MDMBridge.setEnterpriseBridge()
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2421): Got RemoteException sending setActive(false) notification to pid 7331 uid 10641
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Scheme: "mmsto"
,D/elm:14132( 7680): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/elm:14132( 7680): ElmAgentService : onCreate()
W/ActivityManager( 2421): mDVFSHelper.release()
,D/elm:14132( 7680): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7680): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7680): MDMBridge.getInstance()
,D/elm:14132( 7680): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7680): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7696):  
,D/dalvikvm( 2757): GC_CONCURRENT freed 1210K, 27% free 10615K/14460K, paused 9ms+3ms, total 88ms
D/dalvikvm( 2757): WAIT_FOR_CONCURRENT_GC blocked 66ms
I/SELinux ( 7696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7696):  
I/SELinux ( 7696):  
I/SELinux ( 7696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7696): >>>>> Normal User
E/dalvikvm( 7696): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 10% free 9505K/10548K, paused 3ms+3ms, total 37ms
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9505K/10548K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7696): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9505K/10548K, paused 2ms+3ms, total 26ms
,D/EnterpriseDeviceManagerService( 2421): Package has changed for user 0
D/TimaKeyStoreProvider( 7696): Cannot add TimaSignature Service, License check Failed
,D/elm:14132( 7680): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/ActivityThread( 7696): Added TimaKesytore provider
,D/elm:14132( 7680): ElmAgentService : onDestroy().
I/ActivityManager( 2421): Killing 6580:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/BackupManagerService( 2421): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2421): removePackageParticipantsLocked: uid=10641 #1
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
,D/dalvikvm( 2421): GC_EXPLICIT freed 828K, 72% free 25266K/89532K, paused 11ms+31ms, total 466ms
D/PackageManager( 2421): delete sourFile : 
,D/PackageManager( 2421): delete native library directory: 
D/dalvikvm( 7696): GC_CONCURRENT freed 2997K, 30% free 9571K/13568K, paused 6ms+4ms, total 33ms
,D/dalvikvm( 7696): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/AndroidRuntime( 7669): Shutting down VM
D/PackageManager( 2421): return delete result to caller: 1114996952
,D/PackageManager( 2421): returnCode: 1
D/dalvikvm( 7669): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{42ecf3b0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7713):  
I/ActivityManager( 2421): Killing 6472:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2421): initializing...
I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
I/TZ: mc_tlc_communication( 2421): device_id = 0x0
I/TZ: mc_tlc_communication( 2421): tlc_open() was called
I/TZ: mc_tlc_communication( 2421): Opening MobiCore device
I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2421): Opening the session
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7713):  
I/SELinux ( 7713):  
,I/SELinux ( 7713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7713): >>>>> Normal User
,E/dalvikvm( 7713): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7713): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7713): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7713): Added TimaKesytore provider
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7713): GC_CONCURRENT freed 2990K, 30% free 9581K/13568K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7713): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6640): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6640): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6640): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 5825): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5825): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,E/SharedPreferencesImpl( 3561): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/Icing.InternalIcingCorporaProvider( 6452): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 6452): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6452): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 6021): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6021): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7732): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7732):  
,E/AndroidRuntime( 6452): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6452): Process: com.google.android.googlequicksearchbox:search, PID: 6452
E/AndroidRuntime( 6452): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6452): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6452): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6452): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6452): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6452): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6452): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6452): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6452): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6452): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6452): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6452): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6452): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6452): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ApplicationsProvider( 2953): Could not fetch usage stats
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
E/AndroidRuntime( 6021): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6021): Process: com.sec.android.app.shealth, PID: 6021
E/AndroidRuntime( 6021): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6021): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6021): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6021): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6021): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6021): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6021): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6021): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6021): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6021): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6021): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6021): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6021): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6021): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6021): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6021): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 7732): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7732):  
I/SELinux ( 7732):  
I/SELinux ( 7732): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7732): [DEBUG] seapp_context_lookup: seinfoCategory ,= platform
E/dalvikvm( 7732): >>>>> Normal User
E/dalvikvm( 7732): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 7732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/Process ( 6021): Sending signal. PID: 6021 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/Process ( 6452): Sending signal. PID: 6452 SIG: 9
D/TimaKeyStoreProvider( 7732): in addTimaSignatureService
I/ActivityManager( 2421): Process com.sec.android.app.shealth (pid 6021) (adj 5) has died.
D/TimaKeyStoreProvider( 7732): Cannot add TimaSignature Service, License check Failed
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 7732): Added TimaKesytore provider
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2421): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2421): clearDefaults: com.test.thalitest
I/ActivityManager( 2421): Process com.google.android.googlequicksearchbox:search (pid 6452) (adj 5) has died.
,W/AtomicFile( 2421): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2421): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/dalvikvm( 7732): GC_CONCURRENT freed 2994K, 30% free 9572K/13568K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 7732): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/UserAnalysis.PlaceProvider( 7732): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7732): Create SecureDbHelper
,E/SQLiteDatabase( 7732): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7732): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7732): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7732): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7732): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7732): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7732): Opened privacy in read-only mode
,E/SQLiteDatabase( 7732): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7732): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7732): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7732): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7732): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7732): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7732): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7732): Opened privacy in read-only mode
,E/SQLiteDatabase( 7732): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7732): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7732): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7732): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
,W/System.err( 7732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
,W/System.err( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,W/System.err( 7732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7732): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7732): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
,W/System.err( 7732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7732): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7732): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7732): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 7732): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7732): 	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6378): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/RCPManager( 6466):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2421):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2421): queryAllProviders():  providerCallBack is not register for 0
,D/CapabilityManagerService New( 6708): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 6708): The package(com.test.thalitest) removed
,W/System.err( 2421): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
,W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
,E/SQLiteDatabase( 6378): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6378): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6378): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6378): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6378): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6378): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6378): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6378): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6378): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6378): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2421): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2421): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 6378): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err( 6378): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 2421): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6378): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,W/System.err( 6378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6378): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6378): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6378): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6378): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6378): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6378): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 2421): 	... 8 more
,W/System.err( 6378): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6378): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
,W/System.err( 6378): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 2421): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6378): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2421): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
,W/System.err( 2421): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2421): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2421): 	... 8 more
,W/System.err( 6378): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6378): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/MagazineService::MagazineBroadcastReceiver( 6734): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6734): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteDatabase( 6734): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6734): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6734): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6734): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6734): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6734): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7748): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7748):  
,E/AndroidRuntime( 6734): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6734): Process: com.samsung.android.magazine.service, PID: 6734
E/AndroidRuntime( 6734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6734): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6734): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6734): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6734): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6734): Sending signal. PID: 6734 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.samsung.android.magazine.service (pid 6734) (adj 5) has died.
,I/SELinux ( 7748): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7748):  
I/SELinux ( 7748):  
,I/SELinux ( 7748): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7748): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7748): >>>>> Normal User
,E/dalvikvm( 7748): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7748): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7748): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7748): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7748): Added TimaKesytore provider
,D/dalvikvm( 7748): GC_CONCURRENT freed 3004K, 30% free 9568K/13568K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7748): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/ContextImpl( 7748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7748): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7748): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7748): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7748): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7748): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7748): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7748): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7748): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7748): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7748): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7748): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7748): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsModeInstallReceiver( 6761): onReceive intent data =  package:com.test.thalitest
E/AndroidRuntime( 7748): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7748): Process: com.android.keychain, PID: 7748
E/AndroidRuntime( 7748): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7748): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7748): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7748): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7748): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7748): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7748): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7748): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7748): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7748): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/KidsPlatformStub( 6761): Package not found : com.sec.android.app.kidshome
,I/Process ( 7748): Sending signal. PID: 7748 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.android.keychain (pid 7748) (adj 5) has died.
,W/System.err( 6800): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 6800): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6800): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6800): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
,W/System.err( 6800): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6800): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6800): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6800): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 6800): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6800): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6800): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6800): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6800): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3276): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3276): Clearing selected account for com.test.thalitest
,E/SQLiteLog( 3276): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ChimeraCfgMgr( 3276): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3276): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 3276): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 3276): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3276): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3276): disk I/O error (code 3850)
E/DriveAsyncService( 3276): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3276): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3276): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3276): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3276): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3276): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3276): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3276): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3276): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3276): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3276): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3276): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3276): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3276): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 2851): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2851): Shutting down VM
,W/dalvikvm( 2851): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 3276): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 2851): FATAL EXCEPTION: main
E/AndroidRuntime( 2851): Process: com.google.process.gapps, PID: 2851
E/AndroidRuntime( 2851): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2851): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2851): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2851): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2851): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2851): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2851): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2851): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2851): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2851): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2851): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2851): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2851): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2851): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2851): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2851): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2851): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2851): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2851): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2851): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2851): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2851): 	... 10 more
E/SQLiteLog( 3276): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/Process ( 2851): Sending signal. PID: 2851 SIG: 9
,E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
W/dalvikvm( 3276): threadid=48: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 3276): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3276): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3276): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3276): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3276): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3276): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3276): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3276): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3276): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 5559): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5559): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5559): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5559): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5559): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5559): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5559): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5559): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5559): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5559): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5559): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5559): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5559): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5559): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5559): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5559): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5559): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5559): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5559): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/PhenotypeInitializer( 3276): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3276): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3276): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3276): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3276): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3276): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3276): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3276): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3276): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 3276): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3276): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3276): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3276): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3276): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3276): 	at com.google.a,ndroid.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3276): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3276): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3276): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3276): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3276): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7773): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7773):  
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 2851) (adj 5) has died.
E/SQLiteDatabase( 6420): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6420): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6420): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6420): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6420): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6420): 	at dalvik.system.NativeStart.main(Native Method)
E/LNoti   ( 6420): [g] not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3276): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3276): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteDatabase.open(SQ,LiteDatabase.java:859)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3276): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3276): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3276): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3276): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3276): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3276): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3276): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3276): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3276): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3276): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 3276): Runtime exception while performing operation
E/ClearPendingStateOp( 3276): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3276): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3276): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3276): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3276): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3276): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3276): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3276): 	at java.lang.Thread.run(Thread.java:841)
F/ClearPendingStateOp( 3276): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3276): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3276): 	at android.da,tabase.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3276): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3276): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3276): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3276): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3276): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3276): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3276): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3276): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 6420): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6420): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6420): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6420): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6420): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6420): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6420): 	at dalvik.system.NativeStart.main(Native Method)
E/LNoti   ( 6420): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3276): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3276): Process: com.google.android.gms, PID: 3276
E/AndroidRuntime( 3276): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3276): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3276): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3276): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3276): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3276): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3276): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3276): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3276): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3276): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3276): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3276): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3276): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3276): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3276): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3276): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3276): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3276): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 3276): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3276): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SELinux ( 7773): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7773):  
I/SELinux ( 7773):  
I/SELinux ( 7773): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7773): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7773): >>>>> Normal User
E/dalvikvm( 7773): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
E/SELinux ( 7773): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/GMPM-SVC( 3276): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
W/dalvikvm( 3276): threadid=52: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3276): Sending signal. PID: 3276 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_wtf
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,D/TimaKeyStoreProvider( 7773): in addTimaSignatureService
D/TimaKeyStoreProvider( 7773): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7773): Added TimaKesytore provider
D/PowerManagerService( 2421): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3276, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=41)
D/GAV2    ( 5654): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
I/ActivityManager( 2421): Process com.google.android.gms (pid 3276) (adj 0) has died.
,I/GAV2    ( 5654): Thread[main,5,main]: Unexpected disconnect.
,D/dalvikvm( 7773): GC_CONCURRENT freed 3002K, 30% free 9571K/13572K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7773): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/Documents( 7773): Loading roots for com.android.externalstorage.documents
,I/SELinux ( 7792): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7792):  
,E/SQLiteDatabase( 7773): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7773): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7773): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7773): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7773): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7773): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7773): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7773): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7773): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7773): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7773): Shutting down VM
,W/dalvikvm( 7773): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7773): FATAL EXCEPTION: main
E/AndroidRuntime( 7773): Process: com.android.documentsui, PID: 7773
E/AndroidRuntime( 7773): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7773): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7773): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7773): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7773): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7773): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7773): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7773): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7773): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7773): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7773): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7773): 	... 10 more
,I/SELinux ( 7796): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7796):  
,I/Process ( 7773): Sending signal. PID: 7773 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/SELinux ( 7792): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7792):  
I/SELinux ( 7792):  
,I/SELinux ( 7792): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7792): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/ActivityManager( 2421): Process com.android.documentsui (pid 7773) (adj 9) has died.
E/dalvikvm( 7792): >>>>> Normal User
E/dalvikvm( 7792): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
E/SELinux ( 7792): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7792): in addTimaSignatureService
I/SELinux ( 7796): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7796):  
I/SELinux ( 7796):  
,I/SELinux ( 7796): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7796): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7796): >>>>> Normal User
,E/dalvikvm( 7796): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7796): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7792): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7792): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7796): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7796): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7796): Added TimaKesytore provider
,D/dalvikvm( 7792): GC_CONCURRENT freed 2999K, 30% free 9568K/13568K, paused 5ms+1ms, total 26ms
,D/dalvikvm( 7792): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/ExternalStorage( 7792): After updating volumes, found 1 active roots
,D/dalvikvm( 7796): GC_CONCURRENT freed 2936K, 30% free 9634K/13572K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7796): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/dalvikvm( 7796): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7796): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7796): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7796): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7796): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7796): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7796): install
,I/MultiDex( 7796): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7796): loading existing secondary dex files
,I/MultiDex( 7796): load found 3 secondary dex files
,I/MultiDex( 7796): install done
,I/SELinux ( 7818): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7818):  
,I/SELinux ( 7818): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7818):  
I/SELinux ( 7818):  
,I/SELinux ( 7818): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7818): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7818): >>>>> Normal User
,E/dalvikvm( 7818): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7818): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7818): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7818): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7818): Added TimaKesytore provider
,D/dalvikvm( 7818): GC_CONCURRENT freed 2989K, 30% free 9579K/13564K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7818): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 7832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7832):  
,I/Icing.InternalIcingCorporaProvider( 7818): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7832):  
I/SELinux ( 7832):  
,I/SELinux ( 7832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7832): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7832): >>>>> Normal User
,E/dalvikvm( 7832): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7832): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7848): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7848):  
,D/TimaKeyStoreProvider( 7832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7832): Cannot add TimaSignature Service, License check Failed
,D/LocationManagerService( 2421): getProviders()=[passive]
,D/ActivityThread( 7832): Added TimaKesytore provider
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{44a11a88 u0 com.sec.spp.push/.PushClientService}
,I/SELinux ( 7848): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7848):  
I/SELinux ( 7848):  
,I/SELinux ( 7848): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7848): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7848): >>>>> Normal User
,E/dalvikvm( 7848): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7848): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7848): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7848): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7848): Added TimaKesytore provider
,D/dalvikvm( 7832): GC_CONCURRENT freed 2993K, 30% free 9577K/13568K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7832): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7848): GC_CONCURRENT freed 2997K, 30% free 9570K/13564K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7848): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/GservicesProvider( 7832): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7832): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7832): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7832): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7832): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7832): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7832): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7832): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7832): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7832): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7832): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7832): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7832): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7832): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7832): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7832): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7832): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7832): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7832): Shutting down VM
,W/dalvikvm( 7832): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7832): FATAL EXCEPTION: main
E/AndroidRuntime( 7832): Process: com.google.process.gapps, PID: 7832
E/AndroidRuntime( 7832): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7832): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7832): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7832): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7832): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7832): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7832): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7832): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7832): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7832): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7832): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7832): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7832): 	... 12 more
,I/Process ( 7832): Sending signal. PID: 7832 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 7832) (adj 0) has died.
,W/ActivityManager( 2421): Service crashed 2 times, stopping: ServiceRecord{43053df8 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7868): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7868):  
,I/SELinux ( 7868): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7868):  
I/SELinux ( 7868):  
,I/SELinux ( 7868): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7868): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7868): >>>>> Normal User
,E/dalvikvm( 7868): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7868): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7868): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7868): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7868): Added TimaKesytore provider
,D/dalvikvm( 7868): GC_CONCURRENT freed 2994K, 30% free 9581K/13572K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7868): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/GservicesProvider( 7868): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7868): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7868): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7868): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7868): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7868): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7868): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7868): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7868): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7868): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7868): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7868): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7868): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7868): Shutting down VM
,W/dalvikvm( 7868): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7868): FATAL EXCEPTION: main
E/AndroidRuntime( 7868): Process: com.google.process.gapps, PID: 7868
E/AndroidRuntime( 7868): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7868): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7868): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7868): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7868): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7868): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7868): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7868): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7868): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7868): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7868): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7868): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7868): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7868): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7868): 	... 12 more
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7868:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /d,ata/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7848): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7818): Failed to find provider info for com.google.settings
E/ActivityThread( 7796): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7884): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7884):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 10% free 9505K/10548K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9505K/10548K, paused 2ms+3ms, total 23ms
,I/SELinux ( 7884): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7884):  
I/SELinux ( 7884):  
,I/SELinux ( 7884): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7884): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7884): >>>>> Normal User
,E/dalvikvm( 7884): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7884): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7884): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9505K/10548K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7884): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7884): Added TimaKesytore provider
,D/dalvikvm( 7884): GC_CONCURRENT freed 2988K, 30% free 9585K/13572K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7884): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7884): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7884): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7884): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7884): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7884): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7884): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7884): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7884): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7884): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7884): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7884): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7884): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7884): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7884): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7884): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7884): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7884): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7884): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7884): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7884): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7884): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7884): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7884): Shutting down VM
,W/dalvikvm( 7884): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 7884): Sending signal. PID: 7884 SIG: 9
E/AndroidRuntime( 7884): FATAL EXCEPTION: main
E/AndroidRuntime( 7884): Process: com.google.process.gapps, PID: 7884
E/AndroidRuntime( 7884): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7884): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7884): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7884): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7884): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7884): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7884): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7884): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7884): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7884): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7884): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7884): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7884): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7884): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7884): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7884): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7884): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7884): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7884): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7884): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7884): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7884): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7884): 	... 12 more
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<i,nit>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 7884) (adj 0) has died.
,I/SELinux ( 7899): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7899):  
,I/SELinux ( 7899): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7899):  
I/SELinux ( 7899):  
,I/SELinux ( 7899): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7899): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7899): >>>>> Normal User
,E/dalvikvm( 7899): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7899): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7899): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7899): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7899): Added TimaKesytore provider
,D/dalvikvm( 7899): GC_CONCURRENT freed 2990K, 30% free 9581K/13572K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7899): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7899): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7899): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7899): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7899): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7899): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7899): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7899): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7899): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7899): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7899): Shutting down VM
,W/dalvikvm( 7899): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7899): FATAL EXCEPTION: main
E/AndroidRuntime( 7899): Process: com.google.process.gapps, PID: 7899
E/AndroidRuntime( 7899): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7899): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7899): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7899): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7899): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7899): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7899): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7899): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7899): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7899): 	... 12 more
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7899:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
D/dalvikvm( 7796): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
E/ActivityThread( 7848): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7796): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
W/dalvikvm( 7796): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7796): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7796): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 7796): VFY: unable to resolve instance field 36
D/dalvikvm( 7796): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7796): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7796): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7796): VFY: replacing opcode 0x62 at 0x0047
,I/ActivityManager( 2421): Killing 6612:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/dalvikvm( 7796): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7796): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7796): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42245630
D/dalvikvm( 7796): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42245630
D/dalvikvm( 7796): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42245630, skipping init
D/dalvikvm( 7796): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42245630
D/dalvikvm( 7796): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42245630
V/JNIHelp ( 7796): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7796): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42245630
,D/dalvikvm( 7796): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42245630
D/dalvikvm( 7796): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42245630
,D/dalvikvm( 7796): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42245630
,I/ProviderInstaller( 7796): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7916): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7916):  
,I/SELinux ( 7916): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7916):  
I/SELinux ( 7916):  
,I/SELinux ( 7916): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7916): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7916): >>>>> Normal User
,E/dalvikvm( 7916): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7916): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7916): in addTimaSignatureService
D/TimaKeyStoreProvider( 7916): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7916): Added TimaKesytore provider
,D/dalvikvm( 7916): GC_CONCURRENT freed 2994K, 30% free 9581K/13572K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7916): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7916): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7916): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7916): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7916): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7916): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7916): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7916): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7916): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7916): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7916): Shutting down VM
,W/dalvikvm( 7916): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7916): FATAL EXCEPTION: main
E/AndroidRuntime( 7916): Process: com.google.process.gapps, PID: 7916
E/AndroidRuntime( 7916): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7916): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7916): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7916): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7916): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7916): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7916): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7916): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7916): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7916): 	... 12 more
,I/Process ( 7916): Sending signal. PID: 7916 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 7916) (adj 0) has died.
,I/SELinux ( 7931): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7931):  
,W/dalvikvm( 2953): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 2953): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2953): Process: android.process.acore, PID: 2953
E/AndroidRuntime( 2953): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2953): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2953): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2953): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2953): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2953): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2953): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2953): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2953): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2953): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2953): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2953): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2953): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2953): Sending signal. PID: 2953 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/SELinux ( 7931): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7931):  
I/SELinux ( 7931):  
,I/SELinux ( 7931): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7931): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7931): >>>>> Normal User
,E/dalvikvm( 7931): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7931): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/ActivityManager( 2421): Process android.process.acore (pid 2953) (adj -12) has died.
,D/TimaKeyStoreProvider( 7931): in addTimaSignatureService
,I/SELinux ( 7944): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7944):  
,D/TimaKeyStoreProvider( 7931): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7931): Added TimaKesytore provider
,I/SELinux ( 7944): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7944):  
I/SELinux ( 7944):  
,I/SELinux ( 7944): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7944): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7944): >>>>> Normal User
,E/dalvikvm( 7944): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7944): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 7931): GC_CONCURRENT freed 2991K, 30% free 9581K/13568K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7931): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/TimaKeyStoreProvider( 7944): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7944): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7944): Added TimaKesytore provider
,I/GservicesProvider( 7931): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7931): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7931): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7931): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7931): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7931): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7931): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7931): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7931): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7931): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7931): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7931): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7931): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7931): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7931): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7931): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7931): Shutting down VM
,W/dalvikvm( 7931): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7931): FATAL EXCEPTION: main
E/AndroidRuntime( 7931): Process: com.google.process.gapps, PID: 7931
E/AndroidRuntime( 7931): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7931): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7931): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7931): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7931): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7931): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7931): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7931): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7931): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7931): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7931): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7931): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7931): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7931): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7931): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7931): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7931): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7931): 	... 12 more
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7931:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7796): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
D/dalvikvm( 7944): GC_CONCURRENT freed 2985K, 30% free 9583K/13568K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7944): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/NativeLibraryUtils( 7796): Failed to open lock file
W/NativeLibraryUtils( 7796): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7796): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7796): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7796): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7796): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7796): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7796): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7796): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7796): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7796): 	... 3 more
,I/dalvikvm( 7796): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 7796): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 7796): VFY: replacing opcode 0x6e at 0x002b
,I/SELinux ( 7965): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7965):  
,I/SELinux ( 7965): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7965):  
I/SELinux ( 7965):  
,I/SELinux ( 7965): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7965): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/SQLiteDatabase( 7944): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7944): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7944): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7944): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7944): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7944): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/dalvikvm( 7965): >>>>> Normal User
,E/dalvikvm( 7965): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SQLiteOpenHelper( 7944): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7944): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7944): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7944): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7944): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7944): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7944): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7944): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7944): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7944): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SELinux ( 7965): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/SQLiteLog( 7944): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7944): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7944): (14) unable to open database file
,E/SQLiteDatabase( 7944): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7944): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7944): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7944): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7944): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7944): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7944): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7944): Process: android.process.acore, PID: 7944
E/AndroidRuntime( 7944): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7944): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7944): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7944): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7944): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7944): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7944): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7944): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7944): Sending signal. PID: 7944 SIG: 9
,D/TimaKeyStoreProvider( 7965): in addTimaSignatureService
,E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
D/TimaKeyStoreProvider( 7965): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7965): Added TimaKesytore provider
,I/ActivityManager( 2421): Process android.process.acore (pid 7944) (adj -12) has died.
,F/ActivityManager( 2421): Service ServiceRecord{42252da8 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{42f45ef0 7944:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2421): Can't write: system_server_wtf
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2421): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2421): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2421): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2421): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 18 more
,I/SELinux ( 7980): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7980):  
,I/SELinux ( 7980): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7980):  
I/SELinux ( 7980):  
,I/SELinux ( 7980): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7980): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7980): >>>>> Normal User
,E/dalvikvm( 7980): >>>>> android.process.acore [ userId:0 | appId:10020 ]
D/dalvikvm( 7965): GC_CONCURRENT freed 2988K, 30% free 9585K/13572K, paused 4ms+1ms, total 20ms
,D/dalvikvm( 7965): WAIT_FOR_CONCURRENT_GC blocked 11ms
,E/SELinux ( 7980): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7980): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7980): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7980): Added TimaKesytore provider
,I/GservicesProvider( 7965): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7965): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7965): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7965): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7965): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7965): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7965): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7965): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7965): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7965): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7965): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7965): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7965): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7965): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7965): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7965): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7965): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7965): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7965): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7965): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7965): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7965): Shutting down VM
,W/dalvikvm( 7965): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7965): FATAL EXCEPTION: main
E/AndroidRuntime( 7965): Process: com.google.process.gapps, PID: 7965
E/AndroidRuntime( 7965): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7965): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7965): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7965): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7965): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7965): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7965): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7965): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7965): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7965): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7965): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7965): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7965): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7965): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7965): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7965): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7965): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7965): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7965): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7965): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7965): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7965): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7965): 	... 12 more
,I/Process ( 7965): Sending signal. PID: 7965 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop236.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,D/dalvikvm( 7980): GC_CONCURRENT freed 2985K, 30% free 9579K/13564K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7980): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/ActivityManager( 2421): Process com.google.process.gapps (pid 7965) (adj 0) has died.
,I/SELinux ( 7995): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7995):  
,I/SELinux ( 7995): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7995):  
I/SELinux ( 7995):  
,I/SELinux ( 7995): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7995): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7995): >>>>> Normal User
,E/dalvikvm( 7995): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7995): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7995): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7995): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7995): Added TimaKesytore provider
,E/SQLiteDatabase( 7980): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7980): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7980): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7980): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7980): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7980): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7980): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7980): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7980): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7980): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7980): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7980): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7980): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7980): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7980): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7980): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7980): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7980): (14) unable to open database file
,E/SQLiteDatabase( 7980): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7980): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7980): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7980): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7980): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7980): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
