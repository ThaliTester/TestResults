#### Test 56204092c98eeae_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7109): 
D/AndroidRuntime( 7109): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7109): CheckJNI is OFF
D/AndroidRuntime( 7109): setted country_code = Poland
D/AndroidRuntime( 7109): setted countryiso_code = PL
D/AndroidRuntime( 7109): setted sales_code = PLS
D/AndroidRuntime( 7109): readGMSProperty: start
D/AndroidRuntime( 7109): readGMSProperty: already setted!!
D/AndroidRuntime( 7109): readGMSProperty: end
D/AndroidRuntime( 7109): addProductProperty: start
D/dalvikvm( 7109): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7109): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7109): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7109): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7109): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7109): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7109): failed to load memtrack module: -2
D/dalvikvm( 7109): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7109): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SELinux ( 7136): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7136):  
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7109): Shutting down VM
D/dalvikvm( 7109): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7136): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7136):  
I/SELinux ( 7136):  
I/SELinux ( 7136): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7136): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7136): >>>>> Normal User
E/dalvikvm( 7136): >>>>> com.test.thalitest [ userId:0 | appId:10626 ]
E/SELinux ( 7136): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7136): in addTimaSignatureService
D/TimaKeyStoreProvider( 7136): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7136): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4169): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4169): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=17 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=17 Removed YUIInstallC (-2/10)
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by BW check
D/dalvikvm( 7136): GC_CONCURRENT freed 3016K, 32% free 9545K/14020K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7136): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7136): Binding Chromium to the background looper Looper (main, tid 1) {422bc1e0}
I/chromium( 7136): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7136): Initializing chromium process, renderers=0
W/chromium( 7136): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7136): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7136): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7136): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7136): Mali API Version : 401
,I/Mali    ( 7136): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7136): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7136): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7136): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7136): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7136): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7136): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2421): tr p:7136,o:f
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,W/dalvikvm( 7136): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7136): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7136): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7136): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7136): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7136): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7136): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7136): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7136): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7136): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7136): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7136): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7136): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:7136,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7136): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7136): Enabling debug mode 0
,W/AwContents( 7136): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 7136): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 7136): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7136): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7136): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422ad508
,D/dalvikvm( 7136): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422ad508
D/jxcore_app_log( 7136): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027955904
,D/JX-Cordova( 7136): jxcore cordova android initializing
,D/dalvikvm( 7136): GC_CONCURRENT freed 1273K, 20% free 11347K/14072K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7136): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7136): GC_CONCURRENT freed 1715K, 18% free 15175K/18372K, paused 3ms+3ms, total 44ms
,D/dalvikvm( 7136): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7136): GC_FOR_ALLOC freed 5712K, 31% free 16720K/23924K, paused 44ms, total 52ms
,D/dalvikvm( 7136): GC_CONCURRENT freed 6766K, 32% free 18106K/26364K, paused 1ms+10ms, total 66ms
,D/dalvikvm( 7136): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/dalvikvm( 7136): GC_FOR_ALLOC freed 1002K, 32% free 17991K/26364K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7136): Grow heap (frag case) to 22.527MB for 3713210-byte allocation
,D/dalvikvm( 7136): GC_FOR_ALLOC freed 2444K, 37% free 19172K/29992K, paused 51ms, total 51ms
,D/dalvikvm( 7136): GC_FOR_ALLOC freed 2127K, 37% free 19154K/29992K, paused 49ms, total 49ms
,W/jxcore-log( 7136): Initializing JXcore engine
,W/jxcore-log( 7136): JXcore engine is ready
,W/jxcore-log( 7136): Starting JXcore engine
,W/jxcore-log( 7136): Platform android
W/jxcore-log( 7136): 
,W/jxcore-log( 7136): Process ARCH arm
W/jxcore-log( 7136): 
,I/jxcore-log( 7136): JXcore Cordova bridge is ready!
I/jxcore-log( 7136): 
,W/jxcore-log( 7136): JXcore engine is started
,I/chromium( 7136): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/jxcore-log( 7136): Toggling radios to true
I/jxcore-log( 7136): 
,D/BluetoothAdapter( 7136): enable(): BT is already enabled..!
,I/WifiManager( 7136): packageName : com.test.thalitest
,I/WifiManager( 7136): setWifiEnabled : true
,I/WifiService( 2421): setWifiEnabled: true pid=7136, uid=10626
,W/ActivityManager( 2421): Permission Denial: getCurrentUser() from pid=7136, uid=10626 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): Failed getting userId using ActivityManagerNative
W/WifiService( 2421): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7136, uid=10626 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2421): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2421): disconnect: pid=7136, uid=10626
I/wpa_supplicant( 3970): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7136): Radios toggled
I/jxcore-log( 7136): 
,I/jxcore-log( 7136): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7136): 
I/wpa_supplicant( 3970): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/jxcore-log( 7136): Perf Test app loaded loaded
I/jxcore-log( 7136): 
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3970): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3970): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3970): First Scan Start
W/Settings( 2421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2421): ignore requestNetworkTransitionWakelock airplane:true
I/wpa_supplicant( 3970): Scan requested (ret=0) - scan timeout 30 seconds
I/jxcore-log( 7136): check test folder
I/jxcore-log( 7136): 
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
I/jxcore-log( 7136): found test : ./testFindPeers.js
I/jxcore-log( 7136): 
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
I/wpa_supplicant( 3970): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3970): Skip scan - already scanning
D/ConnectivityService( 2421): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2421): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2421): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2421): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2421): Attempting to switch to mobile
,D/ConnectivityService( 2421): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7185): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7185):  
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,I/jxcore-log( 7136): found test : ./testSendData.js
I/jxcore-log( 7136): 
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
E/WifiStateMachine( 2421): Error! unhandled message{ when=-74ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-73ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService( 2421): route cmd failed: 
W/NetworkManagementService( 2421): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SELinux ( 7185): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7185):  
I/SELinux ( 7185):  
I/SELinux ( 7185): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7185): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7185): >>>>> Normal User
E/dalvikvm( 7185): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
E/SELinux ( 7185): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine( 2421): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7185): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7185): Cannot add TimaSignature Service, License check Failed
,D/NetUtils( 2421): android_net_utils_resetConnections in env=0x780c3810 clazz=0x62900001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2421): resetConnections(wlan0, 3)
D/ActivityThread( 7185): Added TimaKesytore provider
,E/SPPClientService( 5531): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5531): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5531): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5531): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5531): [b] ResponseMap empty
,V/NativeCrypto( 2848): Read error: ssl=0x7bac8068: I/O error during system call, Connection timed out
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7bac8068: I/O error during system call, Broken pipe
,D/dalvikvm( 7185): GC_CONCURRENT freed 2985K, 32% free 9580K/14020K, paused 4ms+4ms, total 82ms
,D/dalvikvm( 7185): WAIT_FOR_CONCURRENT_GC blocked 65ms
,D/ConnectivityService( 2421): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2421): updateIfacesLocked()
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 20ms
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,I/chromium( 7136): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/System.out( 7185): Inside WakeupProvider
,I/System.out( 7185): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7185): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7185): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7185): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/DialogFlow( 7185): initQueue()
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2833): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2421): Killing 4205:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2833): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2421): updateDataUsageMap
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2421): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6598): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6598): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6598): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6598): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6598): noConnectivity : true
,I/SELinux ( 7214): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7214):  
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7214): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7214):  
I/SELinux ( 7214):  
,I/SELinux ( 7214): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7214): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7214): >>>>> Normal User
,E/dalvikvm( 7214): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7214): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7214): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7214): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7214): Added TimaKesytore provider
,I/wpa_supplicant( 3970): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 3970): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3970): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/dalvikvm( 7214): GC_CONCURRENT freed 2989K, 32% free 9574K/14020K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7214): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3970): Associated with C0.AA.48
I/wpa_supplicant( 3970): freq(2412) increment count 2
,I/wpa_supplicant( 3970): meet head of list.
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3970): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3970): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,D/WifiNative( 2421): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2421): Killing 6233:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
,D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,I/SELinux ( 7228): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7228):  
,I/SELinux ( 7228): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7228):  
I/SELinux ( 7228):  
,I/SELinux ( 7228): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7228): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7228): >>>>> Normal User
,E/dalvikvm( 7228): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7228): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7228): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7228): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7228): Added TimaKesytore provider
,D/dalvikvm( 7228): GC_CONCURRENT freed 2999K, 32% free 9566K/14024K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7228): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/dhcpcd  ( 7240): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7240): bssid match
,I/ActivityManager( 2421): Killing 6310:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7248): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7248):  
,I/SELinux ( 7248): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7248):  
I/SELinux ( 7248):  
,I/SELinux ( 7248): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7248): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7248): >>>>> Normal User
,E/dalvikvm( 7248): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7248): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7248): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7248): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7248): Added TimaKesytore provider,
,D/dalvikvm( 7248): GC_CONCURRENT freed 3013K, 32% free 9555K/14024K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7248): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...,
,D/KLMS-2.3.201 : ( 7248): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7248): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452883702168
,I/KLMS-2.3.201 : ( 7248): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false,
,I/ActivityManager( 2421): Killing 6323:com.sec.android.app.voicenote/1000 (adj 15): empty #43,
,I/SELinux ( 7260): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7260):  
,I/SELinux ( 7260): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7260):  
I/SELinux ( 7260):  
,I/SELinux ( 7260): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7260): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7260): >>>>> Normal User
,E/dalvikvm( 7260): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7260): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7260): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7260): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7260): Added TimaKesytore provider
,D/dalvikvm( 7260): GC_CONCURRENT freed 3000K, 32% free 9562K/14016K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7260): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7260): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7260): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5775): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5775): [BDLM] already registered in spp
I/SA      ( 5775): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5775): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [OR] == isSIMCardReady false ==
I/SA      ( 5775): [SCU] == networkStateCheck == false
,I/SA      ( 5775): [OR] onReceive END
I/ActivityManager( 2421): Killing 6370:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SELinux ( 7272): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7272):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9499K/11000K, paused 4ms+4ms, total 42ms,
,I/SELinux ( 7272): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7272):  
I/SELinux ( 7272):  
,I/SELinux ( 7272): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7272): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7272): >>>>> Normal User
,E/dalvikvm( 7272): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7272): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9499K/11000K, paused 3ms+4ms, total 37ms,
,D/TimaKeyStoreProvider( 7272): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7272): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7272): Added TimaKesytore provider,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9499K/11000K, paused 3ms+5ms, total 37ms,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 10,
D/dalvikvm( 7272): GC_CONCURRENT freed 2997K, 32% free 9574K/14024K, paused 4ms+2ms, total 32ms
D/dalvikvm( 7272): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/sCloudBackupApp( 7272): sCloudBackupApp Version Info : 3.7.3.KK_APP,
,I/SCloudBackupReceiver( 7272): Other Intent,
I/ActivityManager( 2421): Killing 5577:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7285): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7285):  
,I/SELinux ( 7285): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7285):  
I/SELinux ( 7285):  
I/SELinux ( 7285): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7285): >>>>> Normal User
,E/dalvikvm( 7285): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7285): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7285): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7285): Added TimaKesytore provider
,D/dalvikvm( 7285): GC_CONCURRENT freed 2990K, 32% free 9567K/14016K, paused 6ms+2ms, total 35ms
,D/dalvikvm( 7285): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager,
,D/com.samsung.app( 7285): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create,
,D/com.samsung.app( 7285): [KK AccuPhone]>>> RM:136 [0:0]  V init ,
,D/daemonapp( 5329): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/com.samsung.app( 7285): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5329): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7285): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5329): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ActivityManager( 2421): Killing 6285:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5823): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5823): getCountryCode(): countryCode = PL,
,D/Headlines( 5823): Breath.onCreate,
,D/Headlines( 5823): Breath timer started. interval : 30000,
,I/SELinux ( 7315): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7315):  
,D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5823): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5823): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,V/AlarmManager( 2421): waitForAlarm result :8
D/Headlines( 5823): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5823): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5823): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5823): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7315): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7315):  
I/SELinux ( 7315):  
,I/SELinux ( 7315): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7315): >>>>> Normal User
,E/dalvikvm( 7315): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7315): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7315): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7315): Added TimaKesytore provider
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
,D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2421): VerifyingLinkState enter
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2421): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2421): CaptivePortalCheckState enter
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,D/ConnectivityService( 2421): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 2421): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2421): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/ConnectivityService( 2421): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2421): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2421): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/dalvikvm( 7315): GC_CONCURRENT freed 2994K, 32% free 9569K/14020K, paused 18ms+2ms, total 63ms
,D/dalvikvm( 7315): WAIT_FOR_CONCURRENT_GC blocked 28ms
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,I/jxcore-log( 7136): Connected to the server!
I/jxcore-log( 7136): 
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/chromium( 7136): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/NetworkStats( 2421): updateIfacesLocked()
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/NetworkStats( 2421): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,V/WebViewChromium( 7315): Binding Chromium to the background looper Looper (main, tid 1) {422b92d0}
I/chromium( 7315): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/NetworkStats( 2421): performPollLocked() took 23ms
I/BrowserProcessMain( 7315): Initializing chromium process, renderers=0
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,W/chromium( 7315): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7315): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7315): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7315): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7315): Mali API Version : 401
,I/Mali    ( 7315): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7315): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7315): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7315): Starting up...
,I/iu.Environment( 5887): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5132): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5132): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5132): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422c9708
,I/SELinux ( 7372): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7372):  
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2421): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/SELinux ( 7372): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7372):  
I/SELinux ( 7372):  
,I/SELinux ( 7372): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7372): >>>>> Normal User
,E/dalvikvm( 7372): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4731): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/TimaKeyStoreProvider( 7372): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7372): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7372): Added TimaKesytore provider
V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): waitForAlarm result :4
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7372): GC_CONCURRENT freed 2980K, 32% free 9582K/14020K, paused 4ms+2ms, total 34ms
,D/dalvikvm( 7372): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/SELinux ( 7391): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7391):  
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/ActivityManager( 2421): Killing 6304:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7391): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7391):  
I/SELinux ( 7391):  
,I/SELinux ( 7391): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7391): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7391): >>>>> Normal User
,E/dalvikvm( 7391): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7391): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7401): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7401):  
,D/TimaKeyStoreProvider( 7391): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7391): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7391): Added TimaKesytore provider
,I/ActivityManager( 2421): Killing 5935:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7401): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7401):  
I/SELinux ( 7401):  
,I/SELinux ( 7401): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7401): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7401): >>>>> Normal User
,E/dalvikvm( 7401): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7401): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7401): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7401): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7401): Added TimaKesytore provider
,D/dalvikvm( 7391): GC_CONCURRENT freed 3001K, 32% free 9562K/14020K, paused 6ms+3ms, total 41ms
,D/dalvikvm( 7391): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/BadgeProvider( 7391): onCreate
,D/BadgeProvider( 7391): DatabaseHelper
,D/BadgeProvider( 7391): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7401): GC_CONCURRENT freed 2999K, 32% free 9562K/14020K, paused 4ms+3ms, total 31ms
,D/dalvikvm( 7401): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Launcher.Model( 2781): reloadBadges entered.
D/BadgeProvider( 7391): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7391): sendNotify, [notify] : null
D/BadgeProvider( 7391): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7391): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7391): update, [UpdateCount] : 1
,D/hcjo    ( 5911): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5911): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5911): exit::IDLE
,D/InitializeManagerStateMachine( 5911): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5911): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5911): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5911): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5911): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5911): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5911): entry::SUCCESS
,D/hcjo    ( 5911): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5911): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5911): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5911): exit::SUCCESS
,D/InitializeManagerStateMachine( 5911): entry::IDLE
,E/SPPClientService( 5531): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5531): [SystemStateMoniter] Current Time : 276516
,E/SPPClientService( 5531): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5531): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,D/Headlines( 5823): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5823): Breath 1762 latestRequest time : 1452883703173 current time : 1452883704935
,E/SPPClientService( 5531): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5531): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2421): Killing 6252:com.android.providers.calendar/u0a45 (adj 15): empty #43
,E/SPPClientService( 5531): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5531): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,V/AlarmManager( 2421): waitForAlarm result :4
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,I/dalvikvm( 7136): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7136): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7136): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7136): Shutting down VM
,W/dalvikvm( 7136): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
E/AndroidRuntime( 7136): FATAL EXCEPTION: main
E/AndroidRuntime( 7136): Process: com.test.thalitest, PID: 7136
E/AndroidRuntime( 7136): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7136): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7136): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7136): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7136): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7136): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7136): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7136): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7136): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7136): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7136): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7136): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7136): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7136): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7136): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7136): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7136): 	at dalvik.system.NativeStart.main(Native Method)
,D/PowerManagerService( 2421): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421
E/SPPClientService( 5531): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
I/PCWCLIENTTRACE_PushUtil( 6598): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6598): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6598): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6598): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 2421):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,E/SPPClientService( 5531): [a] [ConnectionManager] Connection is already disconnected.
,D/CrashAnrDetector( 2421): processName: com.test.thalitest
,I/Process ( 7136): Sending signal. PID: 7136 SIG: 9
,D/CrashAnrDetector( 2421): broadcastEvent : com.test.thalitest data_app_crash
,E/SPPClientService( 5531): [g] getNetMCC return empty string
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/11)
I/WindowState( 2421): WIN DEATH: Window{432ecac0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/11)
,I/ActivityManager( 2421): Process com.test.thalitest (pid 7136) (adj 9) has died.
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/11)
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
,I/DBG_DM  ( 4731): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4731): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/KLMS-2.3.201 : ( 7248): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 4731): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 7136
I/DBG_DM  ( 4731): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4731): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/DBG_DM  ( 4731): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4731): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
,I/DBG_DM  ( 4731): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/DBG_DM  ( 4731): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4731): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4731): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4731): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4731): setTransGradationMode to true
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2421): semi p:4731,o:t
I/DBG_DM  ( 4731): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2421): Got RemoteException sending setActive(false) notification to pid 7136 uid 10626
,I/dalvikvm( 7228): Total arena pages for JIT: 11
,I/dalvikvm( 7228): Total arena pages for JIT: 12
,I/dalvikvm( 7228): Total arena pages for JIT: 13
I/dalvikvm( 7228): Total arena pages for JIT: 14
,I/dalvikvm( 7228): Total arena pages for JIT: 15
,I/dalvikvm( 7228): Total arena pages for JIT: 16
,I/dalvikvm( 7228): Total arena pages for JIT: 17
,D/dalvikvm( 2421): GC_EXPLICIT freed 4811K, 75% free 25211K/97964K, paused 8ms+20ms, total 214ms
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
I/System.out( 7228): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7228): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7228): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/KLMS-2.3.201 : ( 7248): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452883705632
,I/KLMS-2.3.201 : ( 7248): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7260): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3295): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7260): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 3295): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3295): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3295): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3423): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7431):  
,I/SELinux ( 7435): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7435):  
,I/SELinux ( 7431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7431):  
I/SELinux ( 7431):  
,I/SELinux ( 7431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7431): >>>>> Normal User
,E/dalvikvm( 7431): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/System.out( 7228): AsyncTask #1 calls detatch()
,I/SELinux ( 7435): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7435):  
I/SELinux ( 7435):  
,I/SELinux ( 7435): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SA      ( 5775): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,E/SELinux ( 7435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7435): >>>>> Normal User
E/dalvikvm( 7435): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
I/SA      ( 5775): [BDLM] already registered in spp
,W/System.err( 7228): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7228): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7228): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7228): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7228): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7228): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7228): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7228): Caused by: java.lang.NullPointerException
E/SELinux ( 7435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/System.err( 7228): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
I/SA      ( 5775): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5775): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
W/System.err( 7228): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,I/SA      ( 5775): [OR] == isSIMCardReady false ==
W/System.err( 7228): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7228): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,I/SA      ( 5775): [SCU] == networkStateCheck == true
I/SA      ( 5775): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5775): isChinaCountryCode : false
I/SA      ( 5775): [OR] == networkStateCheck true ==
D/TimaKeyStoreProvider( 7431): in addTimaSignatureService
,W/System.err( 7228): 	... 8 more
,I/SA      ( 5775): [OR] GetMyCountryZoneTask
,I/SA      ( 5775): [OR] onReceive END
,D/TimaKeyStoreProvider( 7431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7431): Added TimaKesytore provider
,I/SA      ( 5775): [SRS] prepareGetMyCountryZone
,I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [SSP] query invoked
,D/TimaKeyStoreProvider( 7435): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7435): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7435): Added TimaKesytore provider
I/SA      ( 5775): [TPMU] GetMccFromDB : null
,I/SA      ( 5775): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5775): [TPM] isNoProxy(default) : true
,I/SA      ( 5775): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7272): Other Intent
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7285): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/dalvikvm( 7431): GC_CONCURRENT freed 2992K, 32% free 9574K/14020K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7431): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/Headlines( 5823): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5823): getCountryCode(): countryCode = PL
D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5823): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5823): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5823): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5823): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5823): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5823): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7435): GC_CONCURRENT freed 2994K, 32% free 9563K/14016K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 7435): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/iu.Environment( 5887): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5132): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5132): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5132): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422c9708,
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId,
D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,V/KVNProvider( 7435): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7435): getFindoCursor query string : ,
,V/KVNProvider( 7435): getTagSearchCursor() tagSearchCursor count : 0,
,D/hcjo    ( 5911): AutoUpdateManager:IDLE:execute,
D/InitializeManagerStateMachine( 5911): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5911): exit::IDLE
,D/InitializeManagerStateMachine( 5911): entry::NETWORK_CHECK,
D/InitializeManagerStateMachine( 5911): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5911): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5911): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5911): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5911): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5911): entry::SUCCESS
,D/hcjo    ( 5911): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5911): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5911): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
D/InitializeManagerStateMachine( 5911): exit::SUCCESS
,D/InitializeManagerStateMachine( 5911): entry::IDLE,
,I/ActivityManager( 2421): Killing 6133:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43,
,E/SPPClientService( 5531): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE,
E/SPPClientService( 5531): [SystemStateMoniter] Current Time : 277637
,E/SPPClientService( 5531): [SystemStateMoniter] No Connect : false
,V/AlarmManager( 2421): waitForAlarm result :4
,D/dalvikvm( 5531): GC_CONCURRENT freed 1998K, 26% free 10445K/14012K, paused 4ms+3ms, total 35ms
,D/dalvikvm( 5531): WAIT_FOR_CONCURRENT_GC blocked 13ms,
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,I/SA      ( 5775): [RC New] [v2liruge] api execute + 734,
,I/SA      ( 5775): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5775): AsyncTask #2 calls detatch()
,I/SA      ( 5775): [TPMU] getNetworkMcc : 
,I/SA      ( 5775): [SCU] saveMccToPreferece Start
I/SA      ( 5775): [SCU] RegionMCC : 260
,I/SA      ( 5775): [SSP] query invoked
,I/SA      ( 5775): [TPMU] GetMccFromDB : null
I/SA      ( 5775): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5775): [SCU] saveMccToPreferece End
,I/SA      ( 5775): [RC New] executeRequest [v2liruge] end. 749
,I/SA      ( 5775): [RC New] Execute end
,I/SA      ( 5775): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5775): [OR] GetMyCountryZoneTask Success
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,E/WifiStateMachine( 2421): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5531): [b] __InitReply__,
V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): waitForAlarm result :4,
,W/WifiP2pStateTracker( 2421): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
,D/ConnectivityService( 2421): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0,
D/ConnectivityService( 2421):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info ,
,D/ConnectivityService( 2421): updateSourceRoutes : no source routing conditions,
,I/ActivityManager( 2421): Killing 6170:com.google.android.music:main/u0a125 (adj 15): empty #43,
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11),
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11),
D/PowerManagerService( 2421): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2421) eventTime = 280238
D/PowerManagerService( 2421): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421 (0x0)
D/PowerManagerService( 2421): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2421, ws=WorkSource{1000}) (elapsedTime=3483)
,I/GAV2    ( 7315): Thread[GAThread,5,main]: No campaign data found.,
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6598): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6598): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6598): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6598): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6598): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6598): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6598): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6598): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6598): [ensureRegistration] - No Samsung account,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = -10,
,D/CaptivePortalTracker( 2421): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2421): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2421): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2421): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2421): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2421): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2421): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5911): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5911): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5911): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5911): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5911): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5911): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5911): entry::IDLE,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 5911): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5911): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5911): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5911): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5911): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5911): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5911): entry::IDLE
,E/Watchdog( 2421): !@Sync 9,
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{44dc2888 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{445ff838 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :12,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5823): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5823): Breath 27377 latestRequest time : 1452883705863 current time : 1452883733240,
,I/EventLogService( 3153): Aggregate from 1452881833414 (log), 1452881833414 (data),
,D/dalvikvm( 3153): GC_CONCURRENT freed 2199K, 23% free 12675K/16328K, paused 7ms+11ms, total 94ms,
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1,
I/TLC_TIMA_PKM_initialize( 2421): initializing...
I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2421): device_id = 0x0
I/TZ: mc_tlc_communication( 2421): tlc_open() was called
I/TZ: mc_tlc_communication( 2421): Opening MobiCore device
I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2421): Opening the session
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2421): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,I/PowerManagerService( 2421): [PWL] Off : 225s ago,
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4000): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 11,
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7787): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7787):  
,I/SELinux ( 7787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7787):  
I/SELinux ( 7787):  
,I/SELinux ( 7787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7787): >>>>> Normal User
,E/dalvikvm( 7787): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7787): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7787): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7787): Added TimaKesytore provider,
,D/dalvikvm( 7787): GC_CONCURRENT freed 2999K, 32% free 9565K/14020K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7787): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Headlines( 5823): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5823): Breath 76537 latestRequest time : 1452883705863 current time : 1452883782400
,I/ActivityManager( 2421): Killing 6540:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5823): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5823): Breath 87333 latestRequest time : 1452883705863 current time : 1452883793197,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4000): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,E/Watchdog( 2421): !@Sync 12,
,I/PowerManagerService( 2421): [PWL] Off : 275s ago,
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7945): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7945):  
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4,
,I/SELinux ( 7945): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7945):  
I/SELinux ( 7945):  
I/SELinux ( 7945): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7945): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7945): >>>>> Normal User
,E/dalvikvm( 7945): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ],
,E/SELinux ( 7945): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
,D/TimaKeyStoreProvider( 7945): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7945): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7945): Added TimaKesytore provider,
,D/dalvikvm( 7945): GC_CONCURRENT freed 2996K, 32% free 9563K/14016K, paused 3ms+2ms, total 31ms,
,D/dalvikvm( 7945): WAIT_FOR_CONCURRENT_GC blocked 27ms,
,E/SPPClientService( 7945): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7945): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7945): PushLog.txt file is not deleted.
,D/SPPClientService( 7945): PushLog.txt file is not deleted.
,D/SPPClientService( 7945): ============PushLog. stop!,
,I/ActivityManager( 2421): Killing 6431:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,E/SPPClientService( 5531): [b] __PingReply__,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5823): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5823): Breath 117334 latestRequest time : 1452883705863 current time : 1452883823197,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 13
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,D/Headlines( 5823): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5823): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5823): Breath 147336 latestRequest time : 1452883705863 current time : 1452883853199
,D/Headlines( 5823): stop 
,D/Headlines( 5823): Breath.onDestroy : 
I/ActivityManager( 2421): Killing 6573:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2421): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 14
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2421): stay LED for fully charged
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 15
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2421): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 16
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 17
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 18
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2421): GC_CONCURRENT freed 3972K, 75% free 25068K/97964K, paused 18ms+22ms, total 249ms
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 19
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 21
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/GAV2    ( 5621): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5621): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 22
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 600s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2421): LightSensor enable = 0
D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 23
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 24
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 25
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4073): GC_CONCURRENT freed 2889K, 31% free 9722K/14064K, paused 18ms+2ms, total 91ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 26
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 27
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 28
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 29
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 30
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 31
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2421): GC_CONCURRENT freed 3973K, 75% free 24904K/97964K, paused 18ms+20ms, total 242ms
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 9604
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 9609
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 9614
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 9619
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 9622
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 9625
,E/Watchdog( 2421): !@Sync 32
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 33
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 34
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 35
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 10
,E/Watchdog( 2421): !@Sync 36
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = -10
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 37
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 38
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 39
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 40
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 41
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 42
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5531): [b] __PingReply__
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2421): LightSensor enable = 0
D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 5
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 43
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 44
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 45
,I/PowerManagerService( 2421): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_CONCURRENT freed 3796K, 75% free 24907K/97964K, paused 10ms+16ms, total 215ms
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 46
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 47
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 48
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 49
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4073): GC_CONCURRENT freed 2044K, 31% free 9719K/14064K, paused 2ms+3ms, total 23ms
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 50
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 51
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 52
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5531): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,E/SPPClientService( 5531): [b] __PingReply__
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 53
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 54
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 55
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 56
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 57
,I/PowerManagerService( 2421): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 58
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 59
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2421): GC_CONCURRENT freed 3702K, 75% free 25004K/97964K, paused 14ms+16ms, total 224ms
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 60
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 61
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2421): Prepared write state in 51ms
,I/ProcessStatsService( 2421): Prepared write state in 27ms
,I/ProcessStatsService( 2421): Pruning old procstats: /data/system/procstats/state-2016-01-15-04-29-00.bin
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 62
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/NetworkStats( 2421): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/NetworkStats( 2421): performPollLocked() took 45ms
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,I/SELinux (12069): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12069):  
,I/SELinux (12069): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12069):  
I/SELinux (12069):  
,I/SELinux (12069): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12069): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12069): >>>>> Normal User
,E/dalvikvm(12069): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12069): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12069): in addTimaSignatureService
,D/TimaKeyStoreProvider(12069): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12069): Added TimaKesytore provider
,D/dalvikvm(12069): GC_CONCURRENT freed 3000K, 32% free 9562K/14016K, paused 3ms+1ms, total 28ms
,D/dalvikvm(12069): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/@ WidgetProvider(12069): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12069): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12069): Widget random data : 9
,D/@ WidgetProvider(12069): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12069): Widget random data : 3
,E/dalvikvm(12069): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12069): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12069): VFY: replacing opcode 0x22 at 0x0038
I/ActivityManager( 2421): Killing 6585:com.android.musicfx/u0a24 (adj 15): empty #43
,E/dalvikvm(12069): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12069): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12069): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12069): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12069): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12069): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12069): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12069): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12069): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12069): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(12069): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12069): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12069): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 2848): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 2848): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2848): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2848): VFY: replacing opcode 0x1f at 0x0011
,I/dalvikvm( 2848): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2848): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2848): VFY: replacing opcode 0x6e at 0x003d
,I/System.out(12069): Thread-669(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12069): Thread-669(ApacheHTTPLog):isShipBuild true
,I/System.out(12069): Thread-669(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out( 2848): Thread-55(HTTPLog):isShipBuild true
,I/System.out( 2848): Thread-55(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2848): GC_CONCURRENT freed 1957K, 25% free 10891K/14332K, paused 8ms+7ms, total 107ms
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/System.out(12069): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12069): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12069): Max ALLOWED memory (MB): 128
,V/ImageManager(12069): Max SHOULD USE memory (MB): 128
,V/ImageManager(12069): Max Image Cache memory (MB): 32
,D/skia    (12069): getTotalSize : Do not get file length
,D/@ WidgetProvider(12069): Building widget : 5
,D/dalvikvm( 2781): GC_FOR_ALLOC freed 8583K, 40% free 18485K/30376K, paused 58ms, total 58ms
,I/PhenotypeConfigurator( 2736): Scheduling Phenotype for one-off execution 8550 seconds from now (1452885334600)
,D/GetConfigurationSnapshotOperation( 2736): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2736): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
,W/dalvikvm( 2736): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2736): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2736): GC_CONCURRENT freed 1780K, 23% free 11686K/14988K, paused 7ms+8ms, total 72ms
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2736): Thread-122(HTTPLog):isShipBuild true
,I/System.out( 2736): Thread-122(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 10
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2736): GC_CONCURRENT freed 1456K, 20% free 12188K/15168K, paused 6ms+13ms, total 90ms
,E/Watchdog( 2421): !@Sync 63
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 64
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 65
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
I/ActivityManager( 2421): Killing 6425:com.sec.knox.bridge/1000 (adj 15): empty for 1836s
,I/ActivityManager( 2421): Killing 4851:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1836s
,I/ActivityManager( 2421): Killing 6411:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1836s
,I/ActivityManager( 2421): Killing 6388:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1846s
,I/ActivityManager( 2421): Killing 6757:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1846s
,I/ActivityManager( 2421): Killing 6743:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1847s
,I/ActivityManager( 2421): Killing 6731:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1847s
,I/ActivityManager( 2421): Killing 6719:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1847s
I/ActivityManager( 2421): Killing 6706:com.samsung.helphub/1000 (adj 15): empty for 1847s
,I/ActivityManager( 2421): Killing 6693:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1847s
,I/ActivityManager( 2421): Killing 6680:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1848s
,I/ActivityManager( 2421): Killing 6667:com.sec.android.service.cm/u0a82 (adj 15): empty for 1848s
,I/ActivityManager( 2421): Killing 6347:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1848s
I/ActivityManager( 2421): Killing 6067:com.android.mms/u0a49 (adj 15): empty for 1848s
,I/ActivityManager( 2421): Killing 6641:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1848s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2421): Killing 5950:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1849s
,I/ActivityManager( 2421): Killing 6611:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1849s
,D/CountryDetector( 2421): No listener is left
,I/PowerManagerService( 2421): [PWL] Off : 1890s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 66
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 67
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2421): !@Sync 68
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(12577): 
D/AndroidRuntime(12577): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12577): CheckJNI is OFF
D/AndroidRuntime(12577): setted country_code = Poland
D/AndroidRuntime(12577): setted countryiso_code = PL
D/AndroidRuntime(12577): setted sales_code = PLS
D/AndroidRuntime(12577): readGMSProperty: start
D/AndroidRuntime(12577): readGMSProperty: already setted!!
D/AndroidRuntime(12577): readGMSProperty: end
D/AndroidRuntime(12577): addProductProperty: start
D/dalvikvm(12577): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12577): Added shared lib libjavacore.so 0x0
D/dalvikvm(12577): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12577): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12577): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
E/memtrack(12577): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12577): failed to load memtrack module: -2
D/dalvikvm(12577): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(12577): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2421): START PACKAGE DELETE: observer{1147568992}
D/PackageManager( 2421): pkg{<packageName>}
D/PackageManager( 2421): user{0}
D/PackageManager( 2421): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2421): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2421): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2421): !@killApplicatoin: 10626, uninstall pkg
I/ActivityManager( 2421): Killing 6625:com.policydm/1000 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 7260:com.sec.android.soagent/u0a38 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 7185:com.vlingo.midas/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 7248:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 7228:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 5714:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 7214:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 6598:com.sec.pcw.device/1000 (adj 15): empty for 1800s
I/ActivityManager( 2421): Killing 2833:com.android.settings/1000 (adj 15): empty for 1801s
I/ActivityManager( 2421): Killing 7391:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1801s
D/dalvikvm( 2421): GC_CONCURRENT freed 3901K, 75% free 25005K/97964K, paused 11ms+19ms, total 210ms
D/dalvikvm( 2421): WAIT_FOR_CONCURRENT_GC blocked 156ms
D/dalvikvm( 2421): WAIT_FOR_CONCURRENT_GC blocked 169ms
W/PackageSettings( 2421): Skipping PackageSetting{42c0a6e0 com.example.hello/10614} due to missing metadata
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10626, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10626, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2974): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5132): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader( 2421): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
I/SELinux (12591): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12591):  
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2421): PackageReceiver onReceive()
I/HarmonyEASService( 2421): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux (12591): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12591):  
I/SELinux (12591):  
I/SELinux (12591): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12591): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12591): >>>>> Normal User
E/dalvikvm(12591): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12591): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2964): GC_EXPLICIT freed 1470K, 29% free 10033K/14020K, paused 9ms+10ms, total 181ms
D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9499K/11000K, paused 4ms+5ms, total 59ms
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12591): in addTimaSignatureService
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9499K/11000K, paused 3ms+4ms, total 35ms
D/TimaKeyStoreProvider(12591): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12591): Added TimaKesytore provider
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 3153): GC_EXPLICIT freed 417K, 25% free 12401K/16328K, paused 15ms+9ms, total 194ms
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9499K/11000K, paused 4ms+4ms, total 34ms
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mmsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RegisteredServicesCache( 2759): empty dynamic service
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12591): GC_CONCURRENT freed 2997K, 32% free 9569K/14020K, paused 3ms+2ms, total 25ms
D/dalvikvm(12591): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(12591): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mms"
D/elm:14132(12591): ELMEngine.ELMEngine( context ).
D/elm:14132(12591): MDMBridge.setEnterpriseBridge()
D/elm:14132(12591): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mmsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12604): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12604):  
D/elm:14132(12591): ElmAgentService : onCreate()
D/elm:14132(12591): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12591): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12591): MDMBridge.getInstance()
D/elm:14132(12591): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(12591): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12604): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12604):  
I/SELinux (12604):  
I/SELinux (12604): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12604): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12604): >>>>> Normal User
E/dalvikvm(12604): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12604): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/EnterpriseDeviceManagerService( 2421): Package has changed for user 0
D/TimaKeyStoreProvider(12604): in addTimaSignatureService
D/BackupManagerService( 2421): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2421): removePackageParticipantsLocked: uid=10626 #1
D/TimaKeyStoreProvider(12604): Cannot add TimaSignature Service, License check Failed
D/elm:14132(12591): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/ActivityThread(12604): Added TimaKesytore provider
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(12591): ElmAgentService : onDestroy().
D/dalvikvm( 2759): GC_CONCURRENT freed 2333K, 27% free 10252K/14036K, paused 17ms+3ms, total 129ms
I/ActivityManager( 2421): Killing 5775:com.osp.app.signin/u0a44 (adj 15): empty for 1801s
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12604): GC_CONCURRENT freed 2997K, 32% free 9569K/14020K, paused 3ms+1ms, total 28ms
D/dalvikvm(12604): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2421): GC_EXPLICIT freed 2094K, 75% free 25004K/97964K, paused 8ms+32ms, total 518ms
D/PackageManager( 2421): delete sourFile : 
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2421): delete native library directory: 
D/PackageManager( 2421): return delete result to caller: 1147568992
D/AndroidRuntime(12577): Shutting down VM
D/PackageManager( 2421): returnCode: 1
D/dalvikvm(12577): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 5ms+1ms, total 8ms
I/SELinux (12619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12619):  
I/ActivityManager( 2421): Killing 7431:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1801s
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12619):  
I/SELinux (12619):  
I/SELinux (12619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12619): >>>>> Normal User
E/dalvikvm(12619): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (12619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12619): in addTimaSignatureService
D/TimaKeyStoreProvider(12619): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12619): Added TimaKesytore provider
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mmsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12619): GC_CONCURRENT freed 3001K, 32% free 9568K/14024K, paused 4ms+2ms, total 35ms
D/dalvikvm(12619): WAIT_FOR_CONCURRENT_GC blocked 27ms
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ApplicationsProvider( 2964): Could not fetch usage stats
W/ApplicationsProvider( 2964): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2964): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2964): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2964): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2964): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2964): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/CrashAnrDetector( 2421): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2421): clearDefaults: com.test.thalitest
I/SELinux (12634): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12634):  
I/ActivityManager( 2421): Killing 7435:com.sec.android.app.voicenote/1000 (adj 15): empty for 1801s
I/SELinux (12634): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12634):  
I/SELinux (12634):  
I/SELinux (12634): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12634): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12634): >>>>> Normal User
E/dalvikvm(12634): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (12634): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12634): in addTimaSignatureService
D/TimaKeyStoreProvider(12634): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12634): Added TimaKesytore provider
D/dalvikvm(12634): GC_CONCURRENT freed 2997K, 32% free 9562K/14020K, paused 4ms+2ms, total 27ms
D/dalvikvm(12634): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/SELinux (12649): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12649):  
I/SELinux (12649): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12649):  
I/SELinux (12649):  
I/SELinux (12649): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12649): >>>>> Normal User
E/dalvikvm(12649): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
I/ActivityManager( 2421): Killing 7272:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1802s
E/SELinux (12649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12649): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(12649): in addTimaSignatureService
D/TimaKeyStoreProvider(12649): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12649): Added TimaKesytore provider
D/dalvikvm(12649): GC_CONCURRENT freed 3017K, 32% free 9554K/14024K, paused 2ms+1ms, total 26ms
D/dalvikvm(12649): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(12649): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12649): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12649): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12649): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12649): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12649): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12649): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12649): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12649): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12649): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12649): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12649): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12649): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12649): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12649): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12649): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12649): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12649): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12649): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12649): Shutting down VM
W/dalvikvm(12649): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12649): FATAL EXCEPTION: main
E/AndroidRuntime(12649): Process: com.sec.pcw.device, PID: 12649
E/AndroidRuntime(12649): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12649): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12649): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12649): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12649): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12649): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12649): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12649): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12649): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12649): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12649): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12649): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12649): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12649): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12649): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12649): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12649): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12649): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12649): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12649): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12649): 	... 12 more
I/SELinux (12662): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12662):  
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
I/Process (12649): Sending signal. PID: 12649 SIG: 9
I/ActivityManager( 2421): Process com.sec.pcw.device (pid 12649) (adj 0) has died.
I/SELinux (12662): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12662):  
I/SELinux (12662):  
I/SELinux (12662): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12662): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12662): >>>>> Normal User
E/dalvikvm(12662): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12662): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12662): in addTimaSignatureService
D/TimaKeyStoreProvider(12662): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12662): Added TimaKesytore provider
D/dalvikvm(12662): GC_CONCURRENT freed 3006K, 32% free 9559K/14024K, paused 2ms+2ms, total 25ms
D/dalvikvm(12662): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/System.err(12662): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12662): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12662): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12662): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12662): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12662): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12662): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12662): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12662): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12662): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12662): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12662): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12662): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12662): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12662): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12662): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12662): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12662): 	at libcore.io.Posix.open(Native Method)
W/System.err(12662): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12662): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12662): 	... 21 more
D/GalaxyFinderApplication(12662): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12662): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12676): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12676):  
I/ActivityManager( 2421): Killing 7285:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1802s
I/SELinux (12676): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12676):  
I/SELinux (12676):  
I/SELinux (12676): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12676): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12676): >>>>> Normal User
E/dalvikvm(12676): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12676): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12676): in addTimaSignatureService
D/TimaKeyStoreProvider(12676): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12676): Added TimaKesytore provider
D/dalvikvm(12676): GC_CONCURRENT freed 3009K, 32% free 9558K/14024K, paused 2ms+2ms, total 24ms
D/dalvikvm(12676): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(12676): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12676): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12676): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12676): ContentProvider is not null
W/ResourceType(12676): No package identifier when getting value for resource number 0x00000000
I/System.out(12676): resource Id::2131361807
E/SQLiteDatabase(12676): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12676): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12676): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12676): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12676): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12676): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12676): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12676): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12676): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12676): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12676): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12676): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12676): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12676): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12676): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12676): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12676): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12676): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12676): Shutting down VM
W/dalvikvm(12676): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12676): FATAL EXCEPTION: main
E/AndroidRuntime(12676): Process: com.sec.android.app.shealth, PID: 12676
E/AndroidRuntime(12676): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12676): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12676): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12676): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12676): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12676): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12676): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12676): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12676): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12676): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12676): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12676): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12676): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12676): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12676): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12676): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(12676): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(12676): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(12676): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(12676): 	... 10 more
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
I/SELinux (12696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12696):  

```
