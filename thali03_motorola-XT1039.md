#### Test 506502782e2cb10_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager(  995): sending alarm Alarm{44083d00 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4020): 
D/AndroidRuntime( 4020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4020): CheckJNI is OFF
D/dalvikvm( 4020): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4020): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4020): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4020): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4020): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4020): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4020): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4020): failed to load memtrack module: -2
D/AndroidRuntime( 4020): Calling main entry com.android.commands.am.Am
I/ActivityManager(  995): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4020
W/WindowManager(  995): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  995): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4036 uid=10502 gids={50502, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4020): Shutting down VM
D/dalvikvm( 4020): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4036): Binding Chromium to main looper Looper (main, tid 1) {41efabd8}
I/LibraryLoader( 4036): Expected native library version number "",actual native library version number ""
I/chromium( 4036): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4036): Initializing chromium process, renderers=0
D/BluetoothManagerService(  995): Message: 20
D/BluetoothManagerService(  995): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a47e00:true
I/Adreno-EGL( 4036): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4036): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4036): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4036): Local Branch: 
I/Adreno-EGL( 4036): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4036): Local Patches: NONE
I/Adreno-EGL( 4036): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4036): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4036): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4036): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4036): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4036): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4036): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4036): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4036): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4036): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4036): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4036): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4036): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4036): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4036): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4036): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4036): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4036): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4036): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4036): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4036): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4036): Enabling debug mode 0
,W/AwContents( 4036): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4036): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  995): Displayed com.test.thalitest/.MainActivity,cp,ca,379
I/ActivityManager(  995): Displayed com.test.thalitest/.MainActivity: +356ms (total +380ms)
,D/JsMessageQueue( 4036): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4036): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f001a8
,D/dalvikvm( 4036): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f001a8
D/jxcore_app_log( 4036): JniHelper::setJavaVM(0x4154efa8), pthread_self() = 1614555656
,D/JX-Cordova( 4036): jxcore cordova android initializing
,D/dalvikvm( 4036): GC_CONCURRENT freed 2762K, 16% free 14577K/17224K, paused 3ms+2ms, total 60ms
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 189K, 17% free 14389K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 16.177MB for 96598-byte allocation
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 215K, 17% free 14388K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 16.221MB for 144892-byte allocation
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 253K, 18% free 14436K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 16.337MB for 217334-byte allocation
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 369K, 18% free 14510K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 16.514MB for 325996-byte allocation
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 568K, 19% free 14632K/18000K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 16.788MB for 488990-byte allocation
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 867K, 20% free 14809K/18480K, paused 26ms, total 26ms
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 1284K, 19% free 15066K/18480K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 17.794MB for 1100216-byte allocation
,D/dalvikvm( 4036): GC_CONCURRENT freed 1771K, 21% free 15451K/19556K, paused 3ms+3ms, total 37ms
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 278K, 22% free 15392K/19556K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 18.637MB for 1650320-byte allocation
,D/dalvikvm( 4036): GC_CONCURRENT freed 1655K, 25% free 15965K/21168K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 1391K, 25% free 16052K/21168K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 20.069MB for 2475476-byte allocation
,D/dalvikvm( 4036): GC_CONCURRENT freed 299K, 23% free 18335K/23588K, paused 5ms+4ms, total 42ms
,D/dalvikvm( 4036): GC_CONCURRENT freed 4308K, 28% free 17021K/23588K, paused 1ms+7ms, total 41ms
,D/dalvikvm( 4036): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/dalvikvm-heap( 4036): Grow heap (frag case) to 22.196MB for 3713210-byte allocation
,D/dalvikvm( 4036): GC_CONCURRENT freed 381K, 25% free 20444K/27216K, paused 5ms+6ms, total 41ms
,D/dalvikvm( 4036): GC_FOR_ALLOC freed 3067K, 34% free 17972K/27216K, paused 27ms, total 28ms
,W/jxcore-log( 4036): Initializing JXcore engine
,W/jxcore-log( 4036): JXcore engine is ready
,D/dalvikvm( 4036): GC_CONCURRENT freed 358K, 25% free 20600K/27216K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4036): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4036): Starting JXcore engine
,W/jxcore-log( 4036): Platform android
W/jxcore-log( 4036): 
,W/jxcore-log( 4036): Process ARCH arm
W/jxcore-log( 4036): 
,I/jxcore-log( 4036): JXcore Cordova bridge is ready!
I/jxcore-log( 4036): 
,W/jxcore-log( 4036): JXcore engine is started
,I/chromium( 4036): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4036): Toggling radios to true
I/jxcore-log( 4036): 
,D/BluetoothAdapter( 4036): enable(): BT is already enabled..!
D/WifiService(  995): New client listening to asynchronous messages
D/WifiService(  995): setWifiEnabled: true pid=4036, uid=10502
,E/WifiService(  995): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine(  995): handleMessage: E msg.what=131145
D/WifiStateMachine(  995): processMsg: ConnectedState
D/WifiStateMachine(  995): processMsg: L2ConnectedState
I/jxcore-log( 4036): Radios toggled
I/jxcore-log( 4036): 
D/BluetoothManagerService(  995): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4036): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4036): 
I/jxcore-log( 4036): Perf Test app loaded loaded
I/jxcore-log( 4036): 
,I/jxcore-log( 4036): check test folder
I/jxcore-log( 4036): 
,I/jxcore-log( 4036): found test : ./testFindPeers.js
I/jxcore-log( 4036): 
,I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  995): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  995): handleMessage: new destination call exit/enter
D/WifiStateMachine(  995): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  995): invokeExitMethods: ConnectedState
D/WifiStateMachine(  995): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  995): Stopping DHCP and clearing IP
,D/WifiStateMachine(  995): setSuspendOptimizationsNative: 1 true
D/WifiP2pService(  995): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  995): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  995): InitialState.processMessage what=4
,D/Tethering(  995): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService(  995): WiFi NOT Tethered!
,E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/jxcore-log( 4036): found test : ./testSendData.js
I/jxcore-log( 4036): 
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  448): NL - Read 60 bytes from update socket.
D/TCMD    (  448): NL - ignore NL message, type = 21
,D/TCMD    (  448): Listening for incoming client connection request
,D/WifiStateMachine(  995): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  995): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  995): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics(  995): connected time updated 318654
,D/ConnectivityService(  995): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/SBar.NetworkController( 1087): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/ConnectivityService(  995): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1087): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1087): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1087): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService(  995): Attempting to switch to mobile
,D/ConnectivityService(  995): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  995): Attempting to switch to ETHERNET
,D/ConnectivityService(  995): resetConnections(wlan0, 3)
,D/NetUtils(  995): android_net_utils_resetConnections in env=0x61149e08 clazz=0x63600001 iface=wlan0 mask=0x3
D/WifiStateMachine(  995): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  995): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine(  995): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  995): DisconnectingState
I/jxcore-log( 4036): found test : ./testSendData2.js
I/jxcore-log( 4036): 
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=131146
D/WifiStateMachine(  995): processMsg: DisconnectingState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,E/jxcore  ( 4036): Error!: missing ) after argument list
E/jxcore  ( 4036): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/Checkin (  995): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/Choreographer( 4036): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4036): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=147460
D/WifiStateMachine(  995): processMsg: DisconnectingState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): Network connection lost
D/WifiStateMachine(  995): Stopping DHCP and clearing IP
,D/WifiStateMachine(  995): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1364): Read error: ssl=0x6382e3f0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1364): SSL shutdown failed: ssl=0x6382e3f0: I/O error during system call, Broken pipe
,D/WifiP2pService(  995): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  995): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine(  995): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1087): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  995): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  995): handleMessage: new destination call exit/enter
D/WifiStateMachine(  995): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/Checkin (  995): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine(  995): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  995): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  995): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  995): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=147462
D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=131101
D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): processMsg: DriverStartedState
D/WifiStateMachine(  995): processMsg: SupplicantStartedState
D/WifiStateMachine(  995): processMsg: DefaultState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=131216
D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): processMsg: DriverStartedState
D/WifiStateMachine(  995): processMsg: SupplicantStartedState
D/WifiStateMachine(  995): processMsg: DefaultState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=131216
D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): processMsg: DriverStartedState
D/WifiStateMachine(  995): processMsg: SupplicantStartedState
D/WifiStateMachine(  995): processMsg: DefaultState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=147462
D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): handleMessage: X
,D/Nat464Xlat(  995): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  995): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService(  995): Attempting to switch to mobile
D/ConnectivityService(  995): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  995): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat(  995): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  995): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1175): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  448): NL - Read 56 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with,
,D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1175): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine(  995): handleMessage: E msg.what=147461
,D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiStateMachine(  995): processMsg: DriverStartedState
,D/WifiStateMachine(  995): processMsg: SupplicantStartedState
,D/WifiStateMachine(  995): handleMessage: X
,D/WifiStateMachine(  995): handleMessage: E msg.what=147462
D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiStateMachine(  995): handleMessage: X
,I/wpa_supplicant( 1175): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1175): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  448): NL - Read 312 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 192 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1175): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  448): NL - Read 80 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 80 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine(  995): handleMessage: E msg.what=147462
,D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=147462
,D/WifiStateMachine(  995): processMsg: DisconnectedState
D/WifiStateMachine(  995): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiStateMachine(  995): handleMessage: X
,D/Tethering(  995): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1175): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  274): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1215517872
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
,D/WifiStateMachine(  995): handleMessage: E msg.what=147462
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/Tethering(  995): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine(  995): processMsg: DisconnectedState
,D/WifiStateMachine(  995): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=147459
D/WifiStateMachine(  995): processMsg: DisconnectedState
,D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): Network connection established
,D/WifiStateMachine(  995): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1087): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  995): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  995): handleMessage: new destination call exit/enter
D/WifiStateMachine(  995): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  995): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  995): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  995): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  995): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine(  995): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  995): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  995): handleMessage: X
,D/WifiStateMachine(  995): handleMessage: E msg.what=131101
D/WifiStateMachine(  995): processMsg: ObtainingIpState
D/WifiStateMachine(  995): ObtainingIpState{ when=-30ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43a29478 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  995): processMsg: L2ConnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiStateMachine(  995): processMsg: DriverStartedState
D/WifiStateMachine(  995): processMsg: SupplicantStartedState
D/WifiStateMachine(  995): processMsg: DefaultState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=147462
,D/WifiStateMachine(  995): processMsg: ObtainingIpState
D/WifiStateMachine(  995): ObtainingIpState{ when=-30ms what=147462 obj=android.net.wifi.StateChangeResult@43a28700 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  995): processMsg: L2ConnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiStateMachine(  995): handleMessage: X
,D/WifiStateMachine(  995): handleMessage: E msg.what=196612
D/WifiStateMachine(  995): processMsg: ObtainingIpState
D/WifiStateMachine(  995): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  995): processMsg: L2ConnectedState
,D/WifiStateMachine(  995): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine(  995): Unexpected BatchedScanResults :OK
,D/WifiStateMachine(  995): handleMessage: X
D/WifiP2pService(  995): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41fc7f10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  995): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41fc7f10 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 f
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 f
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 fe
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 fe
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  448): NL - Read 56 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
,D/WifiStateMachine(  995): handleMessage: E msg.what=147461
D/WifiP2pService(  995): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  995): processMsg: ObtainingIpState
D/WifiStateMachine(  995): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  995): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  995): processMsg: L2ConnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiP2pService(  995): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  995): processMsg: DriverStartedState
,D/WifiStateMachine(  995): processMsg: SupplicantStartedState
D/WifiP2pService(  995): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43986188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  995): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43986188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  995): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43986188 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  995): handleMessage: X
,D/TCMD    (  448): NL - Read 60 bytes from update socket.
D/TCMD    (  448): NL - ignore NL message, type = 20
,D/TCMD    (  448): Listening for incoming client connection request
,D/WifiStateMachine(  995): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  995): handleMessage: E msg.what=131215
,D/WifiStateMachine(  995): processMsg: ObtainingIpState
,D/WifiStateMachine(  995): ObtainingIpState{ when=-4ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  995): processMsg: L2ConnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
,D/WifiStateMachine(  995): processMsg: DriverStartedState
,D/WifiStateMachine(  995): processMsg: SupplicantStartedState
,D/WifiStateMachine(  995): processMsg: DefaultState
,D/WifiStateMachine(  995): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  995): handleMessage: X
,D/WifiStateMachine(  995): handleMessage: E msg.what=196613
,D/WifiStateMachine(  995): processMsg: ObtainingIpState
,D/WifiStateMachine(  995): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  995): processMsg: L2ConnectedState
,D/WifiStateMachine(  995): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  995): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  995): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  995): DHCP successful
D/WifiStateMachine(  995): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  995): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine(  995): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  995): handleMessage: new destination call exit/enter
D/WifiStateMachine(  995): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  995): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  995): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  995): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine(  995): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  995): VerifyingLinkState enter
D/WifiStateMachine(  995): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1087): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=151572
D/WifiStateMachine(  995): processMsg: VerifyingLinkState
D/WifiStateMachine(  995): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine(  995): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1087): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  995): handleMessage: X
,D/WifiStateMachine(  995): handleMessage: E msg.what=135190
D/WifiStateMachine(  995): processMsg: VerifyingLinkState
,D/WifiStateMachine(  995): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  995): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  995): handleMessage: new destination call exit/enter
D/WifiStateMachine(  995): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  995): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  995): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  995): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine(  995): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  995): CaptivePortalCheckState enter
,D/WifiStateMachine(  995): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService(  995): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  995): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1087): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
D/ConnectivityService(  995): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  995): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=131092
D/WifiStateMachine(  995): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  995): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine(  995): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1087): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  995): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService(  995): WiFi NOT Tethered!
,E/ConnectivityService(  995): Unexpected mtu value: android.net.wifi.WifiStateTracker@41fdeb98
I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1087): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat(  995): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
D/WifiStateMachine(  995): transitionTo: destState=ConnectedState
D/WifiStateMachine(  995): handleMessage: new destination call exit/enter
D/WifiStateMachine(  995): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  995): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  995): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  995): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine(  995): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  995): handleMessage: X
D/WifiStateMachine(  995): handleMessage: E msg.what=131092
D/WifiStateMachine(  995): processMsg: ConnectedState
D/WifiStateMachine(  995): processMsg: L2ConnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): processMsg: DriverStartedState
D/WifiStateMachine(  995): processMsg: SupplicantStartedState
D/WifiStateMachine(  995): processMsg: DefaultState
,D/WifiStateMachine(  995): handleMessage: X
I/SBar.NetworkController( 1087): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1087): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/Checkin (  995): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  995): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService(  995): WiFi NOT Tethered!
E/ConnectivityService(  995): Unexpected mtu value: android.net.wifi.WifiStateTracker@41fdeb98
D/ConnectivityService(  995): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat(  995): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1087): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering(  995): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1087): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1087): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1271): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  995): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  995): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  995): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4185 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/Tethering(  995): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1087): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/CaptivePortalTracker(  995): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1087): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1271): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1557): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1557): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/dalvikvm( 4185): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f03c48, skipping init
I/openssl ( 4185): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4185): Crypto mode 0 already enabled
I/ActivityManager(  995): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4213 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager(  995): Killing 3867:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4213): mnc/mcc: 
V/MmsConfig( 4213): tag: bool value: enabledMMS - true
,V/MmsConfig( 4213): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4213): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4213): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4213): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4213): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4213): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4213): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4213): tag: int value: recipientLimit - 20
V/MmsConfig( 4213): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4213): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4213): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4213): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4213): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4213): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4213): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4213): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4213): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager(  995): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4235 uid=10041 gids={50041, 3003}
,I/ActivityManager(  995): Killing 3377:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4235): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4235): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4235): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4235): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  995): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4248 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager(  995): Killing 3903:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450735983771 min interval config: 0 actual interval: 306186
I/CheckinService( 1408): Checking schedule, now: 1450736289962 next: 1450736013730
,I/CheckinService( 1408): active receiver: enabled
,I/CheckinService( 1408): Preparing to send checkin request
,I/EventLogService( 1408): Accumulating logs since 1450735978910
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  995): GC_EXPLICIT freed 23542K, 65% free 18160K/50752K, paused 4ms+11ms, total 156ms
,I/ActivityManager(  995): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4262 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager(  995): Killing 3393:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1364): GC_EXPLICIT freed 1611K, 40% free 10411K/17224K, paused 3ms+5ms, total 35ms
,V/WebViewChromiumFactoryProvider( 4262): Binding Chromium to main looper Looper (main, tid 1) {41f00b80}
,I/LibraryLoader( 4262): Expected native library version number "",actual native library version number ""
,I/chromium( 4262): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4262): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4262): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4262): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4262): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4262): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4262): Local Branch: 
I/Adreno-EGL( 4262): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4262): Local Patches: NONE
I/Adreno-EGL( 4262): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  995): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  995): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4290 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 4262): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4290): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4290): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4290): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4290): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4290): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4290): install
,I/MultiDex( 4290): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4290): loading existing secondary dex files
,I/MultiDex( 4290): load found 3 secondary dex files
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4262): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/MultiDex( 4290): install done
W/ContextImpl( 4262): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4290): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4290): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4290): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4290): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4290): VFY: unable to resolve instance field 36
,D/dalvikvm( 4290): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4290): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4290): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4290): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4290): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4290): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f06758
,D/dalvikvm( 4290): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f06758
D/dalvikvm( 4290): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f06758, skipping init
,D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f06758
D/dalvikvm( 4290): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f06758
,V/JNIHelp ( 4290): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f06758
,D/dalvikvm( 4290): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f06758
D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f06758
,D/dalvikvm( 4290): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f06758
,I/NSApplication( 4262): Starting up...
,I/ImageResourceManager( 3407): ImageResourceManager: uninitalized
,I/iu.Environment( 3407): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager(  995): Killing 3931:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,I/ProviderInstaller( 4290): Installed default security provider GmsCore_OpenSSL
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4185): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4185): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4235): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4235): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3407): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
I/dalvikvm( 4290): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4290): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4290): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4290): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x000d
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 3407): GC_CONCURRENT freed 621K, 5% free 16441K/17224K, paused 4ms+2ms, total 28ms
,I/dalvikvm( 4290): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4290): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4290): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4290): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4290): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4290): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4290): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x0036
D/AuthorizationBluetoothService( 1364): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1364): Proximity feature is not enabled.
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,D/LocationInitializer( 1408): Restart initialization of location
I/dalvikvm( 4290): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4290): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4290): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1222): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/dalvikvm( 1222): GC_EXPLICIT freed 1030K, 36% free 11082K/17224K, paused 3ms+6ms, total 45ms
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb514a000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb514a000
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1725370901
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4290): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4290): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420eceb0
D/dalvikvm( 4290): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420eceb0
,D/dalvikvm( 4290): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420eceb0, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Settings( 4290): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4290): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4341): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4290): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4290): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 111ms
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4036): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4036): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4036): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4036): Shutting down VM
W/dalvikvm( 4036): threadid=1: thread exiting with uncaught exception (group=0x4162dd40)
E/AndroidRuntime( 4036): FATAL EXCEPTION: main
E/AndroidRuntime( 4036): Process: com.test.thalitest, PID: 4036
E/AndroidRuntime( 4036): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4036): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4036): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4036): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4036): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4036): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4036): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4036): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4036): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4036): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4036): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4036): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4036): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4036): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4036): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4036): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4036): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4036): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4036): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  995):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  995): Killing 3441:com.android.vending/u0a38 (adj 15): empty #9
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4036): Sending signal. PID: 4036 SIG: 9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  995): Process com.test.thalitest (pid 4036) has died.
,D/WifiService(  995): Client connection lost with reason: 4
,I/WindowState(  995): WIN DEATH: Window{443ba908 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService(  995): Got RemoteException sending setActive(false) notification to pid 4036 uid 10502
,W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1926515347
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/Tethering(  995): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  995): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1087): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1271): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1087): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
D/PollingManager( 1557): now: 350655 ,futureTime: 77289914
,D/PollingManager( 1557): Polling alarm set to expire at: 77289914 Current Time: 350655
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1087): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering(  995): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  995): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1271): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1087): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1557): now: 350689 ,futureTime: 77289914
,D/PollingManager( 1557): Polling alarm set to expire at: 77289914 Current Time: 350689
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4185): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4185): Crypto mode 0 already enabled
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/MobileConnectivityChangeReceiver( 4235): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4235): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/CheckinRequestBuilder( 1408): Classify the device as Phone.
D/dalvikvm( 3407): GC_FOR_ALLOC freed 38K, 5% free 16405K/17224K, paused 12ms, total 12ms
,I/dalvikvm-heap( 3407): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
I/iu.Environment( 3407): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/dalvikvm( 1408): GC_CONCURRENT freed 1815K, 30% free 12112K/17224K, paused 6ms+6ms, total 52ms
D/dalvikvm( 3407): GC_FOR_ALLOC freed 4K, 5% free 18183K/19004K, paused 14ms, total 14ms
I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450735983771 min interval config: 0 actual interval: 308740
,V/NativeCrypto( 1408): SSL shutdown failed: ssl=0x6bcfe450: I/O error during system call, Connection timed out
I/openssl ( 4185): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4185): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4235): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4235): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3407): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450735983771 min interval config: 0 actual interval: 308782
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  995): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
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
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  995): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1557): GC_CONCURRENT freed 2060K, 38% free 10728K/17224K, paused 5ms+5ms, total 40ms
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager(  995): Activity reported stop, but no longer stopping: ActivityRecord{42784908 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
I/CheckinTask( 1408): Sending checkin request (11751 bytes)
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,I/CheckinTask( 1408): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1408): Checking schedule, now: 1450736293393 next: 1451329363387
,I/CheckinService( 1408): active receiver: disabled
,I/CheckinService( 1408): Checking schedule, now: 1450736293411 next: 1451329363387
,I/CheckinService( 1408): active receiver: disabled
,D/CheckinService( 1408): Recording last checkin time for package unspecified as 1450736293417
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCM     ( 1408): Message from null null
,E/GCM     ( 1408): Dropping message from null
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 8181 seconds from now (1450736294223)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1222): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1222): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  995): GC_EXPLICIT freed 858K, 65% free 18077K/50752K, paused 3ms+10ms, total 105ms
,D/ConnectivityService(  995): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1087): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1087): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1087): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1281): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  995): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  995): handleMessage: E msg.what=131215
D/WifiStateMachine(  995): processMsg: ConnectedState
D/WifiStateMachine(  995): processMsg: L2ConnectedState
D/WifiStateMachine(  995): processMsg: ConnectModeState
D/WifiStateMachine(  995): processMsg: DriverStartedState
D/WifiStateMachine(  995): processMsg: SupplicantStartedState
,D/WifiStateMachine(  995): processMsg: DefaultState
,D/WifiStateMachine(  995): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  995): handleMessage: X
,D/ConnectivityService(  995): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  995):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat(  995): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  995): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  995): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1222): GC_CONCURRENT freed 1404K, 33% free 11632K/17224K, paused 3ms+8ms, total 36ms
,I/GAV2    ( 4262): Thread[GAThread,5,main]: No campaign data found.
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  995): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4447 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "sms"
,I/InputReader(  995): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 42ms
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "smsto"
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 27ms
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mms"
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mmsto"
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "sms"
,I/Launcher( 1303): Deferring update until onResume
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "smsto"
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mms"
I/Launcher( 1303): Deferring update until onResume
,I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mmsto"
,I/Babel   ( 4447): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4447): MmsConfig.loadMmsSettings
I/Babel   ( 4447): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4447): MmsConfig.loadFromDatabase
,E/Babel   ( 4447): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4447): MmsConfig.loadFromResources
,E/Babel   ( 4447): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4447): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 4447): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  995): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4483 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager(  995): Killing 3994:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  995): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4503 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager(  995): Killing 4185:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2282): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  995): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4520 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager(  995): Killing 4213:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4520): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4520): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4483): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4520): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2282): UpdateCorporaTask done [took 212 ms] updated apps [took 212 ms] 
,I/dalvikvm( 4520): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4520): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4520): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4520): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4520): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4520): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4520): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4520): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4520): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4520): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4520): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4520): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4520): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4520): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4520): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager(  995): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4555 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4520): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4520): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4520): Skipping gmscore version check
,D/Finsky  ( 4520): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4520): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4520): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4520): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager(  995): Killing 4235:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1408): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1408): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4555): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f02310, skipping init
I/openssl ( 4555): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4555): Crypto mode 0 already enabled
,I/ActivityManager(  995): Killing 4248:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4520): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4520): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1408): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1408): GC_CONCURRENT freed 2011K, 31% free 12044K/17224K, paused 4ms+5ms, total 41ms
,I/Icing   ( 1408): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450736302
,D/CaptivePortalTracker(  995): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  995): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  995): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  995): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  995): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  995): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  995): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  995): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{42742680 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{444ddba8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{4406abd0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{444dfb88 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{43d30468 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{44436a10 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{43d9fcc8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{42717378 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{43beec90 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43279568 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43be14f8 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{440e2c78 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{42740450 type 2 android}
,D/ConnectivityService(  995): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  995): sending alarm Alarm{4273f8f8 type 1 com.android.deskclock}
,I/LaunchCheckinHandler(  995): cleanup(): cleared. Last call was 700295 ms ago
,I/ActivityManager(  995): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4620 uid=10015 gids={50015, 1028}
,D/ConnectivityService(  995): Done.
,D/ConnectivityService(  995): Setting timer for 720seconds
,I/ActivityManager(  995): Killing 4262:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 ,
,V/AlarmManager(  995): sending alarm Alarm{43a4d7e8 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{430b8158 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43a13178 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{42722fc0 type 2 com.google.android.gms}
,V/AlarmManager(  995): sending alarm Alarm{42717b38 type 0 com.google.android.gms}
,I/EventLogService( 1408): Aggregate from 1450736289982 (log), 1450735201037 (data)
,D/ConnectivityService(  995): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1087): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1087): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1087): updateTelephonySignalStrength:  No service
,V/AlarmManager(  995): sending alarm Alarm{43465440 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{4283beb8 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43912228 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{44374558 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{440b7718 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43456ac0 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{439955d8 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{440ad660 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{4407af38 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{444b19e0 type 3 android}
,I/ProcessStatsService(  995): Prepared write state in 21ms
,I/ProcessStatsService(  995): Prepared write state in 23ms
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm(  995): GC_CONCURRENT freed 2183K, 65% free 18051K/50752K, paused 19ms+8ms, total 116ms
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{444ba780 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  995): sending alarm Alarm{44557390 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43465500 type 2 android}
,D/ConnectivityService(  995): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  995): sending alarm Alarm{434655d8 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{43465628 type 3 com.google.android.gms}
,V/AlarmManager(  995): sending alarm Alarm{43465678 type 1 com.android.deskclock}
,D/ConnectivityService(  995): Done.
,D/ConnectivityService(  995): Setting timer for 720seconds
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1364): SSL shutdown failed: ssl=0x62c69a90: I/O error during system call, Connection timed out
,V/NativeCrypto( 1364): SSL shutdown failed: ssl=0x63aef508: I/O error during system call, Connection timed out
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/dalvikvm( 1364): GC_EXPLICIT freed 1347K, 40% free 10409K/17224K, paused 2ms+5ms, total 39ms
,D/dalvikvm( 1222): GC_CONCURRENT freed 2208K, 34% free 11404K/17224K, paused 4ms+8ms, total 49ms
,W/PhenotypeConfigurator( 1222): Server returned 404
,V/AlarmManager(  995): sending alarm Alarm{420ad7b8 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{41fb3fc0 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{4271b9b0 type 3 android}
,V/AlarmManager(  995): sending alarm Alarm{420a64d0 type 2 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4691): 
D/AndroidRuntime( 4691): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4691): CheckJNI is OFF
D/dalvikvm( 4691): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4691): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4691): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4691): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4691): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4691): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4691): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4691): failed to load memtrack module: -2
D/AndroidRuntime( 4691): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  995): Force stopping com.test.thalitest appid=10502 user=-1: uninstall pkg
W/PackageSettings(  995): Skipping PackageSetting{421bfce8 com.example.hello/10480} due to missing metadata
I/ActivityManager(  995): Force stopping com.test.thalitest appid=10502 user=0: pkg removed
D/dalvikvm( 2250): GC_EXPLICIT freed 5402K, 44% free 9649K/17224K, paused 2ms+5ms, total 49ms
I/InputReader(  995): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "sms"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/VoicemailCleanupService( 4483): Cleaning up data for package: com.test.thalitest
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1303): GC_EXPLICIT freed 3332K, 33% free 11598K/17224K, paused 2ms+6ms, total 117ms
I/Launcher( 1303): Deferring update until onResume
D/dalvikvm( 1408): GC_EXPLICIT freed 496K, 31% free 11928K/17224K, paused 6ms+20ms, total 150ms
W/SQLiteConnectionPool( 1408): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm(  995): GC_EXPLICIT freed 1018K, 65% free 17969K/50560K, paused 4ms+11ms, total 117ms
D/dalvikvm( 2282): GC_EXPLICIT freed 5284K, 41% free 10187K/17224K, paused 3ms+8ms, total 167ms
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "smsto"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450738091
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mms"
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mmsto"
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "sms"
I/InternalIcingCorporaPro( 2282): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Launcher( 1303): Deferring update until onResume
I/ActivityManager(  995): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4728 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "smsto"
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mms"
I/PackageManager(  995): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  995):   Action: "android.intent.action.SENDTO"
I/PackageManager(  995):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  995):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450738092
D/BackupManagerService(  995): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  995): removePackageParticipantsLocked: uid=10502 #1
I/InternalIcingCorporaPro( 2282): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
D/dalvikvm(  995): GC_EXPLICIT freed 658K, 65% free 17993K/50560K, paused 5ms+15ms, total 212ms
D/AndroidRuntime( 4691): Shutting down VM
D/dalvikvm( 4691): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4728): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 4728): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  995): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4752 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 4752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4520): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4520): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1408): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1408): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1408): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1408): Removing dialog suppression flag for package com.test.thalitest
D/dalvikvm( 3407): GC_FOR_ALLOC freed 28K, 4% free 20543K/21204K, paused 34ms, total 34ms
D/ChimeraCfgMgr( 1408): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1408): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1408): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1408): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1408): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1408): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/NetworkScheduler.SchedulerReceiver( 1364): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1364): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Icing   ( 1408): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1408): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1408): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/ActivityManager(  995): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4796 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1408): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
V/AlarmManager(  995): sending alarm Alarm{427f2d40 type 2 com.motorola.ccc.cce}
W/FileUtils( 1408): Failed to chmod(/data/data/com.google.android.gms/databases/auto_complete_suggestions.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1408): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1408): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 1408): (3850) statement aborts at 29: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1408): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
W/dalvikvm( 1408): threadid=47: thread exiting with uncaught exception (group=0x4162dd40)
E/AndroidRuntime( 1408): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1408): Process: com.google.android.gms, PID: 1408
E/AndroidRuntime( 1408): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1408): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 1408): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 1408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1408): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4752): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4752): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4752): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4752): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4752): threadid=10: thread exiting with uncaught exception (group=0x4162dd40)
I/Process ( 1408): Sending signal. PID: 1408 SIG: 9
E/AndroidRuntime( 4752): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4752): Process: com.android.keychain, PID: 4752
E/AndroidRuntime( 4752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4752): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4752): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4752): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  995): Can't write: system_app_crash
E/DropBoxManagerService(  995): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  995): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  995): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  995): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  995): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  995): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  995): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  995): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  995): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  995): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  995): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  995): 	... 5 more
I/Process ( 4752): Sending signal. PID: 4752 SIG: 9
E/DropBoxManagerService(  995): Can't write: system_app_crash
E/DropBoxManagerService(  995): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  995): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  995): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  995): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  995): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  995): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  995): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  995): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  995): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  995): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  995): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  995): 	... 5 more
I/ActivityManager(  995): Process com.android.keychain (pid 4752) has died.
W/ActivityManager(  995): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  995): Process com.google.android.gms (pid 1408) has died.
D/WifiService(  995): Client connection lost with reason: 4
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  995): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
D/Documents( 4796): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4796): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4796): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4796): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4796): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4796): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4796): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4796): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4796): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4796): Shutting down VM
W/dalvikvm( 4796): threadid=1: thread exiting with uncaught exception (group=0x4162dd40)
D/Documents( 4796): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4796): FATAL EXCEPTION: main
E/AndroidRuntime( 4796): Process: com.android.documentsui, PID: 4796
E/AndroidRuntime( 4796): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4796): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4796): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4796): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4796): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4796): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4796): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4796): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4796): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4796): 	... 10 more
I/ActivityManager(  995): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4814 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager(  995): Killing 4290:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager(  995): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4826 uid=10020 gids={50020, 1028, 1015, 1023}
E/DropBoxManagerService(  995): Can't write: system_app_crash
E/DropBoxManagerService(  995): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  995): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  995): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  995): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  995): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  995): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  995): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  995): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  995): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  995): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  995): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  995): 	... 5 more
I/Process ( 4796): Sending signal. PID: 4796 SIG: 9

```
