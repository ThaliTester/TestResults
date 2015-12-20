#### Test 50650278bb431e6_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c2:ff:d4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 c2:ff:d4
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 06:7c:34
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 06:7c:34
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 64:7c:34
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 64:7c:34
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 0c:bd:51
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 0c:bd:51
D/AndroidRuntime( 3981): 
D/AndroidRuntime( 3981): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3981): CheckJNI is OFF
D/dalvikvm( 3981): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3981): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3981): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3981): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3981): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3981): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3981): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3981): failed to load memtrack module: -2
D/AndroidRuntime( 3981): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3981
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3997 uid=10499 gids={50499, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3981): Shutting down VM
D/dalvikvm( 3981): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3997): Binding Chromium to main looper Looper (main, tid 1) {41f76a18}
I/LibraryLoader( 3997): Expected native library version number "",actual native library version number ""
I/chromium( 3997): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3997): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43308730:true
I/Adreno-EGL( 3997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3997): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3997): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3997): Local Branch: 
I/Adreno-EGL( 3997): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3997): Local Patches: NONE
I/Adreno-EGL( 3997): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3997): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3997): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3997): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3997): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3997): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3997): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3997): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3997): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3997): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3997): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3997): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3997): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3997): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3997): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3997): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3997): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3997): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3997): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3997): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3997): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3997): Enabling debug mode 0
,W/AwContents( 3997): nativeOnDraw failed; clearing to background color.
,W/AwContents( 3997): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,379
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +350ms (total +379ms)
W/IInputConnectionWrapper( 3997): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3997): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3997): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7b2c0
,D/dalvikvm( 3997): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7b2c0,
D/jxcore_app_log( 3997): JniHelper::setJavaVM(0x415c9fa8), pthread_self() = 1615037240
,D/JX-Cordova( 3997): jxcore cordova android initializing
,D/dalvikvm( 3997): GC_CONCURRENT freed 2831K, 17% free 14357K/17224K, paused 1ms+2ms, total 56ms
,D/dalvikvm( 3997): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 155K, 17% free 14353K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 179K, 17% free 14387K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 16.221MB for 144892-byte allocation
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 253K, 17% free 14435K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 16.336MB for 217334-byte allocation
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 369K, 18% free 14509K/17584K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 16.513MB for 325996-byte allocation
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 568K, 19% free 14631K/17904K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 16.788MB for 488990-byte allocation
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 867K, 20% free 14808K/18384K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 17.193MB for 733480-byte allocation
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 1283K, 22% free 15066K/19104K, paused 27ms, total 28ms
,D/dalvikvm( 3997): GC_CONCURRENT freed 1674K, 20% free 15439K/19104K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 3997): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 369K, 20% free 15394K/19104K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 18.640MB for 1650320-byte allocation
,D/dalvikvm( 3997): GC_CONCURRENT freed 1674K, 23% free 15964K/20716K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 1376K, 23% free 16049K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 20.067MB for 2475476-byte allocation
,D/dalvikvm( 3997): GC_CONCURRENT freed 287K, 21% free 18332K/23136K, paused 4ms+3ms, total 34ms
,D/dalvikvm( 3997): GC_CONCURRENT freed 4318K, 27% free 17022K/23136K, paused 2ms+7ms, total 41ms
,D/dalvikvm( 3997): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/dalvikvm-heap( 3997): Grow heap (frag case) to 22.197MB for 3713210-byte allocation
,D/dalvikvm( 3997): GC_CONCURRENT freed 326K, 24% free 20574K/26764K, paused 4ms+6ms, total 59ms
,D/dalvikvm( 3997): GC_FOR_ALLOC freed 3134K, 33% free 17963K/26764K, paused 28ms, total 28ms
,W/jxcore-log( 3997): Initializing JXcore engine
,W/jxcore-log( 3997): JXcore engine is ready
,D/dalvikvm( 3997): GC_CONCURRENT freed 349K, 24% free 20599K/26764K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 3997): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 3997): Starting JXcore engine
,W/jxcore-log( 3997): Platform android
W/jxcore-log( 3997): 
,W/jxcore-log( 3997): Process ARCH arm
W/jxcore-log( 3997): 
,I/jxcore-log( 3997): JXcore Cordova bridge is ready!
I/jxcore-log( 3997): 
,W/jxcore-log( 3997): JXcore engine is started
,I/chromium( 3997): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3997): Toggling radios to true
I/jxcore-log( 3997): 
,D/BluetoothAdapter( 3997): enable(): BT is already enabled..!
D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=3997, uid=10499
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 3997): Radios toggled
I/jxcore-log( 3997): 
D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3997): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3997): 
I/jxcore-log( 3997): Perf Test app loaded loaded
I/jxcore-log( 3997): 
,I/jxcore-log( 3997): check test folder
I/jxcore-log( 3997): 
,I/jxcore-log( 3997): found test : ./testFindPeers.js
I/jxcore-log( 3997): 
,I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  478): NL - Read 1000 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
,D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 1000 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
,D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1020): WiFi NOT Tethered!
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/jxcore-log( 3997): found test : ./testSendData.js
I/jxcore-log( 3997): 
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 21
,D/TCMD    (  478): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1020): connected time updated 193100
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1020): DisconnectingState
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x600f5af8 clazz=0x61a00001 iface=wlan0 mask=0x3
D/CommandListener(  272): Clearing all IP addresses on wlan0
I/jxcore-log( 3997): found test : ./testSendData2.js
I/jxcore-log( 3997): 
V/NativeCrypto( 1360): Read error: ssl=0x634b2670: I/O error during system call, Connection timed out
V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x634b2670: I/O error during system call, Broken pipe
E/jxcore  ( 3997): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 3997): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer( 3997): Skipped 112 frames!  The application may be doing too much work on its main thread.
I/chromium( 3997): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1169): wlan0: Trying to associate with SSID 'NG700'
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  478): NL - Read 56 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1169): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  478): NL - Read 312 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
,D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 192 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 1000 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  478): NL - Read 80 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 80 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
,D/TCMD    (  478): Listening for incoming client connection request,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  478): NL - Read 1000 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
,D/TCMD    (  478): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1208052984
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
,E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@4442c170 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-33ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4442d720 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420d56b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420d56b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 9,
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 0
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/TCMD    (  478): NL - Read 56 bytes from update socket.
,D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06,
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 0c,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiP2pService( 1020): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4443d8d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4443d8d0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4443d8d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 20
,D/TCMD    (  478): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): DHCP successful
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
,D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState enter
,D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4206aa78
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1020): WiFi NOT Tethered!
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4206aa78
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1020): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4144 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1568): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioDown
E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4169 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4144): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f7ed60, skipping init
I/openssl ( 4144): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4144): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Killing 3715:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4169): mnc/mcc: 
V/MmsConfig( 4169): tag: bool value: enabledMMS - true
,V/MmsConfig( 4169): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4169): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4169): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4169): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4169): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4169): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4169): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4169): tag: int value: recipientLimit - 20
,V/MmsConfig( 4169): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4169): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4169): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4169): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4169): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4169): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4169): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4169): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4169): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4189 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 3835:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4189): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4189): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4189): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4189): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4207 uid=10056 gids={50056, 3003, 1028, 1015}
I/ActivityManager( 1020): Killing 3389:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1386): Checkin interval check for package: unspecified last checkin: 1450652980484 min interval config: 0 actual interval: 180714
,I/CheckinService( 1386): Checking schedule, now: 1450653161206 next: 1450653010435
,I/CheckinService( 1386): active receiver: enabled
,I/CheckinService( 1386): Preparing to send checkin request
,I/EventLogService( 1386): Accumulating logs since 1450652975844
,I/CheckinRequestBuilder( 1386): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1386): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4223 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3864:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 1020): GC_EXPLICIT freed 23387K, 65% free 18172K/50812K, paused 6ms+11ms, total 141ms
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4223): Binding Chromium to main looper Looper (main, tid 1) {41f7bca0}
,I/LibraryLoader( 4223): Expected native library version number "",actual native library version number ""
,I/chromium( 4223): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4223): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4223): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4223): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4223): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4223): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4223): Local Branch: 
I/Adreno-EGL( 4223): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4223): Local Patches: NONE
I/Adreno-EGL( 4223): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4244 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 4223): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4244): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4244): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4244): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4244): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4244): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4244): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4244): install
,I/MultiDex( 4244): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4244): loading existing secondary dex files
,I/MultiDex( 4244): load found 3 secondary dex files
,I/MultiDex( 4244): install done
,W/GAV2    ( 4223): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4223): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1360): GC_EXPLICIT freed 1583K, 40% free 10367K/17224K, paused 2ms+4ms, total 31ms
,D/dalvikvm( 4244): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4244): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4244): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4244): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4244): VFY: unable to resolve instance field 36
D/dalvikvm( 4244): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4244): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4244): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4244): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4244): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4244): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4244): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f81870
,D/dalvikvm( 4244): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f81870
D/dalvikvm( 4244): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f81870, skipping init
,D/dalvikvm( 4244): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f81870
D/dalvikvm( 4244): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f81870
,V/JNIHelp ( 4244): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4244): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f81870
,D/dalvikvm( 4244): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f81870
D/dalvikvm( 4244): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f81870
,D/dalvikvm( 4244): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f81870
,I/NSApplication( 4223): Starting up...
,I/ImageResourceManager( 3423): ImageResourceManager: uninitalized
,I/iu.Environment( 3423): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1020): Killing 3406:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1568): onServiceConnected()
D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
,I/ProviderInstaller( 4244): Installed default security provider GmsCore_OpenSSL
I/openssl ( 4144): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4144): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4189): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4189): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3423): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4244): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4244): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4244): VFY: replacing opcode 0x6e at 0x00ce
,D/WearableService( 1217): callingUid 10022, callindPid: 1217
I/dalvikvm( 4244): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4244): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4244): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1386): Restart initialization of location
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,E/MDM     ( 1217): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4244): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4244): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4244): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4244): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4244): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4244): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4244): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4244): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4244): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4244): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4244): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
W/GCoreFlp( 1217): No location to return for getLastLocation()
,W/FusedLocationProvider( 1217): location=null
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51b0000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51b0000
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3408515166
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4244): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4244): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42181378
D/dalvikvm( 4244): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42181378
,D/dalvikvm( 4244): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42181378, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Settings( 4244): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4244): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4295): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4244): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4244): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 106ms
,I/Adreno-EGL( 4244): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4244): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4244): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4244): Local Branch: 
I/Adreno-EGL( 4244): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4244): Local Patches: NONE
I/Adreno-EGL( 4244): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 3997): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 3997): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3997): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 3997): Shutting down VM
,W/dalvikvm( 3997): threadid=1: thread exiting with uncaught exception (group=0x416a8d40)
E/AndroidRuntime( 3997): FATAL EXCEPTION: main
E/AndroidRuntime( 3997): Process: com.test.thalitest, PID: 3997
E/AndroidRuntime( 3997): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3997): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 3997): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 3997): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 3997): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 3997): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 3997): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 3997): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3997): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3997): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3997): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3997): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3997): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 3997): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 3997): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3997): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 3997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 3997): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1020):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1020): Killing 3889:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,I/Process ( 3997): Sending signal. PID: 3997 SIG: 9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ProcessCpuTracker( 1020): Skipping unknown process pid 4202
,W/ProcessCpuTracker( 1020): Skipping unknown process pid 4203
W/ProcessCpuTracker( 1020): Skipping unknown process pid 4205
,W/ProcessCpuTracker( 1020): Skipping unknown process pid 4218
,W/ProcessCpuTracker( 1020): Skipping unknown process pid 4297
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/Adreno-EGL( 4244): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4244): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4244): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4244): Local Branch: 
I/Adreno-EGL( 4244): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4244): Local Patches: NONE
I/Adreno-EGL( 4244): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1020): Process com.test.thalitest (pid 3997) has died.
,D/WifiService( 1020): Client connection lost with reason: 4
,I/WindowState( 1020): WIN DEATH: Window{431c4cc0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 3997 uid 10499
,W/Binder  ( 1199): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1199): java.lang.NullPointerException
W/Binder  ( 1199): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1199): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1199): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1199): 	at dalvik.system.NativeStart.run(Native Method)
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3170985283
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1568): now: 224929 ,futureTime: 73891849
,D/PollingManager( 1568): Polling alarm set to expire at: 73891849 Current Time: 224931
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4144): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4144): Crypto mode 0 already enabled
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1568): now: 224959 ,futureTime: 73891849
,D/PollingManager( 1568): Polling alarm set to expire at: 73891849 Current Time: 224959
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/Tethering( 1020): MasterInitialState.processMessage what=3
D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4189): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4189): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3423): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/Adreno-EGL( 4244): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4244): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4244): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4244): Local Branch: 
I/Adreno-EGL( 4244): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4244): Local Patches: NONE
I/Adreno-EGL( 4244): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinService( 1386): Checkin interval check for package: unspecified last checkin: 1450652980484 min interval config: 0 actual interval: 183103
,D/dalvikvm( 3423): GC_CONCURRENT freed 632K, 5% free 16441K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 3423): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/dalvikvm-heap( 3423): Grow heap (frag case) to 19.825MB for 1821008-byte allocation
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1568): onServiceConnected()
D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4144): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4144): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4189): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4189): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3423): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/Adreno-EGL( 4244): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4244): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4244): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4244): Local Branch: 
I/Adreno-EGL( 4244): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4244): Local Patches: NONE
I/Adreno-EGL( 4244): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinService( 1386): Checkin interval check for package: unspecified last checkin: 1450652980484 min interval config: 0 actual interval: 183162
,D/dalvikvm( 3423): GC_FOR_ALLOC freed 43K, 5% free 18183K/19004K, paused 14ms, total 15ms
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1568): onServiceConnected()
,D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinRequestBuilder( 1386): Classify the device as Phone.
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1020): Activity reported stop, but no longer stopping: ActivityRecord{427dc698 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/dalvikvm( 1568): GC_CONCURRENT freed 2008K, 38% free 10736K/17224K, paused 3ms+3ms, total 31ms
,D/dalvikvm( 1386): GC_CONCURRENT freed 1790K, 30% free 12120K/17224K, paused 10ms+7ms, total 52ms
,I/CheckinTask( 1386): Sending checkin request (11759 bytes)
,I/CheckinRequestBuilder( 1386): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1386): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1217): GC_EXPLICIT freed 1213K, 36% free 11076K/17224K, paused 3ms+5ms, total 41ms
,I/CheckinRequestBuilder( 1386): Classify the device as Phone.
,I/CheckinTask( 1386): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1386): Checking schedule, now: 1450653164558 next: 1451246234554
,I/CheckinService( 1386): active receiver: disabled
,I/CheckinService( 1386): Checking schedule, now: 1450653164574 next: 1451246234554
,I/CheckinService( 1386): active receiver: disabled
,D/CheckinService( 1386): Recording last checkin time for package unspecified as 1450653164580
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype for one-off execution 1518 seconds from now (1450653165025)
,D/GetConfigurationSnapshotOperation( 1217): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1217): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1217): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1310): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1310): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1217): GC_CONCURRENT freed 1318K, 33% free 11697K/17224K, paused 4ms+9ms, total 41ms
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ConnectedState
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1020): handleMessage: X
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1020): GC_EXPLICIT freed 1050K, 65% free 18033K/50812K, paused 14ms+10ms, total 114ms
,I/GAV2    ( 4223): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4388 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+14ms, total 43ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/Launcher( 1324): Deferring update until onResume
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/Launcher( 1324): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/GCoreNlp( 1217): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4388): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4388): MmsConfig.loadMmsSettings
I/Babel   ( 4388): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4388): MmsConfig.loadFromDatabase
,E/Babel   ( 4388): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4388): MmsConfig.loadFromResources
,E/Babel   ( 4388): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4388): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4388): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4425 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3441:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4445 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4144:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2300): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4463 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4169:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4463): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4463): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4425): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4463): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2300): UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
,I/dalvikvm( 4463): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4463): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4463): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4463): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4463): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4463): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4463): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4463): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4463): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4463): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4463): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4463): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4463): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4463): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4463): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4497 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4463): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4463): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4463): Skipping gmscore version check
,D/Finsky  ( 4463): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4463): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4463): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4463): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1020): Killing 4189:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1386): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1386): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1386): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4497): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f7d320, skipping init
I/openssl ( 4497): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4497): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Killing 4207:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4463): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4463): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1386): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1386): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,D/dalvikvm( 1386): GC_CONCURRENT freed 2081K, 31% free 11959K/17224K, paused 5ms+5ms, total 47ms
,I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450653173
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 1020): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1020): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1020): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1020): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1020): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1020): sending alarm Alarm{444e2fa0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41fcba28 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1360): disconnect managed GoogleApiClient
,V/AlarmManager( 1020): sending alarm Alarm{41fc9650 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444e3078 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1020): cleanup(): cleared. Last call was 129080 ms ago
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4548 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1020): Killing 4223:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open '',
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{41fc8af8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{4456c118 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44571d30 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445746e8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44575788 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44578a00 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{4457eb10 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44584710 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{4458bb40 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44592f90 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44594410 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44595630 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444e3150 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{444e3228 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{444e3278 type 0 com.google.android.gms}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/EventLogService( 1386): Aggregate from 1450653161228 (log), 1450651592971 (data)
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1310): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/PhenotypeConfigurator( 1217): Server returned 404
,D/dalvikvm( 1217): GC_CONCURRENT freed 2220K, 34% free 11401K/17224K, paused 10ms+5ms, total 69ms
,V/AlarmManager( 1020): sending alarm Alarm{445be998 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445c18f0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445c2a58 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445bea70 type 0 com.motorola.motocare}
,V/AlarmManager( 1020): sending alarm Alarm{445beb48 type 1 com.android.deskclock}
,V/AlarmManager( 1020): sending alarm Alarm{445c6ff0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445cc2c0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445cd448 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445ce5b0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445cf738 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d08a0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d1fa8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d3130 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d4298 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445dab30 type 3 android}
,I/ProcessStatsService( 1020): Prepared write state in 25ms
,I/ProcessStatsService( 1020): Prepared write state in 16ms
,I/ProcessStatsService( 1020): Prepared write state in 19ms
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-06-42.bin
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445e7738 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1020): GC_CONCURRENT freed 2110K, 65% free 18062K/50812K, paused 35ms+9ms, total 133ms
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445ec128 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4624): 
D/AndroidRuntime( 4624): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4624): CheckJNI is OFF
D/dalvikvm( 4624): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4624): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4624): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4624): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4624): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4624): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4624): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4624): failed to load memtrack module: -2
D/AndroidRuntime( 4624): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10499 user=-1: uninstall pkg
W/PackageSettings( 1020): Skipping PackageSetting{4223b970 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10499 user=0: pkg removed
D/dalvikvm( 2267): GC_EXPLICIT freed 5367K, 44% free 9649K/17224K, paused 2ms+5ms, total 45ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1386): GC_EXPLICIT freed 199K, 31% free 11906K/17224K, paused 4ms+6ms, total 139ms
W/SQLiteConnectionPool( 1386): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1324): GC_EXPLICIT freed 3340K, 33% free 11595K/17224K, paused 2ms+4ms, total 132ms
I/Launcher( 1324): Deferring update until onResume
D/dalvikvm( 2300): GC_EXPLICIT freed 4725K, 42% free 10110K/17224K, paused 2ms+4ms, total 130ms
D/dalvikvm( 1020): GC_EXPLICIT freed 748K, 65% free 17944K/50760K, paused 5ms+12ms, total 118ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/VoicemailCleanupService( 4425): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450654963
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/Launcher( 1324): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2300): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4660 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450654963
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10499 #1
I/InternalIcingCorporaPro( 2300): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
D/dalvikvm( 1020): GC_EXPLICIT freed 511K, 65% free 18017K/50760K, paused 7ms+13ms, total 181ms
D/AndroidRuntime( 4624): Shutting down VM
D/dalvikvm( 4624): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4660): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 4660): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4686 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 4686): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4463): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4463): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4463): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1386): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1386): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1386): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1386): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1386): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1386): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1386): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1360): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1360): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4717 uid=10058 gids={50058}
E/SQLiteLog( 1386): (3850) statement aborts at 26: [DELETE FROM events WHERE app_id=?] disk I/O error
E/GMPM-SVC( 1386): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1775)
E/SharedPreferencesImpl( 1386): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SQLiteDatabase( 1386): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1386): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1386): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1386): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1386): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1386): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1386): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1386): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1386): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1386): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1386): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1386): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1386): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1386): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1386): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1386): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1386): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1386): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1386): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1386): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1386): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1386): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1386): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1386): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1386): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1386): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1386): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1386): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1386): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1386): threadid=48: thread exiting with uncaught exception (group=0x416a8d40)
E/AndroidRuntime( 1386): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1386): Process: com.google.android.gms, PID: 1386
E/AndroidRuntime( 1386): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1386): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1386): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1386): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1386): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1386): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1386): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1386): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1386): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1386): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1386): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1386): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1386): threadid=53: thread exiting with uncaught exception (group=0x416a8d40)
I/Process ( 1386): Sending signal. PID: 1386 SIG: 9
V/AlarmManager( 1020): sending alarm Alarm{424d4a48 type 3 android}
V/AlarmManager( 1020): sending alarm Alarm{424cba80 type 3 com.google.android.gms}
V/AlarmManager( 1020): sending alarm Alarm{424cb3b8 type 2 android}
V/AlarmManager( 1020): sending alarm Alarm{424c14b0 type 2 com.motorola.ccc.cce}
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
E/SQLiteDatabase( 4686): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4686): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4686): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4686): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4686): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4686): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4686): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4686): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4686): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4686): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4686): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4686): threadid=10: thread exiting with uncaught exception (group=0x416a8d40)
D/Documents( 4717): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4717): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4717): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4717): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4717): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4717): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4717): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4717): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4717): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4717): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4717): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4717): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4717): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4717): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4717): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4717): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4717): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4717): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4717): Shutting down VM
W/dalvikvm( 4717): threadid=1: thread exiting with uncaught exception (group=0x416a8d40)
I/ActivityManager( 1020): Killing 4244:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
D/WifiService( 1020): Client connection lost with reason: 4
E/AndroidRuntime( 4717): FATAL EXCEPTION: main
E/AndroidRuntime( 4717): Process: com.android.documentsui, PID: 4717
E/AndroidRuntime( 4717): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4717): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4717): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4717): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4717): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4717): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4717): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4717): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4717): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4717): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4717): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4717): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4717): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4717): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4717): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4717): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4717): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4717): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4717): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4717): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4717): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4717): 	... 10 more
W/BroadcastQueue( 1020): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.nearby.settings.NearbyAppUninstallReceiver}
W/BroadcastQueue( 1020): android.os.DeadObjectException
W/BroadcastQueue( 1020): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue( 1020): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:822)
W/BroadcastQueue( 1020): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:236)
W/BroadcastQueue( 1020): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:879)
W/BroadcastQueue( 1020): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:14032)
W/BroadcastQueue( 1020): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:394)
W/BroadcastQueue( 1020): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2140)
W/BroadcastQueue( 1020): 	at android.os.Binder.execTransact(Binder.java:404)
W/BroadcastQueue( 1020): 	at dalvik.system.NativeStart.run(Native Method)
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/AndroidRuntime( 4686): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4686): Process: com.android.keychain, PID: 4686
E/AndroidRuntime( 4686): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4686): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4686): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4686): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4686): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4686): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4686): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4686): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4686): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4686): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 11000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 21000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30999ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 40999ms
D/Documents( 4717): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1020): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4742 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more

```
