#### Test 54312298239818e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3
D/AndroidRuntime( 4156): 
D/AndroidRuntime( 4156): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4156): CheckJNI is OFF
D/dalvikvm( 4156): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4156): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4156): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4156): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4156): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4156): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4156): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4156): failed to load memtrack module: -2
D/AndroidRuntime( 4156): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1000): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4156
W/WindowManager( 1000): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1000): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4172 uid=10504 gids={50504, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4156): Shutting down VM
D/dalvikvm( 4156): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4172): Binding Chromium to main looper Looper (main, tid 1) {41f03b60}
I/LibraryLoader( 4172): Expected native library version number "",actual native library version number ""
I/chromium( 4172): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4172): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1000): Message: 20
D/BluetoothManagerService( 1000): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432b7858:true
I/Adreno-EGL( 4172): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4172): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4172): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4172): Local Branch: 
I/Adreno-EGL( 4172): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4172): Local Patches: NONE
I/Adreno-EGL( 4172): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4172): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4172): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4172): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4172): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4172): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4172): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4172): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4172): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4172): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4172): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4172): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4172): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4172): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4172): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4172): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4172): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4172): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4172): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4172): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4172): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4172): Enabling debug mode 0
,W/AwContents( 4172): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4172): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1000): Displayed com.test.thalitest/.MainActivity,cp,ca,450
I/ActivityManager( 1000): Displayed com.test.thalitest/.MainActivity: +421ms (total +450ms)
W/IInputConnectionWrapper( 4172): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4172): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4172): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f08350
,D/dalvikvm( 4172): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f08350
,D/jxcore_app_log( 4172): JniHelper::setJavaVM(0x41556fa8), pthread_self() = 1613805560
,D/JX-Cordova( 4172): jxcore cordova android initializing
,D/dalvikvm( 4172): GC_CONCURRENT freed 2809K, 17% free 14380K/17224K, paused 3ms+2ms, total 58ms
,D/dalvikvm( 4172): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4172): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 219K, 17% free 14360K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 187K, 17% free 14388K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 16.221MB for 144892-byte allocation
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 254K, 17% free 14435K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 16.337MB for 217334-byte allocation
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 371K, 18% free 14510K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 16.513MB for 325996-byte allocation
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 572K, 19% free 14631K/17904K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 16.788MB for 488990-byte allocation
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 873K, 20% free 14808K/18384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 17.194MB for 733480-byte allocation
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 1292K, 22% free 15065K/19104K, paused 27ms, total 27ms
,D/dalvikvm( 4172): GC_CONCURRENT freed 1675K, 20% free 15438K/19104K, paused 3ms+4ms, total 34ms
,D/dalvikvm( 4172): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 4172): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 383K, 20% free 15395K/19104K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 18.641MB for 1650320-byte allocation
,D/dalvikvm( 4172): GC_CONCURRENT freed 1784K, 23% free 15986K/20716K, paused 1ms+6ms, total 55ms
,V/AlarmManager( 1000): sending alarm Alarm{43de5600 type 3 android}
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 1307K, 23% free 16039K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 20.056MB for 2475476-byte allocation
,D/dalvikvm( 4172): GC_CONCURRENT freed 167K, 21% free 18431K/23136K, paused 5ms+6ms, total 43ms
,D/dalvikvm( 4172): GC_CONCURRENT freed 4465K, 27% free 17026K/23136K, paused 1ms+6ms, total 45ms
,D/dalvikvm( 4172): WAIT_FOR_CONCURRENT_GC blocked 39ms
,I/dalvikvm-heap( 4172): Grow heap (frag case) to 22.201MB for 3713210-byte allocation
,D/dalvikvm( 4172): GC_CONCURRENT freed 2844K, 33% free 18108K/26764K, paused 7ms+7ms, total 62ms
,D/dalvikvm( 4172): GC_FOR_ALLOC freed 636K, 33% free 17959K/26764K, paused 29ms, total 30ms
,W/jxcore-log( 4172): Initializing JXcore engine
,W/jxcore-log( 4172): JXcore engine is ready
,D/dalvikvm( 4172): GC_CONCURRENT freed 350K, 24% free 20572K/26764K, paused 3ms+3ms, total 33ms
,D/dalvikvm( 4172): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4172): Starting JXcore engine
,W/jxcore-log( 4172): Platform android
W/jxcore-log( 4172): 
,W/jxcore-log( 4172): Process ARCH arm
W/jxcore-log( 4172): 
,I/jxcore-log( 4172): JXcore Cordova bridge is ready!
I/jxcore-log( 4172): 
,W/jxcore-log( 4172): JXcore engine is started
,I/chromium( 4172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4172): Toggling radios to true
I/jxcore-log( 4172): 
,D/BluetoothAdapter( 4172): enable(): BT is already enabled..!
D/WifiService( 1000): New client listening to asynchronous messages
D/WifiService( 1000): setWifiEnabled: true pid=4172, uid=10504
,E/WifiService( 1000): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1000): handleMessage: E msg.what=131145
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
I/jxcore-log( 4172): Radios toggled
I/jxcore-log( 4172): 
D/BluetoothManagerService( 1000): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4172): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4172): 
I/jxcore-log( 4172): Perf Test app loaded loaded
I/jxcore-log( 4172): 
,I/jxcore-log( 4172): check test folder
I/jxcore-log( 4172): 
,I/jxcore-log( 4172): found test : ./testFindPeers.js
I/jxcore-log( 4172): 
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
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
D/TCMD    (  445): NL - Read 1000 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  445): NL - Read 1000 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 68 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 68 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1000): InitialState.processMessage what=4
,V/ConnectivityService( 1000): WiFi NOT Tethered!
D/Tethering( 1000): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1000): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1000): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1000): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1000): Stopping DHCP and clearing IP
D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiP2pService( 1000): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  445): NL - Read 60 bytes from update socket.
D/TCMD    (  445): NL - ignore NL message, type = 21
,D/TCMD    (  445): Listening for incoming client connection request
,D/WifiStateMachine( 1000): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1000): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1000): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1000): connected time updated 192616
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1000): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1000): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,I/jxcore-log( 4172): found test : ./testSendData.js
I/jxcore-log( 4172): 
D/ConnectivityService( 1000): Attempting to switch to mobile
D/ConnectivityService( 1000): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1000): Attempting to switch to ETHERNET
,D/ConnectivityService( 1000): resetConnections(wlan0, 3)
D/NetUtils( 1000): android_net_utils_resetConnections in env=0x6114dc70 clazz=0x63300001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1000): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1000): DisconnectingState
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131146
D/WifiStateMachine( 1000): processMsg: DisconnectingState
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147460
D/WifiStateMachine( 1000): processMsg: DisconnectingState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): Network connection lost
D/WifiStateMachine( 1000): Stopping DHCP and clearing IP
D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
V/NativeCrypto( 1347): Read error: ssl=0x6313d698: I/O error during system call, Connection timed out
V/NativeCrypto( 1347): SSL shutdown failed: ssl=0x6313d698: I/O error during system call, Broken pipe
,D/WifiP2pService( 1000): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/jxcore-log( 4172): found test : ./testSendData2.js
I/jxcore-log( 4172): 
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1000): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/jxcore  ( 4172): Error!: missing ) after argument list
E/jxcore  ( 4172): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/chromium( 4172): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiStateMachine( 1000): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1000): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=4
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1000): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131101
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
D/WifiSt,ateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131216
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131216
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1000): Attempting to switch to mobile
D/ConnectivityService( 1000): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1000): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1000): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  445): NL - Read 56 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
,D/TCMD    (  445): Listening for incoming client connection request
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  445): NL - Read 312 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 192 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 68 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 1000 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
,D/TCMD    (  445): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  445): NL - Read 80 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 80 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/TCMD    (  445): Listening for incoming client connection request
D/TCMD    (  445): NL - Read 68 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
,D/TCMD    (  445): Listening for incoming client connection request,
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  445): NL - Read 1000 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
,D/TCMD    (  445): Listening for incoming client connection request
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197169912
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
,D/WifiStateMachine( 1000): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147459
,D/Tethering( 1000): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1000): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): Network connection established
,D/WifiStateMachine( 1000): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine( 1000): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1000): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1000): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1000): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-37ms what=147462 obj=android.net.wifi.StateChangeResult@443a3b38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-29ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@443a5438 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=196612
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1000): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiP2pService( 1000): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4215a010 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4215a010 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/TCMD    (  445): NL - Read 56 bytes from update socket.
D/TCMD    (  445): NL - message type is RTM_NEWLINK
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/TCMD    (  445): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiP2pService( 1000): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@443b2a08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@443b2a08 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@443b2a08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): handleMessage: X
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
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/TCMD    (  445): NL - Read 60 bytes from update socket.
D/TCMD    (  445): NL - ignore NL message, type = 20
,D/TCMD    (  445): Listening for incoming client connection request
,D/WifiStateMachine( 1000): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
,D/WifiStateMachine( 1000): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1000): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1000): DHCP successful
,D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1000): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1000): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1000): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1000): VerifyingLinkState enter
,D/WifiStateMachine( 1000): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=151572
D/WifiStateMachine( 1000): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1000): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=135190
D/WifiStateMachine( 1000): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1000): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1000): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1000): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1000): CaptivePortalCheckState enter
,D/WifiStateMachine( 1000): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1000): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1000): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131092
D/WifiStateMachine( 1000): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1000): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1000): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1000): WiFi NOT Tethered!
,E/ConnectivityService( 1000): Unexpected mtu value: android.net.wifi.WifiStateTracker@42043e78
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/WifiStateMachine( 1000): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1000): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1000): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131092
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): handleMessage: X
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1000): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1000): WiFi NOT Tethered!
E/ConnectivityService( 1000): Unexpected mtu value: android.net.wifi.WifiStateTracker@42043e78
,D/ConnectivityService( 1000): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1000): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1000): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1593): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/CaptivePortalTracker( 1000): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1593): Failed to find provider info for com.motorola.blur.setupprovider
I/openssl ( 4082): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4082): Crypto mode 0 already enabled
D/PollingManager( 1593): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1593): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1593): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1593): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1593): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1593): [debug] > CusSM.onRadioDown
,I/ActivityManager( 1000): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4312 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 1396): GC_CONCURRENT freed 1908K, 31% free 11994K/17224K, paused 13ms+4ms, total 52ms
,D/dalvikvm( 1000): GC_EXPLICIT freed 23489K, 65% free 18100K/50728K, paused 5ms+11ms, total 155ms
,V/MmsConfig( 4312): mnc/mcc: 
V/MmsConfig( 4312): tag: bool value: enabledMMS - true
,V/MmsConfig( 4312): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4312): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4312): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4312): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4312): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4312): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4312): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4312): tag: int value: recipientLimit - 20
V/MmsConfig( 4312): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4312): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4312): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4312): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4312): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4312): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4312): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4312): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4312): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/ActivityManager( 1000): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4335 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1000): Killing 3937:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4335): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4335): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4335): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4335): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1000): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4349 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 4000:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1450742945723 min interval config: 0 actual interval: 181782
,I/CheckinService( 1396): Checking schedule, now: 1450743127513 next: 1450742975692
,I/CheckinService( 1396): active receiver: enabled
,I/CheckinService( 1396): Preparing to send checkin request
,I/EventLogService( 1396): Accumulating logs since 1450742942164
,I/CheckinRequestBuilder( 1396): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1396): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1000): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4364 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 4016:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4364): Binding Chromium to main looper Looper (main, tid 1) {41f05808}
,I/LibraryLoader( 4364): Expected native library version number "",actual native library version number ""
,I/chromium( 4364): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4364): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4364): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4364): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4364): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4364): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4364): Local Branch: 
I/Adreno-EGL( 4364): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4364): Local Patches: NONE
I/Adreno-EGL( 4364): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1000): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4389 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 4364): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4389): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4389): VFY: replacing opcode 0x60 at 0x000b
,W/GAV2    ( 4364): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4364): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/dalvikvm( 4389): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4389): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 4389): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4389): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4389): install
I/MultiDex( 4389): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4389): loading existing secondary dex files
,I/MultiDex( 4389): load found 3 secondary dex files
,I/MultiDex( 4389): install done
,D/dalvikvm( 1347): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 4389): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4389): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4389): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4389): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4389): VFY: unable to resolve instance field 36
,D/dalvikvm( 4389): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4389): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4389): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4389): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4389): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4389): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4389): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0d918
D/dalvikvm( 4389): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0d918
,D/dalvikvm( 4389): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0d918, skipping init
,D/dalvikvm( 4389): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f0d918
D/dalvikvm( 4389): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f0d918
,V/JNIHelp ( 4389): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4389): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0d918
,D/dalvikvm( 4389): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f0d918
D/dalvikvm( 4389): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f0d918
,D/dalvikvm( 4389): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f0d918
,I/NSApplication( 4364): Starting up...
,I/ProviderInstaller( 4389): Installed default security provider GmsCore_OpenSSL
,I/ImageResourceManager( 4061): ImageResourceManager: uninitalized
,I/iu.Environment( 4061): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1000): Killing 4032:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4082): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4082): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4335): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4335): onReceive CONNECTIVITY_CHANGE networkType=1
,I/dalvikvm( 4389): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4389): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4389): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4389): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4389): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4389): VFY: replacing opcode 0x6e at 0x000d
,I/iu.Environment( 4061): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1593): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/ConnectivityService( 1000): NetTransition Wakelock for ConnectedState released by timeout
W/ContextImpl( 1593): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1593): bindWebServices(): registering our AIDL callback...
I/SundryService( 1593): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1593): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1593): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1593): onServiceConnected()
D/GetNotificationsWS( 1593): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1593): unbindWebServices(): un-registering our AIDL callback...
,I/dalvikvm( 4389): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4389): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4389): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4389): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4389): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4389): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4389): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4389): VFY: replacing opcode 0x6e at 0x0036
D/LocationInitializer( 1396): Restart initialization of location
,D/WearableService( 1238): callingUid 10022, callindPid: 1238
I/dalvikvm( 4389): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4389): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4389): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1238): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1238): No location to return for getLastLocation()
,W/FusedLocationProvider( 1238): location=null
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb534e000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb534e000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2620749387
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4389): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4389): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421090d8
D/dalvikvm( 4389): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421090d8
,D/dalvikvm( 4389): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421090d8, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,W/Settings( 4389): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4389): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4442): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4389): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4389): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 66ms
,I/Adreno-EGL( 4389): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4389): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4389): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4389): Local Branch: 
I/Adreno-EGL( 4389): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4389): Local Patches: NONE
I/Adreno-EGL( 4389): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4389): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4389): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4389): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4389): Local Branch: 
I/Adreno-EGL( 4389): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4389): Local Patches: NONE
I/Adreno-EGL( 4389): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4389): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4389): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4389): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4389): Local Branch: 
I/Adreno-EGL( 4389): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4389): Local Patches: NONE
I/Adreno-EGL( 4389): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4389): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4389): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4389): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4389): Local Branch: 
I/Adreno-EGL( 4389): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4389): Local Patches: NONE
I/Adreno-EGL( 4389): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4172): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4172): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4172): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4172): Shutting down VM
,W/dalvikvm( 4172): threadid=1: thread exiting with uncaught exception (group=0x41635d40)
E/AndroidRuntime( 4172): FATAL EXCEPTION: main
E/AndroidRuntime( 4172): Process: com.test.thalitest, PID: 4172
E/AndroidRuntime( 4172): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4172): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4172): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4172): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4172): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4172): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4172): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4172): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4172): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4172): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4172): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4172): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4172): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4172): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4172): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4172): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4172): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1000):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1000): Killing 3981:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4172): Sending signal. PID: 4172 SIG: 9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1593): [info] > Updatetime from metadata: 10
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1593): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1593): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1000): Process com.test.thalitest (pid 4172) has died.
I/WindowState( 1000): WIN DEATH: Window{42899ce8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1000): Client connection lost with reason: 4
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,W/InputMethodManagerService( 1000): Got RemoteException sending setActive(false) notification to pid 4172 uid 10504
W/Binder  ( 1204): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1204): java.lang.NullPointerException
W/Binder  ( 1204): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1204): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1204): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1204): 	at dalvik.system.NativeStart.run(Native Method)
D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3734389130
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine( 1000): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131215
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1000): handleMessage: X
,D/ConnectivityService( 1000): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1000):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1000): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1396): Classify the device as Phone.
,I/CheckinTask( 1396): Sending checkin request (11750 bytes)
,D/CaptivePortalTracker( 1000): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received,
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1593): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1593): now: 224863 ,futureTime: 70326243
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,D/PollingManager( 1593): Polling alarm set to expire at: 70326243 Current Time: 224868
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1000): DelayedCaptiveCheckState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1593): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1593): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1593): now: 224901 ,futureTime: 70326243
D/PollingManager( 1593): Polling alarm set to expire at: 70326243 Current Time: 224901
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/openssl ( 4082): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4082): Crypto mode 0 already enabled
,E/ActivityThread( 1593): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
D/OtaApp  ( 1593): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1593): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1593): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1593): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4335): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4335): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1593): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/OtaApp  ( 1593): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1593): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.Environment( 4061): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1593): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1450742945723 min interval config: 0 actual interval: 184462
,D/OtaApp  ( 1593): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1593): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1593): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1593): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 588K, 5% free 16433K/17224K, paused 18ms, total 19ms
,D/OtaApp  ( 1593): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1593): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1593): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4082): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4082): Crypto mode 0 already enabled
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/MobileConnectivityChangeReceiver( 4335): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4335): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 10ms, total 10ms
,I/iu.Environment( 4061): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1450742945723 min interval config: 0 actual interval: 184525
,D/DEBUG   ( 1593): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1593): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1593): bindWebServices(): registering our AIDL callback...
I/SundryService( 1593): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1593): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1593): onServiceConnected()
,D/GetNotificationsWS( 1593): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1593): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1593): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1593): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1593): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1593): bindWebServices(): registering our AIDL callback...
I/SundryService( 1593): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1593): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1593): onServiceConnected()
,D/GetNotificationsWS( 1593): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1593): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1593): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1593): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1000): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1593
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1593): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1593): [info] > Updatetime from metadata: 10
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1593): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1593): [info] > Updatetime from metadata: 10
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1593): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1593): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1593): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1000): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1593
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1593): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1593): [info] > Updatetime from metadata: 10
D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1593): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1593): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1593): [info] > Updatetime from metadata: 10
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1593): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1593): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1593): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1593): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1000): Activity reported stop, but no longer stopping: ActivityRecord{41ef97d8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1396): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1396): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1000): GC_EXPLICIT freed 814K, 65% free 18018K/50728K, paused 4ms+11ms, total 99ms
,I/CheckinRequestBuilder( 1396): Classify the device as Phone.
,I/CheckinTask( 1396): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1396): Checking schedule, now: 1450743130547 next: 1451336200541
,I/CheckinService( 1396): active receiver: disabled
,I/CheckinService( 1396): Checking schedule, now: 1450743130565 next: 1451336200541
,I/CheckinService( 1396): active receiver: disabled
,D/CheckinService( 1396): Recording last checkin time for package unspecified as 1450743130574
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1000): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1214): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1214): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4364): Thread[GAThread,5,main]: No campaign data found.
,I/InputReader( 1000): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/ActivityManager( 1000): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4501 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
,I/Launcher( 1306): Deferring update until onResume
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
I/Launcher( 1306): Deferring update until onResume
,I/GCoreNlp( 1238): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4501): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4501): MmsConfig.loadMmsSettings
I/Babel   ( 4501): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4501): MmsConfig.loadFromDatabase
,E/Babel   ( 4501): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4501): MmsConfig.loadFromResources
,E/Babel   ( 4501): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4501): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4501): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1000): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4540 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/ActivityManager( 1000): Killing 3610:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1000): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4559 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 4082:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2309): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1000): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4578 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 4312:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4540): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4578): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4578): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4578): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2309): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
I/dalvikvm( 4578): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4578): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 4578): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4578): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4578): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4578): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4578): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4578): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4578): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4578): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4578): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4578): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4578): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4578): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4578): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1000): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4612 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4578): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4578): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm( 1347): GC_EXPLICIT freed 1201K, 40% free 10339K/17224K, paused 2ms+4ms, total 31ms
,D/Ads     ( 4578): Skipping gmscore version check
,D/Finsky  ( 4578): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4578): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4578): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4578): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1000): Killing 4335:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4612): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f093c8, skipping init
I/openssl ( 4612): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4612): Crypto mode 0 already enabled
,D/PackageBroadcastService( 1396): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1396): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1396): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1000): Killing 4349:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4578): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4578): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1396): GC_CONCURRENT freed 1985K, 31% free 12006K/17224K, paused 5ms+4ms, total 38ms
,D/dalvikvm( 1238): GC_CONCURRENT freed 1757K, 34% free 11528K/17224K, paused 2ms+7ms, total 38ms
,I/Icing   ( 1396): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1396): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450743139
,D/CaptivePortalTracker( 1000): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1000): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 1000): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1000): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1000): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1000): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1000): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{4203d9f8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444c8380 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444cc870 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{4202c7b8 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1000): cleanup(): cleared. Last call was 162783 ms ago
,I/ActivityManager( 1000): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4662 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1000): Killing 4364:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6
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
,V/AlarmManager( 1000): sending alarm Alarm{444d2550 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444dd6f8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444e4e08 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444e93a0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444ef8b8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444f5e20 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{444fd558 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{445033d0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4450ab08 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4450d718 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{445151d0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4451ca18 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{42029130 type 2 android}
,V/AlarmManager( 1000): sending alarm Alarm{42715550 type 2 com.google.android.gms}
,D/ConnectivityService( 1000): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1000): sending alarm Alarm{42027f50 type 0 com.google.android.gms}
,D/ConnectivityService( 1000): Done.
,D/ConnectivityService( 1000): Setting timer for 720seconds
,I/EventLogService( 1396): Aggregate from 1450743127530 (log), 1450741689039 (data)
,D/ConnectivityService( 1000): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1214): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{44531f50 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{44537440 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4453b9b8 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{44532028 type 1 com.android.deskclock}
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
,V/AlarmManager( 1000): sending alarm Alarm{44541e38 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{44548b20 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{445502e0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{44557ac0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4455c0e0 type 3 android}
,D/dalvikvm( 1000): GC_CONCURRENT freed 2021K, 65% free 18131K/50728K, paused 22ms+9ms, total 117ms
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
,V/AlarmManager( 1000): sending alarm Alarm{44564058 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{44534580 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{4449ae78 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{44494738 type 3 android}
,I/ProcessStatsService( 1000): Prepared write state in 24ms
,I/ProcessStatsService( 1000): Prepared write state in 32ms
,I/ProcessStatsService( 1000): Pruning old procstats: /data/system/procstats/state-2015-12-21-05-07-46.bin
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{4438cec8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{427ecc58 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{427da8f8 type 3 android}
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
,TIME-OUT KILL (timeout was 1800000ms),I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4711): 
D/AndroidRuntime( 4711): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4711): CheckJNI is OFF
D/dalvikvm( 4711): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4711): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4711): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4711): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4711): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4711): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4711): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4711): failed to load memtrack module: -2
D/AndroidRuntime( 4711): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1000): Force stopping com.test.thalitest appid=10504 user=-1: uninstall pkg
I/dalvikvm( 1000): Total arena pages for JIT: 15
W/PackageSettings( 1000): Skipping PackageSetting{421dcc20 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1000): Force stopping com.test.thalitest appid=10504 user=0: pkg removed
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
I/InputReader( 1000): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450744928
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
D/dalvikvm( 2279): GC_EXPLICIT freed 5528K, 44% free 9650K/17224K, paused 3ms+13ms, total 104ms
D/dalvikvm( 1000): GC_EXPLICIT freed 1305K, 65% free 17973K/50676K, paused 5ms+10ms, total 143ms
D/dalvikvm( 2309): GC_EXPLICIT freed 2757K, 44% free 9817K/17224K, paused 2ms+3ms, total 52ms
D/dalvikvm( 1306): GC_EXPLICIT freed 3239K, 33% free 11607K/17224K, paused 2ms+4ms, total 73ms
I/Launcher( 1306): Deferring update until onResume
D/dalvikvm( 1396): GC_EXPLICIT freed 621K, 31% free 11901K/17224K, paused 127ms+8ms, total 179ms
W/SQLiteConnectionPool( 1396): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
W/GeofencerStateMachine( 1238): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
D/VoicemailCleanupService( 4540): Cleaning up data for package: com.test.thalitest
I/Launcher( 1306): Deferring update until onResume
I/InternalIcingCorporaPro( 2309): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450744929
I/ActivityManager( 1000): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4742 uid=10059 gids={50059, 3003, 1028, 1015}
D/BackupManagerService( 1000): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1000): removePackageParticipantsLocked: uid=10504 #1
D/dalvikvm( 1000): GC_EXPLICIT freed 362K, 65% free 18035K/50676K, paused 5ms+14ms, total 155ms
I/InternalIcingCorporaPro( 2309): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
D/AndroidRuntime( 4711): Shutting down VM
D/dalvikvm( 4711): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4742): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1000): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4763 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4742): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4763): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1396): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1396): Clearing selected account for com.test.thalitest
I/dalvikvm( 4578): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4578): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4578): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1396): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1396): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1396): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1347): Invalid parameter app
D/ChimeraCfgMgr( 1396): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1396): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1347): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1000): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4790 uid=10058 gids={50058}
W/FileUtils( 1396): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SharedPreferencesImpl( 1396): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
D/gH_CompatibleDatabase( 1396): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1396): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1396): (3850) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1396): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1396): threadid=49: thread exiting with uncaught exception (group=0x41635d40)
I/Icing   ( 1396): doRemovePackageData com.test.thalitest
E/AndroidRuntime( 1396): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1396): Process: com.google.android.gms, PID: 1396
E/AndroidRuntime( 1396): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1396): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1396): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1396): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1396): Sending signal. PID: 1396 SIG: 9
V/AlarmManager( 1000): sending alarm Alarm{4270a920 type 3 android}
E/DropBoxManagerService( 1000): Can't write: system_app_crash
E/DropBoxManagerService( 1000): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1000): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1000): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1000): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1000): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1000): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1000): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1000): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1000): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1000): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1000): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1000): 	... 5 more
V/AlarmManager( 1000): sending alarm Alarm{42706070 type 3 com.google.android.gms}
V/AlarmManager( 1000): sending alarm Alarm{427025c0 type 2 android}
V/AlarmManager( 1000): sending alarm Alarm{42700a90 type 2 com.motorola.ccc.cce}
E/SQLiteDatabase( 4763): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4763): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4763): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4763): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4763): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4763): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4763): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4763): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4763): threadid=10: thread exiting with uncaught exception (group=0x41635d40)
I/ActivityManager( 1000): Process com.google.android.gms (pid 1396) has died.
D/WifiService( 1000): Client connection lost with reason: 4
W/Icing   ( 1238): Error while brokering service: android.os.DeadObjectException
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
E/AndroidRuntime( 4763): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4763): Process: com.android.keychain, PID: 4763
E/AndroidRuntime( 4763): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4763): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4763): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4763): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4763): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4763): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4763): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4763): Sending signal. PID: 4763 SIG: 9
E/DropBoxManagerService( 1000): Can't write: system_app_crash
E/DropBoxManagerService( 1000): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1000): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1000): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1000): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1000): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1000): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1000): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1000): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1000): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1000): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1000): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1000): 	... 5 more
D/Documents( 4790): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1000): Process com.android.keychain (pid 4763) has died.
W/ActivityManager( 1000): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10989ms
E/SQLiteDatabase( 4790): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4790): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4790): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4790): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4790): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4790): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4790): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4790): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4790): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4790): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4790): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4790): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4790): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4790): Shutting down VM
W/dalvikvm( 4790): threadid=1: thread exiting with uncaught exception (group=0x41635d40)
E/AndroidRuntime( 4790): FATAL EXCEPTION: main
E/AndroidRuntime( 4790): Process: com.android.documentsui, PID: 4790
E/AndroidRuntime( 4790): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4790): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4790): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4790): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4790): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4790): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4790): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4790): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4790): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4790): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4790): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4790): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4790): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4790): 	... 10 more
I/ActivityManager( 1000): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4818 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager( 1000): Killing 4389:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
I/Process ( 4790): Sending signal. PID: 4790 SIG: 9
E/DropBoxManagerService( 1000): Can't write: system_app_crash
E/DropBoxManagerService( 1000): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1000): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1000): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1000): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1000): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1000): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1000): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1000): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1000): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1000): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1000): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1000): 	... 5 more
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/SQLiteLog( 2279): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error

```
