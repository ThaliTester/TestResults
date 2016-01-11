#### Test 549702617cfd775_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2397): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7207): 
D/AndroidRuntime( 7207): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7207): CheckJNI is OFF
D/AndroidRuntime( 7207): setted country_code = Poland
D/AndroidRuntime( 7207): setted countryiso_code = PL
D/AndroidRuntime( 7207): setted sales_code = PLS
D/AndroidRuntime( 7207): readGMSProperty: start
D/AndroidRuntime( 7207): readGMSProperty: already setted!!
D/AndroidRuntime( 7207): readGMSProperty: end
D/AndroidRuntime( 7207): addProductProperty: start
D/dalvikvm( 7207): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7207): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7207): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7207): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7207): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7207): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7207): failed to load memtrack module: -2
D/dalvikvm( 7207): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7207): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2397): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.acquire()
I/SELinux ( 7233): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7233):  
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7207): Shutting down VM
D/dalvikvm( 7207): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7233): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7233):  
I/SELinux ( 7233):  
I/SELinux ( 7233): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7233): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7233): >>>>> Normal User
E/dalvikvm( 7233): >>>>> com.test.thalitest [ userId:0 | appId:10609 ]
E/SELinux ( 7233): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7233): in addTimaSignatureService
D/TimaKeyStoreProvider( 7233): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7233): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4165): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4165): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7233): GC_CONCURRENT freed 2998K, 28% free 9571K/13292K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7233): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7233): Binding Chromium to the background looper Looper (main, tid 1) {4228e0f8}
I/chromium( 7233): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7233): Initializing chromium process, renderers=0
W/chromium( 7233): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7233): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7233): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7233): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7233): Mali API Version : 401
,I/Mali    ( 7233): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7233): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7233): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7233): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7233): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7233): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7233): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2397): tr p:7233,o:f
W/dalvikvm( 7233): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7233): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7233): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7233): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7233): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7233): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7233): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7233): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7233): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7233): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7233): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7233): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7233): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2397): semi p:7233,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7233): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7233): Enabling debug mode 0
,W/AwContents( 7233): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/AwContents( 7233): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7233): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7233): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7233): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4228ee80
,D/dalvikvm( 7233): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4228ee80
,D/jxcore_app_log( 7233): JniHelper::setJavaVM(0x41880220), pthread_self() = 2027606360
,D/JX-Cordova( 7233): jxcore cordova android initializing
,D/dalvikvm( 7233): GC_CONCURRENT freed 1292K, 16% free 11353K/13364K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 7233): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 7233): GC_CONCURRENT freed 1939K, 16% free 14956K/17632K, paused 1ms+3ms, total 39ms
,D/dalvikvm( 7233): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7233): GC_FOR_ALLOC freed 5292K, 28% free 16231K/22496K, paused 51ms, total 54ms
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 7233): GC_CONCURRENT freed 6710K, 30% free 17691K/25144K, paused 1ms+9ms, total 55ms
,D/dalvikvm( 7233): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 7233): GC_FOR_ALLOC freed 1195K, 31% free 17539K/25144K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7233): Grow heap (frag case) to 21.345MB for 3688532-byte allocation
,D/dalvikvm( 7233): GC_FOR_ALLOC freed 2463K, 36% free 18677K/28748K, paused 42ms, total 42ms
,W/jxcore-log( 7233): Initializing JXcore engine
,W/jxcore-log( 7233): JXcore engine is ready
,W/jxcore-log( 7233): Starting JXcore engine
,W/jxcore-log( 7233): Platform android
W/jxcore-log( 7233): 
,W/jxcore-log( 7233): Process ARCH arm
W/jxcore-log( 7233): 
,I/jxcore-log( 7233): JXcore Cordova bridge is ready!
I/jxcore-log( 7233): 
,W/jxcore-log( 7233): JXcore engine is started
,I/chromium( 7233): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7233): Toggling radios to true
I/jxcore-log( 7233): 
,D/BluetoothAdapter( 7233): enable(): BT is already enabled..!
,I/WifiManager( 7233): packageName : com.test.thalitest
,I/WifiManager( 7233): setWifiEnabled : true
,I/WifiService( 2397): setWifiEnabled: true pid=7233, uid=10609
W/ActivityManager( 2397): Permission Denial: getCurrentUser() from pid=7233, uid=10609 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2397): Failed getting userId using ActivityManagerNative
W/WifiService( 2397): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7233, uid=10609 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2397): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2397): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2397): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2397): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2397): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2397): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2397): disconnect: pid=7233, uid=10609
,I/jxcore-log( 7233): Radios toggled
I/jxcore-log( 7233): 
I/wpa_supplicant( 3977): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7233): My device name is: samsung-SM-G800F
I/jxcore-log( 7233): 
,I/wpa_supplicant( 3977): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3977): First Scan Start
,I/wpa_supplicant( 3977): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 2397): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2397): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2397): InactiveState{ what=143375 }
D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3977): Skip scan - already scanning
D/ConnectivityService( 2397): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2397): InactiveState{ what=143375 }
D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2397): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2397): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2397): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2397): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2397): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2397): Attempting to switch to mobile
,D/ConnectivityService( 2397): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 7279): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7279):  
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2397): route cmd failed: 
W/NetworkManagementService( 2397): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
I/SELinux ( 7279): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7279):  
I/SELinux ( 7279):  
I/SELinux ( 7279): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7279): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7279): >>>>> Normal User
,E/dalvikvm( 7279): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ],
V/RouteController( 1915): RTNETLINK answers: No such process
E/SELinux ( 7279): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
E/WifiStateMachine( 2397): Error! unhandled message{ when=-95ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2397): Error! unhandled message{ when=-94ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,E/WifiStateMachine( 2397): Error! unhandled message{ when=-16ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetUtils( 2397): android_net_utils_resetConnections in env=0x77e27fa0 clazz=0x62300001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2397): resetConnections(wlan0, 3)
D/TimaKeyStoreProvider( 7279): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7279): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7279): Added TimaKesytore provider
,V/NativeCrypto( 2849): Read error: ssl=0x7be86320: I/O error during system call, Connection timed out
,V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7be86320: I/O error during system call, Broken pipe
,D/dalvikvm( 7279): GC_CONCURRENT freed 2985K, 28% free 9582K/13288K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 7279): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/SPPClientService( 5543): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5543): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5543): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5543): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5543): [b] ResponseMap empty
,I/System.out( 7279): Inside WakeupProvider
,I/System.out( 7279): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7279): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7279): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7279): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/ConnectivityService( 2397): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): updateIfacesLocked()
V/NetworkStats( 2397): performPollLocked(flags=0x1)
V/NetworkStats( 2397): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): performPollLocked() took 25ms
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NearbySettings( 2818): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2818): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2818): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2818): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7279): initQueue()
I/ActivityManager( 2397): Killing 6175:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2818): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2818): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2818): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2818): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2397): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2397): updateDataUsageMap
,D/Tethering( 2397): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2397): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2397): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6590): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6590): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6590): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6590): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/DBG_DM  ( 4741): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6590): noConnectivity : true
,I/SELinux ( 7308): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7308):  
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7308): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7308):  
I/SELinux ( 7308):  
,I/SELinux ( 7308): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7308): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7308): >>>>> Normal User
,E/dalvikvm( 7308): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7308): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7308): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7308): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7308): Added TimaKesytore provider
,I/wpa_supplicant( 3977): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 3977): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
D/Tethering( 2397): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3977): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/dalvikvm( 7308): GC_CONCURRENT freed 2989K, 28% free 9576K/13288K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7308): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3977): Associated with C0.AA.48
I/wpa_supplicant( 3977): freq(2412) increment count 2
,I/wpa_supplicant( 3977): meet head of list.
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3977): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3977): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/ActivityManager( 2397): Killing 6247:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
D/Tethering( 2397): interfaceStatusChanged wlan0, true
D/WifiNative( 2397): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7322):  
D/WifiP2pService( 2397): InactiveState{ what=143375 }
D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
,I/SELinux ( 7322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7322):  
I/SELinux ( 7322):  
,I/SELinux ( 7322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7322): >>>>> Normal User
,E/dalvikvm( 7322): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7322): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7322): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7322): Added TimaKesytore provider
,D/dalvikvm( 7322): GC_CONCURRENT freed 2992K, 28% free 9574K/13292K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/ActivityManager( 2397): Killing 6322:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/dhcpcd  ( 7334): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7334): bssid match
,I/SELinux ( 7341): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7341):  
,I/SELinux ( 7341): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7341):  
I/SELinux ( 7341):  
,I/SELinux ( 7341): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7341): >>>>> Normal User
,E/dalvikvm( 7341): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7341): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7341): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7341): Added TimaKesytore provider
,D/dalvikvm( 7341): GC_CONCURRENT freed 3006K, 29% free 9554K/13284K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7341): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/KLMS-2.3.201 : ( 7341): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7341): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452521112420
,I/KLMS-2.3.201 : ( 7341): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2397): Killing 6348:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7353):  
,I/SELinux ( 7353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7353):  
I/SELinux ( 7353):  
,I/SELinux ( 7353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7353): >>>>> Normal User
,E/dalvikvm( 7353): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7353): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7353): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7353): Added TimaKesytore provider
,D/dalvikvm( 7353): GC_CONCURRENT freed 3000K, 29% free 9564K/13288K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7353): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5812): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5812): [BDLM] already registered in spp
,I/SA      ( 5812): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5812): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5812): [OR] == isSIMCardReady false ==
,I/SA      ( 5812): [SCU] == networkStateCheck == false
,I/SA      ( 5812): [OR] onReceive END
I/ActivityManager( 2397): Killing 6388:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection...
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7365): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7365):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 8% free 9501K/10268K, paused 2ms+3ms, total 31ms
,I/SELinux ( 7365): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7365):  
I/SELinux ( 7365):  
,I/SELinux ( 7365): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7365): >>>>> Normal User
,E/dalvikvm( 7365): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 8% free 9501K/10268K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7365): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7365): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7365): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 8% free 9501K/10268K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 7365): GC_CONCURRENT freed 2997K, 28% free 9576K/13292K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7365): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/sCloudBackupApp( 7365): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7365): Other Intent
I/ActivityManager( 2397): Killing 5590:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7378):  
,I/SELinux ( 7378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7378):  
I/SELinux ( 7378):  
,I/SELinux ( 7378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7378): >>>>> Normal User
,E/dalvikvm( 7378): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7378): Added TimaKesytore provider
,D/dalvikvm( 7378): GC_CONCURRENT freed 2990K, 28% free 9569K/13284K, paused 4ms+2ms, total 20ms
,D/dalvikvm( 7378): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7378): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7378): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5341): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7378): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5341): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7378): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5341): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2397): Killing 6300:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5878): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5878): getCountryCode(): countryCode = PL
,D/Headlines( 5878): Breath.onCreate
,D/Headlines( 5878): Breath timer started. interval : 30000
,I/SELinux ( 7390): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7390):  
,V/AlarmManager( 2397): waitForAlarm result :8
D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5878): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5878): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5878): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7390): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7390):  
I/SELinux ( 7390):  
,I/SELinux ( 7390): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7390): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7390): >>>>> Normal User
,E/dalvikvm( 7390): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7390): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7390): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7390): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7390): Added TimaKesytore provider
,D/dalvikvm( 7390): GC_CONCURRENT freed 2994K, 28% free 9570K/13288K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7390): WAIT_FOR_CONCURRENT_GC blocked 12ms
,V/WebViewChromium( 7390): Binding Chromium to the background looper Looper (main, tid 1) {4228b2d8}
,I/chromium( 7390): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7390): Initializing chromium process, renderers=0
,W/chromium( 7390): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7390): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7390): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7390): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7390): Mali API Version : 401
,I/Mali    ( 7390): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,W/GAV2    ( 7390): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7390): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7390): Starting up...
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/iu.Environment( 5942): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 5942): SYNC; picasa accounts
,I/iu.UploadsManager( 5942): num queued entries: 0
,I/iu.UploadsManager( 5942): num updated entries: 0
,I/iu.SyncManager( 5942): NEXT; no task
,D/QuickConnect[1.1][2] ( 5142): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5142): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5142): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42299610
D/WifiP2pService( 2397): InactiveState{ what=143375 }
D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
,I/SELinux ( 7450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7450):  
,D/WifiStateMachine( 2397): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SELinux ( 7450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7450):  
I/SELinux ( 7450):  
I/SELinux ( 7450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7450): >>>>> Normal User
E/dalvikvm( 7450): >>>>> com.android.email [ userId:0 | appId:10157 ]
E/SELinux ( 7450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/WifiStateMachine( 2397): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2397): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider( 7450): in addTimaSignatureService
,D/WifiStateMachine( 2397): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2397): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2397): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TimaKeyStoreProvider( 7450): Cannot add TimaSignature Service, License check Failed
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ActivityThread( 7450): Added TimaKesytore provider
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
D/ConnectivityService( 2397): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2397): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2397): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2397): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/dalvikvm( 7450): GC_CONCURRENT freed 2973K, 28% free 9590K/13288K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7450): WAIT_FOR_CONCURRENT_GC blocked 20ms
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2397): updateIfacesLocked()
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,V/NetworkStats( 2397): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): performPollLocked() took 26ms
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,I/SELinux ( 7484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7484):  
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,I/SELinux ( 7484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7484):  
I/SELinux ( 7484):  
,I/SELinux ( 7484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 2397): Killing 6318:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7484): >>>>> Normal User
E/dalvikvm( 7484): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ActivityManager( 2397): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 7484): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7484): Added TimaKesytore provider
,I/SELinux ( 7496): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7496):  
,I/ActivityManager( 2397): Killing 5986:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7496): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7496):  
I/SELinux ( 7496):  
,I/SELinux ( 7496): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7496): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7496): >>>>> Normal User
,E/dalvikvm( 7496): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7496): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7496): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7496): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7496): Added TimaKesytore provider
,D/dalvikvm( 7484): GC_CONCURRENT freed 3001K, 29% free 9564K/13288K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/BadgeProvider( 7484): onCreate
,D/BadgeProvider( 7484): DatabaseHelper
,D/BadgeProvider( 7484): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2772): reloadBadges entered.
,D/BadgeProvider( 7484): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7484): sendNotify, [notify] : null
D/BadgeProvider( 7484): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7484): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7484): update, [UpdateCount] : 1
,D/dalvikvm( 7496): GC_CONCURRENT freed 3006K, 29% free 9557K/13288K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7496): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/hcjo    ( 5963): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5963): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5963): exit::IDLE
,D/InitializeManagerStateMachine( 5963): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5963): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5963): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5963): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5963): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): entry::SUCCESS
,D/hcjo    ( 5963): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5963): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5963): exit::SUCCESS
,D/InitializeManagerStateMachine( 5963): entry::IDLE
,E/SPPClientService( 5543): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5543): [SystemStateMoniter] Current Time : 276283
,E/SPPClientService( 5543): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5543): [[SystemStateMonitorService]] No Active Internet
,D/Tethering( 2397): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2397): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2397): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4741): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/NearbySettings( 2818): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2818): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2818): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2818): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 2397): Killing 6266:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 1421 latestRequest time : 1452521113139 current time : 1452521114560
,E/SPPClientService( 5543): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5543): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2818): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2818): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5543): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection...
,D/NearbySettings( 2818): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2818): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2818): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2818): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5543): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2397): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2397
,D/NearbySettings( 2818): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2818): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5543): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
I/PCWCLIENTTRACE_PushUtil( 6590): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6590): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6590): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6590): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5543): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5543): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7341): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/dalvikvm( 2397): GC_EXPLICIT freed 4107K, 74% free 25504K/94904K, paused 10ms+18ms, total 199ms
,I/System.out( 7322): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/KLMS-2.3.201 : ( 7341): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452521115060
,I/System.out( 7322): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7322): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/KLMS-2.3.201 : ( 7341): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3300): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3428): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7523): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7523):  
,D/dalvikvm( 2721): null clazz in OP_INSTANCE_OF, single-stepping,
,I/SELinux ( 7523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7523):  
I/SELinux ( 7523):  
I/SELinux ( 7523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7523): >>>>> Normal User
,E/dalvikvm( 7523): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ],
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,W/WifiP2pStateTracker( 2397): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2397): stay LED for fully charged
,D/TimaKeyStoreProvider( 7523): in addTimaSignatureService,
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/ConnectivityService( 2397): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2397):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2397): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2397): updateSourceRoutes : no source routing conditions
,D/TimaKeyStoreProvider( 7523): Cannot add TimaSignature Service, License check Failed,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/ActivityThread( 7523): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/SA      ( 5812): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5812): [BDLM] already registered in spp
,I/SA      ( 5812): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5812): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5812): [OR] == isSIMCardReady false ==
,I/SA      ( 5812): [SCU] == networkStateCheck == true
I/SA      ( 5812): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5812): isChinaCountryCode : false
,I/SA      ( 5812): [OR] == networkStateCheck true ==
D/dalvikvm( 7523): GC_CONCURRENT freed 2992K, 28% free 9575K/13288K, paused 3ms+2ms, total 21ms
I/SA      ( 5812): [OR] GetMyCountryZoneTask
D/dalvikvm( 7523): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/SA      ( 5812): [OR] onReceive END
,I/SA      ( 5812): [SRS] prepareGetMyCountryZone
I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5812): [SSP] query invoked
I/System.out( 7322): AsyncTask #1 calls detatch()
I/SA      ( 5812): [TPMU] GetMccFromDB : null
I/SA      ( 5812): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5812): [TPM] isNoProxy(default) : true
,I/SA      ( 5812): [RC New] Execute method=[GET] start
,I/SELinux ( 7537): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7537):  
,I/SELinux ( 7537): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7537):  
I/SELinux ( 7537):  
,I/SELinux ( 7537): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7537): >>>>> Normal User
,E/dalvikvm( 7537): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/System.err( 7322): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7322): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7322): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7322): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7322): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7322): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7322): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,W/System.err( 7322): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7322): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7322): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7322): Caused by: java.lang.NullPointerException
,W/System.err( 7322): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7322): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7322): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7322): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,I/SCloudBackupReceiver( 7365): Other Intent
,W/System.err( 7322): 	... 8 more
,D/TimaKeyStoreProvider( 7537): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7537): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7537): Added TimaKesytore provider
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7378): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5878): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5878): getCountryCode(): countryCode = PL
,D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5878): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5878): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5878): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7537): GC_CONCURRENT freed 3005K, 29% free 9555K/13284K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7537): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/iu.Environment( 5942): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/QuickConnect[1.1][2] ( 5142): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5142): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5142): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42299610
,V/KVNProvider( 7537): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7537): getFindoCursor query string : 
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,V/KVNProvider( 7537): getTagSearchCursor() tagSearchCursor count : 0
,I/iu.UploadsManager( 5942): num queued entries: 0
,I/iu.UploadsManager( 5942): num updated entries: 0
,I/iu.SyncManager( 5942): NEXT; no task
I/ActivityManager( 2397): Killing 6162:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/hcjo    ( 5963): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5963): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5963): exit::IDLE
,D/InitializeManagerStateMachine( 5963): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5963): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5963): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5963): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5963): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): entry::SUCCESS
,D/hcjo    ( 5963): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5963): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5963): exit::SUCCESS
,D/InitializeManagerStateMachine( 5963): entry::IDLE
,E/SPPClientService( 5543): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
D/dalvikvm( 5543): GC_CONCURRENT freed 1952K, 22% free 10439K/13280K, paused 5ms+4ms, total 40ms
,E/SPPClientService( 5543): [SystemStateMoniter] Current Time : 277496
,E/SPPClientService( 5543): [SystemStateMoniter] No Connect : false
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 5812): [RC New] [v2liruge] api execute + 758
,I/SA      ( 5812): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5812): AsyncTask #2 calls detatch()
,I/SA      ( 5812): [TPMU] getNetworkMcc : 
,I/SA      ( 5812): [SCU] saveMccToPreferece Start
,I/SA      ( 5812): [SCU] RegionMCC : 260
,I/SA      ( 5812): [SSP] query invoked
,I/SA      ( 5812): [TPMU] GetMccFromDB : null
I/SA      ( 5812): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5812): [SCU] saveMccToPreferece End
I/SA      ( 5812): [RC New] executeRequest [v2liruge] end. 780
,I/SA      ( 5812): [RC New] Execute end
I/SA      ( 5812): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5812): [OR] GetMyCountryZoneTask Success
,D/PackageManager( 2397): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,E/SPPClientService( 5543): [b] __InitReply__,
,E/WifiStateMachine( 2397): CAPTIVE_PORTAL_EVENT_AUTHENTICATED,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 20,
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11),
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11),
I/ActivityManager( 2397): Killing 6199:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2397): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2397) eventTime = 279976
D/PowerManagerService( 2397): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2397 (0x0)
D/PowerManagerService( 2397): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2397, ws=WorkSource{1000}) (elapsedTime=3478)
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4,
,I/GAV2    ( 7390): Thread[GAThread,5,main]: No campaign data found.,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6590): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6590): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6590): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6590): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6590): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6590): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6590): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6590): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6590): [ensureRegistration] - No Samsung account,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/PreloadUpdateManagerStateMachine( 5963): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5963): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5963): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5963): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5963): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5963): entry::IDLE
,I/jxcore-log( 7233): Test app app.js loaded
I/jxcore-log( 7233): 
,D/CaptivePortalTracker( 2397): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2397): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 2397): Checking http://216.58.209.78/generate_204
,I/chromium( 7233): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CaptivePortalTracker( 2397): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2397): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2397): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2397): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2397): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7233): --= Surplus to requirements =--
I/jxcore-log( 7233): 
I/jxcore-log( 7233): ****TEST TOOK:  ms ****
I/jxcore-log( 7233): 
,I/jxcore-log( 7233): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7233): 
,D/AndroidRuntime( 7568): 
D/AndroidRuntime( 7568): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7568): CheckJNI is OFF
,D/AndroidRuntime( 7568): setted country_code = Poland
,D/AndroidRuntime( 7568): setted countryiso_code = PL
D/AndroidRuntime( 7568): setted sales_code = PLS
D/AndroidRuntime( 7568): readGMSProperty: start
,D/AndroidRuntime( 7568): readGMSProperty: already setted!!
D/AndroidRuntime( 7568): readGMSProperty: end
,D/AndroidRuntime( 7568): addProductProperty: start
,D/dalvikvm( 7568): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7568): Added shared lib libjavacore.so 0x0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/dalvikvm( 7568): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7568): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7568): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/BatteryService( 2397): stay LED for fully charged
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/memtrack( 7568): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7568): failed to load memtrack module: -2
,D/dalvikvm( 7568): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7568): Calling main entry com.android.commands.pm.Pm
,D/PreloadUpdateManagerStateMachine( 5963): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5963): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5963): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5963): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5963): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5963): entry::IDLE
,D/PackageManager( 2397): START PACKAGE DELETE: observer{1150948016}
D/PackageManager( 2397): pkg{<packageName>}
D/PackageManager( 2397): user{0}
,D/PackageManager( 2397): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2397): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2397): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2397): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2397): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2397): !@killApplicatoin: 10609, uninstall pkg
,I/ActivityManager( 2397): Killing 7233:com.test.thalitest/u0a609 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2397): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2397): WIN DEATH: Window{42be0e50 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2397): Skipping PackageSetting{4267c328 com.example.hello/10600} due to missing metadata
,D/PackageManager( 2397): setPackageStoppedState - Execution time: 110 ms
D/PackageManager( 2397): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10609, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6750): GC_EXPLICIT freed 159K, 27% free 9957K/13504K, paused 2ms+4ms, total 50ms
,D/PackageManager( 2397): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10609, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4741): [3.19.140541][Line:408][onResume] 
,D/dalvikvm( 6429): GC_EXPLICIT freed 2505K, 26% free 9883K/13292K, paused 5ms+4ms, total 72ms
,D/dalvikvm( 2958): GC_EXPLICIT freed 1471K, 25% free 10033K/13288K, paused 8ms+5ms, total 74ms
,I/DBG_DM  ( 4741): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/DBG_DM  ( 4741): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,I/DBG_DM  ( 4741): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4741): [3.19.140541][Line:418][onResume] Postpone Count : 29
,E/SamsungIME( 2989): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5142): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest,
,I/DBG_DM  ( 4741): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0,
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "sms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7581): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7581):  
,I/DBG_DM  ( 4741): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/SELinux ( 7581): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7581):  
I/SELinux ( 7581):  
,I/SELinux ( 7581): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7581): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7581): >>>>> Normal User
,E/dalvikvm( 7581): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7581): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2397): GC_EXPLICIT freed 2123K, 74% free 25195K/94904K, paused 13ms+19ms, total 231ms
,I/DBG_DM  ( 4741): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/TimaKeyStoreProvider( 7581): in addTimaSignatureService
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mms"
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 7581): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7581): Added TimaKesytore provider
,D/dalvikvm( 3159): GC_EXPLICIT freed 1743K, 18% free 12417K/15100K, paused 9ms+10ms, total 315ms
,I/InputReader( 2397): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4741): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,D/RegisteredServicesCache( 2759): empty dynamic service
,D/RCPManagerService( 2397): PackageReceiver onReceive()
,I/DBG_DM  ( 4741): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "sms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/HarmonyEASService( 2397): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/DBG_DM  ( 4741): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4741): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4741): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4741): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4741): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4741): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4741): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2397): semi p:4741,o:t
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/Watchdog( 2397): !@Sync 9
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2397): Got RemoteException sending setActive(false) notification to pid 7233 uid 10609
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mmsto"
,I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 7581): GC_CONCURRENT freed 3000K, 28% free 9568K/13288K, paused 3ms+13ms, total 46ms
D/dalvikvm( 7581): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 2759): GC_CONCURRENT freed 1210K, 26% free 10611K/14180K, paused 14ms+3ms, total 87ms
,D/dalvikvm( 2759): WAIT_FOR_CONCURRENT_GC blocked 52ms
,D/elm:14132( 7581): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/elm:14132( 7581): ELMEngine.ELMEngine( context ).
,D/EnterpriseDeviceManagerService( 2397): Package has changed for user 0
,D/elm:14132( 7581): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7581): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7581): ElmAgentService : onCreate()
D/elm:14132( 7581): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7581): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7581): MDMBridge.getInstance()
,D/elm:14132( 7581): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7595): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7595):  
,D/elm:14132( 7581): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7581): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7581): ElmAgentService : onDestroy().
I/ActivityManager( 2397): Killing 6533:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7595): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7595):  
I/SELinux ( 7595):  
,I/SELinux ( 7595): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7595): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7595): >>>>> Normal User
,E/dalvikvm( 7595): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7595): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7595): in addTimaSignatureService
,D/BackupManagerService( 2397): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/TimaKeyStoreProvider( 7595): Cannot add TimaSignature Service, License check Failed
,V/BackupManagerService( 2397): removePackageParticipantsLocked: uid=10609 #1
D/ActivityThread( 7595): Added TimaKesytore provider
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2397): sendNotification(2) - 4
D/dalvikvm( 2397): GC_EXPLICIT freed 1144K, 74% free 25277K/94904K, paused 10ms+33ms, total 443ms
,D/PackageManager( 2397): delete sourFile : 
,D/PackageManager( 2397): delete native library directory: 
D/PackageManager( 2397): return delete result to caller: 1150948016
,D/PackageManager( 2397): returnCode: 1
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 7568): Shutting down VM
D/dalvikvm( 7568): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 3ms
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "sms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7595): GC_CONCURRENT freed 3007K, 29% free 9557K/13284K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7595): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7610): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7610):  
I/ActivityManager( 2397): Killing 6449:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7610): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7610):  
I/SELinux ( 7610):  
,I/SELinux ( 7610): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7610): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7610): >>>>> Normal User
,E/dalvikvm( 7610): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7610): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7610): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7610): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7610): Added TimaKesytore provider
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 7610): GC_CONCURRENT freed 3001K, 29% free 9566K/13292K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7610): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2397): onPackageRemoved : com.test.thalitest
,D/UsbSettingsManager( 2397): clearDefaults: com.test.thalitest
,W/AtomicFile( 2397): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,W/AppWidgetServiceImpl( 2397): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 7610): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase( 7610): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7610): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7610): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7610): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7610): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7610): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase( 7610): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 7610): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7610): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7610): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7610): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7610): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7610): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7610): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7610): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7610): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7610): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7610): Shutting down VM
,W/dalvikvm( 7610): threadid=1: thread exiting with uncaught exception (group=0x41893c08)
E/AndroidRuntime( 7610): FATAL EXCEPTION: main
E/AndroidRuntime( 7610): Process: com.sec.android.app.mss, PID: 7610
E/AndroidRuntime( 7610): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7610): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7610): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7610): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7610): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7610): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7610): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7610): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7610): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7610): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7610): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7610): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7610): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7610): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7610): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7610): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7610): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 7610): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 7610): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7610): 	... 10 more
I/PCWCLIENTTRACE_PushUtil( 6590): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6590): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6590): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6590): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 7610): Sending signal. PID: 7610 SIG: 9
,I/SA      ( 5812): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/ActivityManager( 2397): Process com.sec.android.app.mss (pid 7610) (adj 9) has died.
I/SA      ( 5812): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
E/SQLiteLog( 6003): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
W/dalvikvm( 6003): threadid=12: thread exiting with uncaught exception (group=0x41893c08)
,E/SharedPreferencesImpl( 3428): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/AndroidRuntime( 6003): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6003): Process: com.sec.android.app.shealth, PID: 6003
E/AndroidRuntime( 6003): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6003): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6003): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6003): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6003): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6003): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6003): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6003): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6003): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6003): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6003): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6003): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6003): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6003): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6003): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6003): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Icing.InternalIcingCorporaProvider( 6429): Updating corpora: A: com.test.thalitest, C: MAYBE
,W/ApplicationsProvider( 2958): Could not fetch usage stats
W/ApplicationsProvider( 2958): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2958): 	,at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2958): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2958): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2958): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 6429): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DropBoxManagerService( 2397): Can't write: system_app_crash
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
W/dalvikvm( 6429): threadid=15: thread exiting with uncaught exception (group=0x41893c08)
I/SELinux ( 7633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7633):  
,I/Process ( 6003): Sending signal. PID: 6003 SIG: 9,
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 8% free 9501K/10268K, paused 2ms+3ms, total 30ms
I/ActivityManager( 2397): Process com.sec.android.app.shealth (pid 6003) (adj 5) has died.
E/AndroidRuntime( 6429): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6429): Process: com.google.android.googlequicksearchbox:search, PID: 6429
E/AndroidRuntime( 6429): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6429): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6429): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6429): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6429): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6429): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6429): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6429): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6429): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6429): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6429): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6429): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6429): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6429): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7633):  
I/SELinux ( 7633):  
,I/SELinux ( 7633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7633): >>>>> Normal User
E/dalvikvm( 7633): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 8% free 9501K/10268K, paused 2ms+2ms, total 24ms
I/Process ( 6429): Sending signal. PID: 6429 SIG: 9
,E/SELinux ( 7633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/DropBoxManagerService( 2397): Can't write: system_app_crash
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
,D/TimaKeyStoreProvider( 7633): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 8% free 9501K/10268K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 7633): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager( 2397): Process com.google.android.googlequicksearchbox:search (pid 6429) (adj 5) has died.
D/ActivityThread( 7633): Added TimaKesytore provider
,D/dalvikvm( 7633): GC_CONCURRENT freed 3004K, 29% free 9561K/13288K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7633): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/UserAnalysis.PlaceProvider( 7633): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7633): Create SecureDbHelper
E/SQLiteDatabase( 7633): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7633): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7633): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7633): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7633): 	at android.databas,e.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7633): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7633): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7633): Opened privacy in read-only mode
E/SQLiteDatabase( 7633): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelpe,r.java:224)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7633): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7633): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7633): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7633): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7633): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7633): Opened privacy in read-only mode
E/SQLiteDatabase( 7633): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7633): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7633): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7633): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7633): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7633): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
E/SQLiteDatabase( 6365): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6365): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6365): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6365): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6365): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6365): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/RCPManager( 6443):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2397):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2397): queryAllProviders():  providerCallBack is not register for 0
W/System.err( 6365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6365): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6365): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6365): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6365): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6365): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CapabilityManagerService New( 6659): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6659): The package(com.test.thalitest) removed
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
,D/MagazineService::MagazineBroadcastReceiver( 6686): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
I/MagazineService::MagazineService( 6686): [onHandleIntent] ACTION_PACKAGE_REMOVED
E/SQLiteDatabase( 6686): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6686): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6686): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6686): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6686): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6686): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6686): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6686): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6686): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6686): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6686): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6686): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6686): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 6686): threadid=10: thread exiting with uncaught exception (group=0x41893c08)
I/SELinux ( 7648): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7648):  
E/AndroidRuntime( 6686): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6686): Process: com.samsung.android.magazine.service, PID: 6686
E/AndroidRuntime( 6686): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6686): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6686): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6686): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6686): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6686): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6686): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6686): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6686): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6686): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6686): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6686): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6686): Sending signal. PID: 6686 SIG: 9
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
D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 0
D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
I/ActivityManager( 2397): Process com.samsung.android.magazine.service (pid 6686) (adj 5) has died.
,I/SELinux ( 7648): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7648):  
I/SELinux ( 7648):  
,I/SELinux ( 7648): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7648): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7648): >>>>> Normal User
,E/dalvikvm( 7648): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7648): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7648): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7648): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7648): Added TimaKesytore provider
,D/dalvikvm( 7648): GC_CONCURRENT freed 3003K, 29% free 9568K/13292K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7648): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/ContextImpl( 7648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6712): onReceive intent data =  package:com.test.thalitest
,E/SQLiteDatabase( 7648): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7648): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7648): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7648): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7648): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7648): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7648): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 7648): threadid=10: thread exiting with uncaught exception (group=0x41893c08)
,D/KidsPlatformStub( 6712): Package not found : com.sec.android.app.kidshome
,E/AndroidRuntime( 7648): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7648): Process: com.android.keychain, PID: 7648
E/AndroidRuntime( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7648): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7648): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7648): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7648): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7648): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7648): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 6750): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6750): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6750): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
I/Process ( 7648): Sending signal. PID: 7648 SIG: 9
W/System.err( 6750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6750): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6750): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 6750): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6750): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 6750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6750): 	at dalvik.system.NativeStart.main(Native Method)
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
,D/PackageBroadcastService( 3159): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3159): Clearing selected account for com.test.thalitest
I/ActivityManager( 2397): Process com.android.keychain (pid 7648) (adj 5) has died.
,E/SQLiteLog( 3159): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
D/ChimeraCfgMgr( 3159): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3159): Module APK com.google.android.play.games already loaded,
,E/DriveAsyncService( 3159): disk I/O error (code 3850),
E/DriveAsyncService( 3159): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3159): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3159): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3159): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3159): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3159): ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3159): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3159): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3159): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3159): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3159): 	at com.google.android.gms.common.service.f.run(SourceFile:176),
E/DriveAsyncService( 3159): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3159): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3159): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3159): 	at java.lang.Thread.run(Thread.java:841)
,I/LocationSettingsChecker( 3159): Removing dialog suppression flag for package com.test.thalitest,
D/ChimeraCfgMgr( 3159): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3159): Module APK com.google.android.play.games already loaded,
,E/SQLiteLog( 2849): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 2849): Shutting down VM
,W/dalvikvm( 2849): threadid=1: thread exiting with uncaught exception (group=0x41893c08)
,E/SQLiteLog( 3159): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 3159): threadid=48: thread exiting with uncaught exception (group=0x41893c08)
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
,E/SQLiteDatabase( 3159): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3159): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3159): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3159): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3159): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3159): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3159): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3159): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3159): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 3159): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 3159): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3159): Process: com.google.android.gms, PID: 3159
E/AndroidRuntime( 3159): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3159): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3159): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3159): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3159): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3159): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3159): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3159): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3159): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3159): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3159): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3159): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3159): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3159): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3159): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3159): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3159): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 3159): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3159): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3159): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3159): 	at com.google.android.gms.app,.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3159): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3159): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3159): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3159): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3159): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3159): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3159): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3159): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3159): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3159): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3159): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 3159): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3159): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3159): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3159): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3159): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3159): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3159): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2849): Sending signal. PID: 2849 SIG: 9
,E/ClearPendingStateOp( 3159): Runtime exception while performing operation
E/ClearPendingStateOp( 3159): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3159): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3159): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3159): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3159): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3159): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3159): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3159): 	at java.lang.Thread.run(Thread.java:841)
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
I/Process ( 3159): Sending signal. PID: 3159 SIG: 9
,F/ClearPendingStateOp( 3159): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3159): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3159): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3159): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3159): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3159): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3159): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3159): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3159): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3159): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3159): 	at java.lang.Thread.run(Thread.java:841)
E/DropBoxManagerService( 2397): Can't write: system_app_crash
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
,E/SQLiteDatabase( 6405): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6405): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6405): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6405): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6405): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6405): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6405): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6405): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6405): [g] not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 5543): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5543): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5543): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5543): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5543): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5543): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5543): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5543): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5543): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5543): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5543): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5543): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5543): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5543): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5543): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5543): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5543): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5543): 	at dalvik.system.NativeStart.main(Native Method)
E/SPPClientService( 5543): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7674): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7674):  
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 2849) (adj 5) has died.
E/SQLiteDatabase( 6405): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6405): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6405): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6405): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6405): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6405): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6405): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6405): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6405): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6405): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6405): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,D/GAV2    ( 5632): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/ActivityManager( 2397): Process com.google.android.gms (pid 3159) (adj 5) has died.
I/GAV2    ( 5632): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7674): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7674):  
I/SELinux ( 7674):  
,I/SELinux ( 7674): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7674): >>>>> Normal User
,E/dalvikvm( 7674): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7674): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7674): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7674): Added TimaKesytore provider
,D/dalvikvm( 7674): GC_CONCURRENT freed 3004K, 29% free 9556K/13284K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7674): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Documents( 7674): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7674): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7674): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7674): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7674): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7674): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7674): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7674): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7674): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7674): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7674): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7674): Shutting down VM
,W/dalvikvm( 7674): threadid=1: thread exiting with uncaught exception (group=0x41893c08)
E/AndroidRuntime( 7674): FATAL EXCEPTION: main
E/AndroidRuntime( 7674): Process: com.android.documentsui, PID: 7674
E/AndroidRuntime( 7674): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7674): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7674): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7674): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7674): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7674): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7674): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7674): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7674): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7674): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7674): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7674): 	... 10 more
,I/SELinux ( 7690): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7690):  
,I/SELinux ( 7694): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7694):  
,I/Process ( 7674): Sending signal. PID: 7674 SIG: 9,
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73),
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): ,	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/SELinux ( 7690): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7690):  
I/SELinux ( 7690):  
,I/SELinux ( 7690): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7690): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7690): >>>>> Normal User
,E/dalvikvm( 7690): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7690): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2397): Process com.android.documentsui (pid 7674) (adj 9) has died.
,D/TimaKeyStoreProvider( 7690): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7690): Cannot add TimaSignature Service, License check Failed
,I/SELinux ( 7694): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7694):  
I/SELinux ( 7694):  
I/SELinux ( 7694): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/ActivityThread( 7690): Added TimaKesytore provider
E/SELinux ( 7694): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7694): >>>>> Normal User
,E/dalvikvm( 7694): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7694): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7694): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7694): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7694): Added TimaKesytore provider
,D/dalvikvm( 7690): GC_CONCURRENT freed 2998K, 29% free 9564K/13288K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7690): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/ExternalStorage( 7690): After updating volumes, found 1 active roots
,D/dalvikvm( 7694): GC_CONCURRENT freed 2946K, 28% free 9619K/13288K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7694): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 7694): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7694): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7694): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7694): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7694): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7694): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7694): install
,I/MultiDex( 7694): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7694): loading existing secondary dex files
,I/MultiDex( 7694): load found 3 secondary dex files
,I/MultiDex( 7694): install done
,I/SELinux ( 7716): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7716):  
I/ActivityManager( 2397): Waited long enough for: ServiceRecord{43239678 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/SELinux ( 7716): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7716):  
I/SELinux ( 7716):  
,I/SELinux ( 7716): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7716): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7716): >>>>> Normal User
,E/dalvikvm( 7716): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7716): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7716): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7716): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7716): Added TimaKesytore provider
,I/SELinux ( 7730): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7730):  
,I/SELinux ( 7730): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7730):  
I/SELinux ( 7730):  
,I/SELinux ( 7730): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7730): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7730): >>>>> Normal User
,E/dalvikvm( 7730): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7730): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 7716): GC_CONCURRENT freed 2989K, 28% free 9578K/13292K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7716): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/TimaKeyStoreProvider( 7730): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7730): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7730): Added TimaKesytore provider
,I/Icing.InternalIcingCorporaProvider( 7716): Updating corpora: A: com.test.thalitest, C: MAYBE,
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4,
,I/SELinux ( 7746): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7746):  
D/dalvikvm( 7730): GC_CONCURRENT freed 2995K, 28% free 9569K/13288K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7730): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,D/LocationManagerService( 2397): getProviders()=[passive],
,I/SELinux ( 7746): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7746):  
I/SELinux ( 7746):  
I/SELinux ( 7746): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7746): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7746): >>>>> Normal User
,E/dalvikvm( 7746): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ],
,E/SELinux ( 7746): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7746): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7746): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7746): Added TimaKesytore provider,
,I/GservicesProvider( 7730): Gservices pushing to system: true; secure/global: true,
,E/SQLiteDatabase( 7730): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
,E/SQLiteDatabase( 7730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7730): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859),
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,E/SQLiteDatabase( 7730): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7730): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7730): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7730): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7730): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7730): ,	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7730): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7730): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7730): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,E/SQLiteDatabase( 7730): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7730): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7730): 	at dalvik.system.NativeStart.main(Native Method),
D/AndroidRuntime( 7730): Shutting down VM
,W/dalvikvm( 7730): threadid=1: thread exiting with uncaught exception (group=0x41893c08),
,E/AndroidRuntime( 7730): FATAL EXCEPTION: main,
E/AndroidRuntime( 7730): Process: com.google.process.gapps, PID: 7730
E/AndroidRuntime( 7730): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7730): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7730): 	,at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7730): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7730): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/AndroidRuntime( 7730): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7730): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7730): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7730): 	at java.lang.reflect.Method.invoke(Method.java:515)
,E/AndroidRuntime( 7730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7730): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7730): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7730): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859),
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7730): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7730): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7730): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
,E/AndroidRuntime( 7730): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7730): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7730): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7730): 	... 12 more
,I/Process ( 7730): Sending signal. PID: 7730 SIG: 9,
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	,at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/ActivityManager( 2397): Process com.google.process.gapps (pid 7730) (adj 0) has died.
W/ActivityManager( 2397): Service crashed 2 times, stopping: ServiceRecord{43129510 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7764): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7764):  
,D/dalvikvm( 7746): GC_CONCURRENT freed 2990K, 28% free 9576K/13288K, paused 4ms+1ms, total 21ms,
,D/dalvikvm( 7746): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/SELinux ( 7764): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7764):  
I/SELinux ( 7764):  
,I/SELinux ( 7764): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7764): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7764): >>>>> Normal User
,E/dalvikvm( 7764): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7764): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7764): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7764): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7764): Added TimaKesytore provider,
,D/dalvikvm( 7764): GC_CONCURRENT freed 2986K, 28% free 9584K/13292K, paused 1ms+1ms, total 17ms,
,D/dalvikvm( 7764): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7764): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7764): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7764): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7764): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7764): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7764): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7764): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7764): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7764): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888),
E/SQLiteDatabase( 7764): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7764): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7764): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7764): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7764): 	,at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7764): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7764): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7764): Shutting down VM,
,W/dalvikvm( 7764): threadid=1: thread exiting with uncaught exception (group=0x41893c08),
E/AndroidRuntime( 7764): FATAL EXCEPTION: main
E/AndroidRuntime( 7764): Process: com.google.process.gapps, PID: 7764
E/AndroidRuntime( 7764): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/AndroidRuntime( 7764): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7764): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7764): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7764): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7764): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7764): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7764): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7764): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7764): 	at java.lang.reflect.Method.invoke(Method.java:515)
,E/AndroidRuntime( 7764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7764): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7764): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7764): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7764): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7764): 	,at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7764): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7764): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7764): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
,E/AndroidRuntime( 7764): 	... 12 more
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7764:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	,at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,E/ActivityThread( 7716): Failed to find provider info for com.google.settings
E/ActivityThread( 7746): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7781): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7781):  
E/ActivityThread( 7694): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7781): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7781):  
I/SELinux ( 7781):  
,I/SELinux ( 7781): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7781): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7781): >>>>> Normal User
,E/dalvikvm( 7781): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7781): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7781): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7781): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7781): Added TimaKesytore provider,
,D/dalvikvm( 7781): GC_CONCURRENT freed 2997K, 28% free 9570K/13292K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7781): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7781): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7781): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889),
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7781): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7781): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7781): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7781): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7781): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7781): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294),
E/SQLiteDatabase( 7781): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7781): 	at android.os.Looper.loop(Looper.java:146),
E/SQLiteDatabase( 7781): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7781): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7781): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7781): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7781): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7781): Shutting down VM
,W/dalvikvm( 7781): threadid=1: thread exiting with uncaught exception (group=0x41893c08),
,E/AndroidRuntime( 7781): FATAL EXCEPTION: main
E/AndroidRuntime( 7781): Process: com.google.process.gapps, PID: 7781
E/AndroidRuntime( 7781): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7781): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
,E/AndroidRuntime( 7781): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7781): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/AndroidRuntime( 7781): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7781): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7781): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7781): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7781): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7781): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7781): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7781): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7781): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7781): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7781): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7781): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7781): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7781): ,	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7781): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7781): 	... 12 more
,I/Process ( 7781): Sending signal. PID: 7781 SIG: 9,
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): ,	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7781) (adj 0) has died.,
,I/SELinux ( 7797): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7797):  
,I/SELinux ( 7797): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7797):  
I/SELinux ( 7797):  
,I/SELinux ( 7797): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7797): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7797): >>>>> Normal User
,E/dalvikvm( 7797): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7797): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7797): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7797): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7797): Added TimaKesytore provider
,D/dalvikvm( 7797): GC_CONCURRENT freed 3001K, 28% free 9570K/13292K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7797): WAIT_FOR_CONCURRENT_GC blocked 14ms,
,I/GservicesProvider( 7797): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7797): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7797): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224),
E/SQLiteDatabase( 7797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7797): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7797): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7797): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7797): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7797): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7797): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7797): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7797): 	at android.os.Looper.loop(Looper.java:146),
E/SQLiteDatabase( 7797): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7797): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7797): Shutting down VM,
,W/dalvikvm( 7797): threadid=1: thread exiting with uncaught exception (group=0x41893c08),
E/AndroidRuntime( 7797): FATAL EXCEPTION: main
E/AndroidRuntime( 7797): Process: com.google.process.gapps, PID: 7797
E/AndroidRuntime( 7797): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7797): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7797): 	,at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7797): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7797): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7797): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,E/AndroidRuntime( 7797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7797): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7797): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7797): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
,E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7797): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7797): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7797): ,	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7797): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7797): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7797): 	... 12 more
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7797:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null,
E/ActivityThread( 7746): Failed to find provider info for com.google.android.gsf.gservices
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88),
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): ,	... 5 more
D/dalvikvm( 7694): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7694): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7694): VFY: replacing opcode 0x62 at 0x000a
,E/ActivityThread( 7694): Failed to find provider info for com.google.android.gsf.gservices,
D/dalvikvm( 7694): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7694): VFY: unable to resolve instance field 36
D/dalvikvm( 7694): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7694): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7694): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7694): VFY: replacing opcode 0x62 at 0x0047,
D/dalvikvm( 7694): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7694): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7694): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4229aac0
D/dalvikvm( 7694): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4229aac0
D/dalvikvm( 7694): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4229aac0, skipping init
D/dalvikvm( 7694): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4229aac0
D/dalvikvm( 7694): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4229aac0
,V/JNIHelp ( 7694): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7694): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4229aac0,
D/dalvikvm( 7694): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4229aac0
D/dalvikvm( 7694): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4229aac0
,D/dalvikvm( 7694): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4229aac0,
,I/ProviderInstaller( 7694): Installed default security provider GmsCore_OpenSSL,
,I/SELinux ( 7812): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7812):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 8% free 9501K/10268K, paused 2ms+2ms, total 26ms,
,I/SELinux ( 7812): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7812):  
I/SELinux ( 7812):  
,I/SELinux ( 7812): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7812): >>>>> Normal User
,E/dalvikvm( 7812): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 8% free 9501K/10268K, paused 2ms+3ms, total 22ms,
,D/TimaKeyStoreProvider( 7812): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7812): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7812): Added TimaKesytore provider,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 8% free 9501K/10268K, paused 1ms+2ms, total 22ms,
,D/dalvikvm( 7812): GC_CONCURRENT freed 2988K, 28% free 9581K/13292K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7812): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7812): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7812): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7812): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7812): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7812): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7812): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7812): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7812): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7812): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7812): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7812): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7812): 	at android.os.Looper.loop(Looper.java:146),
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7812): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7812): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7812): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7812): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7812): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7812): Shutting down VM
,W/dalvikvm( 7812): threadid=1: thread exiting with uncaught exception (group=0x41893c08),
,E/AndroidRuntime( 7812): FATAL EXCEPTION: main
E/AndroidRuntime( 7812): Process: com.google.process.gapps, PID: 7812
E/AndroidRuntime( 7812): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771),
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7812): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7812): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7812): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7812): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7812): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7812): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7812): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7812): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7812): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7812): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268),
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7812): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7812): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7812): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7812): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
,E/AndroidRuntime( 7812): 	... 12 more
,I/Process ( 7812): Sending signal. PID: 7812 SIG: 9,
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
,E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7812) (adj 0) has died.,
,I/SELinux ( 7827): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7827):  
,I/SELinux ( 7827): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7827):  
I/SELinux ( 7827):  
,I/SELinux ( 7827): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7827): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7827): >>>>> Normal User
,E/dalvikvm( 7827): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7827): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7827): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7827): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7827): Added TimaKesytore provider,
,D/dalvikvm( 7827): GC_CONCURRENT freed 2990K, 28% free 9577K/13288K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7827): WAIT_FOR_CONCURRENT_GC blocked 14ms,
,I/GservicesProvider( 7827): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7827): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7827): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7827): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7827): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7827): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7827): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7827): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7827): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7827): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7827): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7827): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7827): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7827): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7827): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7827): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7827): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7827): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7827): 	,at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7827): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7827): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7827): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7827): Shutting down VM
,W/dalvikvm( 7827): threadid=1: thread exiting with uncaught exception (group=0x41893c08)
,W/dalvikvm( 2958): threadid=13: thread exiting with uncaught exception (group=0x41893c08)
,E/AndroidRuntime( 7827): FATAL EXCEPTION: main
E/AndroidRuntime( 7827): Process: com.google.process.gapps, PID: 7827
E/AndroidRuntime( 7827): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7827): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7827): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7827): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7827): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7827): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7827): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7827): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7827): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7827): 	,at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7827): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7827): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7827): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
,E/AndroidRuntime( 7827): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7827): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7827): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7827): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7827): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7827): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7827): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
,E/AndroidRuntime( 7827): 	... 12 more
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7827:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7694): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
,E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,W/NativeLibraryUtils( 7694): Failed to open lock file
W/NativeLibraryUtils( 7694): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7694): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7694): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7694): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7694): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7694): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7694): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7694): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7694): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7694): 	... 3 more
,E/AndroidRuntime( 2958): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2958): Process: android.process.acore, PID: 2958
E/AndroidRuntime( 2958): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2958): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2958): Sending signal. PID: 2958 SIG: 9
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
,I/dalvikvm( 7694): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7694): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7694): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7847):  
I/ActivityManager( 2397): Process android.process.acore (pid 2958) (adj -12) has died.
,I/SELinux ( 7851): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7851):  
,I/SELinux ( 7847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7847):  
I/SELinux ( 7847):  
,I/SELinux ( 7847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7847): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7847): >>>>> Normal User
,E/dalvikvm( 7847): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7847): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7851): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7851):  
I/SELinux ( 7851):  
,I/SELinux ( 7851): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7851): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7851): >>>>> Normal User
,E/dalvikvm( 7851): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7851): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/ActivityManager( 2397): Waited long enough for: ServiceRecord{4451b8a8 u0 com.sec.spp.push/.PushClientService}
D/TimaKeyStoreProvider( 7847): in addTimaSignatureService
D/TimaKeyStoreProvider( 7847): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7847): Added TimaKesytore provider
D/TimaKeyStoreProvider( 7851): in addTimaSignatureService
D/TimaKeyStoreProvider( 7851): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7851): Added TimaKesytore provider
,D/dalvikvm( 7847): GC_CONCURRENT freed 2994K, 28% free 9570K/13288K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7847): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7851): GC_CONCURRENT freed 2998K, 28% free 9568K/13288K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7851): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7847): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7847): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7847): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7847): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7847): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7847): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7847): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7847): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7847): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7847): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7847): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7847): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7847): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7847): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7847): Shutting down VM
,W/dalvikvm( 7847): threadid=1: thread exiting with uncaught exception (group=0x41893c08)
,E/AndroidRuntime( 7847): FATAL EXCEPTION: main
E/AndroidRuntime( 7847): Process: com.google.process.gapps, PID: 7847
E/AndroidRuntime( 7847): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7847): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7847): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7847): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7847): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7847): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7847): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7847): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7847): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7847): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7847): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7847): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7847): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7847): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7847): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7847): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7847): 	... 12 more
,I/Process ( 7847): Sending signal. PID: 7847 SIG: 9
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
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7847) (adj 0) has died.
,I/SELinux ( 7876): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7876):  
,I/SELinux ( 7876): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7876):  
I/SELinux ( 7876):  
,I/SELinux ( 7876): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7876): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7876): >>>>> Normal User
,E/dalvikvm( 7876): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7876): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7876): in addTimaSignatureService
,E/SQLiteDatabase( 7851): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7851): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7851): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaKeyStoreProvider( 7876): Cannot add TimaSignature Service, License check Failed
E/SQLiteOpenHelper( 7851): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7851): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7851): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7851): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7851): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7851): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7851): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ActivityThread( 7876): Added TimaKesytore provider
E/SQLiteLog( 7851): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7851): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7851): (14) unable to open database file
E/SQLiteDatabase( 7851): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7851): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7851): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7851): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7851): threadid=13: thread exiting with uncaught exception (group=0x41893c08)
E/AndroidRuntime( 7851): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7851): Process: android.process.acore, PID: 7851
E/AndroidRuntime( 7851): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7851): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7851): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7851): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7851): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7851): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 2397): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7851): Sending signal. PID: 7851 SIG: 9
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
,I/ActivityManager( 2397): Process android.process.acore (pid 7851) (adj -12) has died.
,F/ActivityManager( 2397): Service ServiceRecord{46fc6038 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{423cb180 7851:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2397): Can't write: system_server_wtf
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
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
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 18 more
,I/SELinux ( 7891): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7891):  
,D/dalvikvm( 7876): GC_CONCURRENT freed 2995K, 28% free 9577K/13292K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7876): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 7891): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7891):  
I/SELinux ( 7891):  
,I/SELinux ( 7891): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7891): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7891): >>>>> Normal User
,E/dalvikvm( 7891): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7891): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7891): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7891): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7891): Added TimaKesytore provider
,I/GservicesProvider( 7876): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7876): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7876): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7876): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7876): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7876): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7876): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7876): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7876): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7876): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7876): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7876): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7876): Shutting down VM
,W/dalvikvm( 7876): threadid=1: thread exiting with uncaught exception (group=0x41893c08)
E/AndroidRuntime( 7876): FATAL EXCEPTION: main
E/AndroidRuntime( 7876): Process: com.google.process.gapps, PID: 7876
E/AndroidRuntime( 7876): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7876): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7876): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7876): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7876): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7876): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7876): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7876): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7876): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7876): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7876): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7876): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7876): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7876): 	... 12 more
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
,I/ActivityManager( 2397): Killing 7876:com.google.process.gapps/u0a12 (adj 0): crash
,W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,I/GAv4-SVC( 7694): Google Analytics 8.4.89 is starting up.
E/ActivityThread( 7694): Failed to find provider info for com.google.android.gsf.gservices
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
,I/SELinux ( 7906): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7906):  
,D/dalvikvm( 7891): GC_CONCURRENT freed 2988K, 28% free 9579K/13292K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7891): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 7906): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7906):  
I/SELinux ( 7906):  
,I/SELinux ( 7906): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7906): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7906): >>>>> Normal User
,E/dalvikvm( 7906): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7906): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7906): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7906): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7906): Added TimaKesytore provider
,D/dalvikvm( 7906): GC_CONCURRENT freed 2996K, 28% free 9567K/13288K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7906): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/SQLiteDatabase( 7891): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7891): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7891): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7891): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7891): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7891): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7891): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7891): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7891): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7891): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7891): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7891): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7891): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7891): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7891): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7891): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7891): (14) unable to open database file
E/SQLiteDatabase( 7891): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7891): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7891): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7891): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7891): threadid=13: thread exiting with uncaught exception (group=0x41893c08)
E/AndroidRuntime( 7891): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7891): Process: android.process.acore, PID: 7891
E/AndroidRuntime( 7891): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7891): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7891): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7891): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7891): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7891): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7891): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7891): Sending signal. PID: 7891 SIG: 9
W/ActivityManager( 2397): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop238.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2397): Process android.process.acore (pid 7891) (adj -12) has died.
,I/SELinux ( 7924): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7924):  
,I/GservicesProvider( 7906): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7906): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7906): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7906): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7906): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7906): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7906): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7906): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7906): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7906): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7906): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7906): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7906): Shutting down VM

```
