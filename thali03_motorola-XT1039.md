#### Test 506502781c2754f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3984): 
D/AndroidRuntime( 3984): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3984): CheckJNI is OFF
D/dalvikvm( 3984): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3984): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3984): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3984): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3984): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3984): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3984): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3984): failed to load memtrack module: -2
D/AndroidRuntime( 3984): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1024): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3984
W/WindowManager( 1024): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1024): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4000 uid=10501 gids={50501, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3984): Shutting down VM
D/dalvikvm( 3984): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4000): Binding Chromium to main looper Looper (main, tid 1) {429c7270}
I/LibraryLoader( 4000): Expected native library version number "",actual native library version number ""
I/chromium( 4000): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4000): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1024): Message: 20
D/BluetoothManagerService( 1024): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b52388:true
I/Adreno-EGL( 4000): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4000): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4000): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4000): Local Branch: 
I/Adreno-EGL( 4000): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4000): Local Patches: NONE
I/Adreno-EGL( 4000): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4000): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4000): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4000): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4000): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4000): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4000): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4000): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4000): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4000): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4000): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4000): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4000): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4000): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4000): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4000): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4000): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4000): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4000): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4000): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4000): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4000): Enabling debug mode 0
,W/AwContents( 4000): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4000): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1024): Displayed com.test.thalitest/.MainActivity,cp,ca,390
I/ActivityManager( 1024): Displayed com.test.thalitest/.MainActivity: +356ms (total +390ms)
,D/JsMessageQueue( 4000): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4000): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x429cc2e0
,D/dalvikvm( 4000): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x429cc2e0
,D/jxcore_app_log( 4000): JniHelper::setJavaVM(0x420e5f78), pthread_self() = 1614771720
,D/JX-Cordova( 4000): jxcore cordova android initializing
,D/dalvikvm( 4000): GC_CONCURRENT freed 2831K, 17% free 14358K/17224K, paused 3ms+2ms, total 51ms
,D/dalvikvm( 4000): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 140K, 17% free 14378K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.166MB for 96598-byte allocation
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 203K, 17% free 14388K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.222MB for 144892-byte allocation
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 252K, 18% free 14436K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.337MB for 217334-byte allocation
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 369K, 18% free 14511K/17680K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.514MB for 325996-byte allocation
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 568K, 19% free 14632K/18000K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.788MB for 488990-byte allocation
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 867K, 20% free 14809K/18480K, paused 26ms, total 27ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 1284K, 19% free 15066K/18480K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 17.794MB for 1100216-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 1767K, 21% free 15451K/19556K, paused 1ms+4ms, total 36ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 288K, 22% free 15385K/19556K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 18.630MB for 1650320-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 1683K, 25% free 15967K/21168K, paused 3ms+4ms, total 35ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 1359K, 25% free 16049K/21168K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 20.066MB for 2475476-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 308K, 23% free 18387K/23588K, paused 4ms+4ms, total 50ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 4306K, 28% free 17014K/23588K, paused 35ms, total 36ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 22.189MB for 3713210-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 321K, 25% free 20499K/27216K, paused 5ms+5ms, total 40ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 3121K, 34% free 17972K/27216K, paused 27ms, total 29ms
,W/jxcore-log( 4000): Initializing JXcore engine
,W/jxcore-log( 4000): JXcore engine is ready
,D/dalvikvm( 4000): GC_CONCURRENT freed 320K, 25% free 20637K/27216K, paused 1ms+2ms, total 28ms
,D/dalvikvm( 4000): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4000): Starting JXcore engine
,W/jxcore-log( 4000): Platform android
W/jxcore-log( 4000): 
,W/jxcore-log( 4000): Process ARCH arm
W/jxcore-log( 4000): 
,I/jxcore-log( 4000): JXcore Cordova bridge is ready!
I/jxcore-log( 4000): 
,W/jxcore-log( 4000): JXcore engine is started
,I/chromium( 4000): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4000): Toggling radios to true
I/jxcore-log( 4000): 
,D/BluetoothAdapter( 4000): enable(): BT is already enabled..!
D/WifiService( 1024): New client listening to asynchronous messages
D/WifiService( 1024): setWifiEnabled: true pid=4000, uid=10501
,E/WifiService( 1024): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1024): handleMessage: E msg.what=131145
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
I/jxcore-log( 4000): Radios toggled
I/jxcore-log( 4000): 
D/BluetoothManagerService( 1024): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4000): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4000): 
I/jxcore-log( 4000): Perf Test app loaded loaded
I/jxcore-log( 4000): 
,I/jxcore-log( 4000): check test folder
I/jxcore-log( 4000): 
,I/jxcore-log( 4000): found test : ./testFindPeers.js
I/jxcore-log( 4000): 
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1024): InitialState.processMessage what=4
,V/ConnectivityService( 1024): WiFi NOT Tethered!
D/Tethering( 1024): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1024): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1024): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1024): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1024): Stopping DHCP and clearing IP
D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/jxcore-log( 4000): found test : ./testSendData.js
I/jxcore-log( 4000): 
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 21
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1024): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1024): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1024): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1024): connected time updated 292657
,I/SBar.NetworkController( 1086): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1024): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1024): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1086): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1086): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1086): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1024): Attempting to switch to mobile
D/ConnectivityService( 1024): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1024): Attempting to switch to ETHERNET
,D/ConnectivityService( 1024): resetConnections(wlan0, 3)
D/NetUtils( 1024): android_net_utils_resetConnections in env=0x61232cc0 clazz=0x62500001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1024): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1024): DisconnectingState
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131146
D/WifiStateMachine( 1024): processMsg: DisconnectingState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147460
D/WifiStateMachine( 1024): processMsg: DisconnectingState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): Network connection lost
,D/WifiStateMachine( 1024): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1356): Read error: ssl=0x632f8b00: I/O error during system call, Connection timed out
,I/jxcore-log( 4000): found test : ./testSendData2.js
I/jxcore-log( 4000): 
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x632f8b00: I/O error during system call, Broken pipe
,E/jxcore  ( 4000): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4000): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer( 4000): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4000): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1086): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1024): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1024): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=4
D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1024): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131101
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131216
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131216
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1024): Attempting to switch to mobile
D/ConnectivityService( 1024): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1024): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1168): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  277): Event received = Trying to associate with
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1168): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  499): NL - Read 312 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 192 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1200569800
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
,D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/Tethering( 1024): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1024): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147459
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): Network connection established
,D/WifiStateMachine( 1024): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1086): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1024): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1024): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1024): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1024): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-29ms what=147462 obj=android.net.wifi.StateChangeResult@44b31df0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131101
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-28ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4475f558 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=196612
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1024): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiP2pService( 1024): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cf3030 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cf3030 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1024): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/WifiP2pService( 1024): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@44738520 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@44738520 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@44738520 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): handleMessage: X
,D/CaptivePortalTracker( 1024): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1285): No entry in secure settings for enhanced location services: false
,D/ConnectivityService( 1024): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1285): Active network info is not available
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1285): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1285): Active network info is not available
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1569): Registering with Alarm Manager to restart CCE
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1024): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1569): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1569): [debug] > CusSM.onRadioDown
,I/ActivityManager( 1024): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4110 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/dalvikvm( 1024): GC_EXPLICIT freed 1464K, 65% free 18014K/50604K, paused 4ms+10ms, total 93ms
,V/MmsConfig( 4110): mnc/mcc: 
V/MmsConfig( 4110): tag: bool value: enabledMMS - true
V/MmsConfig( 4110): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4110): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4110): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4110): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4110): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4110): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4110): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4110): tag: int value: recipientLimit - 20
V/MmsConfig( 4110): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4110): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4110): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 4110): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4110): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4110): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4110): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4110): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4110): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1024): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4130 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1024): Killing 3778:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 20
D/TCMD    (  499): Listening for incoming client connection request
D/WifiStateMachine( 1024): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1024): handleMessage: E msg.what=131215
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1024): handleMessage: X
,D/MobileConnectivityChangeReceiver( 4130): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4130): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4130): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4130): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1024): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4155 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 3825:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiStateMachine( 1024): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,I/ActivityManager( 1024): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4179 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 3841:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/WifiP2pService( 1024): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): DHCP successful
D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1024): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1024): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1024): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState enter
,D/WifiStateMachine( 1024): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine( 1024): handleMessage: X
,I/SBar.NetworkController( 1086): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1024): handleMessage: E msg.what=151572
D/WifiStateMachine( 1024): processMsg: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1086): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=135190
D/WifiStateMachine( 1024): processMsg: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1024): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1024): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1024): CaptivePortalCheckState enter
,D/WifiStateMachine( 1024): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1024): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1024): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1086): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1024): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1024): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131092
D/WifiStateMachine( 1024): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1024): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
V/WebViewChromiumFactoryProvider( 4179): Binding Chromium to main looper Looper (main, tid 1) {429cbcd8}
I/LibraryLoader( 4179): Expected native library version number "",actual native library version number ""
I/chromium( 4179): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
D/WifiStateMachine( 1024): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/BrowserStartupController( 4179): Initializing chromium process, renderers=0
D/ConnectivityService( 1024): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1024): WiFi NOT Tethered!
,E/ConnectivityService( 1024): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b51240
I/SBar.NetworkController( 1086): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1086): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1024): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1024): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131092
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
E/AudioManagerAndroid( 4179): BLUETOOTH permission is missing!
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
,D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: CONNECTED/CONNECTED
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
V/ConnectivityService( 1024): WiFi NOT Tethered!
E/ConnectivityService( 1024): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b51240
,I/SBar.NetworkController( 1086): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/Adreno-EGL( 4179): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4179): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4179): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4179): Local Branch: 
I/Adreno-EGL( 4179): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4179): Local Patches: NONE
I/Adreno-EGL( 4179): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1024): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
I/CheckinService( 1405): Checkin interval check for package: unspecified last checkin: 1450657933086 min interval config: 0 actual interval: 281035
I/SBar.NetworkController( 1086): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
I/CheckinService( 1405): Checking schedule, now: 1450658214128 next: 1450657963063
I/CheckinService( 1405): active receiver: enabled
,I/CheckinService( 1405): Preparing to send checkin request
,I/EventLogService( 1405): Accumulating logs since 1450657929644
,I/CheckinRequestBuilder( 1405): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1405): Failed to find provider info for com.google.android.wearable.settings
W/chromium( 4179): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4179): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4179): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1024): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4219 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
,W/dalvikvm( 4219): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4219): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
I/dalvikvm( 4219): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4219): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4219): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4219): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4219): install
,I/MultiDex( 4219): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4219): loading existing secondary dex files
,I/MultiDex( 4219): load found 3 secondary dex files
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,I/MultiDex( 4219): install done
,I/NSApplication( 4179): Starting up...
,I/ImageResourceManager( 3883): ImageResourceManager: uninitalized
,D/dalvikvm( 4219): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4219): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4219): VFY: replacing opcode 0x62 at 0x000a
I/iu.Environment( 3883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/dalvikvm( 4219): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4219): VFY: unable to resolve instance field 36
,D/dalvikvm( 4219): VFY: replacing opcode 0x54 at 0x005f
I/ActivityManager( 1024): Killing 3857:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 4219): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4219): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4219): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4219): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4219): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 4219): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429d1948
D/dalvikvm( 4219): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429d1948
D/dalvikvm( 4219): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429d1948, skipping init
D/dalvikvm( 4219): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429d1948
D/dalvikvm( 4219): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429d1948
V/JNIHelp ( 4219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3903): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3903): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4130): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4130): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 4219): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429d1948
,D/dalvikvm( 4219): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x429d1948
D/dalvikvm( 4219): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429d1948
,D/dalvikvm( 4219): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429d1948
,I/ProviderInstaller( 4219): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1228): callingUid 10022, callindPid: 1228
,D/LocationInitializer( 1405): Restart initialization of location
,D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1356): Proximity feature is not enabled.
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1228): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1228): No location to return for getLastLocation()
,W/FusedLocationProvider( 1228): location=null
,I/dalvikvm( 4219): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4219): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4219): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4219): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4219): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4219): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4219): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4219): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4219): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4219): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4219): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4219): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4219): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4219): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4219): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4219): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4219): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50f0000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50f0000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3850324798
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4219): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4219): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c13c08
D/dalvikvm( 4219): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c13c08
,D/dalvikvm( 4219): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c13c08, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,W/Settings( 4219): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService( 1024): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4219): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4255): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4219): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4219): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 84ms
,I/Adreno-EGL( 4219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4219): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4219): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4219): Local Branch: 
I/Adreno-EGL( 4219): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4219): Local Patches: NONE
I/Adreno-EGL( 4219): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4000): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4000): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4000): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4000): Shutting down VM
,W/dalvikvm( 4000): threadid=1: thread exiting with uncaught exception (group=0x420f7d40)
E/AndroidRuntime( 4000): FATAL EXCEPTION: main
E/AndroidRuntime( 4000): Process: com.test.thalitest, PID: 4000
E/AndroidRuntime( 4000): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4000): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4000): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4000): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4000): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4000): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4000): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4000): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4000): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4000): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4000): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4000): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4000): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4000): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4000): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4000): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4000): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4000): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4000): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1024):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1024): Killing 3801:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4000): Sending signal. PID: 4000 SIG: 9
,I/Adreno-EGL( 4219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4219): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4219): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4219): Local Branch: 
I/Adreno-EGL( 4219): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4219): Local Patches: NONE
I/Adreno-EGL( 4219): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1024): Process com.test.thalitest (pid 4000) has died.
,I/WindowState( 1024): WIN DEATH: Window{431e3aa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1024): Client connection lost with reason: 4
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1024): Got RemoteException sending setActive(false) notification to pid 4000 uid 10501
W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=1481330760
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4219): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4219): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4219): Local Branch: 
I/Adreno-EGL( 4219): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4219): Local Patches: NONE
I/Adreno-EGL( 4219): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4219): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4219): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4219): Local Branch: 
I/Adreno-EGL( 4219): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4219): Local Patches: NONE
I/Adreno-EGL( 4219): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1405): Classify the device as Phone.
,I/CheckinTask( 1405): Sending checkin request (11750 bytes)
,I/CheckinRequestBuilder( 1405): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1405): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1405): Classify the device as Phone.
,I/CheckinTask( 1405): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1405): Checking schedule, now: 1450658217102 next: 1451251287095
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1285): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1024): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
D/PollingManager( 1569): now: 324669 ,futureTime: 68938352
,D/PollingManager( 1569): Polling alarm set to expire at: 68938352 Current Time: 324669
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,I/CheckinService( 1405): active receiver: disabled
,I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1285): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1569): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/Tethering( 1024): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1024): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
D/PollingManager( 1569): now: 324704 ,futureTime: 68938352
D/PollingManager( 1569): Polling alarm set to expire at: 68938352 Current Time: 324704
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/openssl ( 3903): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3903): Crypto mode 0 already enabled
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1569): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/CheckinService( 1405): Recording last checkin time for package unspecified as 1450658217198
D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4130): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4130): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1569): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1569): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinService( 1405): Checkin interval check for package: unspecified last checkin: 1450658217198 min interval config: 0 actual interval: 35
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/CheckinService( 1405): Checking schedule, now: 1450658217240 next: 1451251287095
,I/CheckinService( 1405): active receiver: disabled
,D/dalvikvm( 3883): GC_FOR_ALLOC freed 596K, 5% free 16434K/17224K, paused 23ms, total 23ms
,I/dalvikvm-heap( 3883): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3903): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3903): Crypto mode 0 already enabled
,D/dalvikvm( 1024): GC_EXPLICIT freed 1092K, 65% free 17928K/50604K, paused 4ms+8ms, total 87ms
,D/MobileConnectivityChangeReceiver( 4130): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4130): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3883): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 10ms, total 10ms
,I/iu.Environment( 3883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1405): Checkin interval check for package: unspecified last checkin: 1450658217198 min interval config: 0 actual interval: 201
I/CheckinService( 1405): Checking schedule, now: 1450658217402 next: 1451251287095
,I/CheckinService( 1405): active receiver: disabled
,D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1569): onServiceConnected()
,D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1569): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1024): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1569
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1569): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1024): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1569
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1024): Activity reported stop, but no longer stopping: ActivityRecord{42be4418 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/WifiStateMachine( 1024): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1024): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1024):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1024): handleMessage: X
,D/ConnectivityService( 1024): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1024): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1086): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1304): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1304): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4179): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1024): sending alarm Alarm{4321be68 type 3 android}
,I/ActivityManager( 1024): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4329 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/InputReader( 1024): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
,I/Launcher( 1318): Deferring update until onResume
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
I/Launcher( 1318): Deferring update until onResume
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
,I/Babel   ( 4329): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4329): MmsConfig.loadMmsSettings
I/Babel   ( 4329): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4329): MmsConfig.loadFromDatabase
,E/Babel   ( 4329): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4329): MmsConfig.loadFromResources
,E/Babel   ( 4329): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4329): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 4329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1024): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4366 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1024): Killing 3472:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4385 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1024): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4403 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 3903:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024): Killing 4110:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4366): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4403): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4403): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4403): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4403): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4403): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x01d3
,I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 215 ms] updated apps [took 214 ms] 
,I/dalvikvm( 4403): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4403): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4403): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4403): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4403): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4403): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4403): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4403): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4403): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4403): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4403): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4403): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4403): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1024): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4438 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4403): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4403): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4403): Skipping gmscore version check
,D/Finsky  ( 4403): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4403): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4403): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4403): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1024): Killing 4130:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1405): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1405): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1405): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4438): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x429cd260, skipping init
I/openssl ( 4438): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4438): Crypto mode 0 already enabled
,I/ActivityManager( 1024): Killing 4155:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4403): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4403): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1405): GC_CONCURRENT freed 2163K, 31% free 12026K/17224K, paused 3ms+5ms, total 38ms
,I/Icing   ( 1405): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1405): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450658226
,D/CaptivePortalTracker( 1024): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1024): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 1024): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1024): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1024): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1024): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1024): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1024): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42bf4200 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42fc18f8 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6 ,
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4,
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 9,
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44871a70 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42aa5da0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44775618 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{43285110 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b32108 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{444d8320 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{43215920 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1024): cleanup(): cleared. Last call was 476154 ms ago
,I/ActivityManager( 1024): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4481 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1024): Killing 4179:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42b62a60 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b6c368 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b48278 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{4320dfb8 type 2 android}
,V/AlarmManager( 1024): sending alarm Alarm{43205868 type 2 android}
,D/ConnectivityService( 1024): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1024): Done.
,D/ConnectivityService( 1024): Setting timer for 720seconds
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{43ad53b0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44789528 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44ac4110 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42d5c838 type 2 com.google.android.gms}
,D/ConnectivityService( 1024): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1304): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1024): sending alarm Alarm{444b2d90 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{43ba5b80 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{4323ed48 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1024): GC_CONCURRENT freed 1960K, 65% free 18081K/50604K, paused 8ms+9ms, total 93ms
,V/AlarmManager( 1024): sending alarm Alarm{4476acf0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b7ca38 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b63c88 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b5aa48 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b3b960 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b2d3c8 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{444b2e68 type 1 com.android.deskclock}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{44b16440 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{448a1c00 type 3 android}
,I/ProcessStatsService( 1024): Prepared write state in 22ms
,I/ProcessStatsService( 1024): Prepared write state in 31ms
,I/ProcessStatsService( 1024): Pruning old procstats: /data/system/procstats/state-2015-12-20-04-15-29.bin
,V/AlarmManager( 1024): sending alarm Alarm{444b2f40 type 2 android}
,D/ConnectivityService( 1024): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1024): sending alarm Alarm{444b3018 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{444b3068 type 3 com.google.android.gms}
,V/AlarmManager( 1024): sending alarm Alarm{444b3190 type 0 com.google.android.gms}
,D/ConnectivityService( 1024): Done.
,D/ConnectivityService( 1024): Setting timer for 720seconds
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1405): Aggregate from 1450658214152 (log), 1450657927897 (data)
,W/dalvikvm( 1356): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1356): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1356): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1356): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1356): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1356): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1356): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1356): GC_EXPLICIT freed 1180K, 40% free 10369K/17224K, paused 2ms+6ms, total 33ms
,V/AlarmManager( 1024): sending alarm Alarm{432caba8 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{43260328 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42b9bb78 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42ba5b68 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1024): sending alarm Alarm{43285dc0 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1024): sending alarm Alarm{43278260 type 2 com.google.android.gms}
D/CCE     ( 1569): Registering with Alarm Manager to restart CCE
D/ConnectivityService( 1024): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1086): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1304): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1086): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1086): updateTelephonySignalStrength:  No service
V/AlarmManager( 1024): sending alarm Alarm{42dde8c8 type 3 android}
D/AndroidRuntime( 4565): 
D/AndroidRuntime( 4565): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4565): CheckJNI is OFF
D/dalvikvm( 4565): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4565): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4565): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4565): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4565): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4565): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4565): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4565): failed to load memtrack module: -2
D/AndroidRuntime( 4565): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1024): Force stopping com.test.thalitest appid=10501 user=-1: uninstall pkg
I/ActivityManager( 1024): Killing 4219:com.google.android.gms.unstable/u0a22 (adj 15): empty for 1800s
W/ContextImpl( 1248): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings( 1024): Skipping PackageSetting{42c8bb78 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1024): Force stopping com.test.thalitest appid=10501 user=0: pkg removed
D/dalvikvm( 2282): GC_EXPLICIT freed 5504K, 44% free 9649K/17224K, paused 2ms+5ms, total 57ms
I/InputReader( 1024): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2314): GC_EXPLICIT freed 2671K, 44% free 9777K/17224K, paused 2ms+3ms, total 119ms
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1318): GC_EXPLICIT freed 3236K, 33% free 11595K/17224K, paused 2ms+5ms, total 114ms
I/Launcher( 1318): Deferring update until onResume
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450660021
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
D/dalvikvm( 1405): GC_EXPLICIT freed 782K, 31% free 11928K/17224K, paused 25ms+14ms, total 163ms
W/SQLiteConnectionPool( 1405): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 4366): Cleaning up data for package: com.test.thalitest
I/Launcher( 1318): Deferring update until onResume
D/dalvikvm( 1024): GC_EXPLICIT freed 1374K, 65% free 18010K/50604K, paused 17ms+11ms, total 190ms
D/dalvikvm( 1024): WAIT_FOR_CONCURRENT_GC blocked 132ms
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
I/ActivityManager( 1024): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4595 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450660021
I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
D/BackupManagerService( 1024): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1024): removePackageParticipantsLocked: uid=10501 #1
D/dalvikvm( 1024): GC_EXPLICIT freed 562K, 65% free 18006K/50604K, paused 3ms+14ms, total 176ms
D/AndroidRuntime( 4565): Shutting down VM
D/dalvikvm( 4565): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 4595): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1024): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4617 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4595): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4617): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4403): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4403): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4403): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1405): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1405): Module APK com.google.android.play.games already loaded
D/dalvikvm( 3883): GC_FOR_ALLOC freed 25K, 4% free 20464K/21204K, paused 14ms, total 14ms
D/ChimeraCfgMgr( 1405): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1405): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1405): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1405): Clearing selected account for com.test.thalitest
E/SQLiteLog( 1405): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1405): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1405): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1405): threadid=38: thread exiting with uncaught exception (group=0x420f7d40)
E/DriveAsyncService( 1405): disk I/O error (code 3850)
E/DriveAsyncService( 1405): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1405): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1405): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1405): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1405): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1405): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1405): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1405): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1405): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1405): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1405): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1405): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1405): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1405): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1356): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/AndroidRuntime( 1405): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 1405): Process: com.google.android.gms, PID: 1405
E/AndroidRuntime( 1405): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1405): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1405): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1405): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1405): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1405): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1405): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1405): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1405): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1405): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1405): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 1405): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/AndroidRuntime( 1405): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1405): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1405): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1405): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1405): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 1405): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1405): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1405): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1405): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/PhenotypeInitializer( 1405): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1405): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1405): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1405): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1405): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1405): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1405): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1405): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1405): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1405): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1405): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1405): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1405): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1405): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1405): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1405): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AndroidRuntime( 1356): Shutting down VM
W/dalvikvm( 1356): threadid=1: thread exiting with uncaught exception (group=0x420f7d40)
I/Process ( 1405): Sending signal. PID: 1405 SIG: 9
E/AndroidRuntime( 1356): FATAL EXCEPTION: main
E/AndroidRuntime( 1356): Process: com.google.process.gapps, PID: 1356
E/AndroidRuntime( 1356): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1356): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1356): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1356): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1356): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1356): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1356): 	... 10 more
E/DropBoxManagerService( 1024): Can't write: system_app_crash
E/DropBoxManagerService( 1024): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1024): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1024): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1024): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1024): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1024): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1024): 	... 5 more
E/DropBoxManagerService( 1024): Can't write: system_app_crash
E/DropBoxManagerService( 1024): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1024): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1024): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1024): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1024): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1024): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1024): 	... 5 more
I/Process ( 1356): Sending signal. PID: 1356 SIG: 9
I/ActivityManager( 1024): Process com.google.android.gms (pid 1405) has died.
D/WifiService( 1024): Client connection lost with reason: 4
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
D/WifiService( 1024): Client connection lost with reason: 4
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10998ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20998ms
I/ActivityManager( 1024): Process com.google.process.gapps (pid 1356) has died.
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30995ms
E/SQLiteDatabase( 4617): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4617): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4617): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4617): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4617): threadid=10: thread exiting with uncaught exception (group=0x420f7d40)
E/AndroidRuntime( 4617): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4617): Process: com.android.keychain, PID: 4617
E/AndroidRuntime( 4617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4617): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4617): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4617): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4617): Sending signal. PID: 4617 SIG: 9
E/DropBoxManagerService( 1024): Can't write: system_app_crash
E/DropBoxManagerService( 1024): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1024): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1024): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1024): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1024): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1024): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1024): 	... 5 more
I/ActivityManager( 1024): Process com.android.keychain (pid 4617) has died.
W/ActivityManager( 1024): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 40968ms

```
