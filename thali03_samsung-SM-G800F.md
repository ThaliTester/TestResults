#### Test 55613145b105d0b_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2407): stay LED for fully charged
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4016): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7284): 
D/AndroidRuntime( 7284): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7284): CheckJNI is OFF
D/AndroidRuntime( 7284): setted country_code = Poland
D/AndroidRuntime( 7284): setted countryiso_code = PL
D/AndroidRuntime( 7284): setted sales_code = PLS
D/AndroidRuntime( 7284): readGMSProperty: start
D/AndroidRuntime( 7284): readGMSProperty: already setted!!
D/AndroidRuntime( 7284): readGMSProperty: end
D/AndroidRuntime( 7284): addProductProperty: start
D/dalvikvm( 7284): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7284): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7284): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7284): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7284): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7284): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7284): failed to load memtrack module: -2
D/dalvikvm( 7284): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7284): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2407): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2407): mDVFSHelper.acquire()
I/SELinux ( 7303): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7303):  
D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7284): Shutting down VM
D/dalvikvm( 7284): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7303): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7303):  
I/SELinux ( 7303):  
I/SELinux ( 7303): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7303): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7303): >>>>> Normal User
E/dalvikvm( 7303): >>>>> com.test.thalitest [ userId:0 | appId:10621 ]
E/SELinux ( 7303): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7303): in addTimaSignatureService
D/TimaKeyStoreProvider( 7303): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7303): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4172): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4172): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by BW check
D/dalvikvm( 7303): GC_CONCURRENT freed 3007K, 29% free 9566K/13296K, paused 2ms+2ms, total 18ms
D/dalvikvm( 7303): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
V/WebViewChromium( 7303): Binding Chromium to the background looper Looper (main, tid 1) {422082a8}
I/chromium( 7303): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7303): Initializing chromium process, renderers=0
W/chromium( 7303): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7303): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7303): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7303): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7303): Mali API Version : 401
,I/Mali    ( 7303): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7303): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7303): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7303): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7303): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7303): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7303): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2407): tr p:7303,o:f
,W/dalvikvm( 7303): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7303): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7303): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7303): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7303): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7303): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7303): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7303): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7303): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7303): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7303): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7303): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7303): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2407): semi p:7303,o:f
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7303): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7303): Enabling debug mode 0
,W/AwContents( 7303): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7303): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2407): mDVFSHelper.release()
W/IInputConnectionWrapper( 7303): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7303): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7303): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x421ffc30
D/dalvikvm( 7303): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x421ffc30
D/jxcore_app_log( 7303): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027628800
D/JX-Cordova( 7303): jxcore cordova android initializing
D/dalvikvm( 7303): GC_CONCURRENT freed 1290K, 16% free 11349K/13360K, paused 3ms+2ms, total 29ms
D/dalvikvm( 7303): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 7303): GC_CONCURRENT freed 1940K, 16% free 14960K/17640K, paused 2ms+2ms, total 39ms
D/dalvikvm( 7303): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7303): GC_FOR_ALLOC freed 5294K, 28% free 16237K/22508K, paused 51ms, total 51ms
,D/AmoledAdjustTimer( 2407): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 7303): GC_CONCURRENT freed 6711K, 30% free 17697K/25152K, paused 2ms+9ms, total 54ms
,D/dalvikvm( 7303): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 7303): GC_FOR_ALLOC freed 1176K, 31% free 17568K/25152K, paused 49ms, total 50ms
,I/dalvikvm-heap( 7303): Grow heap (frag case) to 21.375MB for 3688532-byte allocation
,D/dalvikvm( 7303): GC_FOR_ALLOC freed 2473K, 35% free 18696K/28756K, paused 40ms, total 40ms
,W/jxcore-log( 7303): Initializing JXcore engine
,W/jxcore-log( 7303): JXcore engine is ready
,W/jxcore-log( 7303): Starting JXcore engine
,W/jxcore-log( 7303): Platform android
W/jxcore-log( 7303): 
,W/jxcore-log( 7303): Process ARCH arm
W/jxcore-log( 7303): 
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7303): JXcore Cordova bridge is ready!
I/jxcore-log( 7303): 
,W/jxcore-log( 7303): JXcore engine is started
,I/chromium( 7303): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7303): Toggling radios to true
I/jxcore-log( 7303): 
,D/BluetoothAdapter( 7303): enable(): BT is already enabled..!
,I/WifiManager( 7303): packageName : com.test.thalitest
,I/WifiManager( 7303): setWifiEnabled : true
,I/WifiService( 2407): setWifiEnabled: true pid=7303, uid=10621
W/ActivityManager( 2407): Permission Denial: getCurrentUser() from pid=7303, uid=10621 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2407): Failed getting userId using ActivityManagerNative
W/WifiService( 2407): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7303, uid=10621 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2407): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2407): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2407): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2407): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2407): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2407): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2407): disconnect: pid=7303, uid=10621
,I/jxcore-log( 7303): Radios toggled
I/jxcore-log( 7303): 
,I/jxcore-log( 7303): My device name is: samsung-SM-G800F
I/jxcore-log( 7303): 
,I/wpa_supplicant( 3978): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3978): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3978): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3978): First Scan Start
,I/wpa_supplicant( 3978): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2407): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2407): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2407): InactiveState{ what=143375 }
D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0,
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling,
D/ConnectivityService( 2407): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3978): Skip scan - already scanning,
D/ConnectivityService( 2407): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2407): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2407): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
,E/ConnectivityService( 2407): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2407): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2407): InactiveState{ what=143375 }
D/WifiP2pService( 2407): P2pEnabledState{ what=143375 },
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3,
,I/SELinux ( 7351): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7351):  
D/ConnectivityService( 2407): Attempting to switch to mobile
D/ConnectivityService( 2407): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling,
,E/WifiStateMachine( 2407): Error! unhandled message{ when=-38ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,E/WifiStateMachine( 2407): Error! unhandled message{ when=-40ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2407): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1,
,I/SELinux ( 7351): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7351):  
I/SELinux ( 7351):  
I/SELinux ( 7351): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7351): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7351): >>>>> Normal User
,E/dalvikvm( 7351): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/SELinux ( 7351): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2407): route cmd failed: 
W/NetworkManagementService( 2407): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2407): '
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2407): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2407): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7351): in addTimaSignatureService
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7351): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7351): Added TimaKesytore provider
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2407): android_net_utils_resetConnections in env=0x7800d1c8 clazz=0x62000001 iface=wlan0 mask=0x3
D/ConnectivityService( 2407): resetConnections(wlan0, 3)
,D/dalvikvm( 7351): GC_CONCURRENT freed 2993K, 28% free 9573K/13288K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7351): WAIT_FOR_CONCURRENT_GC blocked 17ms
,V/NativeCrypto( 2849): Read error: ssl=0x7a073f70: I/O error during system call, Connection timed out
,V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7a073f70: I/O error during system call, Broken pipe
,E/SPPClientService( 5561): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5561): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5561): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5561): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5561): [b] ResponseMap empty
,I/System.out( 7351): Inside WakeupProvider
,I/System.out( 7351): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7351): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7351): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7351): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
D/ConnectivityService( 2407): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2407): updateIfacesLocked()
,V/NetworkStats( 2407): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): performPollLocked() took 34ms
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2834): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2834): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2407): Killing 6197:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7351): initQueue()
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2834): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2834): MountReceiver.mPrefHandler - 7002
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Tethering( 2407): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2407): updateDataUsageMap
,D/Tethering( 2407): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2407): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2407): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): noConnectivity : true
,I/DBG_DM  ( 4757): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7380): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7380):  
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection...
,I/wpa_supplicant( 3978): nl80211: Received scan results (5 BSSes)
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3978): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2407): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7380): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7380):  
I/SELinux ( 7380):  
,I/SELinux ( 7380): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7380): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7380): >>>>> Normal User
,E/dalvikvm( 7380): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7380): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7380): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7380): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7380): Added TimaKesytore provider
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3978): Associated with C0.AA.48
I/wpa_supplicant( 3978): freq(2412) increment count 2
,I/wpa_supplicant( 3978): meet head of list.
,D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
D/Tethering( 2407): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/dalvikvm( 7380): GC_CONCURRENT freed 2997K, 28% free 9567K/13288K, paused 4ms+3ms, total 32ms
D/dalvikvm( 7380): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3978): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3978): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2407): callSECApiVoid - ID [50]
,D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2407): Killing 6267:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2407): InactiveState{ what=143375 }
,D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
,D/dalvikvm( 2407): GC_CONCURRENT freed 4401K, 72% free 25577K/88568K, paused 12ms+21ms, total 292ms
,I/SELinux ( 7394): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7394):  
,I/SELinux ( 7394): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7394):  
I/SELinux ( 7394):  
,I/SELinux ( 7394): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7394): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7394): >>>>> Normal User
,E/dalvikvm( 7394): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7394): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7394): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7394): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7394): Added TimaKesytore provider
,I/dhcpcd  ( 7400): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7400): bssid match
D/dalvikvm( 7394): GC_CONCURRENT freed 3001K, 29% free 9565K/13288K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 7394): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/ActivityManager( 2407): Killing 6341:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7414): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7414):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 8% free 9502K/10272K, paused 3ms+4ms, total 46ms
,I/SELinux ( 7414): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7414):  
I/SELinux ( 7414):  
,I/SELinux ( 7414): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7414): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7414): >>>>> Normal User
E/dalvikvm( 7414): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7414): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9502K/10272K, paused 3ms+4ms, total 40ms
,D/TimaKeyStoreProvider( 7414): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7414): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7414): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9502K/10272K, paused 4ms+4ms, total 38ms
,D/dalvikvm( 7414): GC_CONCURRENT freed 3004K, 29% free 9565K/13292K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7414): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/KLMS-2.3.201 : ( 7414): KLMSValidator() : checkQATesting()
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7414): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452764162517
,I/KLMS-2.3.201 : ( 7414): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2407): Killing 6371:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7426): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7426):  
,I/SELinux ( 7426): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7426):  
I/SELinux ( 7426):  
,I/SELinux ( 7426): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7426): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7426): >>>>> Normal User
,E/dalvikvm( 7426): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7426): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7426): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7426): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7426): Added TimaKesytore provider
,D/dalvikvm( 7426): GC_CONCURRENT freed 2997K, 29% free 9569K/13292K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7426): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/SO_AGENT( 7426): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7426): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5831): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5831): [BDLM] already registered in spp
,I/SA      ( 5831): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5831): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5831): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5831): [OR] == isSIMCardReady false ==
,I/SA      ( 5831): [SCU] == networkStateCheck == false
,I/SA      ( 5831): [OR] onReceive END
I/ActivityManager( 2407): Killing 6409:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SELinux ( 7438): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7438):  
,I/SELinux ( 7438): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7438):  
I/SELinux ( 7438):  
,I/SELinux ( 7438): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7438): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7438): >>>>> Normal User
,E/dalvikvm( 7438): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7438): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7438): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7438): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7438): Added TimaKesytore provider
,D/dalvikvm( 7438): GC_CONCURRENT freed 2994K, 28% free 9570K/13288K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7438): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/sCloudBackupApp( 7438): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7438): Other Intent
I/ActivityManager( 2407): Killing 5611:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7451): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7451):  
,I/SELinux ( 7451): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7451):  
I/SELinux ( 7451):  
,I/SELinux ( 7451): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7451): >>>>> Normal User
,E/dalvikvm( 7451): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7451): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7451): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7451): Added TimaKesytore provider
,D/dalvikvm( 7451): GC_CONCURRENT freed 2997K, 28% free 9571K/13292K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7451): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7451): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7451): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5360): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7451): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5360): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7451): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5360): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2407): Killing 6317:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5894): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5894): getCountryCode(): countryCode = PL
,D/Headlines( 5894): Breath.onCreate
,D/Headlines( 5894): Breath timer started. interval : 30000
,I/SELinux ( 7463): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7463):  
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0,
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() try to query category list,
D/Headlines( 5894): queryCategory.  mRequest is not initialized.
,V/AlarmManager( 2407): waitForAlarm result :8,
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5894): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5894): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7463): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7463):  
I/SELinux ( 7463):  
I/SELinux ( 7463): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7463): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7463): >>>>> Normal User
,E/dalvikvm( 7463): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7463): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7463): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7463): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7463): Added TimaKesytore provider
,D/dalvikvm( 7463): GC_CONCURRENT freed 3001K, 29% free 9565K/13292K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7463): WAIT_FOR_CONCURRENT_GC blocked 16ms
,V/WebViewChromium( 7463): Binding Chromium to the background looper Looper (main, tid 1) {422050f0}
,I/chromium( 7463): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7463): Initializing chromium process, renderers=0
,W/chromium( 7463): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7463): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7463): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7463): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7463): Mali API Version : 401
,I/Mali    ( 7463): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/GAV2    ( 7463): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7463): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7463): Starting up...
,D/WifiP2pService( 2407): InactiveState{ what=143375 }
,D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
,I/iu.Environment( 5962): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/WifiStateMachine( 2407): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.SyncManager( 5962): SYNC; picasa accounts
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2407): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2407): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2407): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2407): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2407): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5163): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42214e10
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling
,I/iu.UploadsManager( 5962): num queued entries: 0
,I/iu.UploadsManager( 5962): num updated entries: 0
D/ConnectivityService( 2407): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2407): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2407): net.tcp.delack.wifi not found in system properties. Using defaults
I/iu.SyncManager( 5962): NEXT; no task
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
I/SELinux ( 7523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7523):  
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/ConnectivityService( 2407): handleConnectivityChange: setting default proxy info ,
,I/SELinux ( 7523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7523):  
I/SELinux ( 7523):  
I/SELinux ( 7523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7523): >>>>> Normal User
,E/dalvikvm( 7523): >>>>> com.android.email [ userId:0 | appId:10157 ],
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1,
,D/TimaKeyStoreProvider( 7523): in addTimaSignatureService
,V/RouteController( 1916): RTNETLINK answers: No such file or directory,
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
,D/TimaKeyStoreProvider( 7523): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7523): Added TimaKesytore provider,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such process,
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2407): updateIfacesLocked(),
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): performPollLocked(flags=0x1)
V/NetworkStats( 2407): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit,
V/NetworkStats( 2407): performPollLocked() took 18ms
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/dalvikvm( 7523): GC_CONCURRENT freed 2981K, 28% free 9581K/13288K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7523): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,I/SELinux ( 7556): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7556):  
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,I/SELinux ( 7556): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7556):  
I/SELinux ( 7556):  
,I/SELinux ( 7556): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7556): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7556): >>>>> Normal User
,E/dalvikvm( 7556): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7556): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7556): in addTimaSignatureService
I/ActivityManager( 2407): Killing 6352:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7556): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7556): Added TimaKesytore provider
W/ActivityManager( 2407): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2407): Killing 6012:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7569): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7569):  
,D/dalvikvm( 7556): GC_CONCURRENT freed 3002K, 29% free 9572K/13296K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7556): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/SELinux ( 7569): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7569):  
I/SELinux ( 7569):  
,I/SELinux ( 7569): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7569): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7569): >>>>> Normal User
,E/dalvikvm( 7569): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7569): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 7556): onCreate
,D/BadgeProvider( 7556): DatabaseHelper
,D/TimaKeyStoreProvider( 7569): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7569): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7569): Added TimaKesytore provider
,D/BadgeProvider( 7556): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7556): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2768): reloadBadges entered.
D/BadgeProvider( 7556): sendNotify, [notify] : null
D/BadgeProvider( 7556): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7556): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7556): update, [UpdateCount] : 1
,D/dalvikvm( 7569): GC_CONCURRENT freed 3006K, 29% free 9566K/13296K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7569): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/hcjo    ( 5983): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5983): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5983): exit::IDLE
,D/InitializeManagerStateMachine( 5983): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5983): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5983): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5983): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5983): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5983): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5983): entry::SUCCESS
,D/hcjo    ( 5983): AutoUpdateManager:INITCHECK:onInitializeSuccess,
D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5983): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5983): exit::SUCCESS
,D/InitializeManagerStateMachine( 5983): entry::IDLE
,D/Tethering( 2407): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2407): MasterInitialState.processMessage what=3
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/CaptivePortalTracker( 2407): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection...
,E/SPPClientService( 5561): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5561): [SystemStateMoniter] Current Time : 286705
,E/SPPClientService( 5561): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5561): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 1462 latestRequest time : 1452764163239 current time : 1452764164701
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5561): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5561): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5561): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5561): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2407): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2407
E/SPPClientService( 5561): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5561): [a] [ConnectionManager] Connection is already disconnected.
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2407): stay LED for fully charged
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,E/SPPClientService( 5561): [g] getNetMCC return empty string
I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4016): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/KLMS-2.3.201 : ( 7414): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7414): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452764165197
,I/KLMS-2.3.201 : ( 7414): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7426): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3391): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3391): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3391): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3391): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7426): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3520): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/dalvikvm( 7394): Total arena pages for JIT: 11
I/dalvikvm( 7394): Total arena pages for JIT: 12
,I/SELinux ( 7593): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7593):  
I/dalvikvm( 7394): Total arena pages for JIT: 13
,I/dalvikvm( 7394): Total arena pages for JIT: 14
I/dalvikvm( 7394): Total arena pages for JIT: 15
,I/dalvikvm( 7394): Total arena pages for JIT: 16
,I/dalvikvm( 7394): Total arena pages for JIT: 17
,I/SELinux ( 7593): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7593):  
I/SELinux ( 7593):  
,I/SELinux ( 7593): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7593): >>>>> Normal User
,E/dalvikvm( 7593): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7593): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7593): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7593): Added TimaKesytore provider
,I/SELinux ( 7605): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7605):  
,I/SA      ( 5831): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,I/SA      ( 5831): [BDLM] already registered in spp,
,I/SA      ( 5831): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5831): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,I/SELinux ( 7605): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7605):  
I/SELinux ( 7605):  
I/SELinux ( 7605): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7605): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7605): >>>>> Normal User
,E/dalvikvm( 7605): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7605): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SA      ( 5831): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5831): [OR] == isSIMCardReady false ==
,I/SA      ( 5831): [SCU] == networkStateCheck == true
I/SA      ( 5831): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5831): isChinaCountryCode : false
,I/SA      ( 5831): [OR] == networkStateCheck true ==
,I/SA      ( 5831): [OR] GetMyCountryZoneTask
,I/SA      ( 5831): [OR] onReceive END
,I/SA      ( 5831): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 7605): in addTimaSignatureService
,I/SA      ( 5831): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5831): [SSP] query invoked
,D/dalvikvm( 7593): GC_CONCURRENT freed 3003K, 29% free 9563K/13288K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7593): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/TimaKeyStoreProvider( 7605): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7605): Added TimaKesytore provider
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7438): Other Intent
,I/SA      ( 5831): [TPMU] GetMccFromDB : null
I/SA      ( 5831): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5831): [TPM] isNoProxy(default) : true
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5831): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7451): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,W/WifiP2pStateTracker( 2407): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2407): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2407):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2407): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2407): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 7605): GC_CONCURRENT freed 3002K, 29% free 9567K/13296K, paused 2ms+1ms, total 43ms
,D/dalvikvm( 7605): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/Headlines( 5894): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5894): getCountryCode(): countryCode = PL,
,V/KVNProvider( 7605): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query,
V/KVNProvider( 7605): getFindoCursor query string : ,
D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5894): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5894): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5894): requestUpdateNewsWelcomeCard !!! no welcome card,
,I/iu.Environment( 5962): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,V/KVNProvider( 7605): getTagSearchCursor() tagSearchCursor count : 0,
,D/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
I/QuickConnect[1.1][2] ( 5163): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5163): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42214e10
,I/iu.UploadsManager( 5962): num queued entries: 0,
,I/iu.UploadsManager( 5962): num updated entries: 0,
,I/iu.SyncManager( 5962): NEXT; no task,
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
I/ActivityManager( 2407): Killing 6286:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection - timeout,
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state,
,D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection...,
,D/hcjo    ( 5983): AutoUpdateManager:IDLE:execute,
D/InitializeManagerStateMachine( 5983): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5983): exit::IDLE,
,D/InitializeManagerStateMachine( 5983): entry::NETWORK_CHECK,
D/InitializeManagerStateMachine( 5983): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5983): exit::NETWORK_CHECK,
D/InitializeManagerStateMachine( 5983): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5983): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5983): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5983): entry::SUCCESS
,D/hcjo    ( 5983): AutoUpdateManager:INITCHECK:onInitializeSuccess,
D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5983): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
,D/InitializeManagerStateMachine( 5983): exit::SUCCESS,
,D/InitializeManagerStateMachine( 5983): entry::IDLE,
,I/System.out( 7394): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
E/SPPClientService( 5561): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5561): [SystemStateMoniter] Current Time : 287851
,E/SPPClientService( 5561): [SystemStateMoniter] No Connect : false
I/System.out( 7394): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7394): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PackageManager( 2407): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Watchdog( 2407): !@Sync 9
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 330, Delta = 20
,I/System.out( 7394): AsyncTask #1 calls detatch()
,W/System.err( 7394): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7394): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7394): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7394): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7394): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7394): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7394): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7394): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7394): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7394): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7394): Caused by: java.lang.NullPointerException
W/System.err( 7394): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7394): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7394): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7394): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7394): 	... 8 more
,I/ActivityManager( 2407): Killing 6183:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 5561): GC_CONCURRENT freed 2000K, 22% free 10442K/13272K, paused 5ms+3ms, total 38ms
,I/SA      ( 5831): [RC New] [v2liruge] api execute + 1072
,I/SA      ( 5831): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5831): AsyncTask #2 calls detatch()
,I/SA      ( 5831): [TPMU] getNetworkMcc : 
,I/SA      ( 5831): [SCU] saveMccToPreferece Start
,I/SA      ( 5831): [SCU] RegionMCC : 260
,I/SA      ( 5831): [SSP] query invoked
,I/SA      ( 5831): [TPMU] GetMccFromDB : null
,I/SA      ( 5831): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5831): [SCU] saveMccToPreferece End
,I/SA      ( 5831): [RC New] executeRequest [v2liruge] end. 1098
,I/SA      ( 5831): [RC New] Execute end
,I/SA      ( 5831): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5831): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/AmoledAdjustTimer( 2407): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/ActivityManager( 2407): Killing 6220:com.google.android.music:main/u0a125 (adj 15): empty #43
,E/WifiStateMachine( 2407): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 2407): GC_EXPLICIT freed 2271K, 72% free 25437K/88436K, paused 9ms+23ms, total 252ms
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
,E/SPPClientService( 5561): [b] __InitReply__
D/PowerManagerService( 2407): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2407) eventTime = 290561
D/PowerManagerService( 2407): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2407 (0x0)
D/PowerManagerService( 2407): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2407, ws=WorkSource{1000}) (elapsedTime=3689)
,I/GAV2    ( 7463): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6612): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6612): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6612): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6612): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6612): [ensureRegistration] - No Samsung account,
,D/PreloadUpdateManagerStateMachine( 5983): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5983): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5983): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5983): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5983): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5983): entry::IDLE,
,D/CaptivePortalTracker( 2407): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,D/CaptivePortalTracker( 2407): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2407): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2407): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2407): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2407): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2407): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2407): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/PowerManagerService( 2407): [PWL] Off : 180s ago,
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2407): stay LED for fully charged
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 4016): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7303): Test app app.js loaded,
I/jxcore-log( 7303): 
,I/chromium( 7303): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/jxcore-log( 7303): --= Surplus to requirements =--,
I/jxcore-log( 7303): 
I/jxcore-log( 7303): ****TEST TOOK:  ms ****
I/jxcore-log( 7303): 
,I/jxcore-log( 7303): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 7303): 
,D/AndroidRuntime( 7647): ,
D/AndroidRuntime( 7647): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7647): CheckJNI is OFF
,D/AndroidRuntime( 7647): setted country_code = Poland
,D/AndroidRuntime( 7647): setted countryiso_code = PL
D/AndroidRuntime( 7647): setted sales_code = PLS
,D/AndroidRuntime( 7647): readGMSProperty: start
D/AndroidRuntime( 7647): readGMSProperty: already setted!!
D/AndroidRuntime( 7647): readGMSProperty: end
,D/AndroidRuntime( 7647): addProductProperty: start,
,D/dalvikvm( 7647): Trying to load lib libjavacore.so 0x0,
D/PreloadUpdateManagerStateMachine( 5983): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5983): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5983): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5983): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/dalvikvm( 7647): Added shared lib libjavacore.so 0x0
D/PreloadUpdateManagerStateMachine( 5983): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5983): entry::IDLE
,D/dalvikvm( 7647): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7647): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7647): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7647): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7647): failed to load memtrack module: -2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 7647): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7647): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2407): START PACKAGE DELETE: observer{1123425360},
D/PackageManager( 2407): pkg{<packageName>}
D/PackageManager( 2407): user{0}
D/ApplicationPolicy( 2407): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2407): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2407): deletePackageX- pkg:com.test.thalitest, userId:0,
D/PackageManager( 2407): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2407): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2407): !@killApplicatoin: 10621, uninstall pkg,
,I/ActivityManager( 2407): Killing 7303:com.test.thalitest/u0a621 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2407): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (8/10),
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/10)
,I/WindowState( 2407): WIN DEATH: Window{42f1de18 u0 com.test.thalitest/com.test.thalitest.MainActivity},
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/10)
D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2407): Skipping PackageSetting{42b65b78 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2407): setPackageStoppedState - Execution time: 105 ms
D/PackageManager( 2407): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10621, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 2954): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/dalvikvm( 6772): GC_EXPLICIT freed 159K, 27% free 9959K/13512K, paused 2ms+4ms, total 50ms
,D/dalvikvm( 6450): GC_EXPLICIT freed 2529K, 26% free 9885K/13292K, paused 3ms+5ms, total 53ms
,D/dalvikvm( 2954): GC_EXPLICIT freed 154K, 25% free 9970K/13276K, paused 3ms+5ms, total 45ms
D/PackageManager( 2407): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10621, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4757): [3.19.140541][Line:408][onResume] 
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,I/DBG_DM  ( 4757): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,E/SamsungIME( 3002): mOCRHelper is null
,I/InputReader( 2407): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 5163): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,D/dalvikvm( 3571): GC_EXPLICIT freed 2195K, 20% free 12427K/15344K, paused 4ms+9ms, total 138ms
,I/DBG_DM  ( 4757): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "sms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7658): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7658):  
,I/DBG_DM  ( 4757): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/DBG_DM  ( 4757): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/SELinux ( 7658): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7658):  
I/SELinux ( 7658):  
,I/SELinux ( 7658): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7658): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7658): >>>>> Normal User
,E/dalvikvm( 7658): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7658): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4757): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider( 7658): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7658): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7658): Added TimaKesytore provider
,I/DBG_DM  ( 4757): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/PackageManager( 2407): queryIntentReceivers - Execution time: 107 ms
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 2407): GC_EXPLICIT freed 1702K, 72% free 25048K/88436K, paused 13ms+23ms, total 211ms
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2407):   Scheme: "smsto"
,I/DBG_DM  ( 4757): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "mms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4757): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4757): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4757): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4757): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/RCPManagerService( 2407): PackageReceiver onReceive()
,D/Activity( 4757): setTransGradationMode to true
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4757): [3.19.140541][Line:400][onPause] 
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "mmsto"
D/StatusBarManagerService( 2407): semi p:4757,o:t
,I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2407): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/RegisteredServicesCache( 2756): empty dynamic service
D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "sms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "smsto"
,I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 7658): GC_CONCURRENT freed 3000K, 29% free 9565K/13288K, paused 4ms+2ms, total 28ms
D/dalvikvm( 7658): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "mms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2407): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2407):   Scheme: "mmsto"
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,W/InputMethodManagerService( 2407): Got RemoteException sending setActive(false) notification to pid 7303 uid 10621,
,D/elm:14132( 7658): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) },
,D/elm:14132( 7658): ELMEngine.ELMEngine( context ).,
,D/elm:14132( 7658): MDMBridge.setEnterpriseBridge(),
,D/elm:14132( 7658): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.,
,D/elm:14132( 7658): ElmAgentService : onCreate(),
,D/elm:14132( 7658): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7658): MainReceiver.listeningToPackageRemoved(),
D/elm:14132( 7658): MDMBridge.getInstance(),
,D/elm:14132( 7658): MDMBridge.getAllLicenseInfoFromSDK(),
,I/SELinux ( 7672): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7672):  
,D/elm:14132( 7658): MDMBridge.getAllLicenseInfoFromSDK(),
,D/dalvikvm( 2756): GC_CONCURRENT freed 1211K, 26% free 10610K/14184K, paused 7ms+3ms, total 94ms,
,D/dalvikvm( 2756): WAIT_FOR_CONCURRENT_GC blocked 40ms,
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 8% free 9502K/10272K, paused 3ms+3ms, total 35ms,
I/SELinux ( 7672): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7672):  
I/SELinux ( 7672):  
,I/SELinux ( 7672): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7672): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7672): >>>>> Normal User
,E/dalvikvm( 7672): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7672): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7672): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9502K/10272K, paused 4ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7672): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7672): Added TimaKesytore provider
,D/elm:14132( 7658): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/EnterpriseDeviceManagerService( 2407): Package has changed for user 0
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9502K/10272K, paused 2ms+3ms, total 26ms
,D/elm:14132( 7658): ElmAgentService : onDestroy().
I/ActivityManager( 2407): Killing 6553:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/dalvikvm( 2407): GC_EXPLICIT freed 863K, 72% free 25196K/88436K, paused 8ms+53ms, total 430ms
D/PackageManager( 2407): delete sourFile : 
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2407): delete native library directory: 
,D/AndroidRuntime( 7647): Shutting down VM
D/PackageManager( 2407): return delete result to caller: 1123425360
,D/PackageManager( 2407): returnCode: 1
,D/dalvikvm( 7647): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms,
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
D/BackupManagerService( 2407): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2407): removePackageParticipantsLocked: uid=10621 #1
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "sms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7672): GC_CONCURRENT freed 3004K, 29% free 9568K/13296K, paused 2ms+2ms, total 29ms,
,D/dalvikvm( 7672): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2407): sendNotification(2) - 4,
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "smsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "mms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2407):   Scheme: "mmsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7687): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7687):  
I/ActivityManager( 2407): Killing 6470:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 7687): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7687):  
I/SELinux ( 7687):  
,I/SELinux ( 7687): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7687): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7687): >>>>> Normal User
,E/dalvikvm( 7687): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7687): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7687): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7687): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7687): Added TimaKesytore provider
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7687): GC_CONCURRENT freed 2997K, 28% free 9571K/13292K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7687): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteDatabase( 7687): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase( 7687): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7687): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7687): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7687): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7687): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7687): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase( 7687): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 7687): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7687): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7687): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7687): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7687): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7687): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7687): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7687): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7687): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7687): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7687): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7687): Shutting down VM
,W/dalvikvm( 7687): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/AndroidRuntime( 7687): FATAL EXCEPTION: main
E/AndroidRuntime( 7687): Process: com.sec.android.app.mss, PID: 7687
E/AndroidRuntime( 7687): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7687): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7687): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7687): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7687): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7687): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7687): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7687): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7687): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7687): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7687): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7687): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7687): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7687): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7687): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7687): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7687): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7687): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 7687): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 7687): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7687): 	... 10 more
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/Process ( 7687): Sending signal. PID: 7687 SIG: 9
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop216.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
I/ActivityManager( 2407): Process com.sec.android.app.mss (pid 7687) (adj 9) has died.
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
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
,I/CrashAnrDetector( 2407): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2407): clearDefaults: com.test.thalitest
,I/SA      ( 5831): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5831): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,W/AtomicFile( 2407): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2407): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SharedPreferencesImpl( 3520): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/SQLiteLog( 6027): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6027): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6027): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6027): Process: com.sec.android.app.shealth, PID: 6027
E/AndroidRuntime( 6027): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6027): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6027): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6027): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6027): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6027): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6027): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6027): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6027): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6027): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6027): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6027): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6027): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6027): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Icing.InternalIcingCorporaProvider( 6450): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 6450): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6450): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop217.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/SELinux ( 7709): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7709):  
,E/AndroidRuntime( 6450): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6450): Process: com.google.android.googlequicksearchbox:search, PID: 6450
E/AndroidRuntime( 6450): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6450): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6450): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6450): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6450): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6450): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6450): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6450): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6450): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6450): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6450): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6450): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6450): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 6027): Sending signal. PID: 6027 SIG: 9
,I/Process ( 6450): Sending signal. PID: 6450 SIG: 9
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/ActivityManager( 2407): Process com.sec.android.app.shealth (pid 6027) (adj 5) has died.
,I/SELinux ( 7709): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7709):  
I/SELinux ( 7709):  
,I/SELinux ( 7709): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7709): >>>>> Normal User
,E/dalvikvm( 7709): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2407): Process com.google.android.googlequicksearchbox:search (pid 6450) (adj 5) has died.
,D/TimaKeyStoreProvider( 7709): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7709): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7709): Added TimaKesytore provider
,D/dalvikvm( 7709): GC_CONCURRENT freed 2986K, 28% free 9577K/13292K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7709): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/UserAnalysis.PlaceProvider( 7709): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7709): Create SecureDbHelper
,E/SQLiteDatabase( 7709): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7709): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7709): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7709): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7709): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7709): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7709): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7709): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7709): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7709): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7709): Opened privacy in read-only mode,
E/SQLiteDatabase( 7709): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7709): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7709): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7709): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7709): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7709): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7709): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7709): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7709): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7709): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7709): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7709): Opened privacy in read-only mode
,E/SQLiteDatabase( 7709): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7709): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7709): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7709): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7709): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7709): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteData,base.java:696)
W/System.err( 7709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7709): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7709): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7709): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7709): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7709): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7709): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7709): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7709): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6464):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2407):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2407): queryAllProviders():  providerCallBack is not register for 0
E/SQLiteDatabase( 6384): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
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
E/SQLiteDatabase( 6384): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6384): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6384): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6384): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6384): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CapabilityManagerService New( 6683): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6683): The package(com.test.thalitest) removed
W/System.err( 2407): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6384): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2407): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2407): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2407): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2407): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2407): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2407): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 6384): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2407): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6384): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 2407): 	... 8 more
W/System.err( 6384): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 2407): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2407): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 6384): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6384): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6384): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 2407): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 6384): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6384): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6384): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
,W/System.err( 2407): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2407): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 6384): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6384): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6384): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6384): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@8
W/System.err( 2407): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 6384): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6384): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6384): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6384): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2407): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2407): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6384): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2407): 	... 8 more
D/MagazineService::MagazineBroadcastReceiver( 6708): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
I/MagazineService::MagazineService( 6708): [onHandleIntent] ACTION_PACKAGE_REMOVED
E/SQLiteDatabase( 6708): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6708): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6708): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6708): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6708): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6708): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6708): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6708): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6708): threadid=10: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 6708): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6708): Process: com.samsung.android.magazine.service, PID: 6708
E/AndroidRuntime( 6708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6708): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6708): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6708): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6708): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6708): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6708): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6708): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 7724): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7724):  
,I/Process ( 6708): Sending signal. PID: 6708 SIG: 9
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/ActivityManager( 2407): Process com.samsung.android.magazine.service (pid 6708) (adj 5) has died.
,I/SELinux ( 7724): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7724):  
I/SELinux ( 7724):  
,I/SELinux ( 7724): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7724): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7724): >>>>> Normal User
,E/dalvikvm( 7724): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7724): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/AmoledAdjustTimer( 2407): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaKeyStoreProvider( 7724): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7724): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7724): Added TimaKesytore provider
,D/dalvikvm( 7724): GC_CONCURRENT freed 3004K, 29% free 9566K/13296K, paused 3ms+1ms, total 18ms
,D/dalvikvm( 7724): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/ContextImpl( 7724): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7724): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7724): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7724): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7724): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7724): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7724): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7724): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7724): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7724): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7724): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7724): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7724): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsModeInstallReceiver( 6734): onReceive intent data =  package:com.test.thalitest
,E/AndroidRuntime( 7724): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7724): Process: com.android.keychain, PID: 7724
E/AndroidRuntime( 7724): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7724): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7724): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7724): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7724): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7724): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7724): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7724): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7724): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7724): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/KidsPlatformStub( 6734): Package not found : com.sec.android.app.kidshome
,I/Process ( 7724): Sending signal. PID: 7724 SIG: 9
,E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
W/System.err( 6772): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6772): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6772): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6772): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6772): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6772): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6772): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6772): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6772): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6772): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6772): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6772): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6772): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager( 2407): Process com.android.keychain (pid 7724) (adj 5) has died.
D/PackageBroadcastService( 3571): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 3571): Clearing selected account for com.test.thalitest
,E/SQLiteLog( 3571): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3571): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3571): disk I/O error (code 3850)
E/DriveAsyncService( 3571): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3571): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3571): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3571): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3571): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3571): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3571): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3571): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3571): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3571): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3571): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3571): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3571): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3571): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3571): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3571): 	at java.lang.Thread.run(Thread.java:841)
,I/LocationSettingsChecker( 3571): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 3571): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3571): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2849): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2849): Shutting down VM
,W/dalvikvm( 2849): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 3571): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 3571): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3571): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3571): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3571): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3571): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3571): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3571): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3571): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3571): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3571): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3571): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3571): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3571): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3571): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3571): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3571): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3571): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3571): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3571): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3571): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3571): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3571): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3571): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3571): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3571): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3571): 	at android.os.HandlerThread.run(HandlerThread.java:61)
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
E/SQLiteLog( 3571): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3571): threadid=48: thread exiting with uncaught exception (group=0x4180ac08)
W/SQLiteOpenHelper( 3571): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3571): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 3571): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 3571): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 3571): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3571): threadid=47: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3571): Sending signal. PID: 3571 SIG: 9
,E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/Process ( 2849): Sending signal. PID: 2849 SIG: 9
,E/SQLiteDatabase( 5561): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5561): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5561): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322),
E/SQLiteDatabase( 5561): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5561): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5561): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5561): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5561): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5561): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5561): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5561): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5561): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5561): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5561): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5561): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5561): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5561): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5561): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5561): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.,
,E/SQLiteDatabase( 6427): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.,
E/SQLiteDatabase( 6427): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6427): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6427): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6427): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6427): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteData,base( 6427): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6427): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6427): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6427): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6427): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6427): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,E/SQLiteDatabase( 6427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6427): 	at dalvik.system.NativeStart.main(Native Method)
E/LNoti   ( 6427): [g] not an error (code 0): Could not open the database in read/write mode.
I/SELinux ( 7750): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7750):  
,D/GAV2    ( 5657): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService},
I/ActivityManager( 2407): Process com.google.process.gapps (pid 2849) (adj 5) has died.
I/ActivityManager( 2407): Process com.google.android.gms (pid 3571) (adj 5) has died.
,E/SQLiteDatabase( 6427): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.,
E/SQLiteDatabase( 6427): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6427): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859),
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6427): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6427): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6427): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6427): ,	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6427): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6427): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6427): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6427): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6427): ,	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6427): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6427): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6427): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
,I/GAV2    ( 5657): Thread[main,5,main]: Unexpected disconnect.,
,I/SELinux ( 7750): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7750):  
I/SELinux ( 7750):  
I/SELinux ( 7750): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7750): >>>>> Normal User
,E/dalvikvm( 7750): >>>>> com.android.documentsui [ userId:0 | appId:10093 ],
,E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7750): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7750): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7750): Added TimaKesytore provider
,I/ActivityManager( 2407): Waited long enough for: ServiceRecord{46b90aa8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/dalvikvm( 7750): GC_CONCURRENT freed 3002K, 29% free 9568K/13292K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7750): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/Documents( 7750): Loading roots for com.android.externalstorage.documents
,I/SELinux ( 7765): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7765):  
,E/SQLiteDatabase( 7750): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
E/SQLiteDatabase( 7750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7750): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7750): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
,E/SQLiteDatabase( 7750): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7750): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7750): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7750): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7750): 	,at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7750): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7750): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7750): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7750): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7750): Shutting down VM,
,W/dalvikvm( 7750): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7750): FATAL EXCEPTION: main
E/AndroidRuntime( 7750): Process: com.android.documentsui, PID: 7750
E/AndroidRuntime( 7750): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
,E/AndroidRuntime( 7750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7750): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7750): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7750): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7750): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7750): 	,at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7750): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7750): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7750): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7750): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7750): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
,E/AndroidRuntime( 7750): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7750): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7750): 	... 10 more
,I/SELinux ( 7769): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7769):  
,I/Process ( 7750): Sending signal. PID: 7750 SIG: 9,
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
,E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/ActivityManager( 2407): Process com.android.documentsui (pid 7750) (adj 9) has died.,
I/SELinux ( 7765): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7765):  
,I/SELinux ( 7765):  
I/SELinux ( 7765): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7765): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7765): >>>>> Normal User
,E/dalvikvm( 7765): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ],
,E/SELinux ( 7765): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/SELinux ( 7769): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7769):  
I/SELinux ( 7769):  
,I/SELinux ( 7769): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7769): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7769): >>>>> Normal User
,E/dalvikvm( 7769): >>>>> com.google.android.gms [ userId:0 | appId:10012 ],
D/TimaKeyStoreProvider( 7765): in addTimaSignatureService,
,E/SELinux ( 7769): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7765): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7765): Added TimaKesytore provider,
,D/TimaKeyStoreProvider( 7769): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7769): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7769): Added TimaKesytore provider,
,D/dalvikvm( 7765): GC_CONCURRENT freed 2999K, 29% free 9565K/13292K, paused 3ms+1ms, total 19ms,
,D/dalvikvm( 7765): WAIT_FOR_CONCURRENT_GC blocked 14ms,
,D/ExternalStorage( 7765): After updating volumes, found 1 active roots,
,D/dalvikvm( 7769): GC_CONCURRENT freed 2936K, 28% free 9630K/13292K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 7769): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/dalvikvm( 7769): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7769): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7769): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7769): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7769): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7769): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7769): install
,I/MultiDex( 7769): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7769): loading existing secondary dex files
,I/MultiDex( 7769): load found 3 secondary dex files
,I/MultiDex( 7769): install done,
,I/SELinux ( 7791): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7791):  
,I/SELinux ( 7791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7791):  
I/SELinux ( 7791):  
I/SELinux ( 7791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7791): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7791): >>>>> Normal User
,E/dalvikvm( 7791): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7791): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7791): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7791): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7791): Added TimaKesytore provider
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
,D/dalvikvm( 7791): GC_CONCURRENT freed 2989K, 28% free 9576K/13288K, paused 3ms+1ms, total 34ms
,D/dalvikvm( 7791): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 7805): GC_CONCURRENT freed 2993K, 28% free 9581K/13296K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7805): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Icing.InternalIcingCorporaProvider( 7791): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7821):  
,D/LocationManagerService( 2407): getProviders()=[passive]
,I/SELinux ( 7821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7821):  
I/SELinux ( 7821):  
,I/SELinux ( 7821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7821): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7821): >>>>> Normal User
,E/dalvikvm( 7821): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7821): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
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
,W/dalvikvm( 7805): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7805): FATAL EXCEPTION: main
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
,D/TimaKeyStoreProvider( 7821): in addTimaSignatureService
,E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
D/TimaKeyStoreProvider( 7821): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7821): Added TimaKesytore provider
I/ActivityManager( 2407): Process com.google.process.gapps (pid 7805) (adj 0) has died.
W/ActivityManager( 2407): Service crashed 2 times, stopping: ServiceRecord{42ec46c0 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7839): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7839):  
,I/SELinux ( 7839): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7839):  
I/SELinux ( 7839):  
,I/SELinux ( 7839): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7839): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7839): >>>>> Normal User
,E/dalvikvm( 7839): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7839): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7839): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7839): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7839): Added TimaKesytore provider
,D/dalvikvm( 7821): GC_CONCURRENT freed 2997K, 29% free 9567K/13292K, paused 5ms+1ms, total 24ms
,D/dalvikvm( 7821): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7839): GC_CONCURRENT freed 2994K, 28% free 9578K/13296K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7839): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7839): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7839): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7839): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7839): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7839): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7839): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7839): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7839): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7839): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7839): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7839): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7839): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7839): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7839): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7839): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7839): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7839): Shutting down VM
,W/dalvikvm( 7839): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7839): FATAL EXCEPTION: main
E/AndroidRuntime( 7839): Process: com.google.process.gapps, PID: 7839
E/AndroidRuntime( 7839): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7839): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7839): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7839): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7839): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7839): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7839): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7839): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7839): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7839): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7839): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7839): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7839): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7839): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7839): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7839): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7839): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7839): 	... 12 more
W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 7839:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /d,ata/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7821): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7769): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7791): Failed to find provider info for com.google.settings
,I/SELinux ( 7857): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7857):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 8% free 9502K/10272K, paused 2ms+2ms, total 27ms
,I/SELinux ( 7857): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7857):  
I/SELinux ( 7857):  
,I/SELinux ( 7857): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7857): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7857): >>>>> Normal User
,E/dalvikvm( 7857): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7857): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7857): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9502K/10272K, paused 3ms+2ms, total 26ms
,D/TimaKeyStoreProvider( 7857): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7857): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9502K/10272K, paused 3ms+3ms, total 25ms,
,D/dalvikvm( 7857): GC_CONCURRENT freed 2987K, 28% free 9582K/13292K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7857): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7857): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7857): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
,E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7857): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7857): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7857): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7857): ,	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7857): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7857): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7857): ,	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7857): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7857): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7857): Shutting down VM,
,W/dalvikvm( 7857): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 7857): FATAL EXCEPTION: main
E/AndroidRuntime( 7857): Process: com.google.process.gapps, PID: 7857
E/AndroidRuntime( 7857): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7857): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7857): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7857): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7857): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7857): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7857): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7857): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7857): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7857): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7857): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7857): 	... 12 more
,I/Process ( 7857): Sending signal. PID: 7857 SIG: 9
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 7857) (adj 0) has died.
,I/SELinux ( 7872): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7872):  
,I/SELinux ( 7872): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7872):  
I/SELinux ( 7872):  
,I/SELinux ( 7872): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7872): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7872): >>>>> Normal User
,E/dalvikvm( 7872): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7872): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7872): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7872): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7872): Added TimaKesytore provider
,D/dalvikvm( 7872): GC_CONCURRENT freed 3000K, 29% free 9568K/13292K, paused 1ms+2ms, total 17ms
,D/dalvikvm( 7872): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7872): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7872): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7872): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7872): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7872): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7872): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7872): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7872): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7872): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7872): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7872): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7872): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7872): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7872): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7872): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7872): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7872): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7872): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7872): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7872): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7872): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7872): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7872): Shutting down VM
,W/dalvikvm( 7872): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7872): FATAL EXCEPTION: main
E/AndroidRuntime( 7872): Process: com.google.process.gapps, PID: 7872
E/AndroidRuntime( 7872): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7872): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7872): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7872): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7872): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7872): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7872): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7872): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7872): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7872): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7872): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7872): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7872): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7872): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7872): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7872): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7872): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7872): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7872): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7872): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7872): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7872): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7872): 	... 12 more
W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 7872:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7821): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,E/ActivityThread( 7769): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7769): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7769): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7769): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7769): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7769): VFY: unable to resolve instance field 36
D/dalvikvm( 7769): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7769): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7769): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7769): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7769): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7769): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7769): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422006a0
D/dalvikvm( 7769): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422006a0
D/dalvikvm( 7769): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422006a0, skipping init
D/dalvikvm( 7769): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422006a0
D/dalvikvm( 7769): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422006a0
V/JNIHelp ( 7769): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7769): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422006a0
,D/dalvikvm( 7769): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422006a0
D/dalvikvm( 7769): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422006a0
,D/dalvikvm( 7769): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422006a0
,I/ProviderInstaller( 7769): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7887): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7887):  
,I/SELinux ( 7887): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7887):  
I/SELinux ( 7887):  
,I/SELinux ( 7887): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7887): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7887): >>>>> Normal User
,E/dalvikvm( 7887): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7887): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7887): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7887): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7887): Added TimaKesytore provider
,D/dalvikvm( 7887): GC_CONCURRENT freed 2994K, 28% free 9572K/13292K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 7887): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7887): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7887): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7887): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7887): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7887): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7887): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7887): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7887): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7887): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7887): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7887): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7887): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7887): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7887): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7887): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7887): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7887): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7887): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7887): Shutting down VM
,W/dalvikvm( 7887): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7887): FATAL EXCEPTION: main
E/AndroidRuntime( 7887): Process: com.google.process.gapps, PID: 7887
E/AndroidRuntime( 7887): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7887): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7887): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7887): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7887): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7887): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7887): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7887): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7887): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7887): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7887): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7887): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7887): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7887): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7887): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7887): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7887): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7887): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7887): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7887): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7887): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7887): 	... 12 more
,I/Process ( 7887): Sending signal. PID: 7887 SIG: 9
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
I/ActivityManager( 2407): Waited long enough for: ServiceRecord{45dbf328 u0 com.sec.spp.push/.PushClientService}
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 7887) (adj 0) has died.
,I/SELinux ( 7902): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7902):  
,I/SELinux ( 7902): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7902):  
I/SELinux ( 7902):  
,I/SELinux ( 7902): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7902): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7902): >>>>> Normal User
,E/dalvikvm( 7902): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7902): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7902): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7902): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7902): Added TimaKesytore provider
,D/dalvikvm( 7902): GC_CONCURRENT freed 2998K, 29% free 9572K/13296K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 7902): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7902): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7902): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7902): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7902): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7902): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7902): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7902): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7902): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7902): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7902): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7902): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7902): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7902): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7902): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7902): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7902): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7902): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7902): Shutting down VM
,W/dalvikvm( 7902): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7902): FATAL EXCEPTION: main
E/AndroidRuntime( 7902): Process: com.google.process.gapps, PID: 7902
E/AndroidRuntime( 7902): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7902): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7902): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7902): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7902): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7902): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7902): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7902): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7902): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7902): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7902): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7902): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7902): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7902): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7902): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7902): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7902): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7902): 	... 12 more
W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 7902:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7769): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,W/NativeLibraryUtils( 7769): Failed to open lock file
W/NativeLibraryUtils( 7769): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7769): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7769): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7769): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7769): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7769): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7769): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7769): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7769): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7769): 	... 3 more
,I/dalvikvm( 7769): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7769): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7769): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7921): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7921):  
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
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/SELinux ( 7921): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7921):  
I/SELinux ( 7921):  
,I/SELinux ( 7921): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7921): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7921): >>>>> Normal User
,E/dalvikvm( 7921): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7921): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7921): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7921): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7921): Added TimaKesytore provider
,I/ActivityManager( 2407): Process android.process.acore (pid 2954) (adj -12) has died.
,I/SELinux ( 7934): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7934):  
,I/SELinux ( 7934): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7934):  
I/SELinux ( 7934):  
I/SELinux ( 7934): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 7921): GC_CONCURRENT freed 2996K, 28% free 9579K/13296K, paused 3ms+1ms, total 18ms
,D/dalvikvm( 7921): WAIT_FOR_CONCURRENT_GC blocked 14ms
,E/SELinux ( 7934): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7934): >>>>> Normal User
E/dalvikvm( 7934): >>>>> android.process.acore [ userId:0 | appId:10020 ]
E/SELinux ( 7934): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7934): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7934): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7934): Added TimaKesytore provider
,I/GservicesProvider( 7921): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7921): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7921): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7921): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7921): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7921): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7921): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7921): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7921): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7921): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7921): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7921): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7921): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7921): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7921): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7921): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7921): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7921): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7921): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7921): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7921): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7921): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7921): Shutting down VM
,W/dalvikvm( 7921): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7921): FATAL EXCEPTION: main
E/AndroidRuntime( 7921): Process: com.google.process.gapps, PID: 7921
E/AndroidRuntime( 7921): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7921): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7921): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7921): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7921): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7921): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7921): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7921): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7921): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7921): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7921): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7921): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7921): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7921): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7921): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7921): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7921): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7921): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7921): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7921): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7921): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7921): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7921): 	... 12 more
,I/Process ( 7921): Sending signal. PID: 7921 SIG: 9
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/ActivityManager( 2407): Process com.google.process.gapps (pid 7921) (adj 0) has died.
,D/dalvikvm( 7934): GC_CONCURRENT freed 2982K, 28% free 9587K/13296K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7934): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7949): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7949):  
,I/SELinux ( 7949): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7949):  
I/SELinux ( 7949):  
,I/SELinux ( 7949): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7949): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7949): >>>>> Normal User
,E/dalvikvm( 7949): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7949): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7949): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7949): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7949): Added TimaKesytore provider
,E/SQLiteDatabase( 7934): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7934): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7934): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7934): 	at com.android.provider,s.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7934): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7934): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7934): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7934): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 7949): GC_CONCURRENT freed 2986K, 28% free 9578K/13292K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7949): WAIT_FOR_CONCURRENT_GC blocked 17ms
E/SQLiteLog( 7934): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7934): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7934): (14) unable to open database file
E/SQLiteDatabase( 7934): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7934): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7934): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7934): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7934): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7934): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7934): Process: android.process.acore, PID: 7934
E/AndroidRuntime( 7934): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7934): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7934): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7934): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7934): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7934): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7934): Sending signal. PID: 7934 SIG: 9
W/ActivityManager( 2407): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/ActivityManager( 2407): Process android.process.acore (pid 7934) (adj -12) has died.
,F/ActivityManager( 2407): Service ServiceRecord{4394eb50 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{43033880 7934:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2407): Can't write: system_server_wtf
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop167.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2407): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2407): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2407): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2407): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2407): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2407): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 18 more
,I/SELinux ( 7967): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7967):  
,I/GservicesProvider( 7949): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7949): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7949): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7949): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7949): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7949): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7949): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7949): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7949): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7949): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7949): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7949): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7949): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7949): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7949): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7949): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7949): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7949): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7949): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7949): Shutting down VM
,W/dalvikvm( 7949): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7949): FATAL EXCEPTION: main
E/AndroidRuntime( 7949): Process: com.google.process.gapps, PID: 7949
E/AndroidRuntime( 7949): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7949): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7949): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7949): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7949): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7949): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7949): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7949): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7949): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7949): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7949): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7949): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7949): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7949): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7949): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7949): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7949): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7949): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7949): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7949): 	... 12 more
,I/GAv4-SVC( 7769): Google Analytics 8.4.89 is starting up.
W/ActivityManager( 2407): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2407): Killing 7949:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2407): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7769): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
,I/SELinux ( 7967): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7967):  
I/SELinux ( 7967):  
,I/SELinux ( 7967): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7967): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7967): >>>>> Normal User
,E/dalvikvm( 7967): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7967): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 7973): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7973):  
,D/TimaKeyStoreProvider( 7967): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7967): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7967): Added TimaKesytore provider
,I/SELinux ( 7973): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7973):  
I/SELinux ( 7973):  
,I/SELinux ( 7973): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7973): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7973): >>>>> Normal User
,E/dalvikvm( 7973): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7973): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7973): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7973): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7973): Added TimaKesytore provider
,D/dalvikvm( 7967): GC_CONCURRENT freed 3000K, 29% free 9566K/13288K, paused 1ms+1ms, total 19ms
,D/dalvikvm( 7967): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 7973): GC_CONCURRENT freed 2994K, 28% free 9572K/13292K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7973): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7973): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7973): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7973): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7973): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7973): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7973): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7973): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7973): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7973): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7973): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7973): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7973): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7973): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7973): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7973): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7973): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7973): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7973): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7973): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7973): Shutting down VM
,W/dalvikvm( 7973): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 7967): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7967): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7967): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7967): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7967): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7967): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7967): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7967): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 7973): FATAL EXCEPTION: main
E/AndroidRuntime( 7973): Process: com.google.process.gapps, PID: 7973
E/AndroidRuntime( 7973): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7973): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7973): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7973): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7973): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7973): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7973): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7973): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7973): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7973): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7973): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7973): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7973): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7973): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7973): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7973): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7973): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7973): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7973): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7973): 	... 12 more
,I/Process ( 7973): Sending signal. PID: 7973 SIG: 9
E/SQLiteLog( 7967): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7967): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7967): (14) unable to open database file
,E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
E/SQLiteDatabase( 7967): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7967): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7967): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7967): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7967): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7967): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7967): Process: android.process.acore, PID: 7967
E/AndroidRuntime( 7967): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7967): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7967): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7967): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7967): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7967): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7967): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
