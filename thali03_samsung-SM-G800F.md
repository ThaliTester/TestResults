#### Test 5615109319b4771_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/AmoledAdjustTimer( 2419): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4
--------- beginning of /dev/log/main
D/AndroidRuntime( 7374): 
D/AndroidRuntime( 7374): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7374): CheckJNI is OFF
D/AndroidRuntime( 7374): setted country_code = Poland
D/AndroidRuntime( 7374): setted countryiso_code = PL
D/AndroidRuntime( 7374): setted sales_code = PLS
D/AndroidRuntime( 7374): readGMSProperty: start
D/AndroidRuntime( 7374): readGMSProperty: already setted!!
D/AndroidRuntime( 7374): readGMSProperty: end
D/AndroidRuntime( 7374): addProductProperty: start
D/dalvikvm( 7374): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7374): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7374): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7374): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7374): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7374): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7374): failed to load memtrack module: -2
D/dalvikvm( 7374): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7374): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=24 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=25 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7401): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7401):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7374): Shutting down VM
D/dalvikvm( 7374): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7401): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7401):  
I/SELinux ( 7401):  
I/SELinux ( 7401): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7401): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7401): >>>>> Normal User
E/dalvikvm( 7401): >>>>> com.test.thalitest [ userId:0 | appId:10631 ]
E/SELinux ( 7401): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7401): in addTimaSignatureService
D/TimaKeyStoreProvider( 7401): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7401): Added TimaKesytore provider
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4179): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4179): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=20 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=20 Removed Mauncher (-2/10)
D/Launcher( 2773): onTrimMemory. Level: 20
D/dalvikvm( 7401): GC_CONCURRENT freed 3004K, 32% free 9557K/13968K, paused 2ms+2ms, total 18ms
D/dalvikvm( 7401): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7401): Binding Chromium to the background looper Looper (main, tid 1) {429123e8}
I/chromium( 7401): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7401): Initializing chromium process, renderers=0
W/chromium( 7401): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7401): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7401): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7401): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7401): Mali API Version : 401
,I/Mali    ( 7401): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7401): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7401): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7401): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7401): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7401): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7401): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): tr p:7401,o:f
W/dalvikvm( 7401): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7401): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7401): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7401): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7401): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7401): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7401): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7401): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7401): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7401): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7401): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7401): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7401): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2419): semi p:7401,o:f
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1921): id=26 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7401): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7401): Enabling debug mode 0
,W/AwContents( 7401): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7401): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7401): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7401): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x429109d8
,D/dalvikvm( 7401): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x429109d8
,D/jxcore_app_log( 7401): JniHelper::setJavaVM(0x41e5c220), pthread_self() = 2028059704
,D/JX-Cordova( 7401): jxcore cordova android initializing
,D/dalvikvm( 7401): GC_CONCURRENT freed 1274K, 20% free 11354K/14028K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 7401): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 7401): GC_CONCURRENT freed 1718K, 18% free 15188K/18336K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 7401): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7401): GC_FOR_ALLOC freed 5695K, 30% free 16763K/23900K, paused 43ms, total 44ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7401): GC_CONCURRENT freed 6776K, 32% free 18147K/26356K, paused 1ms+10ms, total 65ms
,D/dalvikvm( 7401): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/dalvikvm( 7401): GC_FOR_ALLOC freed 942K, 32% free 18032K/26356K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7401): Grow heap (frag case) to 22.492MB for 3688532-byte allocation
,D/dalvikvm( 7401): GC_FOR_ALLOC freed 2426K, 36% free 19208K/29960K, paused 64ms, total 64ms
,D/dalvikvm( 7401): GC_FOR_ALLOC freed 2269K, 36% free 19198K/29960K, paused 50ms, total 50ms
,W/jxcore-log( 7401): Initializing JXcore engine
,W/jxcore-log( 7401): JXcore engine is ready
,W/jxcore-log( 7401): Starting JXcore engine
,W/jxcore-log( 7401): Platform android
W/jxcore-log( 7401): 
,W/jxcore-log( 7401): Process ARCH arm
W/jxcore-log( 7401): 
,I/jxcore-log( 7401): JXcore Cordova bridge is ready!
I/jxcore-log( 7401): 
,W/jxcore-log( 7401): JXcore engine is started
,I/chromium( 7401): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7401): Toggling radios to true
I/jxcore-log( 7401): 
,D/BluetoothAdapter( 7401): enable(): BT is already enabled..!
,I/WifiManager( 7401): packageName : com.test.thalitest
,I/WifiManager( 7401): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7401, uid=10631
W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7401, uid=10631 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7401, uid=10631 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2419): disconnect: pid=7401, uid=10631
,I/wpa_supplicant( 3978): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7401): Radios toggled
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): My device name is: samsung-SM-G800F
I/jxcore-log( 7401): 
,I/wpa_supplicant( 3978): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3978): First Scan Start
W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3978): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3978): Skip scan - already scanning
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2419): Attempting to switch to mobile
,D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7447): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7447):  
D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,I/SELinux ( 7447): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7447):  
I/SELinux ( 7447):  
,I/SELinux ( 7447): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/SELinux ( 7447): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7447): >>>>> Normal User
,E/dalvikvm( 7447): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7447): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-107ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-106ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
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
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-11ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7447): in addTimaSignatureService,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,D/TimaKeyStoreProvider( 7447): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7447): Added TimaKesytore provider
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x77e913e8 clazz=0x61d00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,V/NativeCrypto( 2848): Read error: ssl=0x7bae8688: I/O error during system call, Connection timed out
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7bae8688: I/O error during system call, Broken pipe
,D/dalvikvm( 7447): GC_CONCURRENT freed 2991K, 32% free 9582K/13976K, paused 3ms+1ms, total 34ms
,D/dalvikvm( 7447): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 340, Delta = 10
,E/SPPClientService( 5594): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5594): [e] exceptionCaught(). NET_TIMEOUT
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,E/SPPClientService( 5594): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
E/SPPClientService( 5594): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5594): [b] ResponseMap empty
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
,I/System.out( 7447): Inside WakeupProvider
,I/System.out( 7447): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7447): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7447): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7447): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2419): updateIfacesLocked()
V/NetworkStats( 2419): performPollLocked(flags=0x1)
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 20ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/dalvikvm( 2419): GC_CONCURRENT freed 4006K, 57% free 25330K/57596K, paused 7ms+14ms, total 171ms
,D/NearbySettings( 4753): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4753): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4753): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4753): MountReceiver.onReceive - Set preference state off
,I/ActivityManager( 2419): Killing 5440:com.google.android.talk/u0a109 (adj 15): empty #43
V/NearbySettings( 4753): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7447): initQueue()
,D/NearbySettings( 4753): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4753): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4753): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4753): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7477): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7477):  
,I/SELinux ( 7477): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7477):  
I/SELinux ( 7477):  
,I/SELinux ( 7477): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7477): >>>>> Normal User
,E/dalvikvm( 7477): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7477): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7477): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7477): Added TimaKesytore provider
,D/dalvikvm( 7477): GC_CONCURRENT freed 3001K, 32% free 9571K/13976K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/dalvikvm( 7477): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7477): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7477): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0000
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
E/dalvikvm( 7477): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0037
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4779): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,W/dalvikvm( 7477): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7477): Link of class 'Ldqp;' failed
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7477): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7477): Link of class 'Ldqp;' failed
I/dalvikvm( 7477): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7477): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7477): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7477): Link of class 'Ldqp;' failed
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7477): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7477): Link of class 'Ldqp;' failed
I/dalvikvm( 7477): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7477): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7477): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7477): Link of class 'Ldqp;' failed
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
I/wpa_supplicant( 3978): nl80211: Received scan results (7 BSSes)
W/dalvikvm( 7477): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7477): Link of class 'Ldqp;' failed
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3978): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/dalvikvm( 7477): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0003
I/wpa_supplicant( 3978): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
W/dalvikvm( 7477): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7477): Link of class 'Lax;' failed
E/dalvikvm( 7477): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7477): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7477): Link of class 'Laz;' failed
E/dalvikvm( 7477): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7477): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 7477): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7477): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 7477): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7477): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7477): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7477): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7477): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7477): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7477): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7477): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7477): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7477): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7477): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7477): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7477): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7477): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7477): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7477): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7477): VFY: replacing opcode 0x1f at 0x000c
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3978): Associated with C0.AA.48
I/wpa_supplicant( 3978): freq(2412) increment count 2
,I/wpa_supplicant( 3978): meet head of list.
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7477): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7477): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7477): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
I/wpa_supplicant( 3978): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3978): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
W/dalvikvm( 7477): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7477): Link of class 'Lax;' failed
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
,W/dalvikvm( 7477): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7477): Link of class 'Laz;' failed
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7477): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4290c808
,D/dalvikvm( 7477): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4290c808
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/dalvikvm( 7477): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
,W/dalvikvm( 7477): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7477): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7477): MmsConfig.loadMmsSettings
I/Babel_SMS( 7477): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7477): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7477): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7477): MmsConfig.loadFromResources
E/Babel_SMS( 7477): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7477): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7477): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7477): Link of class 'Lfzc;' failed
E/dalvikvm( 7477): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7477): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7477): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7477): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
D/dalvikvm( 7477): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7477): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7477): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7477): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7477): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7477): Link of class 'Lfzc;' failed
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/dalvikvm( 7477): GC_CONCURRENT freed 1757K, 23% free 10887K/14044K, paused 3ms+2ms, total 32ms
D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 11ms
,W/Settings( 7477): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7477): startup - clean
,I/Babel   ( 7477): deleted: false for 0
I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7477): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7477): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7477): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7477): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7477): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7477): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7477): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): noConnectivity : true
,I/dalvikvm( 7477): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0074
,I/vclib   ( 7477): onServiceConnected
,W/Babel   ( 7477): Attempted to change video mute state without an active call.
I/ActivityManager( 2419): Killing 6360:com.sec.phone/1001 (adj 15): empty #43
,I/dhcpcd  ( 7500): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7500): bssid match
,I/SELinux ( 7509): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7509):  
,I/SELinux ( 7509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7509):  
I/SELinux ( 7509):  
,I/SELinux ( 7509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7509): >>>>> Normal User
,E/dalvikvm( 7509): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 7477): GC_CONCURRENT freed 1006K, 17% free 11905K/14324K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/TimaKeyStoreProvider( 7509): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7509): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7509): Added TimaKesytore provider
,D/dalvikvm( 7477): GC_FOR_ALLOC freed 488K, 18% free 12399K/15092K, paused 24ms, total 24ms
,D/dalvikvm( 7509): GC_CONCURRENT freed 2999K, 32% free 9574K/13976K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7509): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7477): GC_FOR_ALLOC freed 1759K, 24% free 12769K/16676K, paused 28ms, total 29ms
,I/ActivityManager( 2419): Killing 6429:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7521):  
,I/SELinux ( 7521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7521):  
I/SELinux ( 7521):  
,I/SELinux ( 7521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7521): >>>>> Normal User
,E/dalvikvm( 7521): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7521): in addTimaSignatureService
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7521): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7521): Added TimaKesytore provider
,D/dalvikvm( 7521): GC_CONCURRENT freed 3009K, 32% free 9567K/13976K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/KLMS-2.3.201 : ( 7521): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7521): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453045036711
,I/KLMS-2.3.201 : ( 7521): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6247:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 7533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7533):  
,I/SELinux ( 7533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7533):  
I/SELinux ( 7533):  
,I/SELinux ( 7533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7533): >>>>> Normal User
,E/dalvikvm( 7533): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7533): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7533): Added TimaKesytore provider
,D/dalvikvm( 7533): GC_CONCURRENT freed 3013K, 32% free 9560K/13976K, paused 1ms+1ms, total 19ms
,D/dalvikvm( 7533): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/SO_AGENT( 7533): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7533): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5879): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5879): [BDLM] already registered in spp
I/SA      ( 5879): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5879): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5879): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5879): [OR] == isSIMCardReady false ==
I/SA      ( 5879): [SCU] == networkStateCheck == false
,I/SA      ( 5879): [OR] onReceive END
I/ActivityManager( 2419): Killing 6042:com.android.calendar/u0a144 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2750): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2750): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6631): Other Intent
,I/SELinux ( 7545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7545):  
,I/SELinux ( 7545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7545):  
I/SELinux ( 7545):  
,I/SELinux ( 7545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7545): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7545): >>>>> Normal User
,E/dalvikvm( 7545): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7545): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7545): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7545): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7545): Added TimaKesytore provider
,D/dalvikvm( 7545): GC_CONCURRENT freed 2999K, 32% free 9576K/13976K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7545): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7545): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7545): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5386): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7545): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5386): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7545): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5386): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6398:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/Headlines( 5947): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5947): getCountryCode(): countryCode = PL
D/Headlines( 5947): Breath.onCreate
,D/Headlines( 5947): Breath timer started. interval : 30000
,I/SELinux ( 7557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7557):  
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5947): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5947): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5947): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2419): waitForAlarm result :8
,I/SELinux ( 7557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7557):  
I/SELinux ( 7557):  
,I/SELinux ( 7557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7557): >>>>> Normal User
,E/dalvikvm( 7557): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7557): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7557): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7557): Added TimaKesytore provider
,D/dalvikvm( 7557): GC_CONCURRENT freed 2996K, 32% free 9573K/13976K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 23ms
,V/WebViewChromium( 7557): Binding Chromium to the background looper Looper (main, tid 1) {42918dd8},
,I/chromium( 7557): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7557): Initializing chromium process, renderers=0,
,W/chromium( 7557): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7557): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7557): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7557): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7557): Mali API Version : 401
,I/Mali    ( 7557): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7557): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 7557): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2419): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/NSApplication( 7557): Starting up...
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/iu.Environment( 5607): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 28ms
D/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5184): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42910148
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux ( 7631): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7631):  
,I/SELinux ( 7631): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7631):  
I/SELinux ( 7631):  
,I/SELinux ( 7631): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7631): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7631): >>>>> Normal User
E/dalvikvm( 7631): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7631): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7631): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7631): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7631): Added TimaKesytore provider
,D/dalvikvm( 7631): GC_CONCURRENT freed 3010K, 32% free 9566K/13976K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7631): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7650): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7650):  
,I/ActivityManager( 2419): Killing 6212:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9504K/10952K, paused 3ms+3ms, total 32ms
,I/SELinux ( 7650): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7650):  
I/SELinux ( 7650):  
,I/SELinux ( 7650): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7650): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7650): >>>>> Normal User
,E/dalvikvm( 7650): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7650): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10952K, paused 2ms+3ms, total 24ms
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10952K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7650): in addTimaSignatureService
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,D/TimaKeyStoreProvider( 7650): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7650): Added TimaKesytore provider
,I/DBG_DM  ( 4779): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 7662): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7662):  
,I/ActivityManager( 2419): Killing 6342:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7662): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7662):  
I/SELinux ( 7662):  
,I/SELinux ( 7662): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7662): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7662): >>>>> Normal User
,E/dalvikvm( 7662): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7662): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7662): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7662): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7662): Added TimaKesytore provider
,D/dalvikvm( 7650): GC_CONCURRENT freed 2997K, 32% free 9574K/13972K, paused 4ms+3ms, total 37ms
,D/dalvikvm( 7650): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/BadgeProvider( 7650): onCreate
,D/BadgeProvider( 7650): DatabaseHelper
,D/BadgeProvider( 7650): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/AmoledAdjustTimer( 2419): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
,D/BadgeProvider( 7650): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7650): sendNotify, [notify] : null
D/BadgeProvider( 7650): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7650): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7650): update, [UpdateCount] : 1
,D/Launcher.Model( 2773): reloadBadges entered.
,D/dalvikvm( 7662): GC_CONCURRENT freed 2990K, 32% free 9578K/13972K, paused 3ms+4ms, total 44ms
,D/dalvikvm( 7662): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/WaitQueueForNetworkActivate( 6897): notifyNetworkActivated
,W/ContextImpl( 6897): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2419): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7477): Thread-662(HTTPLog):isShipBuild true
,I/System.out( 7477): Thread-662(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Babel   ( 7477): connection state changed from UNKNOWN to CONNECTED
,D/hcjo    ( 6897): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6897): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6897): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6897): VFY: replacing opcode 0x6e at 0x0024
,E/SPPClientService( 5594): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [SystemStateMoniter] Current Time : 331500
,E/SPPClientService( 5594): [SystemStateMoniter] No Connect : true
,D/InitializeManagerStateMachine( 6897): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6897): exit::IDLE
,D/InitializeManagerStateMachine( 6897): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6897): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6897): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6897): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6897): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6897): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6897): entry::SUCCESS
,D/hcjo    ( 6897): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6897): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6897): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/SPPClientService( 5594): [[SystemStateMonitorService]] No Active Internet
D/InitializeManagerStateMachine( 6897): exit::SUCCESS
,D/InitializeManagerStateMachine( 6897): entry::IDLE
,D/NearbySettings( 4753): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4753): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4753): MountReceiver.onReceive - Keep current state
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
I/ActivityManager( 2419): Killing 6529:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 1951 latestRequest time : 1453045037210 current time : 1453045039161
E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4753): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4753): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5594): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 4753): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4753): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4753): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4753): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1921): id=27 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
D/NearbySettings( 4753): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 4753): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 7521): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7521): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453045039587
,I/KLMS-2.3.201 : ( 7521): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/SO_AGENT( 7533): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3470): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7533): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3470): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3470): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3470): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3598): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7690): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7690):  
,I/SA      ( 5879): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5879): [BDLM] already registered in spp
,I/SA      ( 5879): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5879): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5879): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5879): [OR] == isSIMCardReady false ==
,I/SA      ( 5879): [SCU] == networkStateCheck == true
I/SA      ( 5879): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5879): isChinaCountryCode : false
,I/SA      ( 5879): [OR] == networkStateCheck true ==
,I/SA      ( 5879): [OR] GetMyCountryZoneTask
,I/SA      ( 5879): [OR] onReceive END
,I/SA      ( 5879): [SRS] prepareGetMyCountryZone
,I/SA      ( 5879): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5879): [SSP] query invoked
,I/SELinux ( 7690): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7690):  
I/SELinux ( 7690):  
,I/SELinux ( 7690): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7690): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7690): >>>>> Normal User
,E/dalvikvm( 7690): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
D/PhoneNumberLocatorBootCompletedReceiver( 2750): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2750): Phone number locator feature is dsiabled
,E/SELinux ( 7690): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SCloudBackupReceiver( 6631): Other Intent
,D/TimaKeyStoreProvider( 7690): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7690): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7690): Added TimaKesytore provider
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/dalvikvm( 7690): GC_CONCURRENT freed 3000K, 32% free 9568K/13968K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 7690): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/System.out( 7509): Thread-654(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7545): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5947): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,I/System.out( 7509): Thread-654(ApacheHTTPLog):isShipBuild true
,I/System.out( 7509): Thread-654(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/KVNProvider( 7690): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,V/KVNProvider( 7690): getFindoCursor query string : 
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,D/HeadlinesChannelUtil( 5947): getCountryCode(): countryCode = PL
,V/KVNProvider( 7690): getTagSearchCursor() tagSearchCursor count : 0
D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5947): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5947): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5947): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 5879): [TPMU] GetMccFromDB : null
I/SA      ( 5879): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5879): [TPM] isNoProxy(default) : true
,I/SA      ( 5879): [RC New] Execute method=[GET] start
,I/iu.Environment( 5607): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5184): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42910148
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/hcjo    ( 6897): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6897): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6897): exit::IDLE
,D/InitializeManagerStateMachine( 6897): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6897): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6897): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6897): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6897): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6897): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6897): entry::SUCCESS
,D/hcjo    ( 6897): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6897): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6897): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6897): exit::SUCCESS
,D/InitializeManagerStateMachine( 6897): entry::IDLE
,I/System.out( 7509): AsyncTask #1 calls detatch()
,E/SPPClientService( 5594): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [SystemStateMoniter] Current Time : 332614
,E/SPPClientService( 5594): [SystemStateMoniter] No Connect : false
,W/System.err( 7509): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7509): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7509): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7509): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7509): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7509): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7509): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7509): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7509): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7509): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7509): Caused by: java.lang.NullPointerException
W/System.err( 7509): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7509): ,	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7509): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7509): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7509): 	... 8 more
,D/dalvikvm( 5594): GC_CONCURRENT freed 1992K, 26% free 10454K/13956K, paused 7ms+4ms, total 53ms
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5879): [RC New] [v2liruge] api execute + 741
,I/SA      ( 5879): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5879): AsyncTask #2 calls detatch()
,I/SA      ( 5879): [TPMU] getNetworkMcc : 
,I/SA      ( 5879): [SCU] saveMccToPreferece Start
I/SA      ( 5879): [SCU] RegionMCC : 260
,I/SA      ( 5879): [SSP] query invoked
,I/SA      ( 5879): [TPMU] GetMccFromDB : null
I/SA      ( 5879): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5879): [SCU] saveMccToPreferece End
I/SA      ( 5879): [RC New] executeRequest [v2liruge] end. 761
I/SA      ( 5879): [RC New] Execute end
,I/SA      ( 5879): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5879): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7401): 
,E/SPPClientService( 5594): [b] __InitReply__
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7401): 
,I/GAV2    ( 7557): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7401): Test app app.js loaded
I/jxcore-log( 7401): 
,I/chromium( 7401): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger( 1921): id=27 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=27 Removed Uoast (-2/11)
I/ActivityManager( 2419): Killing 6673:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 335171
D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3473)
,I/jxcore-log( 7401): --= Surplus to requirements =--
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): ****TEST TOOK:  ms ****
I/jxcore-log( 7401): 
,I/jxcore-log( 7401): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7401): 
,D/AndroidRuntime( 7720): 
D/AndroidRuntime( 7720): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7720): CheckJNI is OFF
,D/AndroidRuntime( 7720): setted country_code = Poland
,D/AndroidRuntime( 7720): setted countryiso_code = PL
D/AndroidRuntime( 7720): setted sales_code = PLS
D/AndroidRuntime( 7720): readGMSProperty: start
,D/AndroidRuntime( 7720): readGMSProperty: already setted!!
D/AndroidRuntime( 7720): readGMSProperty: end
,D/AndroidRuntime( 7720): addProductProperty: start
,D/dalvikvm( 7720): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7720): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7720): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7720): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7720): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7720): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7720): failed to load memtrack module: -2
,D/dalvikvm( 7720): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7720): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2419): START PACKAGE DELETE: observer{1158223912}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
,D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2419): deletePackageX- pkg:com.test.thalitest, userId:0
,D/PackageManager( 2419): !@killApplicatoin: 10631, uninstall pkg
,I/ActivityManager( 2419): Killing 7401:com.test.thalitest/u0a631 (adj 0): stop com.test.thalitest
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1921): id=25 Removed EimLayer (5/10)
,I/SurfaceFlinger( 1921): id=25 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1921): id=24 Removed EimLayer (4/9)
I/SurfaceFlinger( 1921): id=24 Removed EimLayer (-2/9)
,I/WindowState( 2419): WIN DEATH: Window{451879b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=26 Removed NainActivit (6/8)
I/SurfaceFlinger( 1921): id=26 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 1921): id=26 Removed NainActivit (-2/8)
V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2773): onRestart, Launcher: 1120800944
D/Launcher( 2773): onStart, Launcher: 1120800944
,D/Launcher.HomeView( 2773): onStart
,I/SurfaceFlinger( 1921): id=28 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2419): tr p:2773,o:f
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): semi p:2773,o:f
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7401 uid 10631
,W/PackageSettings( 2419): Skipping PackageSetting{43088d60 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2419): checkUidPermission - Execution time: 168 ms
,D/PackageManager( 2419): checkUidPermission - Execution time: 123 ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10631, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6699): [hasSamungAccount] - No Samsung Account
,D/dalvikvm( 6866): GC_EXPLICIT freed 162K, 30% free 9960K/14216K, paused 5ms+6ms, total 99ms
,D/dalvikvm( 6510): GC_EXPLICIT freed 573K, 29% free 9986K/13960K, paused 59ms+5ms, total 123ms
,D/dalvikvm( 2951): GC_EXPLICIT freed 1470K, 29% free 10035K/13972K, paused 11ms+7ms, total 114ms
,D/PackageManager( 2419): queryIntentReceivers - Execution time: 109 ms
,D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10631, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,E/SamsungIME( 2990): mOCRHelper is null
I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.PACKAGE_REMOVED
,I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 2733): Ignoring removeGeofence because network location is disabled.
,D/QuickConnect[1.1][2] ( 5184): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,D/dalvikvm( 3273): GC_EXPLICIT freed 1784K, 22% free 12464K/15804K, paused 10ms+29ms, total 232ms
,I/SELinux ( 7735): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7735):  
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7735): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7735):  
I/SELinux ( 7735):  
,I/SELinux ( 7735): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7735): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7735): >>>>> Normal User
,E/dalvikvm( 7735): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7735): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7735): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7735): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7735): Added TimaKesytore provider
,D/dalvikvm( 2419): GC_EXPLICIT freed 3093K, 56% free 25533K/57596K, paused 16ms+27ms, total 334ms
,D/PackageManager( 2419): queryIntentReceivers - Execution time: 123 ms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6699): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6699): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6699): GetString : secure API is not supported!!
,D/RCPManagerService( 2419): PackageReceiver onReceive()
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/HarmonyEASService( 2419): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6699): [ensureRegistration] - No Samsung account
,D/RegisteredServicesCache( 2755): empty dynamic service
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7735): GC_CONCURRENT freed 2998K, 32% free 9567K/13968K, paused 4ms+3ms, total 46ms
,D/dalvikvm( 7735): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
,D/elm:14132( 7735): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7735): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7735): MDMBridge.setEnterpriseBridge()
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
,D/elm:14132( 7735): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7735): ElmAgentService : onCreate()
,D/elm:14132( 7735): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7735): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7735): MDMBridge.getInstance()
,D/elm:14132( 7735): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7751): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7751):  
D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = 10
,D/elm:14132( 7735): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7751): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7751):  
I/SELinux ( 7751):  
I/SELinux ( 7751): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7751): >>>>> Normal User
,E/dalvikvm( 7751): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/EnterpriseDeviceManagerService( 2419): Package has changed for user 0
,D/TimaKeyStoreProvider( 7751): in addTimaSignatureService
D/dalvikvm( 2755): GC_CONCURRENT freed 1216K, 29% free 10607K/14864K, paused 15ms+3ms, total 134ms
,D/dalvikvm( 2755): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/TimaKeyStoreProvider( 7751): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7751): Added TimaKesytore provider
,D/elm:14132( 7735): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7735): ElmAgentService : onDestroy().
I/ActivityManager( 2419): Killing 6685:com.android.musicfx/u0a24 (adj 15): empty #43
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7751): GC_CONCURRENT freed 3002K, 32% free 9570K/13972K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 7751): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2419): GC_EXPLICIT freed 1202K, 56% free 25475K/57596K, paused 13ms+29ms, total 511ms
D/PackageManager( 2419): delete sourFile : 
,D/BackupManagerService( 2419): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2419): removePackageParticipantsLocked: uid=10631 #1
,D/PackageManager( 2419): delete native library directory: 
D/PackageManager( 2419): return delete result to caller: 1158223912
,D/AndroidRuntime( 7720): Shutting down VM
D/PackageManager( 2419): returnCode: 1
,D/dalvikvm( 7720): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 4ms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Scheme: "smsto"
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7770): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7770):  
I/ActivityManager( 2419): Killing 6713:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7770): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7770):  
I/SELinux ( 7770):  
,I/SELinux ( 7770): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7770): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7770): >>>>> Normal User
,E/dalvikvm( 7770): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7770): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7770): in addTimaSignatureService
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7770): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7770): Added TimaKesytore provider
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 7770): GC_CONCURRENT freed 2999K, 32% free 9569K/13972K, paused 5ms+2ms, total 35ms
,D/dalvikvm( 7770): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7783): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7783):  
,I/ActivityManager( 2419): Killing 6057:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ApplicationsProvider( 2951): Could not fetch usage stats
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
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 7783): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7783):  
I/SELinux ( 7783):  
,I/SELinux ( 7783): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 7783): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7783): >>>>> Normal User
,E/dalvikvm( 7783): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 7783): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2419): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2419): clearDefaults: com.test.thalitest
,D/TimaKeyStoreProvider( 7783): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7783): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7783): Added TimaKesytore provider
,W/AtomicFile( 2419): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2419): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/dalvikvm( 7783): GC_CONCURRENT freed 3009K, 32% free 9560K/13972K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7783): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SELinux ( 7798): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7798):  
,I/SELinux ( 7798): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7798):  
I/SELinux ( 7798):  
,I/SELinux ( 7798): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7798): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/ActivityManager( 2419): Killing 6743:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
E/dalvikvm( 7798): >>>>> Normal User
E/dalvikvm( 7798): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux ( 7798): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7798): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7798): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7798): Added TimaKesytore provider
,D/dalvikvm( 7798): GC_CONCURRENT freed 3006K, 32% free 9564K/13972K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7798): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/System.err( 7798): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 7798): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 7798): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 7798): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
,W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 7798): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 7798): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 7798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 7798): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 7798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7798): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7798): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7798): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7798): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7798): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 7798): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 7798): 	at libcore.io.Posix.open(Native Method)
W/System.err( 7798): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 7798): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 7798): 	... 21 more
,D/GalaxyFinderApplication( 7798): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 7798): [Slink platform] use state of slink location service is [false] to [true]
,I/SELinux ( 7812): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7812):  
I/ActivityManager( 2419): Killing 6443:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 7812): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7812):  
I/SELinux ( 7812):  
,I/SELinux ( 7812): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7812): >>>>> Normal User
,E/dalvikvm( 7812): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7812): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7812): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7812): Added TimaKesytore provider
,D/dalvikvm( 7812): GC_CONCURRENT freed 2993K, 32% free 9570K/13968K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7812): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/ContextImpl( 7812): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,E/Device Type Shared Preferences( 7812): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 7812): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7812): ContentProvider is not null
,W/ResourceType( 7812): No package identifier when getting value for resource number 0x00000000
,I/System.out( 7812): resource Id::2131361807
,E/SQLiteDatabase( 7812): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase( 7812): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7812): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7812): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase( 7812): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase( 7812): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 7812): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 7812): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 7812): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase( 7812): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase( 7812): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7812): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7812): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7812): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7812): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7812): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase,( 7812): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7812): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7812): Shutting down VM
W/dalvikvm( 7812): threadid=1: thread exiting with uncaught exception (group=0x41e6fc08)
E/AndroidRuntime( 7812): FATAL EXCEPTION: main
E/AndroidRuntime( 7812): Process: com.sec.android.app.shealth, PID: 7812
E/AndroidRuntime( 7812): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7812): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7812): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7812): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7812): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7812): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7812): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7812): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7812): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7812): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7812): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime( 7812): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime( 7812): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime( 7812): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime( 7812): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime( 7812): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime( 7812): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime( 7812): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime( 7812): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime( 7812): 	... 10 more
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
I/SELinux ( 7832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7832):  
I/Process ( 7812): Sending signal. PID: 7812 SIG: 9
,I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 7812) (adj 0) has died.
,I/SELinux ( 7832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7832):  
I/SELinux ( 7832):  
,I/SELinux ( 7832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7832): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7832): >>>>> Normal User
,E/dalvikvm( 7832): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
,E/SELinux ( 7832): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7832): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7832): Added TimaKesytore provider
,D/dalvikvm( 7832): GC_CONCURRENT freed 2997K, 32% free 9571K/13972K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7832): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/SQLiteDatabase( 7832): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
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
E/SQLiteDatabase( 7832): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
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
,W/dalvikvm( 7832): threadid=1: thread exiting with uncaught exception (group=0x41e6fc08)
E/AndroidRuntime( 7832): FATAL EXCEPTION: main
E/AndroidRuntime( 7832): Process: com.samsung.android.sdk.samsunglink, PID: 7832
E/AndroidRuntime( 7832): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime( 7832): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime( 7832): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7832): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7832): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7832): 	... 12 more
,I/Process ( 7832): Sending signal. PID: 7832 SIG: 9
,I/SA      ( 5879): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,E/DropBoxManagerService( 2419): Can't write: system_app_crash,
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	,at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/SA      ( 5879): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ],
I/ActivityManager( 2419): Killing 6769:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/ActivityManager( 2419): Process com.samsung.android.sdk.samsunglink (pid 7832) (adj 9) has died.,
,E/SharedPreferencesImpl( 3598): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak,
,I/Icing.InternalIcingCorporaProvider( 6510): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 6510): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6510): threadid=15: thread exiting with uncaught exception (group=0x41e6fc08)
,I/SELinux ( 7849): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7849):  
E/AndroidRuntime( 6510): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6510): Process: com.google.android.googlequicksearchbox:search, PID: 6510
E/AndroidRuntime( 6510): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6510): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6510): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6510): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6510): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6510): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6510): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6510): Sending signal. PID: 6510 SIG: 9
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
,I/ActivityManager( 2419): Process com.google.android.googlequicksearchbox:search (pid 6510) (adj 5) has died.
,I/SELinux ( 7849): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7849):  
I/SELinux ( 7849):  
,I/SELinux ( 7849): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7849): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7849): >>>>> Normal User
,E/dalvikvm( 7849): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7849): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7849): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7849): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7849): Added TimaKesytore provider
,D/dalvikvm( 7849): GC_CONCURRENT freed 3000K, 32% free 9571K/13976K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7849): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/UserAnalysis.PlaceProvider( 7849): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7849): Create SecureDbHelper
,E/SQLiteDatabase( 7849): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7849): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7849): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7849): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7849): Opened privacy in read-only mode
,E/SQLiteDatabase( 7849): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7849): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7849): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7849): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7849): Opened privacy in read-only mode
,E/SQLiteDatabase( 7849): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7849): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteData,base.java:696)
W/System.err( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7849): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7849): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7849): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 7862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7862):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 14% free 9504K/10952K, paused 3ms+4ms, total 36ms
,I/SELinux ( 7862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7862):  
I/SELinux ( 7862):  
,I/SELinux ( 7862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7862): >>>>> Normal User
,E/dalvikvm( 7862): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 7862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10952K, paused 3ms+4ms, total 29ms
,D/TimaKeyStoreProvider( 7862): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7862): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10952K, paused 3ms+4ms, total 30ms
,D/dalvikvm( 7862): GC_CONCURRENT freed 3021K, 32% free 9551K/13976K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 7862): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/ContextImpl( 7862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 6524):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2419):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2419): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteDatabase( 7862): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 7862): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512),
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859),
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7862): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7862): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteDatabase( 7862): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7862): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 7862): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 7862): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7862): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/SQLiteDatabase( 7862): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7862): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 7862): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7862): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
,W/System.err( 7862): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7862): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7862): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7862): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
,W/System.err( 7862): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7862): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
,W/System.err( 7862): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7862): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7862): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7862): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 7862): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
,W/System.err( 7862): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 7862): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7862): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 7862): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7875): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7875):  
I/ActivityManager( 2419): Killing 6786:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,I/SELinux ( 7875): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7875):  
I/SELinux ( 7875):  
,I/SELinux ( 7875): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7875): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7875): >>>>> Normal User
,E/dalvikvm( 7875): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ],
,E/SELinux ( 7875): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
,D/TimaKeyStoreProvider( 7875): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7875): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7875): Added TimaKesytore provider
,D/dalvikvm( 7875): GC_CONCURRENT freed 3014K, 32% free 9561K/13976K, paused 2ms+2ms, total 24ms,
,D/dalvikvm( 7875): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/CapabilityManagerService New( 7875): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 7875): The package(com.test.thalitest) removed
,W/System.err( 2419): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409),
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2419): ,	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2419): ,	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2419): 	at android.os.Binder.execTransact(Binder.java:404),
W/System.err( 2419): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2419): ,	at libcore.io.Posix.open(Native Method)
W/System.err( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393),
W/System.err( 2419): 	... 8 more
W/System.err( 2419): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2419): 	,at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2419): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2419): ,	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,W/System.err( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2419): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2419): ,	... 8 more
,I/SELinux ( 7887): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7887):  
I/ActivityManager( 2419): Killing 6802:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,I/SELinux ( 7887): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7887):  
I/SELinux ( 7887):  
,I/SELinux ( 7887): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7887): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 7887): >>>>> Normal User
,E/dalvikvm( 7887): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ],
,E/SELinux ( 7887): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7887): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7887): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7887): Added TimaKesytore provider
,D/dalvikvm( 7887): GC_CONCURRENT freed 3001K, 32% free 9571K/13976K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 7887): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7899): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7899):  
I/ActivityManager( 2419): Killing 6815:com.samsung.helphub/1000 (adj 15): empty #43
,I/SELinux ( 7899): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7899):  
I/SELinux ( 7899):  
,I/SELinux ( 7899): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7899): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7899): >>>>> Normal User
,E/dalvikvm( 7899): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
,E/SELinux ( 7899): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7899): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7899): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7899): Added TimaKesytore provider
,D/dalvikvm( 7899): GC_CONCURRENT freed 2998K, 32% free 9576K/13976K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7899): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/MagazineService Version( 7899): Magazine-Channel: 13
,D/MagazineService Version( 7899): Magazine-Provider: 13
,D/MagazineService Version( 7899): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 7899): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7899): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 7899): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteDatabase( 7899): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
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
E/SQLiteDatabase( 7899): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 7899): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 7899): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 7899): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 7899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7899): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7899): threadid=10: thread exiting with uncaught exception (group=0x41e6fc08)
,I/SELinux ( 7912): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7912):  
E/AndroidRuntime( 7899): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 7899): Process: com.samsung.android.magazine.service, PID: 7899
E/AndroidRuntime( 7899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime( 7899): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 7899): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 7899): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 7899): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 7899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7899): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7916): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7916):  
,I/Process ( 7899): Sending signal. PID: 7899 SIG: 9
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
,I/ActivityManager( 2419): Process com.samsung.android.magazine.service (pid 7899) (adj 5) has died.
,I/SELinux ( 7912): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7912):  
I/SELinux ( 7912):  
,I/SELinux ( 7912): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7912): >>>>> Normal User
,E/dalvikvm( 7912): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 7912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7916): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7916):  
I/SELinux ( 7916):  
,I/SELinux ( 7916): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7916): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7916): >>>>> Normal User
,E/dalvikvm( 7916): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7916): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7912): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7912): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7912): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7916): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7916): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7916): Added TimaKesytore provider
,D/dalvikvm( 7912): GC_CONCURRENT freed 3024K, 32% free 9547K/13972K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7912): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SQLiteDatabase( 7912): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 7912): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7912): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7912): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7912): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7912): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 7912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7912): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7912): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7912): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7912): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7912): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7912): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7912): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7912): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 7912): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7912): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7912): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7912): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7912): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 7912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 7912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 7912): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteOpenHelper( 7912): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteOpenHelper( 7912): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteOpenHelper( 7912): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteOpenHelper( 7912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteOpenHelper( 7912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7912): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7912): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7912): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7912): Opened search.db in read-only mode
,I/SELinux ( 7937): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7937):  
D/dalvikvm( 7916): GC_CONCURRENT freed 2981K, 32% free 9588K/13972K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7916): WAIT_FOR_CONCURRENT_GC blocked 25ms,
I/ActivityManager( 2419): Killing 6828:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,I/Icing.InternalIcingCorporaProvider( 7916): Updating corpora: A: com.test.thalitest, C: MAYBE,
I/SELinux ( 7937): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7937):  
I/SELinux ( 7937):  
,I/SELinux ( 7937): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7937): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7937): >>>>> Normal User
,E/dalvikvm( 7937): >>>>> com.android.keychain [ userId:0 | appId:1000 ],
,E/SELinux ( 7937): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7937): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7937): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7937): Added TimaKesytore provider
,I/SELinux ( 7953): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7953):  
,D/LocationManagerService( 2419): getProviders()=[passive]
,I/SELinux ( 7953): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7953):  
I/SELinux ( 7953):  
,I/SELinux ( 7953): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7953): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7953): >>>>> Normal User
,E/dalvikvm( 7953): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7953): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 7937): GC_CONCURRENT freed 3008K, 32% free 9567K/13976K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7937): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/TimaKeyStoreProvider( 7953): in addTimaSignatureService
,W/ContextImpl( 7937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
D/TimaKeyStoreProvider( 7953): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7953): Added TimaKesytore provider
,E/SQLiteDatabase( 7937): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.,
E/SQLiteDatabase( 7937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696),
E/SQLiteDatabase( 7937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7937): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7937): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
E/SQLiteDatabase( 7937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7937): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 7937): threadid=10: thread exiting with uncaught exception (group=0x41e6fc08)
,I/SELinux ( 7970): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7970):  
,E/AndroidRuntime( 7937): FATAL EXCEPTION: IntentService[KeyChainService],
E/AndroidRuntime( 7937): Process: com.android.keychain, PID: 7937
E/AndroidRuntime( 7937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
,E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7937): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7937): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
,E/AndroidRuntime( 7937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7937): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Process ( 7937): Sending signal. PID: 7937 SIG: 9,
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
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
I/SELinux ( 7970): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7970):  
I/SELinux ( 7970):  
I/SELinux ( 7970): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7970): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7970): >>>>> Normal User
E/dalvikvm( 7970): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
E/SELinux ( 7970): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/ActivityManager( 2419): Process com.android.keychain (pid 7937) (adj 5) has died.
D/dalvikvm( 5607): GC_CONCURRENT freed 570K, 8% free 26824K/28860K, paused 3ms+4ms, total 61ms
,D/dalvikvm( 5607): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
,D/TimaKeyStoreProvider( 7970): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7970): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7970): Added TimaKesytore provider
D/dalvikvm( 7953): GC_CONCURRENT freed 3007K, 32% free 9569K/13976K, paused 4ms+2ms, total 44ms
,D/dalvikvm( 7953): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 2419): Killing 6840:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/dalvikvm( 7970): GC_CONCURRENT freed 3000K, 32% free 9571K/13976K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7970): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/KidsModeInstallReceiver( 7970): onReceive intent data =  package:com.test.thalitest
D/AmoledAdjustTimer( 2419): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4
,D/KidsPlatformStub( 7970): Package not found : com.sec.android.app.kidshome
,E/SharedPreferencesImpl( 3273): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 3273): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/SELinux ( 7989): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7989):  
I/ActivityManager( 2419): Killing 6852:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,E/SharedPreferencesImpl( 3273): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 3273): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 3273): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/SELinux ( 7989): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7989):  
I/SELinux ( 7989):  
,I/SELinux ( 7989): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7989): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7989): >>>>> Normal User
,E/dalvikvm( 7989): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]

```
