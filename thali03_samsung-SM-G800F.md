#### Test 549702610263d9b_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2386): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
--------- beginning of /dev/log/main
D/AndroidRuntime( 7190): 
D/AndroidRuntime( 7190): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7190): CheckJNI is OFF
D/AndroidRuntime( 7190): setted country_code = Poland
D/AndroidRuntime( 7190): setted countryiso_code = PL
D/AndroidRuntime( 7190): setted sales_code = PLS
D/AndroidRuntime( 7190): readGMSProperty: start
D/AndroidRuntime( 7190): readGMSProperty: already setted!!
D/AndroidRuntime( 7190): readGMSProperty: end
D/AndroidRuntime( 7190): addProductProperty: start
D/dalvikvm( 7190): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7190): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7190): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7190): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7190): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7190): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7190): failed to load memtrack module: -2
D/dalvikvm( 7190): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7190): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2386): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2386): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2386  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2386): mDVFSHelper.acquire()
I/SELinux ( 7218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7218):  
D/PointerIcon( 2386): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2386): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2386): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2386): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7190): Shutting down VM
D/dalvikvm( 7190): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7218):  
I/SELinux ( 7218):  
I/SELinux ( 7218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7218): >>>>> Normal User
E/dalvikvm( 7218): >>>>> com.test.thalitest [ userId:0 | appId:10587 ]
E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7218): in addTimaSignatureService
D/TimaKeyStoreProvider( 7218): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7218): Added TimaKesytore provider
V/WindowManager( 2386): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2771): onTrimMemory. Level: 20
D/dalvikvm( 7218): GC_CONCURRENT freed 3007K, 31% free 9564K/13680K, paused 2ms+1ms, total 22ms
D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7218): Binding Chromium to the background looper Looper (main, tid 1) {42595268}
I/chromium( 7218): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7218): Initializing chromium process, renderers=0
W/chromium( 7218): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7218): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7218): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7218): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7218): Mali API Version : 401
,I/Mali    ( 7218): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7218): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7218): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7218): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7218): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7218): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7218): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2386): tr p:7218,o:f
,W/dalvikvm( 7218): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7218): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,I/dalvikvm( 7218): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7218): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7218): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7218): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7218): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7218): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7218): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7218): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7218): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7218): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7218): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2386): semi p:7218,o:f
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2386): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2386): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2386): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2386): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2386): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2386): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7218): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7218): Enabling debug mode 0
,W/AwContents( 7218): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2386): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2386  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 7218): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2386): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2386): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2386  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 7218): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7218): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7218): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4258d7d8
,D/dalvikvm( 7218): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4258d7d8
D/jxcore_app_log( 7218): JniHelper::setJavaVM(0x41b24220), pthread_self() = 2027600200
,D/JX-Cordova( 7218): jxcore cordova android initializing
,D/dalvikvm( 7218): GC_CONCURRENT freed 1289K, 18% free 11349K/13744K, paused 3ms+3ms, total 33ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 4ms
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7218): GC_CONCURRENT freed 1912K, 17% free 14993K/18032K, paused 2ms+2ms, total 41ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/CustomFrequencyManagerService( 2386): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2386  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7218): GC_FOR_ALLOC freed 5337K, 30% free 16280K/22976K, paused 51ms, total 51ms
,D/dalvikvm( 7218): GC_CONCURRENT freed 6715K, 31% free 17735K/25580K, paused 3ms+9ms, total 67ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 7218): GC_FOR_ALLOC freed 1048K, 31% free 17711K/25580K, paused 38ms, total 38ms
,I/dalvikvm-heap( 7218): Grow heap (frag case) to 21.892MB for 3688532-byte allocation
,D/dalvikvm( 7218): GC_FOR_ALLOC freed 2557K, 36% free 18756K/29184K, paused 34ms, total 34ms
,W/jxcore-log( 7218): Initializing JXcore engine
,W/jxcore-log( 7218): JXcore engine is ready
,W/jxcore-log( 7218): Starting JXcore engine
,W/jxcore-log( 7218): Platform android
W/jxcore-log( 7218): 
,W/jxcore-log( 7218): Process ARCH arm
W/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7218): JXcore Cordova bridge is ready!
I/jxcore-log( 7218): 
,W/jxcore-log( 7218): JXcore engine is started
,I/chromium( 7218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7218): Toggling radios to true
I/jxcore-log( 7218): 
,D/BluetoothAdapter( 7218): enable(): BT is already enabled..!
,I/WifiManager( 7218): packageName : com.test.thalitest
,I/WifiManager( 7218): setWifiEnabled : true
,I/WifiService( 2386): setWifiEnabled: true pid=7218, uid=10587
W/ActivityManager( 2386): Permission Denial: getCurrentUser() from pid=7218, uid=10587 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2386): Failed getting userId using ActivityManagerNative
W/WifiService( 2386): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7218, uid=10587 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2386): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2386): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2386): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2386): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2386): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2386): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2386): disconnect: pid=7218, uid=10587
,I/jxcore-log( 7218): Radios toggled
I/jxcore-log( 7218): 
,I/wpa_supplicant( 3981): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3981): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2386): interfaceStatusChanged wlan0, true
D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2386): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3981): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3981): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3981): First Scan Start
,I/wpa_supplicant( 3981): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2386): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2386): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2386): InactiveState{ what=143375 }
D/WifiP2pService( 2386): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2386): evaluateTrafficStatsPolling
D/ConnectivityService( 2386): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2386): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,E/ConnectivityService( 2386): net.tcp.usercfg.default not found in system default properties
I/wpa_supplicant( 3981): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3981): Skip scan - already scanning
E/ConnectivityService( 2386): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2386): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2386): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/WifiP2pService( 2386): InactiveState{ what=143375 }
,D/WifiP2pService( 2386): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2386): Attempting to switch to mobile
,D/ConnectivityService( 2386): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7266):  
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2386): evaluateTrafficStatsPolling
E/WifiStateMachine( 2386): Error! unhandled message{ when=-59ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2386): Error! unhandled message{ when=-59ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7266):  
I/SELinux ( 7266):  
,I/SELinux ( 7266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7266): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7266): >>>>> Normal User
,E/dalvikvm( 7266): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
E/WifiStateMachine( 2386): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/SELinux ( 7266): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2386): route cmd failed: 
W/NetworkManagementService( 2386): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2386): '
W/NetworkManagementService( 2386): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2386): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2386): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2386): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2386): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2386): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2386): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2386): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2386): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2386): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2386): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2386): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7266): in addTimaSignatureService
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7266): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7266): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2386): android_net_utils_resetConnections in env=0x78bb34b0 clazz=0x62600001 iface=wlan0 mask=0x3
D/ConnectivityService( 2386): resetConnections(wlan0, 3)
,E/SPPClientService( 5544): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5544): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5544): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5544): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5544): [b] ResponseMap empty
,D/dalvikvm( 7266): GC_CONCURRENT freed 2993K, 30% free 9572K/13672K, paused 4ms+1ms, total 70ms
,D/dalvikvm( 7266): WAIT_FOR_CONCURRENT_GC blocked 48ms
,V/NativeCrypto( 2848): Read error: ssl=0x7b291198: I/O error during system call, Connection timed out
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7b291198: I/O error during system call, Broken pipe
,D/ConnectivityService( 2386): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2386): updateIfacesLocked()
,V/NetworkStats( 2386): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
V/NetworkStats( 2386): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
V/NetworkStats( 2386): performPollLocked() took 26ms
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,I/System.out( 7266): Inside WakeupProvider
,I/System.out( 7266): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7266): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7266): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7266): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,E/Watchdog( 2386): !@Sync 9
,D/NearbySettings( 2824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2824): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2824): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2824): MountReceiver.onReceive - Set preference state off
I/ActivityManager( 2386): Killing 6168:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7266): initQueue()
,V/NearbySettings( 2824): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 2824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2824): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2824): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2824): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2824): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2386): updateDataUsageMap
,D/Tethering( 2386): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2386): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2386): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2386): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6585): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6585): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6585): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6585): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6585): noConnectivity : true
,I/DBG_DM  ( 4754): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2386): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7295): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7295):  
,I/SELinux ( 7295): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7295):  
I/SELinux ( 7295):  
,I/SELinux ( 7295): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7295): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7295): >>>>> Normal User
,E/dalvikvm( 7295): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7295): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7295): in addTimaSignatureService
,I/wpa_supplicant( 3981): nl80211: Received scan results (8 BSSes)
I/wpa_supplicant( 3981): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3981): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/TimaKeyStoreProvider( 7295): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7295): Added TimaKesytore provider
,D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2386): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7295): GC_CONCURRENT freed 2997K, 31% free 9566K/13672K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7295): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3981): Associated with C0.AA.48
D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
D/Tethering( 2386): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3981): freq(2412) increment count 2
,I/wpa_supplicant( 3981): meet head of list.
,D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
D/Tethering( 2386): interfaceStatusChanged wlan0, true
D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2386): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3981): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3981): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2386): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2386): interfaceStatusChanged wlan0, true
,D/WifiNative( 2386): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2386): Killing 6242:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2386): InactiveState{ what=143375 }
,D/WifiP2pService( 2386): P2pEnabledState{ what=143375 }
,I/SELinux ( 7309): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7309):  
,I/SELinux ( 7309): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7309):  
I/SELinux ( 7309):  
,I/SELinux ( 7309): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7309): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7309): >>>>> Normal User
,E/dalvikvm( 7309): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7309): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7309): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7309): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7309): Added TimaKesytore provider
,D/dalvikvm( 7309): GC_CONCURRENT freed 3001K, 31% free 9564K/13672K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7309): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/dhcpcd  ( 7321): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7321): bssid match
,I/ActivityManager( 2386): Killing 6304:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7328): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7328):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9501K/10656K, paused 2ms+3ms, total 30ms
,I/SELinux ( 7328): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7328):  
I/SELinux ( 7328):  
I/SELinux ( 7328): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7328): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7328): >>>>> Normal User
E/dalvikvm( 7328): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7328): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9501K/10656K, paused 2ms+3ms, total 24ms
D/TimaKeyStoreProvider( 7328): in addTimaSignatureService
D/TimaKeyStoreProvider( 7328): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7328): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9501K/10656K, paused 3ms+3ms, total 26ms
,D/dalvikvm( 7328): GC_CONCURRENT freed 3004K, 31% free 9564K/13676K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7328): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/KLMS-2.3.201 : ( 7328): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7328): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452015393113
,I/KLMS-2.3.201 : ( 7328): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2386): Killing 6343:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7340): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7340):  
,I/SELinux ( 7340): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7340):  
I/SELinux ( 7340):  
,I/SELinux ( 7340): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7340): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7340): >>>>> Normal User
,E/dalvikvm( 7340): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7340): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7340): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7340): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7340): Added TimaKesytore provider
D/libgps  ( 2386): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2386): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2386): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2386): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7340): GC_CONCURRENT freed 3014K, 31% free 9558K/13680K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7340): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/SO_AGENT( 7340): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7340): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5808): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5808): [BDLM] already registered in spp
I/SA      ( 5808): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5808): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5808): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5808): [OR] == isSIMCardReady false ==
,I/SA      ( 5808): [SCU] == networkStateCheck == false
,I/SA      ( 5808): [OR] onReceive END
I/ActivityManager( 2386): Killing 5590:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7352): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7352):  
,I/SELinux ( 7352): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7352):  
I/SELinux ( 7352):  
,I/SELinux ( 7352): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7352): >>>>> Normal User
,E/dalvikvm( 7352): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7352): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7352): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7352): Added TimaKesytore provider
,D/dalvikvm( 7352): GC_CONCURRENT freed 2994K, 31% free 9569K/13672K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/sCloudBackupApp( 7352): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7352): Other Intent
I/ActivityManager( 2386): Killing 6295:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7365): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7365):  
,I/SELinux ( 7365): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7365):  
I/SELinux ( 7365):  
,I/SELinux ( 7365): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7365): >>>>> Normal User
,E/dalvikvm( 7365): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7365): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7365): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7365): Added TimaKesytore provider
,D/dalvikvm( 7365): GC_CONCURRENT freed 2998K, 31% free 9569K/13676K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7365): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7365): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7365): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7365): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7365): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2386): Killing 6320:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/Headlines( 5875): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5875): getCountryCode(): countryCode = PL
,D/Headlines( 5875): Breath.onCreate
,D/Headlines( 5875): Breath timer started. interval : 30000
,I/SELinux ( 7377): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7377):  
D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5875): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5875): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5875): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5875): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5875): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5875): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2386): waitForAlarm result :8
,I/SELinux ( 7377): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7377):  
I/SELinux ( 7377):  
,I/SELinux ( 7377): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7377): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7377): >>>>> Normal User
,E/dalvikvm( 7377): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7377): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7377): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7377): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7377): Added TimaKesytore provider
,D/dalvikvm( 7377): GC_CONCURRENT freed 3002K, 31% free 9564K/13676K, paused 7ms+1ms, total 24ms
,D/dalvikvm( 7377): WAIT_FOR_CONCURRENT_GC blocked 15ms
,V/WebViewChromium( 7377): Binding Chromium to the background looper Looper (main, tid 1) {42592308}
,I/chromium( 7377): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7377): Initializing chromium process, renderers=0
,W/chromium( 7377): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7377): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7377): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7377): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7377): Mali API Version : 401
,I/Mali    ( 7377): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/WifiP2pService( 2386): InactiveState{ what=143375 }
,D/WifiP2pService( 2386): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2386): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/libgps  ( 2386): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2386): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2386): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2386): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2386): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2386): evaluateTrafficStatsPolling
D/ConnectivityService( 2386): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2386): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2386): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/GAV2    ( 7377): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/WifiTrafficPoller( 2386): evaluateTrafficStatsPolling,
D/ConnectivityService( 2386): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2386): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2386): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30,
D/ConnectivityService( 2386): handleConnectivityChange: setting default proxy info 
,W/ContextImpl( 7377): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,V/NetworkStats( 2386): updateIfacesLocked()
V/NetworkStats( 2386): performPollLocked(flags=0x1)
V/NetworkStats( 2386): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
V/NetworkStats( 2386): performPollLocked() took 21ms
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit,
,I/NSApplication( 7377): Starting up...,
,I/iu.Environment( 5939): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true,
,D/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,I/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
,I/SELinux ( 7451): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7451):  
,I/SELinux ( 7451): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7451):  
I/SELinux ( 7451):  
,I/SELinux ( 7451): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7451): >>>>> Normal User
,E/dalvikvm( 7451): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7451): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7451): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7451): Added TimaKesytore provider
,D/dalvikvm( 7451): GC_CONCURRENT freed 2991K, 30% free 9570K/13672K, paused 2ms+1ms, total 19ms,
D/dalvikvm( 7451): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId,
,I/SELinux ( 7469): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7469):  
,D/Tethering( 2386): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2386): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2386): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/SELinux ( 7469): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7469):  
I/SELinux ( 7469):  
,I/SELinux ( 7469): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7469): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7469): >>>>> Normal User
,E/dalvikvm( 7469): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7469): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7469): in addTimaSignatureService
,I/DBG_DM  ( 4754): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/TimaKeyStoreProvider( 7469): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7469): Added TimaKesytore provider
,W/ActivityManager( 2386): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId
,I/ActivityManager( 2386): Killing 6261:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/ActivityManager( 2386): Killing 5986:com.android.calendar/u0a144 (adj 15): empty #44
,D/libgps  ( 2386): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7469): GC_CONCURRENT freed 3010K, 31% free 9557K/13676K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7469): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 7484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7484):  
,D/BadgeProvider( 7469): onCreate
,D/BadgeProvider( 7469): DatabaseHelper
,D/BadgeProvider( 7469): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SELinux ( 7484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7484):  
I/SELinux ( 7484):  
,I/SELinux ( 7484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7484): >>>>> Normal User
,E/dalvikvm( 7484): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/BadgeProvider( 7469): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2771): reloadBadges entered.
D/BadgeProvider( 7469): sendNotify, [notify] : null
D/BadgeProvider( 7469): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7469): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7469): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 7484): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7484): Added TimaKesytore provider
,D/dalvikvm( 2386): GC_CONCURRENT freed 3913K, 74% free 25136K/95384K, paused 15ms+34ms, total 261ms
,D/dalvikvm( 2386): GC_EXPLICIT freed 232K, 74% free 24907K/95384K, paused 8ms+16ms, total 172ms
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 330, Delta = 20
,D/AmoledAdjustTimer( 2386): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 7484): GC_CONCURRENT freed 2989K, 30% free 9575K/13676K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/hcjo    ( 5960): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5960): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5960): exit::IDLE
,D/InitializeManagerStateMachine( 5960): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5960): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5960): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5960): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5960): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5960): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5960): entry::SUCCESS
,D/hcjo    ( 5960): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5960): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5960): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5960): exit::SUCCESS
,D/InitializeManagerStateMachine( 5960): entry::IDLE
,E/SPPClientService( 5544): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5544): [SystemStateMoniter] Current Time : 292087
,E/SPPClientService( 5544): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5544): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2824): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2824): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2824): MountReceiver.onReceive - Keep current state
,D/Headlines( 5875): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5875): Breath 1819 latestRequest time : 1452015393870 current time : 1452015395689
,D/NearbySettings( 2824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2824): MountReceiver.onReceive - Keep current state
E/SPPClientService( 5544): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5544): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5544): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2824): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2824): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2824): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2824): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5544): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
I/ActivityManager( 2386): Killing 6155:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5544): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/NearbySettings( 2824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2824): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=4, Uoast
,I/PCWCLIENTTRACE_PushUtil( 6585): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6585): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6585): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6585): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/PowerManagerService( 2386): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2386
E/SPPClientService( 5544): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5544): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7328): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7328): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452015396132
,I/KLMS-2.3.201 : ( 7328): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7340): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3435): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7340): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 3435): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3435): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3435): [Slink platform] The state of Slink geocode service is true
D/libgps  ( 2386): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2386): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2386): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2386): agps_ril_update_network_availability: Waiting for IPC connection...
,I/GallerySearchProvider( 3563): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7507): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7507):  
,I/SELinux ( 7507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7507):  
I/SELinux ( 7507):  
I/SELinux ( 7507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7507): >>>>> Normal User
,E/dalvikvm( 7507): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7517): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7517):  
,D/TimaKeyStoreProvider( 7507): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7507): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7507): Added TimaKesytore provider,
,I/SELinux ( 7517): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7517):  
I/SELinux ( 7517):  
I/SELinux ( 7517): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7517): >>>>> Normal User
,E/dalvikvm( 7517): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
,E/SELinux ( 7517): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7517): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7517): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7517): Added TimaKesytore provider,
D/dalvikvm( 7507): GC_CONCURRENT freed 2993K, 31% free 9572K/13676K, paused 5ms+2ms, total 24ms
,D/dalvikvm( 7507): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,I/System.out( 7309): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,D/dalvikvm( 7517): GC_CONCURRENT freed 2996K, 31% free 9572K/13676K, paused 4ms+1ms, total 25ms,
,D/dalvikvm( 7517): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,I/SA      ( 5808): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,I/SA      ( 5808): [BDLM] already registered in spp,
,I/SA      ( 5808): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5808): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,I/SA      ( 5808): [TPMU]  strSIMState ,	:SIM_STATE_UNKNOWN
,I/SA      ( 5808): [OR] == isSIMCardReady false ==,
,I/SA      ( 5808): [SCU] == networkStateCheck == true,
I/SA      ( 5808): [DM] getCountryCodeFromCSC : PL,
,I/SA      ( 5808): isChinaCountryCode : false,
,I/SA      ( 5808): [OR] == networkStateCheck true ==,
,V/KVNProvider( 7517): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query,
,V/KVNProvider( 7517): getFindoCursor query string : ,
,V/KVNProvider( 7517): getTagSearchCursor() tagSearchCursor count : 0,
,I/SA      ( 5808): [OR] GetMyCountryZoneTask,
,I/SA      ( 5808): [OR] onReceive END,
I/System.out( 7309): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7309): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,I/SA      ( 5808): [SRS] prepareGetMyCountryZone,
,I/SA      ( 5808): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5808): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled,
I/SCloudBackupReceiver( 7352): Other Intent
,I/SA      ( 5808): [TPMU] GetMccFromDB : null
I/SA      ( 5808): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5808): [TPM] isNoProxy(default) : true
,I/SA      ( 5808): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7365): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5875): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5875): getCountryCode(): countryCode = PL
,D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5875): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5875): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5875): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5875): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5875): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5875): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5939): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId
,D/RCPManagerService( 2386): exchangeData() failure , invalid userId
,D/PackageManager( 2386): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/hcjo    ( 5960): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5960): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5960): exit::IDLE
,D/InitializeManagerStateMachine( 5960): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5960): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5960): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5960): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5960): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5960): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5960): entry::SUCCESS
,D/hcjo    ( 5960): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5960): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5960): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5960): exit::SUCCESS
,D/InitializeManagerStateMachine( 5960): entry::IDLE
,E/SPPClientService( 5544): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5544): [SystemStateMoniter] Current Time : 293229
,E/SPPClientService( 5544): [SystemStateMoniter] No Connect : false
,I/System.out( 7309): AsyncTask #1 calls detatch()
,W/System.err( 7309): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7309): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7309): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7309): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7309): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7309): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7309): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7309): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7309): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7309): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7309): Caused by: java.lang.NullPointerException
,W/System.err( 7309): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7309): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7309): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7309): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7309): 	... 8 more
,I/ActivityManager( 2386): Killing 6193:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5544): GC_CONCURRENT freed 2012K, 24% free 10450K/13656K, paused 6ms+3ms, total 40ms
,D/dalvikvm( 5544): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/libgps  ( 2386): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2386): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2386): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,I/SA      ( 5808): [RC New] [v2liruge] api execute + 652,
,I/SA      ( 5808): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK,
,I/System.out( 5808): AsyncTask #2 calls detatch(),
,I/SA      ( 5808): [TPMU] getNetworkMcc : ,
,I/SA      ( 5808): [SCU] saveMccToPreferece Start,
I/SA      ( 5808): [SCU] RegionMCC : 260,
,I/SA      ( 5808): [SSP] query invoked,
I/SA      ( 5808): [TPMU] GetMccFromDB : null
I/SA      ( 5808): [SCU] getMccFromPreferece mcc = 260,
I/SA      ( 5808): [SCU] saveMccToPreferece End
I/SA      ( 5808): [RC New] executeRequest [v2liruge] end. 680
I/SA      ( 5808): [RC New] Execute end
I/SA      ( 5808): [OR] GetMyCountryZoneTask mcc = 260,
,I/SA      ( 5808): [OR] GetMyCountryZoneTask Success,
,E/WifiStateMachine( 2386): CAPTIVE_PORTAL_EVENT_AUTHENTICATED,
,E/SPPClientService( 5544): [b] __InitReply__
,W/WifiP2pStateTracker( 2386): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
,D/ConnectivityService( 2386): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0,
D/ConnectivityService( 2386):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2386): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2386): updateSourceRoutes : no source routing conditions
,I/PowerManagerService( 2386): [PWL] Off : 225s ago,
,I/ActivityManager( 2386): Killing 6529:com.android.defcontainer/u0a6 (adj 15): empty #43,
I/SurfaceFlinger( 1920): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (-2/11),
D/PowerManagerService( 2386): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2386) eventTime = 295758
D/PowerManagerService( 2386): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2386 (0x0)
D/PowerManagerService( 2386): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2386, ws=WorkSource{1000}) (elapsedTime=3456)
,I/GAV2    ( 7377): Thread[GAThread,5,main]: No campaign data found.,
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6585): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6585): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6585): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6585): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6585): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6585): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6585): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6585): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6585): [ensureRegistration] - No Samsung account
,D/CaptivePortalTracker( 2386): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2386): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2386): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2386): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2386): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2386): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2386): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2386): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7218): Test app app.js loaded
I/jxcore-log( 7218): 
,I/Choreographer( 7218): Skipped 854 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 284, currTemp = 286, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 5960): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5960): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5960): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5960): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5960): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5960): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5960): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5960): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5960): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5960): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 5960): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 5960): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
,D/PreloadUpdateManagerStateMachine( 5960): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5960): entry::IDLE,
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2386): Waited long enough for: ServiceRecord{4471e7d0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2386): Waited long enough for: ServiceRecord{466e40a8 u0 com.sec.spp.push/.PushClientService}
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2386): initializing...,
I/TLC_TIMA_PKM_initialize( 2386): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2386): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2386): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2386): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2386): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2386): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2386): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2386): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2386): device_id = 0x0
I/TZ: mc_tlc_communication( 2386): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2386): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2386): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2386): Opening the session,
,I/TZ: mc_tlc_communication( 2386): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2386): Trustlet response is completed,
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2386): stay LED for fully charged
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2386): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager( 2386): waitForAlarm result :8
,D/Headlines( 5875): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5875): Breath 27246 latestRequest time : 1452015396640 current time : 1452015423886
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,W/ProcessCpuTracker( 2386): Skipping unknown process pid 7746
,W/ProcessCpuTracker( 2386): Skipping unknown process pid 7749
W/ProcessCpuTracker( 2386): Skipping unknown process pid 7750
,D/BatteryService( 2386): level:100, scale:100, status:3, health:9, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2386): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
,D/LightsService( 2386): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/lights  ( 2386): led_pattern : 0 +
D/LightsService( 2386): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/BatteryService( 2386): turn off LED
D/PowerManagerService( 2386): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2386): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2386): Waking up from sleep...
D/PowerManagerService( 2386): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2386): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2386): [s] WAKEFULNESS_AWAKE
,I/SensorManagerA( 2386): getReportingMode :: sensor.mType = 5
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerManagerService( 2386): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2386): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2386): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2386): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2386): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2386): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/DisplayPowerController( 2386): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2386): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2386): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/lights  ( 2386): led_pattern : 0 -
D/Sensors ( 2386): LightSensor setDelay = 200000000
D/Sensors ( 2386): LightSensor setSensorDelay = 200000000
D/lights  ( 2386): button : 1 +
D/lights  ( 2386): button : 1 -
D/Sensors ( 2386): Light sensor flush: not enabled 0
D/Sensors ( 2386): LightSensor enable = 1
,D/Sensors ( 2386): LightSensor enableSensor = 1
D/SensorManager( 2386): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/libsuspend( 2386): !@[s] autosuspend_autosleep_disable
,I/SensorManagerA( 2386): getReportingMode :: sensor.mType = 1
,I/libsuspend( 2386): !@[s] autosuspend_autosleep_disable done
D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2386): unblankAllDisplays() is called.
D/PowerManagerService( 2386): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 7ms
,I/Sensors ( 2386): HAL: batch Dry Run is complete
,D/SurfaceFlinger( 1920): Screen acquired, type=0 flinger=0x41da5550
D/PowerManagerService( 2386): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,I/Sensors ( 2386): HAL:resetDataRates mEnabled=4
D/PowerUI ( 2580): Overvoltage/Undervoltage (recovered) so turn on the screen.
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/RampAnimator( 2386): Light Animator Finished currentValue=8
D/PowerManagerService( 2386): [api] [s] wakeUp (uid: 10019 pid: 2580) eventTime = 337463
D/UsbDeviceManager( 2386): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
I/SensorManagerA( 2386): getReportingMode :: sensor.mType = 65558
,D/SensorManager( 2386): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,D/SensorService( 2386): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2386): AutoRotationSensor::activate (ident=0x840c9e30, enabled=1)
D/SensorService( 2386): AutoRotationSensor::AR_init
,I/Sensors ( 2386): HAL: batch Dry Run is complete
W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/PowerManagerService( 2386): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 27ms
I/Sensors ( 2386): HAL:resetDataRates mEnabled=4
D/UsbDeviceManager( 2386): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/NotificationService( 2386): cancelNotificationLocked
D/NotificationService( 2386):  hasClearableItems
D/NotificationService( 2386):  has clearable items no 
D/NotificationService( 2386): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2386): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2386): sendNotification(3) - 5
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorManager( 2386): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2386): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@4260d830)
,I/SELinux ( 7771): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7771):  
,D/KeyguardViewMediator( 2580): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 2580): notifyScreenOnLocked
,D/KeyguardViewMediator( 2580): handleNotifyScreenOn
,D/KeyguardViewManager( 2580): onScreenTurnedOn()
,D/InputDispatcher( 2386): setInputDispatchMode: enabled=1, frozen=0
,V/KeyguardViewManager( 2580): send wm null token: host was null
I/KeyguardEffectViewMain( 2580): *** KeyguardEffectView getInstance ***
V/KeyguardServiceDelegate( 2386): **** SHOWN CALLED ****
,D/VisualEffectParticleEffect( 2580): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2580): screenOnAnimationStart
I/WindowManager( 2386): No lock screen! windowToken=null
,I/SurfaceFlinger( 1920): id=14 Removed FlectronBea (10/10)
D/PowerManagerNotifier( 2386): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2386): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2386): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 2386): !@ElectronBeam exit
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
I/SurfaceFlinger( 1920): id=14 Removed FlectronBea (-2/10)
D/lights  ( 2386): lcd : 8 +
,D/lights  ( 2386): lcd : 8 -
D/DisplayPowerController( 2386): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2386): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LockPatternUtils( 2580): isPcwEnable = 10
D/BatteryMeterView( 2580): onDraw batteryColor : -1
,I/SELinux ( 7771): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7771):  
I/SELinux ( 7771):  
,I/SELinux ( 7771): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7771): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7771): >>>>> Normal User
,E/dalvikvm( 7771): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 7771): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7771): in addTimaSignatureService
,D/SensorService( 2386): AutoRotationSensor::process: Acc  eventTimestamp = 337559373370, previousAccTimestamp = 69444010062, difference = 268115363308 
,D/SensorService( 2386): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 7771): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7771): Added TimaKesytore provider
,D/DisplayPowerController( 2386): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2386): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2386): AutoRotationSensor::process: Acc  eventTimestamp = 337626036543, previousAccTimestamp = 69444010062, difference = 268182026481 
D/SensorService( 2386):  [AR] 0.2 -0.0 9.9
,D/SensorService( 2386): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2386): Excessive delay in unblankDisplay() while turning screen on: 244ms
,D/MISC PowerHAL( 2386): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2386): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2386): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 248ms
,D/LightsService( 2386): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2386) 
,D/LightsService( 2386): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2386): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/UsbDeviceManager( 2386): received ACTION_POWER_DISCONNECTED = -1
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/MISC PowerHAL( 2386): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2386): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2386): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/LightsService( 2386): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2386) 
,D/LightsService( 2386): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2386): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PalmMotionService( 2386): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/chromium( 7218): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/PalmMotionService( 2386): SURFACE_PALM_SWIPE: 1
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.USER_PRESENT
,E/MotionRecognitionService( 2386):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SamsungIME( 2993): showDlgMsgBox : false true true
D/SSRMv2:TSP:AirViewOnOff( 2386): SettingsAirViewInfo:: 000000000
,I/NfcService( 2765): applyRouting return - 2 
,I/WifiTrafficPoller( 2386): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,I/chromium( 7218): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService( 2386): ACTION_SCREEN_ON
D/LightsService( 2386): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2386) 
D/LightsService( 2386): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2386): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/NfcService( 2765): callback == null
I/SecExternalDisplayIntents_Java( 2386): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
E/libGLESv2( 7218): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
E/libGLESv2( 7218): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/MISC PowerHAL( 2386): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2386): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2386): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2386): Excessive delay in MISC setInteractive(true) while turning screen on: 169ms
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2386): Excessive delay in nativeSetInteractive(true): 170ms
,D/PowerManagerService( 2386): SecHardwareInterface.setBatteryADC : true
D/IpRemoteDisplayController( 2386): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 2386): Bridge Server is not available
,D/PersonaManagerService( 2386): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2386): MSG_ACTION_SCREEN_ON called
,D/StatusBarManagerService( 2386): semi p:7218,o:f
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,E/libGLESv2( 7218): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7218): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
D/dalvikvm( 7771): GC_CONCURRENT freed 3000K, 31% free 9571K/13680K, paused 5ms+1ms, total 64ms
,D/dalvikvm( 7771): WAIT_FOR_CONCURRENT_GC blocked 53ms
E/libGLESv2( 7218): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7218): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,I/NfcService( 2765): NFC: Screen On & Cover Open
,I/NfcService( 2765): applyRouting return - 2 
,E/NfcService( 2765): callback == null
,I/KIES_RECEIVE( 7771): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 7771): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
D/STATUSBAR-NetworkController( 2580): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,E/TranscodeReceiver( 7507): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7507): core_num = 4
,D/dalvikvm( 7507): No JNI_OnLoad found in /system/lib/libsavsff.so 0x4258fd80, skipping init
,W/linker  ( 7507): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/QuickConnect[1.1][2] ( 5144): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
D/videowall-Global( 7507): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
D/videowall-Global( 7507): dsp : 720, swkey : false, Cores : 4, Clock : 0
,V/QuickConnect[1.1][2] ( 5144): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5144): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
,V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
V/QuickConnect[1.1][2] ( 5144): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
D/QuickConnect[1.1][2] ( 5144): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5144): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5144): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5144): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/PowerManagerService( 2386): [PWL] sb release: PowerManagerService.Broadcasts
,I/SELinux ( 7788): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7788):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 11% free 9501K/10656K, paused 3ms+4ms, total 41ms
,I/SELinux ( 7788): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7788):  
I/SELinux ( 7788):  
,I/SELinux ( 7788): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7788): >>>>> Normal User
,E/dalvikvm( 7788): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9501K/10656K, paused 3ms+3ms, total 30ms
,D/TimaKeyStoreProvider( 7788): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7788): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7788): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9501K/10656K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 6429): GC_CONCURRENT freed 2549K, 27% free 10060K/13684K, paused 3ms+4ms, total 56ms
,D/dalvikvm( 7788): GC_CONCURRENT freed 2998K, 31% free 9571K/13680K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/SELinux ( 7804): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7804):  
,I/ActivityManager( 2386): Killing 6449:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 7804): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7804):  
I/SELinux ( 7804):  
,I/SELinux ( 7804): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7804): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7804): >>>>> Normal User
,E/dalvikvm( 7804): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7804): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7804): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7804): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7804): Added TimaKesytore provider
,D/dalvikvm( 7804): GC_CONCURRENT freed 2997K, 31% free 9570K/13676K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7804): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/iu.Environment( 5939): update battery state; isPlugged? false*
,D/PicasaUploader( 7804):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7804):    wifiOnlyVideo changed to true
,D/PicasaUploader( 7804):    syncOnBattery changed to true
,I/iu.SyncManager( 5939): SYNC; picasa accounts
,D/PicasaUploaderSync( 7804): sync account database
,I/ActivityManager( 2386): Killing 6559:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/PicasaUploaderSync( 7804): accounts in DB=1
,D/PicasaUploaderSyncManager( 7804): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7804): background data: true
,I/iu.UploadsManager( 5939): num queued entries: 0
,I/iu.UploadsManager( 5939): num updated entries: 0
,I/iu.SyncManager( 5939): NEXT; no task
,I/iu.Environment( 3278): update battery state; isPlugged? false*
,I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/GCoreUlr( 2735): DispatchingService.onCreate()
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.SyncManager( 3278): NEXT; no task
,D/PicasaUploaderSyncManager( 7804): battery info: false
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SSRMv2:TSP:AirViewOnOff( 2386): SettingsAirViewInfo:: 000000000
I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5342): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 5342): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5342): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5342): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5342): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5342): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5342): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5342): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5342): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1452032400000
,D/daemonapp( 5342): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1452015442463
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5342): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/lights  ( 2386): button : 0 +
,D/lights  ( 2386): button : 0 -
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,D/SensorService( 2386):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): TAP version 13
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # multiplex can send data
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2386):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2386):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2386): level:100, scale:100, status:2, health:2, present:true, voltage: 4361, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/PowerManagerService( 2386): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2580): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2386): [api] [s] wakeUp (uid: 10019 pid: 2580) eventTime = 347378
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/PowerUI ( 2580): playSound : 1
D/UsbDeviceManager( 2386): handleMessage -> MSG_POWER_STATE = 1
D/UsbDeviceManager( 2386): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/EntropyMixer( 2386): Writing entropy...
V/Vibrator( 2580): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
V/Vibrator( 2580): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/VibratorService( 2386): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2386): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2386): JNI vibratorOff()
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/VibratorService( 2386): JNI vibratorOn() : 100
D/PowerUI ( 2580): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
E/TranscodeReceiver( 7507): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/BatteryMeterView( 2580): onDraw batteryColor : -1
,I/SCloudBackupReceiver( 7352): Other Intent
,D/TranscodeService( 7507): onCreate()
,D/dalvikvm( 7507): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x4258fd80, skipping init
,D/PicasaUploaderSyncManager( 7804): battery info: true
,D/dalvikvm( 7507): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x4258fd80, skipping init
,D/dalvikvm( 7507): No JNI_OnLoad found in /system/lib/libsthmb.so 0x4258fd80, skipping init
,D/TranscodeService( 7507): power? : true / screen off : false
,D/TranscodeService( 7507): releaseTranscodeThread.
,I/iu.Environment( 5939): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5939): num queued entries: 0
,I/iu.UploadsManager( 5939): num updated entries: 0
,I/iu.SyncManager( 5939): NEXT; no task
,I/iu.FingerprintManager( 5939): Start processing all media
,I/iu.FingerprintManager( 5939): Start processing media store URI: content://media/external/images/media
D/VibratorService( 2386): JNI vibratorOff()
,I/iu.Environment( 3278): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 5939): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.SyncManager( 3278): NEXT; no task
E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3278): Start processing all media
,I/iu.FingerprintManager( 5939): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5939): Start processing media store URI: content://media/phoneStorage/video/media
,I/GCoreUlr( 2735): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5939): Finished generating fingerprints; 0.076 seconds
,I/iu.FingerprintManager( 5939):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,D/dalvikvm( 2723): GC_EXPLICIT freed 358K, 28% free 9964K/13664K, paused 5ms+7ms, total 69ms
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3278): Finished generating fingerprints; 0.134 seconds
,I/iu.FingerprintManager( 3278):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
,D/dalvikvm( 2735): GC_CONCURRENT freed 1722K, 20% free 12089K/14988K, paused 5ms+15ms, total 96ms
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 7218): ok 1 String should be length:200
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 10
,E/Watchdog( 2386): !@Sync 11
,D/SensorService( 2386):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 7218): # basic
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2386): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/SensorService( 2386):   0.3 -0.0 9.9
,I/ActivityManager( 2386): Waited long enough for: ServiceRecord{4357e5e0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,V/AlarmManager( 2386): waitForAlarm result :4
,V/AlarmManager( 2386): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7828): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7828):  
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 7828): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7828):  
I/SELinux ( 7828):  
,I/SELinux ( 7828): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7828): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7828): >>>>> Normal User
,E/dalvikvm( 7828): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7828): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7828): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7828): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7828): Added TimaKesytore provider
,I/jxcore-log( 7218): ok 2 sane
I/jxcore-log( 7218): 
D/dalvikvm( 7828): GC_CONCURRENT freed 2987K, 30% free 9571K/13672K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7828): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/Headlines( 5875): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5875): Breath 61990 latestRequest time : 1452015396640 current time : 1452015458630
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2386):   0.2 -0.0 9.9
,I/jxcore-log( 7218): # another
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2386):   0.2 -0.0 9.8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,I/ActivityManager( 2386): Waited long enough for: ServiceRecord{435d2380 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/SensorService( 2386):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 7218): ok 3 sane
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2386):   0.2 -0.0 9.9
,I/jxcore-log( 7218): ok 4 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 5 null
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 6 (unnamed assert)
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 7 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 8 should not throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/PowerManagerService( 2386): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2580
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): onDraw batteryColor : -1
,D/dalvikvm( 2386): GC_EXPLICIT freed 3031K, 74% free 25046K/94244K, paused 12ms+23ms, total 241ms
W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/NotificationService( 2386): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2386): sendNotification(1) - 5
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2386): NotificationReceiver onReceive()
D/RCPManagerService( 2386):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2386): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298386
D/RCPManagerService( 2386): getPolicy: policy value returned = false
D/RCPManagerService( 2386): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2386): app label == com.android.systemui
,D/RCPManagerService( 2386): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298386
D/RCPManagerService( 2386): getPolicy: policy value returned = true
,D/RCPManagerService( 2386): Calling User is -1
,D/RCPManagerService( 2386): userid of SBN ==-1
D/UserManagerService( 2386): User -1does not exists!!
E/PersonaManagerService( 2386): returning null in  getPersonasForUser
,D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2580): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@425ec1a8
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2386):   0.2 -0.0 9.9
,I/jxcore-log( 7218): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/PowerManagerService( 2386): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2386): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2386): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/RampAnimator( 2386): Light Animator Finished currentValue=2
D/lights  ( 2386): lcd : 2 +
,D/lights  ( 2386): lcd : 2 -
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
,D/SensorService( 2386):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7218): ok 9 (unnamed assert)
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 10 (unnamed assert)
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 11 should not throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 12 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 13 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7218): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7218): 
,D/SensorService( 2386):   0.2 -0.0 9.9
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5342): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
D/PowerManagerService( 2386): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2386): [PWL] On : 337438 (39938 ms ago)
I/PowerManagerService( 2386): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService( 2386): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2580, ws=null) (elapsedTime=9878)
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2386): !@Sync 12
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7218): ok 14 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/SensorService( 2386):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2386): waitForAlarm result :8
,D/Headlines( 5875): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5875): Breath 87248 latestRequest time : 1452015396640 current time : 1452015483888
,I/jxcore-log( 7218): # failed to get mobile documents path
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2386): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/SensorService( 2386):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/SensorService( 2386):   0.3 -0.0 9.9
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2386): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2580 (0x0)
I/PowerManagerService( 2386): Nap time...
,D/PowerManagerService( 2386): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2386): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2386): Going to sleep due to screen timeout...
D/PowerManagerService( 2386): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2386): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2386): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/DisplayPowerController( 2386): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/Sensors ( 2386): LightSensor enable = 0
D/Sensors ( 2386): LightSensor enableSensor = 0
,I/SurfaceFlinger( 1920): id=22 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/DisplayPowerController( 2386): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/SensorManager( 2386): unregisterListener ::   
,I/Sensors ( 2386): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2386): !@ElectronBeam entry
,D/SensorManager( 2386): unregisterListener ::   
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/lights  ( 2386): lcd : 0 +
,D/lights  ( 2386): lcd : 0 -
,D/MISC PowerHAL( 2386): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2386): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2386): blankAllDisplays() is called.
D/PowerManagerService( 2386): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2386): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2386): [PWL] sb release: PowerManagerService.Display
V/WindowOrientationListener( 2386): WindowOrientationListener disabled
D/SensorService( 2386): AutoRotationSensor::activate (ident=0x840c9e30, enabled=0)
I/Sensors ( 2386): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2386): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2386): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2386): sysfs_write +: /sys/class/input/input0/enabled: 0
D/KeyguardViewMediator( 2580): onScreenTurnedOff(3)
D/MISC PowerHAL( 2386): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2386): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2386): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2386): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2386): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SensorManager( 2386): unregisterListener ::   
,D/PowerManagerService( 2386): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/InputDispatcher( 2386): setInputDispatchMode: enabled=0, frozen=0
D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x41da5550
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SurfaceControl( 2386): Excessive delay in blankDisplay() while turning screen off: 214ms
,I/libsuspend( 2386): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2386): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2386): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 219ms
D/PowerManagerService( 2386): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2386): [PWL] Off : 0s ago
I/PowerManagerService( 2386): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2386): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2386): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2386, ws=null) (elapsedTime=212)
I/PowerManagerService( 2386): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2580): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2386): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2386) 
,I/SensorManagerA( 2386): getReportingMode :: sensor.mType = 5
D/Sensors ( 2386): LightSensor setDelay = 200000000
,D/Sensors ( 2386): LightSensor setSensorDelay = 200000000
,D/LightsService( 2386): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2386): Light sensor flush: not enabled 0
D/Sensors ( 2386): LightSensor enable = 1
D/Sensors ( 2386): LightSensor enableSensor = 1
,D/SensorManager( 2386): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2386): turn on LED for fully charged
D/VibratorService( 2386): JNI vibratorOff()
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0
,I/WifiTrafficPoller( 2386): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2386): ACTION_SCREEN_OFF
D/LightsService( 2386): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2386) 
,D/LightsService( 2386): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2386): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2386): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2386): Bridge Server is not available
,D/PersonaManagerService( 2386): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2386): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2580): makeExpandedInvisible
D/PhoneStatusBarView( 2580): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2765): applyRouting return - 2 
,E/NfcService( 2765): callback == null
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0
D/QuickConnect[1.1][2] ( 5144): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5144): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5144): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1e40
D/QuickConnect[1.1][2] ( 5144): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5144): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 5144): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5144): stopLeScan()
,D/QuickConnect[1.1][2] ( 5144): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7507): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7507): power? : true / screen off : true
D/PowerManagerService( 2386): [PWL] sb release: PowerManagerService.Broadcasts
,D/TranscodeService( 7507): Music is = false
,D/TranscodeService( 7507): runvideoplayer is false
,D/TranscodeService( 7507): Thread start
D/TranscodeService( 7507): WakeLock.acquire()
,D/videowall-FileMgr( 7507): thumbnailDBSync -1
,D/Sensors ( 2386): LightSensor enable = 0
,D/Sensors ( 2386): LightSensor enableSensor = 0
,D/LightsService( 2386): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2386): unregisterListener ::   
D/lights  ( 2386): led_pattern : 5 +
,D/lights  ( 2386): led_pattern : 5 -
D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onInitialize : 94
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onSetOnInfoListener : add 94
I/PrGenericPlugin( 1924): [A] ENTER onInitialize : 0x5e
,I/PrGenericPlugin( 1924): [A] LEAVE onInitialize : 0x5e
,D/TranscodeService( 7507): Thread end
,D/TranscodeService( 7507): WakeLock.release()
,D/TranscodeService( 7507): onDestroy()
,D/TranscodeService( 7507): releaseTranscodeThread.
,V/ApplicationPolicy( 2386): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2386): Killing 6572:com.android.musicfx/u0a24 (adj 15): empty #43
,I/jxcore-log( 7218): ok 15 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :4
D/KeyguardViewMediator( 2580): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2580): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): doKeyguard: not showing because lockscreen is off
,V/AlarmManager( 2386): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2386): [PWL] Off : 5s ago
,I/jxcore-log( 7218): ok 16 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 17 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 18 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #init should register the networkChanged event
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2580): GC_CONCURRENT freed 15712K, 34% free 33886K/50704K, paused 10ms+10ms, total 86ms
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 320, Delta = 0
,I/jxcore-log( 7218): ok 19 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #startBroadcasting should throw on null device name
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 15s ago
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7218): ok 20 should throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = -10
,E/Watchdog( 2386): !@Sync 13
,I/jxcore-log( 7218): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 21 should throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
V/AlarmManager( 2386): waitForAlarm result :8
,I/jxcore-log( 7218): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 22 should throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2386): [PWL] Off : 30s ago
,I/jxcore-log( 7218): ok 23 should throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2386): waitForAlarm result :4
,V/AlarmManager( 2386): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5875): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5875): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5875): Breath 125183 latestRequest time : 1452015396640 current time : 1452015521823
,D/Headlines( 5875): stop 
,D/Headlines( 5875): Breath.onDestroy : 
,I/ActivityManager( 2386): Killing 6600:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,I/jxcore-log( 7218): # #startBroadcasting should throw on negative port
I/jxcore-log( 7218): 
D/AmoledAdjustTimer( 2386): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): stay LED for fully charged
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7218): ok 24 should throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7218): # #startBroadcasting should throw on too large port
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7218): ok 25 should throw
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup,
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2386): [PWL] Off : 50s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2386): !@Sync 14
,I/jxcore-log( 7218): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7218): ok 26 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 27 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 28 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): ok 29 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 30 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 31 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7218): 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 75s ago
,I/jxcore-log( 7218): ok 32 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 33 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7218): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2386): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2386): !@Sync 15
,I/jxcore-log( 7218): ok 34 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 35 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 36 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 37 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 38 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 39 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 40 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 7218): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7218): 
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 41 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 42 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7218): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 105s ago
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2386): !@Sync 16
,I/jxcore-log( 7218): ok 43 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): ok 44 should be equal
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # setup
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7218): 
,I/jxcore-log( 7218): # teardown
I/jxcore-log( 7218): 
,D/AmoledAdjustTimer( 2386): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/dalvikvm( 7218): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 7218): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7218): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 7218): Shutting down VM
,W/dalvikvm( 7218): threadid=1: thread exiting with uncaught exception (group=0x41b37c08)
,E/AndroidRuntime( 7218): FATAL EXCEPTION: main
E/AndroidRuntime( 7218): Process: com.test.thalitest, PID: 7218
E/AndroidRuntime( 7218): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7218): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7218): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7218): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7218): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7218): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 7218): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 7218): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7218): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7218): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7218): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7218): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7218): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7218): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7218): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7218): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7218): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7218): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7218): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2386):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2386): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2386): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2386): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2386): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2386): Killing 6001:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/CrashAnrDetector( 2386): processName: com.test.thalitest
,I/Process ( 7218): Sending signal. PID: 7218 SIG: 9
,D/CrashAnrDetector( 2386): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager( 2386): Process com.test.thalitest (pid 7218) (adj 9) has died.
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/10)
,I/WindowState( 2386): WIN DEATH: Window{434963f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (6/9)
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/8)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/8)
,V/WindowManager( 2386): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2771): onRestart, Launcher: 1113341848
D/Launcher( 2771): onStart, Launcher: 1113341848
,D/Launcher.HomeView( 2771): onStart
,I/SurfaceFlinger( 1920): id=23 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2386): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2386): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2386): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2386): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2386): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2386): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2386): tr p:2771,o:f
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2386): semi p:2771,o:f
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2386): Got RemoteException sending setActive(false) notification to pid 7218 uid 10587
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2386): [PWL] Off : 140s ago
,E/Watchdog( 2386): !@Sync 17
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 18
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2386): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2386): !@Sync 19
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2386): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 225s ago
I/PowerManagerService( 2386): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2386): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2386): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2386, ws=null) (elapsedTime=1121)
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2386): GC_CONCURRENT freed 3243K, 73% free 25586K/94244K, paused 11ms+19ms, total 219ms
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2386): !@Sync 20
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2386): !@Sync 21
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/GAV2    ( 5635): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5635): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2386): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2386): <AppSync3 Whitelist>
,V/AlarmManager( 2386): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 22
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2386): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 23
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4089): GC_CONCURRENT freed 2891K, 30% free 9724K/13724K, paused 14ms+3ms, total 72ms
,E/Watchdog( 2386): !@Sync 24
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 25
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 26
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2386): waitForAlarm result :4
,V/AlarmManager( 2386): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5544): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3278): Aggregate from 1452014020358 (log), 1452014020358 (data)
,D/dalvikvm( 2848): GC_CONCURRENT freed 1855K, 22% free 10812K/13848K, paused 5ms+5ms, total 78ms
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 27
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 28
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 29
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 525s ago
I/PowerManagerService( 2386): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2386): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2386): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2386, ws=null) (elapsedTime=1232)
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2386): !@Sync 30
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2386): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 31
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 32
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 33
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 34
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm( 2386): GC_CONCURRENT freed 3933K, 73% free 25579K/94184K, paused 23ms+19ms, total 256ms
,I/PowerManagerService( 2386): [PWL] Off : 680s ago
,E/Watchdog( 2386): !@Sync 35
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 36
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2386): waitForAlarm result :4
,I/SensorManagerA( 2386): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2386): LightSensor setDelay = 200000000
,D/LightsService( 2386): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2386): LightSensor setSensorDelay = 200000000
D/Sensors ( 2386): Light sensor flush: not enabled 0
D/Sensors ( 2386): LightSensor enable = 1
D/Sensors ( 2386): LightSensor enableSensor = 1
D/SensorManager( 2386): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2386): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2386): LightSensor enable = 0
,D/Sensors ( 2386): LightSensor enableSensor = 0
,D/SensorManager( 2386): unregisterListener ::   
D/LightsService( 2386): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5544): [b] __PingReply__
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 37
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2386): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 38
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 39
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2386): !@Sync 40
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2386): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 41
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2386): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2386): <AppSync3 Whitelist>
,V/AlarmManager( 2386): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 42
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 43
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2386): [PWL] Off : 950s ago
,E/Watchdog( 2386): !@Sync 44
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 45
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 46
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 47
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4089): GC_CONCURRENT freed 2048K, 30% free 9721K/13724K, paused 4ms+2ms, total 55ms
,E/Watchdog( 2386): !@Sync 48
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 49
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2386): GC_CONCURRENT freed 3917K, 73% free 25707K/94184K, paused 12ms+18ms, total 218ms
,D/dalvikvm( 2386): WAIT_FOR_CONCURRENT_GC blocked 187ms
,D/dalvikvm( 2386): WAIT_FOR_CONCURRENT_GC blocked 205ms
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2386): !@Sync 50
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2386): stay LED for fully charged
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2386): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 51
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 52
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 53
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 54
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2386): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 55
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 56
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2386): waitForAlarm result :8
,E/SPPClientService( 5544): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 57
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 58
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2386): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 59
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2386): Prepared write state in 36ms
,I/ProcessStatsService( 2386): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-55-25.bin
,I/ProcessStatsService( 2386): Prepared write state in 31ms
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2386): !@Sync 60
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2386): !@Sync 61
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): stay LED for fully charged
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2386): waitForAlarm result :4
,D/LightsService( 2386): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2386): getReportingMode :: sensor.mType = 5
D/Sensors ( 2386): LightSensor setDelay = 200000000
D/Sensors ( 2386): LightSensor setSensorDelay = 200000000
D/Sensors ( 2386): Light sensor flush: not enabled 0
D/Sensors ( 2386): LightSensor enable = 1
D/Sensors ( 2386): LightSensor enableSensor = 1
D/SensorManager( 2386): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
V/NetworkStats( 2386): performPollLocked(flags=0x3)
,V/AlarmManager( 2386): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/NetworkStats( 2386): performPollLocked() took 45ms
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
D/NtpTrustedTime( 2386): currentTimeMillis() cache hit
,I/SELinux (11619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11619):  
,I/SELinux (11619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11619):  
I/SELinux (11619):  
,I/SELinux (11619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11619): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11619): >>>>> Normal User
,E/dalvikvm(11619): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11619): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11619): in addTimaSignatureService
,D/TimaKeyStoreProvider(11619): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11619): Added TimaKesytore provider
,D/Sensors ( 2386): LightSensor enable = 0
,D/Sensors ( 2386): LightSensor enableSensor = 0
,D/LightsService( 2386): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2386): unregisterListener ::   
D/LightsService( 2386): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm(11619): GC_CONCURRENT freed 2998K, 31% free 9565K/13676K, paused 3ms+2ms, total 27ms
,D/dalvikvm(11619): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(11619): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11619): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11619): Widget random data : 6
,D/@ WidgetProvider(11619): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11619): Widget random data : 6
E/dalvikvm(11619): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11619): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11619): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11619): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11619): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11619): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11619): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11619): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11619): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11619): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11619): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11619): VFY: replacing opcode 0x22 at 0x0038
D/dalvikvm(11619): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(11619): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11619): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11619): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11619): Thread-681(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11619): Thread-681(ApacheHTTPLog):isShipBuild true
,I/System.out(11619): Thread-681(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 3278): GC_CONCURRENT freed 1719K, 19% free 12691K/15556K, paused 7ms+14ms, total 110ms
,W/SQLiteConnectionPool( 3278): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/System.out(11619): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11619): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11619): Max ALLOWED memory (MB): 128
V/ImageManager(11619): Max SHOULD USE memory (MB): 128
,V/ImageManager(11619): Max Image Cache memory (MB): 32
,D/skia    (11619): getTotalSize : Do not get file length
,D/@ WidgetProvider(11619): Building widget : 5
,D/dalvikvm( 2771): GC_CONCURRENT freed 8461K, 38% free 18660K/30032K, paused 10ms+6ms, total 74ms
,D/dalvikvm( 2771): WAIT_FOR_CONCURRENT_GC blocked 56ms
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2386): stay LED for fully charged
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2386): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2386): <AppSync3 Whitelist>
,V/AlarmManager( 2386): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 62
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2386): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2386): GC_CONCURRENT freed 4032K, 73% free 25630K/94184K, paused 12ms+17ms, total 210ms
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2386): !@Sync 63
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 64
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2386): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2386): !@Sync 65
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2386): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2386): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2386): mCoverManager.getCoverState() : true
,D/BatteryService( 2386): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
I/ActivityManager( 2386): Killing 6443:com.sec.knox.bridge/1000 (adj 15): empty for 1841s
,I/ActivityManager( 2386): Killing 4865:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1841s
,I/ActivityManager( 2386): Killing 6405:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1851s
,I/ActivityManager( 2386): Killing 6747:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1852s
,I/ActivityManager( 2386): Killing 6733:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1852s
,I/ActivityManager( 2386): Killing 6721:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1852s
,I/ActivityManager( 2386): Killing 6709:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1852s
I/ActivityManager( 2386): Killing 6696:com.samsung.helphub/1000 (adj 15): empty for 1853s
,I/ActivityManager( 2386): Killing 6683:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1853s
,I/ActivityManager( 2386): Killing 6669:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1853s
,I/ActivityManager( 2386): Killing 6656:com.sec.android.service.cm/u0a82 (adj 15): empty for 1853s
,I/ActivityManager( 2386): Killing 6361:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1853s
,I/ActivityManager( 2386): Killing 5698:com.android.mms/u0a49 (adj 15): empty for 1853s
,I/ActivityManager( 2386): Killing 6630:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1853s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2386): No listener is left
,E/Watchdog( 2386): !@Sync 66
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2386): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 67
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2386): !@Sync 68
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2386): !@Sync 69
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService( 2386): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2386): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2386): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2386): waitForAlarm result :8
,V/AlarmManager( 2386): ClockReceiver onReceive() ACTION_TIME_TICK
,I/ActivityManager( 2386): Killing 7377:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1823s
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
I/ActivityManager( 2386): Killing 7365:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 5808:com.osp.app.signin/u0a44 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 7517:com.sec.android.app.voicenote/1000 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 6614:com.policydm/1000 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 7340:com.sec.android.soagent/u0a38 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 7266:com.vlingo.midas/u0a34 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 7328:com.samsung.klmsagent/u0a18 (adj 15): empty for 1823s
I/ActivityManager( 2386): Killing 7309:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1824s
I/ActivityManager( 2386): Killing 5748:com.sec.android.diagmonagent/1000 (adj 15): empty for 1824s
I/ActivityManager( 2386): Killing 6585:com.sec.pcw.device/1000 (adj 15): empty for 1824s
I/ActivityManager( 2386): Killing 2824:com.android.settings/1000 (adj 15): empty for 1824s
I/ActivityManager( 2386): Killing 7469:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1824s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2386): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2386): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2386): !@Sync 70
,D/SSRMv2:SIOP( 2386): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2386): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
