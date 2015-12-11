#### Test 5065027857de7f1_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7200): 
D/AndroidRuntime( 7200): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7200): CheckJNI is OFF
D/AndroidRuntime( 7200): setted country_code = Poland
D/AndroidRuntime( 7200): setted countryiso_code = PL
D/AndroidRuntime( 7200): setted sales_code = PLS
D/AndroidRuntime( 7200): readGMSProperty: start
D/AndroidRuntime( 7200): readGMSProperty: already setted!!
D/AndroidRuntime( 7200): readGMSProperty: end
D/AndroidRuntime( 7200): addProductProperty: start
D/dalvikvm( 7200): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7200): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7200): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7200): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7200): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7200): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7200): failed to load memtrack module: -2
D/dalvikvm( 7200): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7200): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.acquire()
I/SELinux ( 7227): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7227):  
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7200): Shutting down VM
D/dalvikvm( 7200): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7227): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7227):  
I/SELinux ( 7227):  
I/SELinux ( 7227): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7227): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7227): >>>>> Normal User
E/dalvikvm( 7227): >>>>> com.test.thalitest [ userId:0 | appId:10533 ]
E/SELinux ( 7227): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7227): in addTimaSignatureService
D/TimaKeyStoreProvider( 7227): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7227): Added TimaKesytore provider
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
I/SQLiteSecureOpenHelper( 4180): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4180): getDatabaseLocked(b,b,pwd)...
D/dalvikvm( 7227): GC_CONCURRENT freed 3014K, 31% free 9558K/13808K, paused 2ms+2ms, total 19ms
D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7227): Binding Chromium to the background looper Looper (main, tid 1) {422882a8}
I/chromium( 7227): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7227): Initializing chromium process, renderers=0
W/chromium( 7227): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7227): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7227): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7227): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7227): Mali API Version : 401
,I/Mali    ( 7227): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,I/dalvikvm( 7227): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7227): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7227): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7227): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2403): tr p:7227,o:f
,W/dalvikvm( 7227): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7227): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7227): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7227): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7227): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7227): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7227): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7227): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7227): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7227): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7227): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:7227,o:f
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7227): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7227): Enabling debug mode 0
,W/AwContents( 7227): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7227): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2403): mDVFSHelper.release()
,D/JsMessageQueue( 7227): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7227): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42289030
,D/dalvikvm( 7227): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42289030
D/jxcore_app_log( 7227): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030879496
,D/JX-Cordova( 7227): jxcore cordova android initializing
I/dalvikvm( 7227): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 7227): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7227): GC_CONCURRENT freed 1287K, 19% free 11343K/13864K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7227): GC_CONCURRENT freed 1933K, 18% free 14926K/18116K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7227): GC_FOR_ALLOC freed 5328K, 30% free 16211K/23024K, paused 49ms, total 49ms
,D/dalvikvm( 7227): GC_CONCURRENT freed 6670K, 32% free 17678K/25636K, paused 1ms+9ms, total 54ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/dalvikvm( 7227): GC_FOR_ALLOC freed 1448K, 33% free 17367K/25636K, paused 49ms, total 49ms
,I/dalvikvm-heap( 7227): Grow heap (frag case) to 21.705MB for 3713210-byte allocation
,D/dalvikvm( 7227): GC_FOR_ALLOC freed 2442K, 37% free 18551K/29264K, paused 69ms, total 69ms
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/jxcore-log( 7227): Initializing JXcore engine
,W/jxcore-log( 7227): JXcore engine is ready
,W/jxcore-log( 7227): Starting JXcore engine
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,W/jxcore-log( 7227): Platform android
W/jxcore-log( 7227): 
,W/jxcore-log( 7227): Process ARCH arm
W/jxcore-log( 7227): 
,I/jxcore-log( 7227): JXcore Cordova bridge is ready!
I/jxcore-log( 7227): 
,W/jxcore-log( 7227): JXcore engine is started
,I/chromium( 7227): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7227): Toggling radios to true
I/jxcore-log( 7227): 
,D/BluetoothAdapter( 7227): enable(): BT is already enabled..!
,I/WifiManager( 7227): packageName : com.test.thalitest
,I/WifiManager( 7227): setWifiEnabled : true
,I/WifiService( 2403): setWifiEnabled: true pid=7227, uid=10533
,W/ActivityManager( 2403): Permission Denial: getCurrentUser() from pid=7227, uid=10533 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2403): Failed getting userId using ActivityManagerNative
W/WifiService( 2403): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7227, uid=10533 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2403): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2403): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2403): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2403): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2403): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2403): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2403): disconnect: pid=7227, uid=10533
I/jxcore-log( 7227): Radios toggled
I/jxcore-log( 7227): 
I/wpa_supplicant( 3971): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7227): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7227): 
I/jxcore-log( 7227): Perf Test app loaded loaded
I/jxcore-log( 7227): 
,I/wpa_supplicant( 3971): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/jxcore-log( 7227): check test folder
I/jxcore-log( 7227): 
,I/jxcore-log( 7227): found test : ./testFindPeers.js
I/jxcore-log( 7227): 
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3971): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3971): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3971): First Scan Start
W/Settings( 2403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2403): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3971): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2403): InactiveState{ what=143375 }
D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3971): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3971): Skip scan - already scanning
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/ConnectivityService( 2403): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2403): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2403): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2403): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2403): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2403): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2403): InactiveState{ what=143375 }
D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2403): Attempting to switch to mobile
D/ConnectivityService( 2403): Attempting to switch to BLUETOOTH_TETHER
D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 7275): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7275):  
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/jxcore-log( 7227): found test : ./testSendData.js,
I/jxcore-log( 7227): 
,V/RouteController( 1915): RTNETLINK answers: No such process,
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1,
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/SELinux ( 7275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7275):  
I/SELinux ( 7275):  
,I/SELinux ( 7275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7275): >>>>> Normal User
,E/dalvikvm( 7275): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2403): route cmd failed: 
W/NetworkManagementService( 2403): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2403): '
W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2403): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2403): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2403): Error! unhandled message{ when=-87ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,E/WifiStateMachine( 2403): Error! unhandled message{ when=-88ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): RTNETLINK answers: No such process,
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1,
,E/WifiStateMachine( 2403): Error! unhandled message{ when=-12ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7275): in addTimaSignatureService
,D/NetUtils( 2403): android_net_utils_resetConnections in env=0x77f1e420 clazz=0x61600001 iface=wlan0 mask=0x3,
,D/TimaKeyStoreProvider( 7275): Cannot add TimaSignature Service, License check Failed
,D/ConnectivityService( 2403): resetConnections(wlan0, 3)
D/ActivityThread( 7275): Added TimaKesytore provider
,E/SPPClientService( 5594): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5594): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5594): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5594): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5594): [b] ResponseMap empty
,V/NativeCrypto( 2850): Read error: ssl=0x745e8650: I/O error during system call, Connection timed out
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x745e8650: I/O error during system call, Broken pipe
,D/dalvikvm( 7275): GC_CONCURRENT freed 2993K, 31% free 9572K/13800K, paused 3ms+18ms, total 72ms
,D/dalvikvm( 7275): WAIT_FOR_CONCURRENT_GC blocked 52ms
,I/System.out( 7275): Inside WakeupProvider
,I/System.out( 7275): Inside onCreate() of WakeupTriggerProvide
,I/chromium( 7227): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService( 2403): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit,
V/NetworkStats( 2403): updateIfacesLocked()
,V/NetworkStats( 2403): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit,
V/NetworkStats( 2403): performPollLocked() took 25ms
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,I/VlingoApplication( 7275): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7275): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7275): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 4742): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/NearbySettings( 4742): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4742): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4742): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7275): initQueue()
I/ActivityManager( 2403): Killing 6236:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 4742): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4742): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4742): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4742): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2403): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2403): updateDataUsageMap
,D/Tethering( 2403): MasterInitialState.processMessage what=3
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/CaptivePortalTracker( 2403): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
D/ConnectivityService( 2403): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PCWCLIENTTRACE_PushUtil( 6654): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6654): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6654): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6654): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6654): noConnectivity : true
,I/DBG_DM  ( 4774): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7304): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7304):  
,I/SELinux ( 7304): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7304):  
I/SELinux ( 7304):  
,I/SELinux ( 7304): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7304): >>>>> Normal User
,E/dalvikvm( 7304): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7304): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7304): in addTimaSignatureService,
I/wpa_supplicant( 3971): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3971): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3971): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 7304): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7304): Added TimaKesytore provider
,D/dalvikvm( 7304): GC_CONCURRENT freed 2997K, 31% free 9566K/13804K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 7304): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3971): Associated with C0.AA.48
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3971): freq(2412) increment count 2
,I/wpa_supplicant( 3971): meet head of list.
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3971): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3971): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
D/Tethering( 2403): interfaceStatusChanged wlan0, true
,D/WifiNative( 2403): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2403): Killing 6306:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2403): InactiveState{ what=143375 }
,D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,I/SELinux ( 7318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7318):  
,I/SELinux ( 7318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7318):  
I/SELinux ( 7318):  
,I/SELinux ( 7318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7318): >>>>> Normal User
,E/dalvikvm( 7318): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7318): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7318): Added TimaKesytore provider
,D/dalvikvm( 7318): GC_CONCURRENT freed 3011K, 31% free 9554K/13800K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 7318): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 2403): GC_CONCURRENT freed 4266K, 72% free 25546K/88768K, paused 14ms+29ms, total 293ms
,I/dhcpcd  ( 7330): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7330): bssid match
,I/ActivityManager( 2403): Killing 6361:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9502K/10784K, paused 3ms+5ms, total 47ms
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10784K, paused 3ms+4ms, total 37ms
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10784K, paused 3ms+4ms, total 37ms
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7337): GC_CONCURRENT freed 3004K, 31% free 9564K/13804K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/KLMS-2.3.201 : ( 7337): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7337): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449832526004
,I/KLMS-2.3.201 : ( 7337): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2403): Killing 6373:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7349):  
,I/SELinux ( 7349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7349):  
I/SELinux ( 7349):  
,I/SELinux ( 7349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7349): >>>>> Normal User
,E/dalvikvm( 7349): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7349): Added TimaKesytore provider
,D/dalvikvm( 7349): GC_CONCURRENT freed 3014K, 31% free 9558K/13808K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5863): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5863): [BDLM] already registered in spp
I/SA      ( 5863): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5863): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5863): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5863): [OR] == isSIMCardReady false ==
,I/SA      ( 5863): [SCU] == networkStateCheck == false
,I/SA      ( 5863): [OR] onReceive END
I/ActivityManager( 2403): Killing 6390:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7361): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7361):  
,I/SELinux ( 7361): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7361):  
I/SELinux ( 7361):  
,I/SELinux ( 7361): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7361): >>>>> Normal User
,E/dalvikvm( 7361): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7361): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7361): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7361): Added TimaKesytore provider
,D/dalvikvm( 7361): GC_CONCURRENT freed 2994K, 31% free 9570K/13800K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7361): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/sCloudBackupApp( 7361): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7361): Other Intent
I/ActivityManager( 2403): Killing 5647:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7374):  
,I/SELinux ( 7374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7374):  
I/SELinux ( 7374):  
,I/SELinux ( 7374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7374): >>>>> Normal User
,E/dalvikvm( 7374): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7374): Added TimaKesytore provider
,D/dalvikvm( 7374): GC_CONCURRENT freed 3008K, 31% free 9559K/13808K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 7374): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7374): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7374): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5394): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7374): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5394): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7374): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5394): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2403): Killing 6341:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5929): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5929): getCountryCode(): countryCode = PL
,D/Headlines( 5929): Breath.onCreate
,D/Headlines( 5929): Breath timer started. interval : 30000
,I/SELinux ( 7400): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7400):  
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5929): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5929): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5929): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5929): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,V/AlarmManager( 2403): waitForAlarm result :8
D/HeadlinesCardManager( 5929): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5929): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7400): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7400):  
I/SELinux ( 7400):  
,I/SELinux ( 7400): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7400): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7400): >>>>> Normal User
,E/dalvikvm( 7400): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7400): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7400): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7400): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7400): Added TimaKesytore provider
,D/dalvikvm( 7400): GC_CONCURRENT freed 2995K, 31% free 9571K/13804K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7400): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 7400): WAIT_FOR_CONCURRENT_GC blocked 1ms
,V/WebViewChromium( 7400): Binding Chromium to the background looper Looper (main, tid 1) {422853d8}
,I/chromium( 7400): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7400): Initializing chromium process, renderers=0
D/WifiP2pService( 2403): InactiveState{ what=143375 }
D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,I/jxcore-log( 7227): Connected to the server!
I/jxcore-log( 7227): 
,D/WifiStateMachine( 2403): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2403): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,W/chromium( 7400): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/WifiStateMachine( 2403): CaptivePortalCheckState enter
,I/chromium( 7227): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/ConnectivityService( 2403): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2403): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 2403): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/libEGL  ( 7400): loaded /system/lib/egl/libEGL_mali.so
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/ConnectivityService( 2403): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2403): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2403): net.tcp.delack.wifi not found in system properties. Using defaults
,D/libEGL  ( 7400): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/libEGL  ( 7400): loaded /system/lib/egl/libGLESv2_mali.so
D/ConnectivityService( 2403): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
I/Mali    ( 7400): Mali API Version : 401
I/Mali    ( 7400): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/PackageManager( 2403): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7400): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 7400): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/NetworkStats( 2403): updateIfacesLocked()
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,V/NetworkStats( 2403): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): performPollLocked() took 28ms
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit,
,I/NSApplication( 7400): Starting up...,
,I/iu.Environment( 5996): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true,
,D/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5193): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228d450
,I/SELinux ( 7469): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7469):  
,I/SELinux ( 7469): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7469):  
I/SELinux ( 7469):  
,I/SELinux ( 7469): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7469): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7469): >>>>> Normal User
,E/dalvikvm( 7469): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7469): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7469): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7469): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7469): Added TimaKesytore provider
,D/dalvikvm( 7469): GC_CONCURRENT freed 2981K, 31% free 9581K/13800K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7469): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Tethering( 2403): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2403): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2403): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4774): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection...
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,I/SELinux ( 7488): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7488):  
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,I/ActivityManager( 2403): Killing 6406:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/ActivityManager( 2403): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
I/SELinux ( 7488): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7488):  
I/SELinux ( 7488):  
,I/SELinux ( 7488): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7488): >>>>> Normal User
,E/dalvikvm( 7488): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7488): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7488): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7488): Added TimaKesytore provider
,I/ActivityManager( 2403): Killing 6040:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7492):  
I/SELinux ( 7492):  
,I/SELinux ( 7492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7492): >>>>> Normal User
,E/dalvikvm( 7492): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7492): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7492): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7492): Added TimaKesytore provider
,D/dalvikvm( 7488): GC_CONCURRENT freed 3010K, 31% free 9558K/13804K, paused 6ms+2ms, total 34ms
,D/dalvikvm( 7488): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/BadgeProvider( 7488): onCreate
,D/BadgeProvider( 7488): DatabaseHelper
,D/BadgeProvider( 7488): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2772): reloadBadges entered.
,D/BadgeProvider( 7488): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7488): sendNotify, [notify] : null
D/BadgeProvider( 7488): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7488): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7488): update, [UpdateCount] : 1
D/dalvikvm( 7492): GC_CONCURRENT freed 2996K, 31% free 9568K/13804K, paused 3ms+4ms, total 38ms
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/hcjo    ( 6017): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6017): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6017): exit::IDLE
,D/InitializeManagerStateMachine( 6017): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6017): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6017): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6017): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6017): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6017): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6017): entry::SUCCESS
,D/hcjo    ( 6017): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6017): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6017): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/SPPClientService( 5594): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
D/InitializeManagerStateMachine( 6017): exit::SUCCESS
,D/InitializeManagerStateMachine( 6017): entry::IDLE
,E/SPPClientService( 5594): [SystemStateMoniter] Current Time : 275806,
,E/SPPClientService( 5594): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5594): [[SystemStateMonitorService]] No Active Internet,
,D/NearbySettings( 4742): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4742): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4742): MountReceiver.onReceive - Keep current state
,D/Headlines( 5929): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5929): Breath 1744 latestRequest time : 1449832527052 current time : 1449832528797
I/ActivityManager( 2403): Killing 6223:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/NearbySettings( 4742): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4742): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5594): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 4742): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4742): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/jxcore-log( 7227): BLE advertisement not supported: Build version is 19
I/jxcore-log( 7227): 
I/NearbySettings( 4742): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4742): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4742): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2403): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2403
,D/NearbySettings( 4742): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4742): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,I/PCWCLIENTTRACE_PushUtil( 6654): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6654): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6654): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6654): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [g] getNetMCC return empty string
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7337): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7337): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449832529315
,I/KLMS-2.3.201 : ( 7337): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3468): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3596): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7523):  
,I/SELinux ( 7527): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7527):  
,I/SELinux ( 7523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7523):  
I/SELinux ( 7523):  
,I/SELinux ( 7523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7523): >>>>> Normal User
,E/dalvikvm( 7523): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7523): in addTimaSignatureService
I/SELinux ( 7527): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7527):  
I/SELinux ( 7527):  
,I/SELinux ( 7527): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7527): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7527): >>>>> Normal User
,E/dalvikvm( 7527): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
I/SA      ( 5863): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5863): [BDLM] already registered in spp
E/SELinux ( 7527): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SA      ( 5863): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5863): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/TimaKeyStoreProvider( 7523): Cannot add TimaSignature Service, License check Failed
I/SA      ( 5863): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5863): [OR] == isSIMCardReady false ==
,I/SA      ( 5863): [SCU] == networkStateCheck == true
,D/ActivityThread( 7523): Added TimaKesytore provider
I/SA      ( 5863): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5863): isChinaCountryCode : false
,I/SA      ( 5863): [OR] == networkStateCheck true ==
,I/SA      ( 5863): [OR] GetMyCountryZoneTask
,I/SA      ( 5863): [OR] onReceive END
,D/TimaKeyStoreProvider( 7527): in addTimaSignatureService
,I/SA      ( 5863): [SRS] prepareGetMyCountryZone
,I/SA      ( 5863): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5863): [SSP] query invoked
,D/TimaKeyStoreProvider( 7527): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7527): Added TimaKesytore provider
D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
I/SA      ( 5863): [TPMU] GetMccFromDB : null
I/SA      ( 5863): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5863): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver( 7361): Other Intent
,I/SA      ( 5863): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/dalvikvm( 7523): GC_CONCURRENT freed 2993K, 31% free 9572K/13804K, paused 6ms+2ms, total 48ms
,D/dalvikvm( 7523): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5929): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5929): getCountryCode(): countryCode = PL
D/dalvikvm( 7527): GC_CONCURRENT freed 2996K, 31% free 9573K/13808K, paused 7ms+2ms, total 32ms
,D/dalvikvm( 7527): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5929): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5929): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5929): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5929): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5929): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5929): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 7318): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/KVNProvider( 7527): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7527): getFindoCursor query string : 
,I/System.out( 7318): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7318): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5996): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5193): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228d450
,V/KVNProvider( 7527): getTagSearchCursor() tagSearchCursor count : 0
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/hcjo    ( 6017): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6017): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6017): exit::IDLE
,D/InitializeManagerStateMachine( 6017): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6017): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6017): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6017): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6017): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6017): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6017): entry::SUCCESS
,D/hcjo    ( 6017): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6017): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6017): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6017): exit::SUCCESS
,D/InitializeManagerStateMachine( 6017): entry::IDLE
,E/SPPClientService( 5594): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [SystemStateMoniter] Current Time : 276973
,E/SPPClientService( 5594): [SystemStateMoniter] No Connect : false
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/System.out( 7318): AsyncTask #1 calls detatch()
,D/dalvikvm( 5594): GC_CONCURRENT freed 2010K, 25% free 10450K/13784K, paused 5ms+7ms, total 65ms
,D/dalvikvm( 5594): WAIT_FOR_CONCURRENT_GC blocked 47ms
,W/System.err( 7318): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7318): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7318): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7318): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7318): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7318): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7318): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7318): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7318): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7318): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7318): Caused by: java.lang.NullPointerException
W/System.err( 7318): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7318): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7318): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7318): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7318): 	... 8 more
,I/ActivityManager( 2403): Killing 6258:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 10
,W/WifiP2pStateTracker( 2403): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2403): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2403):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2403): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2403): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine( 2403): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5594): [b] __InitReply__,
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11),
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11),
I/ActivityManager( 2403): Killing 6593:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/PowerManagerService( 2403): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2403) eventTime = 279543
,D/PowerManagerService( 2403): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2403 (0x0)
,D/PowerManagerService( 2403): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2403, ws=WorkSource{1000}) (elapsedTime=3484)
,I/GAV2    ( 7400): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 5863): [RC New] [v2liruge] api execute + 3186,
I/SA      ( 5863): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5863): AsyncTask #2 calls detatch()
,I/SA      ( 5863): [TPMU] getNetworkMcc : 
,I/SA      ( 5863): [SCU] saveMccToPreferece Start
I/SA      ( 5863): [SCU] RegionMCC : 260
,I/SA      ( 5863): [SSP] query invoked
,I/SA      ( 5863): [TPMU] GetMccFromDB : null
,I/SA      ( 5863): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5863): [SCU] saveMccToPreferece End
I/SA      ( 5863): [RC New] executeRequest [v2liruge] end. 3221
,I/SA      ( 5863): [RC New] Execute end
I/SA      ( 5863): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5863): [OR] GetMyCountryZoneTask Success
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 296, prevStep = 4, currStep = 4,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6654): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6654): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6654): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6654): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6654): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6654): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6654): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6654): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6654): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/CaptivePortalTracker( 2403): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2403): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null,
,D/CaptivePortalTracker( 2403): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2403): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2403): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2403): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
,D/CaptivePortalTracker( 2403): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2403): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6017): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6017): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6017): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6017): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6017): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6017): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6017): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 6017): execute::IDLE:EXECUTE,
,D/PreloadUpdateManagerStateMachine( 6017): exit::IDLE,
,D/PreloadUpdateManagerStateMachine( 6017): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 6017): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6017): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6017): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6017): entry::IDLE,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = -10,
,E/Watchdog( 2403): !@Sync 9,
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{46b35258 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{42fde818 u0 com.sec.spp.push/.PushClientService},
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 180s ago,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5929): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5929): Breath 27352 latestRequest time : 1449832529729 current time : 1449832557081,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2403): initializing...,
,I/TLC_TIMA_PKM_initialize( 2403): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32,
,I/TZ: mc_tlc_communication( 2403): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2403): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2403): root = 0, root_len = 1,
,I/TZ: mc_tlc_communication( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2403): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2403): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2403): device_id = 0x0
I/TZ: mc_tlc_communication( 2403): tlc_open() was called
,I/TZ: mc_tlc_communication( 2403): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2403): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2403): Opening the session
,I/TZ: mc_tlc_communication( 2403): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2403): Trustlet response is completed,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 225s ago,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2403): !@Sync 11,
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8027): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8027):  
,I/SELinux ( 8027): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8027):  
I/SELinux ( 8027):  
,I/SELinux ( 8027): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8027): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8027): >>>>> Normal User
,E/dalvikvm( 8027): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 8027): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 8027): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 8027): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 8027): Added TimaKesytore provider,
,D/dalvikvm( 8027): GC_CONCURRENT freed 3001K, 31% free 9564K/13804K, paused 3ms+1ms, total 29ms,
,D/dalvikvm( 8027): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,D/Headlines( 5929): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5929): Breath 77906 latestRequest time : 1449832529729 current time : 1449832607636
,I/ActivityManager( 2403): Killing 6508:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5929): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5929): Breath 87359 latestRequest time : 1449832529729 current time : 1449832617088,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): stay LED for fully charged
D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 12
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/dalvikvm( 2580): GC_CONCURRENT freed 15715K, 34% free 33870K/50820K, paused 28ms+9ms, total 128ms,
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2403): [PWL] Off : 275s ago,
,V/AlarmManager( 2403): waitForAlarm result :8,
,D/Headlines( 5929): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5929): Breath 117350 latestRequest time : 1449832529729 current time : 1449832647079,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2403): !@Sync 13,
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2403): waitForAlarm result :8
,D/Headlines( 5929): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5929): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5929): Breath 147351 latestRequest time : 1449832529729 current time : 1449832677080
,D/Headlines( 5929): stop 
,D/Headlines( 5929): Breath.onDestroy : 
I/ActivityManager( 2403): Killing 6626:com.samsung.groupcast/u0a15 (adj 15): empty #43
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 14
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 15
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2403): GC_CONCURRENT freed 4071K, 71% free 25399K/87348K, paused 24ms+21ms, total 286ms
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 16
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 17
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 18
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 19
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2403): !@Sync 20
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 525s ago
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 21
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/GAV2    ( 5690): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5690): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2403): !@Sync 22
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 23
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 4071): GC_CONCURRENT freed 2891K, 30% free 9725K/13872K, paused 8ms+3ms, total 52ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 24
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 25
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 680s ago
,E/Watchdog( 2403): !@Sync 26
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :8
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5594): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 19
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 27
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 28
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 765s ago
,E/Watchdog( 2403): !@Sync 29
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2403): GC_CONCURRENT freed 3989K, 72% free 25294K/87348K, paused 20ms+19ms, total 261ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2403): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 31
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2403): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 855s ago
,E/Watchdog( 2403): !@Sync 32
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 33
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 34
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 950s ago
,E/Watchdog( 2403): !@Sync 35
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 36
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SPPClientService( 5594): [b] __PingReply__
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 37
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 38
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 39
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 41
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1155s ago
,E/Watchdog( 2403): !@Sync 42
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 43
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2403): GC_FOR_ALLOC freed 3817K, 71% free 25424K/87348K, paused 201ms, total 201ms
,D/dalvikvm( 2403): GC_CONCURRENT freed 220K, 72% free 25248K/87348K, paused 9ms+17ms, total 219ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 44
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 45
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1265s ago
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 46
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 47
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4071): GC_CONCURRENT freed 2050K, 30% free 9722K/13868K, paused 3ms+6ms, total 60ms
,D/dalvikvm( 4071): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 48
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 13
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 49
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5996): GC_CONCURRENT freed 520K, 7% free 26872K/28628K, paused 5ms+12ms, total 62ms
,D/dalvikvm( 5996): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 2736): GC_CONCURRENT freed 1545K, 19% free 12110K/14936K, paused 7ms+10ms, total 82ms
,I/PowerManagerService( 2403): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 11729
,D/AmoledAdjustTimer( 2403): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 51
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 52
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 53
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 54
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 55
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 56
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2403): GC_CONCURRENT freed 3779K, 72% free 25320K/87348K, paused 22ms+20ms, total 275ms
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5594): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3312): Aggregate from 1449832058032 (log), 1449832058032 (data)
,D/dalvikvm( 3312): GC_CONCURRENT freed 1765K, 20% free 12681K/15684K, paused 8ms+9ms, total 97ms
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 57
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2403): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 58
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 59
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 61
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): performPollLocked(flags=0x3)
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): performPollLocked() took 51ms
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,I/SELinux (12736): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12736):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9502K/10784K, paused 4ms+4ms, total 45ms
,I/SELinux (12736): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12736):  
I/SELinux (12736):  
,I/SELinux (12736): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ProcessStatsService( 2403): Prepared write state in 48ms
E/SELinux (12736): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12736): >>>>> Normal User
E/dalvikvm(12736): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
E/SELinux (12736): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/ProcessStatsService( 2403): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-45-03.bin
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10784K, paused 3ms+5ms, total 40ms
,D/TimaKeyStoreProvider(12736): in addTimaSignatureService
,D/TimaKeyStoreProvider(12736): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12736): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10784K, paused 3ms+4ms, total 36ms
,D/dalvikvm(12736): GC_CONCURRENT freed 3005K, 31% free 9565K/13808K, paused 4ms+2ms, total 28ms
,D/dalvikvm(12736): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/@ WidgetProvider(12736): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12736): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12736): Widget random data : 1
,D/@ WidgetProvider(12736): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12736): Widget random data : 2
,E/dalvikvm(12736): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(12736): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12736): VFY: replacing opcode 0x22 at 0x0038
,I/ActivityManager( 2403): Killing 6640:com.android.musicfx/u0a24 (adj 15): empty #43
E/dalvikvm(12736): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12736): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12736): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12736): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12736): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12736): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12736): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12736): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12736): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12736): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12736): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12736): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12736): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12736): Thread-672(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7bab15d8: I/O error during system call, Connection timed out
I/System.out(12736): Thread-672(ApacheHTTPLog):isShipBuild true
,I/System.out(12736): Thread-672(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(12736): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12736): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12736): Max ALLOWED memory (MB): 128
,V/ImageManager(12736): Max SHOULD USE memory (MB): 128
,V/ImageManager(12736): Max Image Cache memory (MB): 32
,D/skia    (12736): getTotalSize : Do not get file length
,D/@ WidgetProvider(12736): Building widget : 5
,D/ChimeraCfgMgr( 3312): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3312): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 2772): GC_FOR_ALLOC freed 8587K, 39% free 18492K/30152K, paused 94ms, total 94ms
,I/SELinux (12760): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12760):  
,I/SELinux (12760): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12760):  
I/SELinux (12760):  
,I/SELinux (12760): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12760): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm(12760): >>>>> Normal User
E/dalvikvm(12760): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
I/GamesSyncServiceMain( 3312): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 3312): Failed to execute periodic sync, missing client context - aborting
,E/SELinux (12760): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider(12760): in addTimaSignatureService
,D/TimaKeyStoreProvider(12760): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12760): Added TimaKesytore provider
,D/dalvikvm(12760): GC_CONCURRENT freed 2997K, 31% free 9573K/13808K, paused 4ms+2ms, total 30ms
,D/dalvikvm(12760): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/dalvikvm(12760): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm(12760): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm(12760): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm(12760): Unable to resolve superclass of Lal; (749)
W/dalvikvm(12760): Link of class 'Lal;' failed
E/dalvikvm(12760): Could not find class 'al', referenced from method b.a
W/dalvikvm(12760): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm(12760): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm(12760): Unable to resolve superclass of Lan; (749)
W/dalvikvm(12760): Link of class 'Lan;' failed
E/dalvikvm(12760): Could not find class 'an', referenced from method b.a
W/dalvikvm(12760): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm(12760): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm(12760): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm(12760): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm(12760): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm(12760): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm(12760): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm(12760): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm(12760): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm(12760): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm(12760): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm(12760): Unable to resolve superclass of Lal; (749)
W/dalvikvm(12760): Link of class 'Lal;' failed
,D/dalvikvm(12760): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm(12760): Unable to resolve superclass of Lan; (749)
W/dalvikvm(12760): Link of class 'Lan;' failed
D/dalvikvm(12760): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm(12760): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm(12760): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(12760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm(12760): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(12760): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm(12760): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm(12760): VFY: unable to resolve instance field 36
,D/dalvikvm(12760): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm(12760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm(12760): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(12760): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm(12760): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm(12760): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm(12760): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4232bb58
,D/dalvikvm(12760): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4232bb58
,D/dalvikvm(12760): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4232bb58, skipping init
,D/dalvikvm(12760): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4232bb58
D/dalvikvm(12760): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4232bb58
,V/JNIHelp (12760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm(12760): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(12760): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4232bb58
,D/dalvikvm(12760): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4232bb58
D/dalvikvm(12760): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4232bb58
,D/dalvikvm(12760): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4232bb58
,I/dalvikvm(12760): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm(12760): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm(12760): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm(12760): DexOpt: --- BEGIN 'ads796062310.jar' (bootstrap=0) ---
,I/ProviderInstaller(12760): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(12789): DexOpt: load 5ms, verify+opt 14ms, 194052 bytes
,D/dalvikvm(12760): DexOpt: --- END 'ads796062310.jar' (success) ---
,D/dalvikvm(12760): DEX prep '/data/data/com.google.android.youtube/cache/ads796062310.jar': unzip in 0ms, rewrite 115ms
,E/YouTube MDX(12760): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm(12760): GC_CONCURRENT freed 1933K, 23% free 10707K/13876K, paused 6ms+6ms, total 57ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl(12760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(12760): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(12760): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(12760): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(12760): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm(12760): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm(12760): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm(12760): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm(12760): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12760): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm(12760): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm(12760): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(12760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl(12760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(12760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/InstanceID/Rpc(12760): Found 10012
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(12760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/System.out(12760): Thread-737(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12760): Thread-737(ApacheHTTPLog):isShipBuild true
,I/System.out(12760): Thread-737(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(12760): Thread-737 calls detatch()
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2403): [PWL] Off : 1755s ago
,I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=2850, ws=WorkSource{10175 com.google.android.youtube}) (elapsedTime=5610)
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/System.out(12760): Thread-725 calls detatch()
,D/dalvikvm(12760): GC_CONCURRENT freed 1306K, 19% free 11375K/13952K, paused 9ms+7ms, total 71ms
,I/ActivityManager( 2403): Killing 6666:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/dalvikvm( 2850): GC_CONCURRENT freed 1928K, 23% free 10922K/14156K, paused 5ms+6ms, total 61ms
,I/System.out(12760): Thread-726 calls detatch()
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 62
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 63
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2403): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2403): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 64
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 65
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2403): GC_CONCURRENT freed 3794K, 71% free 25381K/87348K, paused 21ms+20ms, total 265ms
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
I/ActivityManager( 2403): Killing 6503:com.sec.knox.bridge/1000 (adj 15): empty for 1832s
I/ActivityManager( 2403): Killing 4913:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1832s
I/ActivityManager( 2403): Killing 6489:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1832s
I/ActivityManager( 2403): Killing 6465:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1842s
,I/ActivityManager( 2403): Killing 6812:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1842s
,I/ActivityManager( 2403): Killing 6798:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1843s
,I/ActivityManager( 2403): Killing 6786:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1843s
,I/ActivityManager( 2403): Killing 6774:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1843s
I/ActivityManager( 2403): Killing 6761:com.samsung.helphub/1000 (adj 15): empty for 1844s
,I/ActivityManager( 2403): Killing 6748:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1844s
I/ActivityManager( 2403): Killing 6735:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1844s
,I/ActivityManager( 2403): Killing 6721:com.sec.android.service.cm/u0a82 (adj 15): empty for 1844s
,I/ActivityManager( 2403): Killing 6422:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1844s
,I/ActivityManager( 2403): Killing 5750:com.android.mms/u0a49 (adj 15): empty for 1844s
I/ActivityManager( 2403): Killing 6696:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1844s
,I/ActivityManager( 2403): Killing 6058:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1845s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2403): No listener is left
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 66
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 67
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 68
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2403): LightSensor setDelay = 200000000
,D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 14
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 69
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2403): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
D/AndroidRuntime(13456): 
D/AndroidRuntime(13456): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13456): CheckJNI is OFF
D/AndroidRuntime(13456): setted country_code = Poland
D/AndroidRuntime(13456): setted countryiso_code = PL
D/AndroidRuntime(13456): setted sales_code = PLS
D/AndroidRuntime(13456): readGMSProperty: start
D/AndroidRuntime(13456): readGMSProperty: already setted!!
D/AndroidRuntime(13456): readGMSProperty: end
D/AndroidRuntime(13456): addProductProperty: start
D/dalvikvm(13456): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13456): Added shared lib libjavacore.so 0x0
D/dalvikvm(13456): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13456): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13456): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13456): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13456): failed to load memtrack module: -2
D/dalvikvm(13456): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13456): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2403): START PACKAGE DELETE: observer{1122852992}
D/PackageManager( 2403): pkg{<packageName>}
D/PackageManager( 2403): user{0}
D/PackageManager( 2403): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2403): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2403): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2403): !@killApplicatoin: 10533, uninstall pkg
I/ActivityManager( 2403): Killing 7227:com.test.thalitest/u0a533 (adj 0): stop com.test.thalitest
I/ActivityManager( 2403): Killing 5863:com.osp.app.signin/u0a44 (adj 15): empty for 1828s
I/ActivityManager( 2403): Killing 6680:com.policydm/1000 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 7349:com.sec.android.soagent/u0a38 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 7275:com.vlingo.midas/u0a34 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 7337:com.samsung.klmsagent/u0a18 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 7318:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 5803:com.sec.android.diagmonagent/1000 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 7304:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 6654:com.sec.pcw.device/1000 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 4742:com.android.settings/1000 (adj 15): empty for 1829s
I/ActivityManager( 2403): Killing 7488:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1829s
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (8/10)
I/WindowState( 2403): WIN DEATH: Window{43022988 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/10)
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 2403): Skipping PackageSetting{42a20520 com.example.hello/10511} due to missing metadata
D/PackageManager( 2403): setPackageStoppedState - Execution time: 134 ms
D/PackageManager( 2403): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10533, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2403): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10533, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/DBG_DM  ( 4774): [3.19.140541][Line:408][onResume] 
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2981): mOCRHelper is null
I/InputReader( 2403): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 4774): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
I/DBG_DM  ( 4774): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/DBG_DM  ( 4774): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
D/dalvikvm( 2951): GC_EXPLICIT freed 1470K, 28% free 10036K/13804K, paused 7ms+4ms, total 95ms
I/DBG_DM  ( 4774): [3.19.140541][Line:418][onResume] Postpone Count : 26
D/QuickConnect[1.1][2] ( 5193): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 4774): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/DBG_DM  ( 4774): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/SELinux (13488): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13488):  
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4774): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/SELinux (13488): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13488):  
I/SELinux (13488):  
I/SELinux (13488): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13488): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13488): >>>>> Normal User
E/dalvikvm(13488): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13488): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3312): GC_EXPLICIT freed 456K, 21% free 12410K/15684K, paused 12ms+20ms, total 219ms
D/TimaKeyStoreProvider(13488): in addTimaSignatureService
D/TimaKeyStoreProvider(13488): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13488): Added TimaKesytore provider
D/dalvikvm( 2403): GC_EXPLICIT freed 2837K, 71% free 24891K/85240K, paused 10ms+41ms, total 258ms
D/dalvikvm( 2403): WAIT_FOR_CONCURRENT_GC blocked 229ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4774): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
D/RegisteredServicesCache( 2757): empty dynamic service
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/DBG_DM  ( 4774): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4774): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4774): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4774): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4774): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
D/RCPManagerService( 2403): PackageReceiver onReceive()
I/DBG_DM  ( 4774): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/StatusBarManagerService( 2403): semi p:4774,o:t
D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/HarmonyEASService( 2403): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/Activity( 4774): setTransGradationMode to true
I/DBG_DM  ( 4774): [3.19.140541][Line:400][onPause] 
I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13488): GC_CONCURRENT freed 3000K, 31% free 9568K/13808K, paused 6ms+1ms, total 30ms
D/dalvikvm(13488): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13488): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13488): ELMEngine.ELMEngine( context ).
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13488): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13488): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13488): ElmAgentService : onCreate()
D/elm:14132(13488): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13488): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13488): MDMBridge.getInstance()
D/elm:14132(13488): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13488): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13505): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13505):  
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2403): Got RemoteException sending setActive(false) notification to pid 7227 uid 10533
I/SELinux (13505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13505):  
I/SELinux (13505):  
I/SELinux (13505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13505): >>>>> Normal User
E/dalvikvm(13505): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132(13488): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(13488): ElmAgentService : onDestroy().
I/ActivityManager( 2403): Killing 7523:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1829s
D/TimaKeyStoreProvider(13505): in addTimaSignatureService
D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.release()
D/TimaKeyStoreProvider(13505): Cannot add TimaSignature Service, License check Failed
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/ActivityThread(13505): Added TimaKesytore provider
D/EnterpriseDeviceManagerService( 2403): Package has changed for user 0
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13505): GC_CONCURRENT freed 2998K, 31% free 9567K/13804K, paused 5ms+1ms, total 21ms
D/dalvikvm(13505): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/BackupManagerService( 2403): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2403): removePackageParticipantsLocked: uid=10533 #1
D/dalvikvm( 2403): GC_EXPLICIT freed 1122K, 71% free 24839K/85240K, paused 10ms+31ms, total 432ms
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(2) - 4
I/SELinux (13520): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13520):  
I/ActivityManager( 2403): Killing 7361:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1829s
I/SELinux (13520): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13520):  
I/SELinux (13520):  
I/SELinux (13520): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13520): >>>>> Normal User
E/dalvikvm(13520): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13520): in addTimaSignatureService
D/TimaKeyStoreProvider(13520): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13520): Added TimaKesytore provider
D/PackageManager( 2403): delete sourFile : 
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2403): delete native library directory: 
D/PackageManager( 2403): return delete result to caller: 1122852992
D/PackageManager( 2403): returnCode: 1
D/AndroidRuntime(13456): Shutting down VM
D/dalvikvm(13456): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13520): GC_CONCURRENT freed 3001K, 31% free 9567K/13808K, paused 2ms+1ms, total 19ms
D/dalvikvm(13520): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13534): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13534):  
I/ActivityManager( 2403): Killing 7527:com.sec.android.app.voicenote/1000 (adj 15): empty for 1829s
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13534): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13534):  
I/SELinux (13534):  
I/SELinux (13534): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13534): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13534): >>>>> Normal User
E/dalvikvm(13534): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13534): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13534): in addTimaSignatureService
D/TimaKeyStoreProvider(13534): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13534): Added TimaKesytore provider
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ApplicationsProvider( 2951): Could not fetch usage stats
W/ApplicationsProvider( 2951): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2951): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2951): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2951): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2951): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2951): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2403): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2403): clearDefaults: com.test.thalitest
D/dalvikvm(13534): GC_CONCURRENT freed 2998K, 31% free 9572K/13808K, paused 3ms+2ms, total 22ms
D/dalvikvm(13534): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/SELinux (13549): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13549):  
I/SELinux (13549): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13549):  
I/SELinux (13549):  
I/SELinux (13549): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13549): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13549): >>>>> Normal User
E/dalvikvm(13549): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13549): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13549): Enabling JNI app bug workarounds for target SDK version 8...
I/ActivityManager( 2403): Killing 7374:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1830s
D/TimaKeyStoreProvider(13549): in addTimaSignatureService
D/TimaKeyStoreProvider(13549): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13549): Added TimaKesytore provider
D/dalvikvm(13549): GC_CONCURRENT freed 2997K, 31% free 9570K/13804K, paused 1ms+2ms, total 18ms
D/dalvikvm(13549): WAIT_FOR_CONCURRENT_GC blocked 16ms
E/SQLiteDatabase(13549): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13549): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13549): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13549): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13549): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13549): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13549): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13549): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13549): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13549): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13549): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13549): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13549): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13549): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13549): Shutting down VM
W/dalvikvm(13549): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13549): FATAL EXCEPTION: main
E/AndroidRuntime(13549): Process: com.sec.pcw.device, PID: 13549
E/AndroidRuntime(13549): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13549): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13549): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13549): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13549): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13549): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13549): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13549): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13549): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13549): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13549): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13549): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13549): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13549): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13549): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13549): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13549): 	... 12 more
I/SELinux (13562): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13562):  
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop237.tmp: open failed: EROFS (Read-only file system)
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
I/Process (13549): Sending signal. PID: 13549 SIG: 9
I/ActivityManager( 2403): Process com.sec.pcw.device (pid 13549) (adj 0) has died.
I/SELinux (13562): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13562):  
I/SELinux (13562):  
I/SELinux (13562): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13562): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13562): >>>>> Normal User
E/dalvikvm(13562): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13562): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AlarmManager( 2403): waitForAlarm result :8
V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/TimaKeyStoreProvider(13562): in addTimaSignatureService
D/TimaKeyStoreProvider(13562): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13562): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/dalvikvm(13562): GC_CONCURRENT freed 2989K, 31% free 9579K/13804K, paused 3ms+2ms, total 23ms
D/dalvikvm(13562): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
W/System.err(13562): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13562): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13562): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13562): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13562): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13562): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13562): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13562): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13562): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13562): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13562): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13562): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13562): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13562): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13562): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13562): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13562): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13562): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13562): 	at libcore.io.Posix.open(Native Method)
W/System.err(13562): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13562): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13562): 	... 21 more
D/GalaxyFinderApplication(13562): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13562): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13576):  
I/ActivityManager( 2403): Killing 7400:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1830s
I/SELinux (13576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13576):  
I/SELinux (13576):  
I/SELinux (13576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13576): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13576): >>>>> Normal User
E/dalvikvm(13576): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13576): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13576): in addTimaSignatureService
D/TimaKeyStoreProvider(13576): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13576): Added TimaKesytore provider
D/dalvikvm(13576): GC_CONCURRENT freed 3003K, 31% free 9557K/13800K, paused 2ms+2ms, total 19ms
D/dalvikvm(13576): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/ContextImpl(13576): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13576): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13576): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13576): ContentProvider is not null
W/ResourceType(13576): No package identifier when getting value for resource number 0x00000000
I/System.out(13576): resource Id::2131361807
D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): stay LED for fully charged
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
E/SQLiteDatabase(13576): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13576): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13576): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13576): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13576): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13576): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13576): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13576): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13576): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13576): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13576): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13576): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13576): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13576): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13576): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13576): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13576): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13576): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13576): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase
```
