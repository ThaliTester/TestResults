#### Test 506502789b39735_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1013): sending alarm Alarm{428007c8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4134): 
D/AndroidRuntime( 4134): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4134): CheckJNI is OFF
D/dalvikvm( 4134): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4134): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4134): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4134): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4134): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4134): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4134): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4134): failed to load memtrack module: -2
D/AndroidRuntime( 4134): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1013): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4134
W/WindowManager( 1013): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1013): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4150 uid=10482 gids={50482, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4134): Shutting down VM
D/dalvikvm( 4134): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 4ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4150): Binding Chromium to main looper Looper (main, tid 1) {41ff0808}
I/LibraryLoader( 4150): Expected native library version number "",actual native library version number ""
I/chromium( 4150): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4150): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1013): Message: 20
D/BluetoothManagerService( 1013): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42989ad0:true
I/Adreno-EGL( 4150): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4150): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4150): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4150): Local Branch: 
I/Adreno-EGL( 4150): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4150): Local Patches: NONE
I/Adreno-EGL( 4150): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4150): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4150): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4150): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4150): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4150): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4150): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4150): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4150): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4150): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4150): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4150): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4150): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4150): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4150): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4150): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4150): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4150): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4150): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4150): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4150): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4150): Enabling debug mode 0
,W/AwContents( 4150): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4150): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1013): Displayed com.test.thalitest/.MainActivity,cp,ca,419
I/ActivityManager( 1013): Displayed com.test.thalitest/.MainActivity: +395ms (total +420ms)
,D/JsMessageQueue( 4150): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4150): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41ff54d8
,D/dalvikvm( 4150): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41ff54d8
,D/jxcore_app_log( 4150): JniHelper::setJavaVM(0x4164cf78), pthread_self() = 1614724424
,D/JX-Cordova( 4150): jxcore cordova android initializing
,D/dalvikvm( 4150): GC_CONCURRENT freed 2778K, 17% free 14375K/17224K, paused 2ms+2ms, total 53ms
,D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 134K, 17% free 14357K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 304K, 17% free 14422K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 16.254MB for 144892-byte allocation
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 268K, 17% free 14459K/17368K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 16.360MB for 217334-byte allocation
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 369K, 18% free 14533K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 16.536MB for 325996-byte allocation
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 572K, 19% free 14655K/17904K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 16.810MB for 488990-byte allocation
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 871K, 20% free 14831K/18384K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 17.215MB for 733480-byte allocation
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 1292K, 22% free 15089K/19104K, paused 27ms, total 28ms
,D/dalvikvm( 4150): GC_CONCURRENT freed 1677K, 20% free 15460K/19104K, paused 1ms+3ms, total 39ms
,D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 382K, 20% free 15419K/19104K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 18.664MB for 1650320-byte allocation
,D/dalvikvm( 4150): GC_CONCURRENT freed 1718K, 23% free 15996K/20716K, paused 1ms+4ms, total 42ms
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 1361K, 23% free 16069K/20716K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 20.085MB for 2475476-byte allocation
,D/dalvikvm( 4150): GC_CONCURRENT freed 265K, 21% free 18356K/23136K, paused 5ms+5ms, total 44ms
,D/dalvikvm( 4150): GC_CONCURRENT freed 4375K, 27% free 17050K/23136K, paused 1ms+8ms, total 55ms
,D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 45ms
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 22.223MB for 3713210-byte allocation
,D/dalvikvm( 4150): GC_CONCURRENT freed 2708K, 32% free 18212K/26764K, paused 4ms+6ms, total 62ms
,D/dalvikvm( 4150): GC_FOR_ALLOC freed 792K, 33% free 18002K/26764K, paused 28ms, total 28ms
,W/jxcore-log( 4150): Initializing JXcore engine
,W/jxcore-log( 4150): JXcore engine is ready
,D/dalvikvm( 4150): GC_CONCURRENT freed 367K, 23% free 20635K/26764K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 4150): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/PluginManager( 4150): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,W/jxcore-log( 4150): Starting JXcore engine
,W/jxcore-log( 4150): Platform android
W/jxcore-log( 4150): 
,W/jxcore-log( 4150): Process ARCH arm
W/jxcore-log( 4150): 
,I/jxcore-log( 4150): JXcore Cordova bridge is ready!
I/jxcore-log( 4150): 
,W/jxcore-log( 4150): JXcore engine is started
,I/chromium( 4150): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4150): Toggling radios to true
I/jxcore-log( 4150): 
,D/BluetoothAdapter( 4150): enable(): BT is already enabled..!
D/WifiService( 1013): New client listening to asynchronous messages
D/WifiService( 1013): setWifiEnabled: true pid=4150, uid=10482
,E/WifiService( 1013): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1013): handleMessage: E msg.what=131145
D/WifiStateMachine( 1013): processMsg: ConnectedState
D/WifiStateMachine( 1013): processMsg: L2ConnectedState
I/jxcore-log( 4150): Radios toggled
I/jxcore-log( 4150): 
D/BluetoothManagerService( 1013): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4150): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4150): 
I/jxcore-log( 4150): Perf Test app loaded loaded
I/jxcore-log( 4150): 
,I/jxcore-log( 4150): check test folder
I/jxcore-log( 4150): 
,I/jxcore-log( 4150): found test : ./testFindPeers.js
I/jxcore-log( 4150): 
,I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  270): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  270): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  270):  STA Disconnected !!
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): get_property_value, Enter
I/MDMCTBK (  270): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  270): get_property_value, Exit
I/MDMCTBK (  270): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  270): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  270): set_property_value, Enter
I/MDMCTBK (  270): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  568): NL - Read 1000 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
I/MDMCTBK (  270): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  270): set_property_value, Exit
I/MDMCTBK (  270): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  270): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  270): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  270): set_property_value, Enter
I/MDMCTBK (  270): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  270): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  270): set_property_value, Exit
E/MDMCTBK (  270): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  270): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  568): NL - Read 1000 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 68 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 68 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
,D/TCMD    (  568): Listening for incoming client connection request
D/WifiStateMachine( 1013): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1013): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1013): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1013): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1013): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine( 1013): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1013): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1013): InitialState.processMessage what=4
,D/Tethering( 1013): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1013): WiFi NOT Tethered!
,D/WifiP2pService( 1013): InactiveState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1013): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4150): found test : ./testSendData.js
I/jxcore-log( 4150): 
,E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  268): Clearing all IP addresses on wlan0
D/TCMD    (  568): NL - Read 60 bytes from update socket.
D/TCMD    (  568): NL - ignore NL message, type = 21
,D/TCMD    (  568): Listening for incoming client connection request
,D/WifiStateMachine( 1013): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1013): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1013): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1013): connected time updated 338804
D/ConnectivityService( 1013): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1013): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1076): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1013): Attempting to switch to mobile
D/ConnectivityService( 1013): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1013): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1076): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1076): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1076): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1013): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1013): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1013): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1013): DisconnectingState
,D/ConnectivityService( 1013): resetConnections(wlan0, 3)
D/Checkin ( 1013): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/NetUtils( 1013): android_net_utils_resetConnections in env=0x61227338 clazz=0x62d00001 iface=wlan0 mask=0x3
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=131146
D/WifiStateMachine( 1013): processMsg: DisconnectingState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/MDMCTBK (  270): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=147460
D/WifiStateMachine( 1013): processMsg: DisconnectingState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): Network connection lost
D/WifiStateMachine( 1013): Stopping DHCP and clearing IP
D/WifiStateMachine( 1013): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1359): Read error: ssl=0x63620260: I/O error during system call, Connection timed out
D/WifiP2pService( 1013): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1013): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x63620260: I/O error during system call, Broken pipe
D/CommandListener(  268): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1013): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1076): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1013): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1013): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1013): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1013): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1013): moveTempStackToStateStack: i=0,j=4
D/Checkin ( 1013): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1013): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1013): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=131101
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): processMsg: DriverStartedState
D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
D/WifiStateMachine( 1013): processMsg: DefaultState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=131216
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): processMsg: DriverStartedState
D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
D/WifiStateMachine( 1013): processMsg: DefaultState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=131216
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): processMsg: DriverStartedState
D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
D/WifiStateMachine( 1013): processMsg: DefaultState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): handleMessage: X
,D/Nat464Xlat( 1013): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1013): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1013): Attempting to switch to mobile
D/ConnectivityService( 1013): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1013): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1013): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1013): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
,I/chromium( 4150): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1165): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  270): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  270): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  270): Event received = Trying to associate with
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  568): NL - Read 56 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
,D/TCMD    (  568): Listening for incoming client connection request
E/wpa_supplicant( 1165): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1013): handleMessage: E msg.what=147461
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): processMsg: DriverStartedState
,D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1013): handleMessage: X
,D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1013): processMsg: ConnectModeState
,D/WifiStateMachine( 1013): handleMessage: X
,I/wpa_supplicant( 1165): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1165): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  568): NL - Read 312 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 88 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 68 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 1000 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
,D/TCMD    (  568): Listening for incoming client connection request
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1165): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  270): Event received = Associated with c0:ff:d4
D/TCMD    (  568): NL - Read 80 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 80 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/TCMD    (  568): NL - Read 68 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
,D/TCMD    (  568): Listening for incoming client connection request,
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1013): processMsg: ConnectModeState
,D/WifiStateMachine( 1013): handleMessage: X
,D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  270): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  270): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  270):  STA Connected !!
D/TCMD    (  568): NL - Read 1000 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
,D/TCMD    (  568): Listening for incoming client connection request
E/MDMCTBK (  270): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  270): get_freq !!, resp=0
I/MDMCTBK (  270): get_freq !!, Strip data
I/MDMCTBK (  270): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): get_property_value, Enter
I/MDMCTBK (  270): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  270): get_property_value, Exit
I/MDMCTBK (  270): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  270): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  270): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  270): set_property_value, Enter
I/MDMCTBK (  270): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  270): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  270): set_property_value, Exit
I/MDMCTBK (  270): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  270): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  270): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): get_property_value, Enter
I/MDMCTBK (  270): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  270): get_property_value, Exit
I/MDMCTBK (  270): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1196602544
I/MDMCTBK (  270): return from set_get_from_wpa_supplicant
I/MDMCTBK (  270): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  270): set_property_value, Enter
,I/MDMCTBK (  270): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  270): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  270): set_property_value, Exit
E/MDMCTBK (  270): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  270): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  270): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  270): , reply_len: 3, ret: 0
E/MDMCTBK (  270): MdmCutbackHndler, resp=OK
E/MDMCTBK (  270): 
,D/MDMCTBK (  270): wifi_set_tx_pwr: Exit
,D/Tethering( 1013): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
,D/Tethering( 1013): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1013): processMsg: DisconnectedState
,D/WifiStateMachine( 1013): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1013): processMsg: ConnectModeState
,D/WifiStateMachine( 1013): handleMessage: X
,D/WifiStateMachine( 1013): handleMessage: E msg.what=147459
D/WifiStateMachine( 1013): processMsg: DisconnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): Network connection established
,D/WifiStateMachine( 1013): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1076): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1013): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1013): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1013): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1013): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1013): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1013): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1013): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1013): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1013): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1013): processMsg: ObtainingIpState
,D/WifiStateMachine( 1013): ObtainingIpState{ when=-31ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4287cd40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1013): processMsg: L2ConnectedState
,D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): processMsg: DriverStartedState
D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1013): processMsg: DefaultState
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=147462
D/WifiStateMachine( 1013): processMsg: ObtainingIpState
,D/WifiStateMachine( 1013): ObtainingIpState{ when=-32ms what=147462 obj=android.net.wifi.StateChangeResult@43d82eb0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1013): processMsg: L2ConnectedState
,D/WifiStateMachine( 1013): processMsg: ConnectModeState
,D/WifiStateMachine( 1013): handleMessage: X
,D/WifiStateMachine( 1013): handleMessage: E msg.what=196612
D/WifiStateMachine( 1013): processMsg: ObtainingIpState
,D/WifiStateMachine( 1013): ObtainingIpState{ when=-18ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1013): processMsg: L2ConnectedState
,D/WifiStateMachine( 1013): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1013): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1013): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423a8228 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1013): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423a8228 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1013): handleMessage: X
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,D/WifiStateMachine( 1013): handleMessage: E msg.what=147461
D/WifiStateMachine( 1013): processMsg: ObtainingIpState
D/WifiStateMachine( 1013): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1013): processMsg: L2ConnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/TCMD    (  568): NL - Read 56 bytes from update socket.
D/TCMD    (  568): NL - message type is RTM_NEWLINK
D/TCMD    (  568): Listening for incoming client connection request
D/WifiStateMachine( 1013): processMsg: DriverStartedState
D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 8
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 9 8
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  270): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 8a
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 6 8a
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 b8
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 7 b8
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 64
,D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-ADDED 8 64,
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  270): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  270): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  270): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1013): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1013): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1013): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1013): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e70230 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1013): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e70230 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1013): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e70230 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1013): handleMessage: X
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,D/TCMD    (  568): NL - Read 60 bytes from update socket.
D/TCMD    (  568): NL - ignore NL message, type = 20
,D/TCMD    (  568): Listening for incoming client connection request
,D/WifiStateMachine( 1013): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1013): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1013): processMsg: ObtainingIpState
D/WifiStateMachine( 1013): ObtainingIpState{ when=-7ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1013): processMsg: L2ConnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
,D/WifiStateMachine( 1013): processMsg: DriverStartedState
D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
D/WifiStateMachine( 1013): processMsg: DefaultState
D/WifiStateMachine( 1013): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1013): handleMessage: X
,D/WifiStateMachine( 1013): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1013): processMsg: ObtainingIpState
,D/WifiStateMachine( 1013): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1013): processMsg: L2ConnectedState
,D/WifiStateMachine( 1013): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1013): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1013): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1013): DHCP successful
,D/WifiStateMachine( 1013): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1013): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1013): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1013): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1013): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1013): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1013): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1013): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1013): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1013): VerifyingLinkState enter
,D/WifiStateMachine( 1013): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1076): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=151572
D/WifiStateMachine( 1013): processMsg: VerifyingLinkState
D/WifiStateMachine( 1013): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1013): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1076): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1013): handleMessage: X
,D/WifiStateMachine( 1013): handleMessage: E msg.what=135190
D/WifiStateMachine( 1013): processMsg: VerifyingLinkState
D/WifiStateMachine( 1013): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1013): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1013): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1013): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1013): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1013): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1013): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1013): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1013): CaptivePortalCheckState enter
,D/WifiStateMachine( 1013): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1013): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1013): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1013): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1013): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1076): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1013): handleMessage: X
D/WifiStateMachine( 1013): handleMessage: E msg.what=131092
D/WifiStateMachine( 1013): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1013): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1013): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1013): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1076): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1013): WiFi NOT Tethered!
,E/ConnectivityService( 1013): Unexpected mtu value: android.net.wifi.WifiStateTracker@420cc2b8
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1076): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1013): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1013): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/WifiStateMachine( 1013): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1013): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1013): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1013): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1013): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1013): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1013): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1013): handleMessage: X
,D/WifiStateMachine( 1013): handleMessage: E msg.what=131092
D/WifiStateMachine( 1013): processMsg: ConnectedState
D/WifiStateMachine( 1013): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1076): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,D/Checkin ( 1013): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1013): processMsg: ConnectModeState
D/WifiStateMachine( 1013): processMsg: DriverStartedState
,D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
D/WifiStateMachine( 1013): processMsg: DefaultState
,D/WifiStateMachine( 1013): handleMessage: X
,V/ConnectivityService( 1013): WiFi NOT Tethered!
,I/SBar.NetworkController( 1076): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1013): Unexpected mtu value: android.net.wifi.WifiStateTracker@420cc2b8
,D/ConnectivityService( 1013): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1013): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
,D/Tethering( 1013): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1013): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1013): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1076): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1076): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1076): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1076): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1076): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1557): Registering with Alarm Manager to restart CCE
D/Tethering( 1013): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1013): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/openssl ( 4070): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4070): Crypto mode 0 already enabled
D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
,I/ActivityManager( 1013): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4299 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 1013): GC_EXPLICIT freed 1814K, 65% free 18104K/50800K, paused 3ms+10ms, total 92ms
,D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
,I/dalvikvm( 1207): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1207): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1207): VFY: replacing opcode 0x6e at 0x003d
,V/MmsConfig( 4299): mnc/mcc: 
,V/MmsConfig( 4299): tag: bool value: enabledMMS - true
V/MmsConfig( 4299): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4299): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4299): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4299): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4299): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4299): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4299): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4299): tag: int value: recipientLimit - 20
V/MmsConfig( 4299): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4299): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4299): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4299): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4299): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4299): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4299): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4299): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4299): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1013): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4321 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1013): Killing 3929:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4321): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4321): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4321): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4321): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1013): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4335 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1013): Killing 3994:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1450229562276 min interval config: 0 actual interval: 328174
,I/CheckinService( 1400): Checking schedule, now: 1450229890462 next: 1450229592244
,I/CheckinService( 1400): active receiver: enabled
,I/CheckinService( 1400): Preparing to send checkin request
,I/EventLogService( 1400): Accumulating logs since 1450229558409
,I/CheckinRequestBuilder( 1400): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1400): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager( 1013): Killing 4010:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ImageResourceManager( 4050): ImageResourceManager: uninitalized
,I/iu.Environment( 4050): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/openssl ( 4070): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4070): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4321): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4321): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4050): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1013): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4355 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4355): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4355): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4355): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4355): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4355): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4355): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4355): install
,I/MultiDex( 4355): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4355): loading existing secondary dex files
,I/MultiDex( 4355): load found 3 secondary dex files
,I/MultiDex( 4355): install done
,D/dalvikvm( 4355): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4355): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4355): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4355): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4355): VFY: unable to resolve instance field 36
,D/dalvikvm( 4355): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4355): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4355): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4355): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4355): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4355): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4355): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff9c10
D/dalvikvm( 4355): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff9c10
,D/dalvikvm( 4355): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff9c10, skipping init
,D/dalvikvm( 4355): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41ff9c10
D/dalvikvm( 4355): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41ff9c10
,V/JNIHelp ( 4355): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4355): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff9c10
,D/dalvikvm( 4355): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41ff9c10
D/dalvikvm( 4355): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41ff9c10
,D/dalvikvm( 4355): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41ff9c10
,I/jxcore-log( 4150): Connected to the server!
I/jxcore-log( 4150): 
,I/ProviderInstaller( 4355): Installed default security provider GmsCore_OpenSSL
,I/chromium( 4150): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WearableService( 1207): callingUid 10022, callindPid: 1207
,E/MDM     ( 1207): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,D/LocationInitializer( 1400): Restart initialization of location
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4355): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4355): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4355): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4355): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4355): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4355): VFY: replacing opcode 0x6e at 0x000d
,W/GCoreFlp( 1207): No location to return for getLastLocation()
,W/FusedLocationProvider( 1207): location=null
,I/dalvikvm( 4355): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4355): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4355): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4355): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4355): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4355): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4355): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4355): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4355): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4355): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4355): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/ConnectivityService( 1013): NetTransition Wakelock for ConnectedState released by timeout
,D/WVCdm   (  275): Instantiating CDM.
,I/WVCdm   (  275): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  275): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  275): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  275): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb524e000
,E/DrmWidevineDash(  275): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb524e000
D/DrmWidevineDash(  275): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  275): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  275): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  275): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  275): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  275): OEMCrypto_GetRandom returns 0
I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=1845974757
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4355): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4355): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4222fea0
D/dalvikvm( 4355): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4222fea0
,D/dalvikvm( 4355): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4222fea0, skipping init
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
,D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4355): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4399): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4355): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4355): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 4355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4355): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4355): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4355): Local Branch: 
I/Adreno-EGL( 4355): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4355): Local Patches: NONE
I/Adreno-EGL( 4355): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4355): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4355): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4355): Local Branch: 
I/Adreno-EGL( 4355): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4355): Local Patches: NONE
I/Adreno-EGL( 4355): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4355): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 4150): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4150): 
,I/Adreno-EGL( 4355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4355): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4355): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4355): Local Branch: 
I/Adreno-EGL( 4355): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4355): Local Patches: NONE
I/Adreno-EGL( 4355): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4355): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4355): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4355): Local Branch: 
I/Adreno-EGL( 4355): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4355): Local Patches: NONE
I/Adreno-EGL( 4355): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  275): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=3246873409
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
,D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1400): Classify the device as Phone.
,V/NativeCrypto( 1400): SSL shutdown failed: ssl=0x6a3f04c0: I/O error during system call, Connection timed out
,I/CheckinTask( 1400): Sending checkin request (11797 bytes)
,D/WifiStateMachine( 1013): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1013): handleMessage: E msg.what=131215
D/WifiStateMachine( 1013): processMsg: ConnectedState
,D/WifiStateMachine( 1013): processMsg: L2ConnectedState
D/WifiStateMachine( 1013): processMsg: ConnectModeState
,D/WifiStateMachine( 1013): processMsg: DriverStartedState
,D/WifiStateMachine( 1013): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1013): processMsg: DefaultState
,D/WifiStateMachine( 1013): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1013): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1013):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1013): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1013): handleMessage: X
,D/ConnectivityService( 1013): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1013): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering( 1013): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1076): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1076): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1013): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): now: 370142 ,futureTime: 65294421
,D/PollingManager( 1557): Polling alarm set to expire at: 65294421 Current Time: 370143
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1076): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1076): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): now: 370174 ,futureTime: 65294421
D/PollingManager( 1557): Polling alarm set to expire at: 65294421 Current Time: 370174
D/Tethering( 1013): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1013): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/openssl ( 4070): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4070): Crypto mode 0 already enabled
D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4321): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/MobileConnectivityChangeReceiver( 4321): onReceive CONNECTIVITY_CHANGE networkType=1
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 4050): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/TelephonyProvider( 1245): Column apn id key is 'apn_id'
I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1450229562276 min interval config: 0 actual interval: 330956
,D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
I/openssl ( 4070): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4070): Crypto mode 0 already enabled
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/dalvikvm( 4050): GC_FOR_ALLOC freed 587K, 5% free 16434K/17224K, paused 27ms, total 38ms
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/MobileConnectivityChangeReceiver( 4321): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4321): onReceive CONNECTIVITY_CHANGE networkType=1
,I/dalvikvm-heap( 4050): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 4050): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 13ms, total 14ms
,I/iu.Environment( 4050): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1450229562276 min interval config: 0 actual interval: 331022
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1557): onServiceConnected()
,D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1013): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinRequestBuilder( 1400): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1400): Failed to find provider info for com.google.android.wearable.settings
D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1013): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1013): GC_EXPLICIT freed 759K, 65% free 18019K/50800K, paused 5ms+9ms, total 96ms
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4150): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1013): Activity reported stop, but no longer stopping: ActivityRecord{429bdb50 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1013): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,221
,I/CheckinRequestBuilder( 1400): Classify the device as Phone.
,I/CheckinTask( 1400): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1400): Checking schedule, now: 1450229893581 next: 1450822963578
,I/CheckinService( 1400): active receiver: disabled
,I/CheckinService( 1400): Checking schedule, now: 1450229893597 next: 1450822963578
,I/CheckinService( 1400): active receiver: disabled
,D/CheckinService( 1400): Recording last checkin time for package unspecified as 1450229893602
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1207): GC_EXPLICIT freed 987K, 36% free 11097K/17224K, paused 4ms+27ms, total 60ms
,I/PhenotypeConfigurator( 1207): Scheduling Phenotype for one-off execution 3992 seconds from now (1450229894509)
,D/GetConfigurationSnapshotOperation( 1207): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1207): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1207): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1207): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1207): VFY: replacing opcode 0x6e at 0x00bb
,D/dalvikvm( 1359): GC_EXPLICIT freed 1611K, 40% free 10336K/17224K, paused 2ms+5ms, total 38ms
,I/GoogleURLConnFactory( 1207): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1013): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1076): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1292): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1292): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1076): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1076): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1207): GC_CONCURRENT freed 1367K, 32% free 11776K/17224K, paused 4ms+10ms, total 45ms
,I/ActivityManager( 1013): Killing 4026:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1013): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4481 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "sms"
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "smsto"
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mms"
,I/Launcher( 1304): Deferring update until onResume
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mmsto"
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "sms"
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "smsto"
I/Launcher( 1304): Deferring update until onResume
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mms"
,I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mmsto"
,I/GCoreNlp( 1207): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4481): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4481): MmsConfig.loadMmsSettings
I/Babel   ( 4481): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4481): MmsConfig.loadFromDatabase
,E/Babel   ( 4481): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4481): MmsConfig.loadFromResources
,E/Babel   ( 4481): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4481): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4481): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1013): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4519 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2329): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1013): Killing 4070:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1400): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1400): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1400): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1013): Killing 4299:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1400): GC_CONCURRENT freed 1925K, 30% free 12073K/17224K, paused 4ms+5ms, total 38ms
,I/InternalIcingCorporaPro( 2329): UpdateCorporaTask done [took 308 ms] updated apps [took 308 ms] 
,I/Icing   ( 1400): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1400): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450229902
,D/CaptivePortalTracker( 1013): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1013): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1013): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1013): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1013): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1013): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1013): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1013): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1013): sending alarm Alarm{420fe930 type 2 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{420e41a0 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{428f4b90 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{44164c00 type 3 android}
,D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  270): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  270): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{441684b0 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{42136690 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{428bbca8 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{42922d20 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{420cd910 type 0 com.google.android.gms}
,V/AlarmManager( 1013): sending alarm Alarm{420c9fe8 type 1 com.android.deskclock}
,I/ActivityManager( 1013): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4575 uid=10015 gids={50015, 1028}
,I/EventLogService( 1400): Aggregate from 1450229890481 (log), 1450228324444 (data)
I/ActivityManager( 1013): Killing 4321:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1013): sending alarm Alarm{43d5ec10 type 2 android}
,D/ConnectivityService( 1013): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1013): Done.
,D/ConnectivityService( 1013): Setting timer for 720seconds
,V/AlarmManager( 1013): sending alarm Alarm{43d5eb38 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{42886430 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43ed4c10 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{43d5ece8 type 2 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43ecdd98 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{44147198 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{437f6820 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{441d5b98 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{43da9b20 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{43d5edc0 type 2 com.google.android.gms}
,D/ConnectivityService( 1013): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1076): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1076): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1292): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1076): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1013): sending alarm Alarm{441dfbf0 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{42863e30 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{42906948 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{43e00e28 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43d23060 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
,I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{441c5b78 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43d6a748 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{42987a10 type 2 android}
,D/ConnectivityService( 1013): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1013): sending alarm Alarm{42987aa0 type 1 com.android.deskclock}
,D/ConnectivityService( 1013): Done.
,D/ConnectivityService( 1013): Setting timer for 720seconds
,D/dalvikvm( 1013): GC_CONCURRENT freed 1980K, 65% free 18185K/50800K, paused 10ms+9ms, total 102ms
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43d6c540 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{4431fe88 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{441ea5c8 type 3 android}
,I/ProcessStatsService( 1013): Prepared write state in 30ms
,I/ProcessStatsService( 1013): Prepared write state in 23ms
,I/ProcessStatsService( 1013): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-18.bin
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43e8c270 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{43ce4438 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{428f5d80 type 3 android}
,V/AlarmManager( 1013): sending alarm Alarm{42869298 type 3 android}
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  270): NetlinkHandler, power_supply subsys
I/MDMCTBK (  270): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  270): checkDefaultInst, current pid is = 270
I/MDMCTBK (  270): checkDefaultInst, pid match
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  270): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  270): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1013): sending alarm Alarm{427f2a10 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4658): 
D/AndroidRuntime( 4658): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4658): CheckJNI is OFF
D/dalvikvm( 4658): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4658): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4658): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4658): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4658): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4658): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4658): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4658): failed to load memtrack module: -2
D/AndroidRuntime( 4658): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10482 user=-1: uninstall pkg
I/ActivityManager( 1013): Killing 4150:com.test.thalitest/u0a482 (adj 9): stop com.test.thalitest
I/ActivityManager( 1013):   Force finishing activity ActivityRecord{425eb370 u0 com.test.thalitest/.MainActivity t3}
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1013): WIN DEATH: Window{43094fe0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1013): Client connection lost with reason: 4
W/PackageSettings( 1013): Skipping PackageSetting{422b5078 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10482 user=0: pkg removed
D/dalvikvm( 2296): GC_EXPLICIT freed 5525K, 44% free 9648K/17224K, paused 3ms+6ms, total 49ms
I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "sms"
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1304): GC_EXPLICIT freed 3236K, 33% free 11595K/17224K, paused 2ms+47ms, total 136ms
I/Launcher( 1304): Deferring update until onResume
D/dalvikvm( 1013): GC_EXPLICIT freed 1059K, 65% free 18030K/50800K, paused 4ms+11ms, total 117ms
D/dalvikvm( 1400): GC_EXPLICIT freed 1177K, 31% free 11927K/17224K, paused 13ms+12ms, total 159ms
W/SQLiteConnectionPool( 1400): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2329): GC_EXPLICIT freed 2757K, 43% free 9818K/17224K, paused 20ms+15ms, total 162ms
W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "smsto"
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
D/VoicemailCleanupService( 3972): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mms"
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mmsto"
I/Launcher( 1304): Deferring update until onResume
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "sms"
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450231692
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "smsto"
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mms"
I/PackageManager( 1013): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1013):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1013):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1013):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2329): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1013): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4694 uid=10059 gids={50059, 3003, 1028, 1015}
D/dalvikvm(  273): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+2ms, total 21ms
D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1013): removePackageParticipantsLocked: uid=10482 #1
D/dalvikvm(  273): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450231692
D/dalvikvm(  273): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 21ms
I/InternalIcingCorporaPro( 2329): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
D/dalvikvm( 1013): GC_EXPLICIT freed 658K, 65% free 18054K/50800K, paused 15ms+13ms, total 186ms
D/AndroidRuntime( 4658): Shutting down VM
D/dalvikvm( 4658): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4694): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1013): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4719 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1013): Killing 4335:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/GAV2    ( 4694): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3620): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3620): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3620): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1400): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1400): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1400): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1400): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1400): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1400): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1359): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1359): Shutting down VM
W/dalvikvm( 1359): threadid=1: thread exiting with uncaught exception (group=0x41723d40)
E/SQLiteDatabase( 1400): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1400): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1400): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1400): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1400): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 1400): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1400): Module APK com.google.android.play.games already loaded
E/PhenotypeInitializer( 1400): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1400): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1400): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1400): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1400): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 1400): disk I/O error (code 3850)
E/DriveAsyncService( 1400): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1400): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1400): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1400): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1400): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1400): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1400): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1400): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1400): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1400): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1400): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1400): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1400): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1400): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1400): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1400): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1400): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1400): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1400): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SharedPreferencesImpl( 1400): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/AndroidRuntime( 1359): FATAL EXCEPTION: main
E/AndroidRuntime( 1359): Process: com.google.process.gapps, PID: 1359
E/AndroidRuntime( 1359): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1359): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1359): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1359): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1359): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1359): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1359): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1359): 	... 10 more
E/SQLiteDatabase( 1400): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1400): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1400): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1400): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1400): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1400): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1400): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1400): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1400): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1400): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1400): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1400): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1400): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1400): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1400): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1400): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1400): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1400): Runtime exception while performing operation
E/ClearPendingStateOp( 1400): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1400): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1400): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1400): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1400): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1400): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1400): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1400): 	at java.lang.Thread.run(Thread.java:841)
F/ClearPendingStateOp( 1400): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1400): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1400): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1400): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1400): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1400): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1400): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1400): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1400): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1400): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1400): 	at java.lang.Thread.run(Thread.java:841)
W/SQLiteOpenHelper( 1400): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1400): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1400): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1400): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1400): threadid=50: thread exiting with uncaught exception (group=0x41723d40)
E/SQLiteLog( 1400): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
W/dalvikvm( 1400): threadid=52: thread exiting with uncaught exception (group=0x41723d40)
I/Process ( 1400): Sending signal. PID: 1400 SIG: 9
E/DropBoxManagerService( 1013): Can't write: system_app_crash
E/DropBoxManagerService( 1013): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1013): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1013): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1013): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1013): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1013): 	... 5 more
E/DropBoxManagerService( 1013): Can't write: system_app_wtf
E/DropBoxManagerService( 1013): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1013): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1013): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1013): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1013): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1013): 	... 5 more
I/Process ( 1359): Sending signal. PID: 1359 SIG: 9
E/SQLiteDatabase( 4719): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4719): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4719): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4719): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4719): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4719): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4719): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4719): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4719): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4719): threadid=10: thread exiting with uncaught exception (group=0x41723d40)
I/ActivityManager( 1013): Process com.google.process.gapps (pid 1359) has died.
D/WifiService( 1013): Client connection lost with reason: 4
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
D/WifiService( 1013): Client connection lost with reason: 4
I/ActivityManager( 1013): Process com.google.android.gms (pid 1400) has died.
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10995ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10995ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10995ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10995ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10994ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 20994ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 30994ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 40994ms
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 40994ms
E/AndroidRuntime( 4719): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4719): Process: com.android.keychain, PID: 4719
E/AndroidRuntime( 4719): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4719): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4719): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4719): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4719): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4719): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4719): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4719): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4719): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4719): Sending signal. PID: 4719 SIG: 9
E/DropBoxManagerService( 1013): Can't write: system_app_crash
E/DropBoxManagerService( 1013): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1013): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1013): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1013): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1013): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1013): 	... 5 more
I/ActivityManager( 1013): Process com.android.keychain (pid 4719) has died.

```
