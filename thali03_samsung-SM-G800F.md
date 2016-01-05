#### Test 54970261aa56788_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7225): 
D/AndroidRuntime( 7225): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7225): CheckJNI is OFF
D/AndroidRuntime( 7225): setted country_code = Poland
D/AndroidRuntime( 7225): setted countryiso_code = PL
D/AndroidRuntime( 7225): setted sales_code = PLS
D/AndroidRuntime( 7225): readGMSProperty: start
D/AndroidRuntime( 7225): readGMSProperty: already setted!!
D/AndroidRuntime( 7225): readGMSProperty: end
D/AndroidRuntime( 7225): addProductProperty: start
D/dalvikvm( 7225): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7225): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7225): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7225): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7225): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7225): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7225): failed to load memtrack module: -2
D/dalvikvm( 7225): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7225): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7237):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7225): Shutting down VM
D/dalvikvm( 7225): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7237):  
I/SELinux ( 7237):  
I/SELinux ( 7237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7237): >>>>> Normal User
E/dalvikvm( 7237): >>>>> com.test.thalitest [ userId:0 | appId:10588 ]
E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7237): in addTimaSignatureService
D/TimaKeyStoreProvider( 7237): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7237): Added TimaKesytore provider
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4174): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4174): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2777): onTrimMemory. Level: 20
D/dalvikvm( 7237): GC_CONCURRENT freed 2996K, 31% free 9571K/13760K, paused 2ms+2ms, total 20ms
D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7237): Binding Chromium to the background looper Looper (main, tid 1) {425682c8}
I/chromium( 7237): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7237): Initializing chromium process, renderers=0
W/chromium( 7237): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7237): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7237): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7237): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7237): Mali API Version : 401
,I/Mali    ( 7237): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7237): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7237): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7237): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7237): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7237): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7237): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): tr p:7237,o:f
W/dalvikvm( 7237): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7237): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7237): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7237): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7237): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7237): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7237): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7237): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7237): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7237): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7237): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7237): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7237): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:7237,o:f
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7237): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7237): Enabling debug mode 0
,W/AwContents( 7237): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7237): showStatusIcon on inactive InputConnection
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7237): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7237): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42569090
,D/dalvikvm( 7237): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42569090
D/jxcore_app_log( 7237): JniHelper::setJavaVM(0x41ae2220), pthread_self() = 2031020904
,D/JX-Cordova( 7237): jxcore cordova android initializing
,D/dalvikvm( 7237): GC_CONCURRENT freed 1304K, 19% free 11340K/13832K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7237): GC_CONCURRENT freed 1871K, 18% free 14973K/18052K, paused 2ms+3ms, total 46ms
,D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 7237): GC_FOR_ALLOC freed 5423K, 30% free 16286K/23100K, paused 41ms, total 41ms
,D/dalvikvm( 7237): GC_CONCURRENT freed 6707K, 31% free 17734K/25668K, paused 3ms+10ms, total 67ms
,D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 7237): GC_FOR_ALLOC freed 1398K, 33% free 17424K/25668K, paused 48ms, total 48ms
,I/dalvikvm-heap( 7237): Grow heap (frag case) to 21.691MB for 3688532-byte allocation
,D/dalvikvm( 7237): GC_FOR_ALLOC freed 2431K, 37% free 18594K/29272K, paused 55ms, total 55ms
,W/jxcore-log( 7237): Initializing JXcore engine
,W/jxcore-log( 7237): JXcore engine is ready
,W/jxcore-log( 7237): Starting JXcore engine
,W/jxcore-log( 7237): Platform android
W/jxcore-log( 7237): 
,W/jxcore-log( 7237): Process ARCH arm
W/jxcore-log( 7237): 
,I/jxcore-log( 7237): JXcore Cordova bridge is ready!
I/jxcore-log( 7237): 
,W/jxcore-log( 7237): JXcore engine is started
,I/chromium( 7237): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7237): Toggling radios to true
I/jxcore-log( 7237): 
,D/BluetoothAdapter( 7237): enable(): BT is already enabled..!
,I/WifiManager( 7237): packageName : com.test.thalitest
,I/WifiManager( 7237): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7237, uid=10588
W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7237, uid=10588 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7237, uid=10588 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2419): disconnect: pid=7237, uid=10588
,I/jxcore-log( 7237): Radios toggled
I/jxcore-log( 7237): 
,I/wpa_supplicant( 3976): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3976): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3976): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3976): First Scan Start
,W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3976): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3976): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3976): Skip scan - already scanning
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2419): Attempting to switch to mobile
,D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7283): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7283):  
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
E/WifiStateMachine( 2419): Error! unhandled message{ when=-72ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-73ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SELinux ( 7283): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7283):  
I/SELinux ( 7283):  
I/SELinux ( 7283): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/WifiStateMachine( 2419): Error! unhandled message{ when=-16ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/SELinux ( 7283): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7283): >>>>> Normal User
E/dalvikvm( 7283): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
W/NetworkManagementService( 2419): route cmd failed: 
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
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
E/SELinux ( 7283): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7283): in addTimaSignatureService
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7283): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7283): Added TimaKesytore provider
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x782a20b0 clazz=0x61700001 iface=wlan0 mask=0x3
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,E/SPPClientService( 5548): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5548): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5548): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5548): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5548): [b] ResponseMap empty
,V/NativeCrypto( 2847): Read error: ssl=0x7bba8c80: I/O error during system call, Connection timed out
D/dalvikvm( 7283): GC_CONCURRENT freed 2993K, 31% free 9575K/13760K, paused 4ms+2ms, total 59ms
,D/dalvikvm( 7283): WAIT_FOR_CONCURRENT_GC blocked 41ms
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7bba8c80: I/O error during system call, Broken pipe
,I/System.out( 7283): Inside WakeupProvider
,I/System.out( 7283): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2419): updateIfacesLocked()
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x1)
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 44ms
I/VlingoApplication( 7283): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7283): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7283): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2419): GC_CONCURRENT freed 3807K, 72% free 25125K/87148K, paused 17ms+17ms, total 224ms
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2419): Killing 6175:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7283): initQueue()
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2419): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2419): updateDataUsageMap
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6591): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6591): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6591): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): noConnectivity : true
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/DBG_DM  ( 4762): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7312): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7312):  
,I/SELinux ( 7312): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7312):  
I/SELinux ( 7312):  
,I/SELinux ( 7312): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7312): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7312): >>>>> Normal User
,E/dalvikvm( 7312): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7312): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7312): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7312): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7312): Added TimaKesytore provider
,D/dalvikvm( 7312): GC_CONCURRENT freed 3007K, 31% free 9559K/13756K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7312): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/wpa_supplicant( 3976): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3976): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3976): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/ActivityManager( 2419): Killing 6245:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): Associated with C0.AA.48
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3976): freq(2412) increment count 2
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): meet head of list.
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3976): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3976): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7326): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7326):  
,I/SELinux ( 7326): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7326):  
I/SELinux ( 7326):  
,I/SELinux ( 7326): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7326): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7326): >>>>> Normal User
,E/dalvikvm( 7326): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7326): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7326): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7326): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7326): Added TimaKesytore provider
,D/dalvikvm( 7326): GC_CONCURRENT freed 3011K, 31% free 9557K/13760K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7326): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/ActivityManager( 2419): Killing 6332:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7339): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7339):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 12% free 9504K/10740K, paused 3ms+2ms, total 30ms
,I/SELinux ( 7339): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7339):  
I/SELinux ( 7339):  
,I/SELinux ( 7339): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7339): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7339): >>>>> Normal User
,E/dalvikvm( 7339): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7339): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9504K/10740K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7339): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7339): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7339): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9504K/10740K, paused 2ms+3ms, total 24ms
I/dhcpcd  ( 7338): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7338): bssid match
,D/dalvikvm( 7339): GC_CONCURRENT freed 2997K, 31% free 9574K/13760K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7339): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/KLMS-2.3.201 : ( 7339): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7339): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452019478276
,I/KLMS-2.3.201 : ( 7339): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6328:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7357): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7357):  
,I/SELinux ( 7357): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7357):  
I/SELinux ( 7357):  
,I/SELinux ( 7357): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7357): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7357): >>>>> Normal User
,E/dalvikvm( 7357): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7357): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7357): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7357): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7357): Added TimaKesytore provider
,D/dalvikvm( 7357): GC_CONCURRENT freed 2996K, 31% free 9571K/13760K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7357): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/SO_AGENT( 7357): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7357): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5814): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5814): [BDLM] already registered in spp
,I/SA      ( 5814): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5814): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5814): [OR] == isSIMCardReady false ==
I/SA      ( 5814): [SCU] == networkStateCheck == false
,I/SA      ( 5814): [OR] onReceive END
I/ActivityManager( 2419): Killing 5596:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): Phone number locator feature is dsiabled
,I/SELinux ( 7369): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7369):  
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7369): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7369):  
I/SELinux ( 7369):  
,I/SELinux ( 7369): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7369): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7369): >>>>> Normal User
,E/dalvikvm( 7369): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7369): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7369): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7369): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7369): Added TimaKesytore provider
,D/dalvikvm( 7369): GC_CONCURRENT freed 3004K, 31% free 9562K/13756K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7369): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/sCloudBackupApp( 7369): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7369): Other Intent
I/ActivityManager( 2419): Killing 6296:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7382): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7382):  
,I/SELinux ( 7382): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7382):  
I/SELinux ( 7382):  
,I/SELinux ( 7382): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7382): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7382): >>>>> Normal User
,E/dalvikvm( 7382): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7382): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7382): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7382): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7382): Added TimaKesytore provider
,D/dalvikvm( 7382): GC_CONCURRENT freed 2998K, 31% free 9572K/13760K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7382): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
D/com.samsung.app( 7382): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7382): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7382): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5347): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7382): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5347): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7382): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5347): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6315:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/Headlines( 5878): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5878): getCountryCode(): countryCode = PL
,D/Headlines( 5878): Breath.onCreate
,D/Headlines( 5878): Breath timer started. interval : 30000
D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5878): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5878): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5878): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2419): waitForAlarm result :8
,I/SELinux ( 7394): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7394):  
,I/SELinux ( 7394): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7394):  
I/SELinux ( 7394):  
,I/SELinux ( 7394): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7394): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7394): >>>>> Normal User
,E/dalvikvm( 7394): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7394): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7394): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7394): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7394): Added TimaKesytore provider
,D/dalvikvm( 7394): GC_CONCURRENT freed 2995K, 31% free 9574K/13760K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7394): WAIT_FOR_CONCURRENT_GC blocked 21ms
,V/WebViewChromium( 7394): Binding Chromium to the background looper Looper (main, tid 1) {42565180}
,I/chromium( 7394): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7394): Initializing chromium process, renderers=0
,W/chromium( 7394): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7394): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7394): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7394): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7394): Mali API Version : 401
,I/Mali    ( 7394): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/GAV2    ( 7394): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 7394): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/NSApplication( 7394): Starting up...
,I/iu.Environment( 5946): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 5946): SYNC; picasa accounts
,D/QuickConnect[1.1][2] ( 5150): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5150): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5150): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42576100
,I/iu.UploadsManager( 5946): num queued entries: 0
,I/iu.UploadsManager( 5946): num updated entries: 0
,I/iu.SyncManager( 5946): NEXT; no task
,I/SELinux ( 7454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7454):  
,I/SELinux ( 7454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7454):  
I/SELinux ( 7454):  
,I/SELinux ( 7454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7454): >>>>> Normal User
,E/dalvikvm( 7454): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7454): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7454): Cannot add TimaSignature Service, License check Failed
,D/WifiStateMachine( 2419): VerifyingLinkState enter
,D/ActivityThread( 7454): Added TimaKesytore provider
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/dalvikvm( 7454): GC_CONCURRENT freed 2981K, 31% free 9583K/13756K, paused 4ms+7ms, total 42ms
,D/dalvikvm( 7454): WAIT_FOR_CONCURRENT_GC blocked 27ms
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x1)
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 21ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7488): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7488):  
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/ActivityManager( 2419): Killing 5990:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7488): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7488):  
I/SELinux ( 7488):  
,I/SELinux ( 7488): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7488): >>>>> Normal User
,E/dalvikvm( 7488): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
,D/TimaKeyStoreProvider( 7488): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7488): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7488): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6264:com.android.providers.calendar/u0a45 (adj 15): empty #43
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
,D/dalvikvm( 7488): GC_CONCURRENT freed 3002K, 31% free 9567K/13760K, paused 4ms+1ms, total 22ms
,D/dalvikvm( 7488): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/BadgeProvider( 7488): onCreate
,D/BadgeProvider( 7488): DatabaseHelper
,D/BadgeProvider( 7488): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7492): GC_CONCURRENT freed 2989K, 31% free 9578K/13760K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/Launcher.Model( 2777): reloadBadges entered.
D/BadgeProvider( 7488): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7488): sendNotify, [notify] : null
D/BadgeProvider( 7488): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7488): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7488): update, [UpdateCount] : 1
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/hcjo    ( 5968): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5968): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5968): exit::IDLE
,D/InitializeManagerStateMachine( 5968): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5968): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5968): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5968): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5968): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5968): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5968): entry::SUCCESS
D/hcjo    ( 5968): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4762): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/hcjo    ( 5968): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5968): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5968): exit::SUCCESS
,D/InitializeManagerStateMachine( 5968): entry::IDLE
,E/SPPClientService( 5548): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5548): [SystemStateMoniter] Current Time : 287123
,E/SPPClientService( 5548): [SystemStateMoniter] No Connect : true
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5548): [[SystemStateMonitorService]] No Active Internet
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 1638 latestRequest time : 1452019478913 current time : 1452019480551
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
I/ActivityManager( 2419): Killing 6162:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5548): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5548): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5548): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5548): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6591): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6591): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6591): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5548): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5548): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5548): [g] getNetMCC return empty string
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/KLMS-2.3.201 : ( 7339): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7339): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452019480959
,I/KLMS-2.3.201 : ( 7339): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7357): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3384): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3384): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3384): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3384): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7357): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7525): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7525):  
,I/GallerySearchProvider( 3516): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7525): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7525):  
I/SELinux ( 7525):  
,I/SELinux ( 7525): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7525): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7525): >>>>> Normal User
,E/dalvikvm( 7525): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7525): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7525): in addTimaSignatureService
,I/SELinux ( 7537): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7537):  
,D/TimaKeyStoreProvider( 7525): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7525): Added TimaKesytore provider
,I/SELinux ( 7537): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7537):  
I/SELinux ( 7537):  
,I/SELinux ( 7537): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7537): >>>>> Normal User
,E/dalvikvm( 7537): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,I/SA      ( 5814): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5814): [BDLM] already registered in spp
,E/SELinux ( 7537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5814): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5814): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/TimaKeyStoreProvider( 7537): in addTimaSignatureService
,I/SA      ( 5814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/TimaKeyStoreProvider( 7537): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7537): Added TimaKesytore provider
,I/SA      ( 5814): [OR] == isSIMCardReady false ==
,D/dalvikvm( 7525): GC_CONCURRENT freed 2993K, 31% free 9575K/13760K, paused 7ms+1ms, total 29ms
,D/dalvikvm( 7525): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SA      ( 5814): [SCU] == networkStateCheck == true
,I/SA      ( 5814): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5814): isChinaCountryCode : false
,I/SA      ( 5814): [OR] == networkStateCheck true ==
,I/SA      ( 5814): [OR] GetMyCountryZoneTask
,I/SA      ( 5814): [OR] onReceive END
,I/SA      ( 5814): [SRS] prepareGetMyCountryZone
D/dalvikvm( 7537): GC_CONCURRENT freed 3013K, 31% free 9558K/13764K, paused 3ms+2ms, total 43ms
,D/dalvikvm( 7537): WAIT_FOR_CONCURRENT_GC blocked 39ms
,I/SA      ( 5814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5814): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7369): Other Intent
,V/KVNProvider( 7537): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7537): getFindoCursor query string : 
,I/SA      ( 5814): [TPMU] GetMccFromDB : null
,I/SA      ( 5814): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5814): [TPM] isNoProxy(default) : true
,I/SA      ( 5814): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7382): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,V/KVNProvider( 7537): getTagSearchCursor() tagSearchCursor count : 0
,D/Headlines( 5878): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5878): getCountryCode(): countryCode = PL
,D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5878): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5878): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5878): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
D/HeadlinesDataCenter( 5878): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Watchdog( 2419): !@Sync 9
,I/iu.Environment( 5946): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/System.out( 7326): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/iu.UploadsManager( 5946): num queued entries: 0
,I/iu.UploadsManager( 5946): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5150): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/iu.SyncManager( 5946): NEXT; no task
,I/QuickConnect[1.1][2] ( 5150): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5150): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42576100
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
I/System.out( 7326): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7326): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 5968): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5968): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5968): exit::IDLE
,D/InitializeManagerStateMachine( 5968): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5968): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5968): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5968): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5968): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5968): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5968): entry::SUCCESS
,D/hcjo    ( 5968): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5968): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5968): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5968): exit::SUCCESS
,D/InitializeManagerStateMachine( 5968): entry::IDLE
,E/SPPClientService( 5548): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5548): [SystemStateMoniter] Current Time : 288190
,E/SPPClientService( 5548): [SystemStateMoniter] No Connect : false
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/System.out( 7326): AsyncTask #1 calls detatch()
,W/System.err( 7326): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7326): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7326): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7326): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7326): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7326): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7326): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7326): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7326): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7326): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7326): Caused by: java.lang.NullPointerException
W/System.err( 7326): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7326): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7326): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7326): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7326): 	... 8 more
,I/ActivityManager( 2419): Killing 6198:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5548): GC_CONCURRENT freed 2012K, 24% free 10455K/13740K, paused 6ms+4ms, total 44ms
,D/dalvikvm( 5548): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SA      ( 5814): [RC New] [v2liruge] api execute + 688
,I/SA      ( 5814): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5814): AsyncTask #2 calls detatch()
,I/SA      ( 5814): [TPMU] getNetworkMcc : 
,I/SA      ( 5814): [SCU] saveMccToPreferece Start
,I/SA      ( 5814): [SCU] RegionMCC : 260
,I/SA      ( 5814): [SSP] query invoked
I/SA      ( 5814): [TPMU] GetMccFromDB : null
,I/SA      ( 5814): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5814): [SCU] saveMccToPreferece End
I/SA      ( 5814): [RC New] executeRequest [v2liruge] end. 716
,I/SA      ( 5814): [RC New] Execute end
I/SA      ( 5814): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5814): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 20
,E/SPPClientService( 5548): [b] __InitReply__
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (-2/11)
I/ActivityManager( 2419): Killing 6530:com.android.defcontainer/u0a6 (adj 15): empty #43
D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 290787
D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3477)
,I/GAV2    ( 7394): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6591): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6591): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6591): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6591): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6591): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6591): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6591): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6591): [ensureRegistration] - No Samsung account
,D/dalvikvm( 2419): GC_EXPLICIT freed 2275K, 72% free 24994K/87016K, paused 7ms+15ms, total 178ms
,I/PowerManagerService( 2419): [PWL] Off : 225s ago
,I/jxcore-log( 7237): Test app app.js loaded
I/jxcore-log( 7237): 
,I/chromium( 7237): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/PreloadUpdateManagerStateMachine( 5968): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5968): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5968): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/hcjo    ( 5968): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/PreloadUpdateManagerStateMachine( 5968): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5968): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5968): entry::IDLE
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-12ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5968): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5968): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5968): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5968): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5968): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5968): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5968): entry::IDLE
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{46ed9a68 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{46d35950 u0 com.sec.spp.push/.PushClientService}
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2419): initializing...
,I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2419): device_id = 0x0
I/TZ: mc_tlc_communication( 2419): tlc_open() was called
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2419): Opening the session
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 27519 latestRequest time : 1452019481410 current time : 1452019508929
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 7666
W/ProcessCpuTracker( 2419): Skipping unknown process pid 7671
W/ProcessCpuTracker( 2419): Skipping unknown process pid 7680
W/ProcessCpuTracker( 2419): Skipping unknown process pid 7682
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 7683
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 7237): TAP version 13
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # multiplex can send data
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): ok 1 String should be length:200
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7237): # basic
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 2 sane
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # another
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 3 sane
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 4 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 5 null
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 6 (unnamed assert)
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 7 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 8 should not throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 275s ago
,I/jxcore-log( 7237): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 9 (unnamed assert)
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 10 (unnamed assert)
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 11 should not throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 12 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 13 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,E/Watchdog( 2419): !@Sync 11
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 14 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7986): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7986):  
,I/SELinux ( 7986): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7986):  
I/SELinux ( 7986):  
,I/SELinux ( 7986): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7986): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7986): >>>>> Normal User
,E/dalvikvm( 7986): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7986): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7986): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7986): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7986): Added TimaKesytore provider
,D/dalvikvm( 7986): GC_CONCURRENT freed 3011K, 31% free 9557K/13756K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 7986): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 66670 latestRequest time : 1452019481410 current time : 1452019548080
,I/ActivityManager( 2419): Killing 6450:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/jxcore-log( 7237): # failed to get mobile documents path
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): ok 15 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7237): ok 16 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 17 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 18 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # #init should register the networkChanged event
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 19 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 87535 latestRequest time : 1452019481410 current time : 1452019568945
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 12
,I/jxcore-log( 7237): # #startBroadcasting should throw on null device name
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 20 should throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 21 should throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 22 should throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): ok 23 should throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 117517 latestRequest time : 1452019481410 current time : 1452019598927
,E/Watchdog( 2419): !@Sync 13
,I/jxcore-log( 7237): # #startBroadcasting should throw on negative port
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): ok 24 should throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # #startBroadcasting should throw on too large port
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): ok 25 should throw
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): ok 26 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 27 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 28 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5878): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5878): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5878): Breath 147531 latestRequest time : 1452019481410 current time : 1452019628941
,D/Headlines( 5878): stop 
,D/Headlines( 5878): Breath.onDestroy : 
I/ActivityManager( 2419): Killing 6563:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 14
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7237): ok 29 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 30 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 31 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 32 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 33 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 34 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 35 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7237): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): ok 36 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 37 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 38 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 15
,I/jxcore-log( 7237): ok 39 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 40 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7237): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 41 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 42 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7237): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7237): 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 43 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): ok 44 should be equal
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # setup
I/jxcore-log( 7237): 
,I/jxcore-log( 7237): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7237): 
,E/Watchdog( 2419): !@Sync 16
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/jxcore-log( 7237): # teardown
I/jxcore-log( 7237): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/dalvikvm( 7237): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 7237): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7237): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 7237): Shutting down VM
,W/dalvikvm( 7237): threadid=1: thread exiting with uncaught exception (group=0x41af5c08)
,E/AndroidRuntime( 7237): FATAL EXCEPTION: main
E/AndroidRuntime( 7237): Process: com.test.thalitest, PID: 7237
E/AndroidRuntime( 7237): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7237): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7237): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7237): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7237): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7237): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 7237): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 7237): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7237): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7237): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7237): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7237): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7237): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7237): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7237): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7237): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7237): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2419):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2419): Killing 6575:com.android.musicfx/u0a24 (adj 15): empty #43
,D/CrashAnrDetector( 2419): processName: com.test.thalitest
,D/CrashAnrDetector( 2419): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 7237): Sending signal. PID: 7237 SIG: 9
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager( 2419): Process com.test.thalitest (pid 7237) (adj 9) has died.
,I/WindowState( 2419): WIN DEATH: Window{439d1068 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=20 Removed NainActivit (8/10)
I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1920): id=19 Removed EimLayer (6/9)
,I/SurfaceFlinger( 1920): id=19 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/8)
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/8)
,V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2777): onRestart, Launcher: 1116938088
,D/Launcher( 2777): onStart, Launcher: 1116938088
,D/Launcher.HomeView( 2777): onStart
,I/SurfaceFlinger( 1920): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2419): tr p:2777,o:f
,D/StatusBarManagerService( 2419): semi p:2777,o:f
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7237 uid 10588
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,E/Watchdog( 2419): !@Sync 17
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 18
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 19
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2581): GC_CONCURRENT freed 15768K, 34% free 33829K/50784K, paused 22ms+8ms, total 119ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 20
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 21
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3862K, 72% free 24903K/87016K, paused 20ms+16ms, total 235ms
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/GAV2    ( 5641): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5641): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
V/AlarmManager( 2419): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 25
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4084): GC_CONCURRENT freed 2882K, 30% free 9727K/13800K, paused 18ms+3ms, total 95ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
,D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5548): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3567): Aggregate from 1452018048813 (log), 1452018048813 (data)
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 3879K, 72% free 24893K/87016K, paused 14ms+17ms, total 215ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SPPClientService( 5548): [b] __PingReply__
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2777): GC_CONCURRENT freed 6913K, 38% free 19107K/30680K, paused 8ms+8ms, total 102ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 40
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2419): LightSensor enable = 0
D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4084): GC_CONCURRENT freed 2048K, 30% free 9724K/13800K, paused 4ms+3ms, total 50ms
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3721K, 72% free 24918K/87016K, paused 35ms+24ms, total 300ms
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 50
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5548): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 11804
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 60
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 45ms
,I/ProcessStatsService( 2419): Prepared write state in 31ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2016-01-05-08-59-00.bin
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 3779K, 72% free 24902K/87016K, paused 19ms+16ms, total 231ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
I/ActivityManager( 2419): Killing 6444:com.sec.knox.bridge/1000 (adj 15): empty for 1830s
,I/ActivityManager( 2419): Killing 4871:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1830s
,I/ActivityManager( 2419): Killing 6430:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1830s
,I/ActivityManager( 2419): Killing 6407:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6749:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6735:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 6723:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 6711:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1841s
I/ActivityManager( 2419): Killing 6698:com.samsung.helphub/1000 (adj 15): empty for 1841s
I/ActivityManager( 2419): Killing 6685:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 6672:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1842s
,I/ActivityManager( 2419): Killing 6659:com.sec.android.service.cm/u0a82 (adj 15): empty for 1842s
I/ActivityManager( 2419): Killing 6366:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1842s
,I/ActivityManager( 2419): Killing 5705:com.android.mms/u0a49 (adj 15): empty for 1842s
,I/ActivityManager( 2419): Killing 6633:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1842s
,I/ActivityManager( 2419): Killing 6008:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1843s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2419): Killing 6603:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1843s
,D/CountryDetector( 2419): No listener is left
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/NetworkStats( 2419): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 54ms
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (12241): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12241):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9504K/10740K, paused 4ms+4ms, total 43ms
,I/SELinux (12241): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12241):  
I/SELinux (12241):  
,I/SELinux (12241): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12241): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12241): >>>>> Normal User
,E/dalvikvm(12241): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12241): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9504K/10740K, paused 3ms+4ms, total 35ms
,D/TimaKeyStoreProvider(12241): in addTimaSignatureService
,D/TimaKeyStoreProvider(12241): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12241): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9504K/10740K, paused 2ms+4ms, total 35ms
,D/dalvikvm(12241): GC_CONCURRENT freed 3005K, 31% free 9567K/13760K, paused 3ms+2ms, total 25ms
,D/dalvikvm(12241): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/@ WidgetProvider(12241): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12241): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12241): Widget random data : 2
,D/@ WidgetProvider(12241): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12241): Widget random data : 8
,E/dalvikvm(12241): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(12241): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12241): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12241): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12241): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12241): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12241): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12241): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12241): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12241): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12241): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12241): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12241): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(12241): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12241): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12241): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12241): Thread-672(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12241): Thread-672(ApacheHTTPLog):isShipBuild true
,I/System.out(12241): Thread-672(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12241): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12241): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12241): Max ALLOWED memory (MB): 128
V/ImageManager(12241): Max SHOULD USE memory (MB): 128
,V/ImageManager(12241): Max Image Cache memory (MB): 32
,D/skia    (12241): getTotalSize : Do not get file length
,D/@ WidgetProvider(12241): Building widget : 5
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 67
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 69
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 2030s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
I/ActivityManager( 2419): Killing 6617:com.policydm/1000 (adj 15): empty for 1818s
,I/ActivityManager( 2419): Killing 7357:com.sec.android.soagent/u0a38 (adj 15): empty for 1819s
,I/ActivityManager( 2419): Killing 7283:com.vlingo.midas/u0a34 (adj 15): empty for 1819s
,I/ActivityManager( 2419): Killing 7339:com.samsung.klmsagent/u0a18 (adj 15): empty for 1819s
I/ActivityManager( 2419): Killing 7326:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1819s
,I/ActivityManager( 2419): Killing 5754:com.sec.android.diagmonagent/1000 (adj 15): empty for 1819s
,I/ActivityManager( 2419): Killing 7312:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1819s
I/ActivityManager( 2419): Killing 6591:com.sec.pcw.device/1000 (adj 15): empty for 1819s
,I/ActivityManager( 2419): Killing 2832:com.android.settings/1000 (adj 15): empty for 1819s
,I/ActivityManager( 2419): Killing 7488:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1819s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1800000ms)
```
