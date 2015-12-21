#### Test 50650278d1b06e8_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main,
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
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
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3984
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4000 uid=10500 gids={50500, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3984): Shutting down VM
D/dalvikvm( 3984): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4000): Binding Chromium to main looper Looper (main, tid 1) {41fdfeb0}
I/LibraryLoader( 4000): Expected native library version number "",actual native library version number ""
I/chromium( 4000): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4000): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423f7420:true
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
W/AwContents( 4000): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4000): showStatusIcon on inactive InputConnection
I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,374
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +339ms (total +375ms)
D/JsMessageQueue( 4000): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4000): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe4180
D/dalvikvm( 4000): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe4180
D/jxcore_app_log( 4000): JniHelper::setJavaVM(0x4162ffa8), pthread_self() = 1614711200
D/JX-Cordova( 4000): jxcore cordova android initializing
D/dalvikvm( 4000): GC_CONCURRENT freed 2763K, 17% free 14378K/17224K, paused 1ms+3ms, total 47ms
D/dalvikvm( 4000): GC_FOR_ALLOC freed 226K, 17% free 14362K/17224K, paused 24ms, total 24ms
D/dalvikvm( 4000): GC_FOR_ALLOC freed 188K, 17% free 14387K/17224K, paused 24ms, total 24ms
I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.220MB for 144892-byte allocation
D/dalvikvm( 4000): GC_FOR_ALLOC freed 253K, 17% free 14435K/17368K, paused 24ms, total 24ms
I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.336MB for 217334-byte allocation
D/dalvikvm( 4000): GC_FOR_ALLOC freed 369K, 18% free 14510K/17584K, paused 24ms, total 24ms
I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.513MB for 325996-byte allocation
D/dalvikvm( 4000): GC_FOR_ALLOC freed 568K, 19% free 14631K/17904K, paused 25ms, total 25ms
I/dalvikvm-heap( 4000): Grow heap (frag case) to 16.787MB for 488990-byte allocation
D/dalvikvm( 4000): GC_FOR_ALLOC freed 867K, 20% free 14808K/18384K, paused 26ms, total 26ms
I/dalvikvm-heap( 4000): Grow heap (frag case) to 17.193MB for 733480-byte allocation
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 1284K, 22% free 15065K/19104K, paused 26ms, total 26ms
,D/dalvikvm( 4000): GC_CONCURRENT freed 1674K, 20% free 15439K/19104K, paused 3ms+4ms, total 41ms
,D/dalvikvm( 4000): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 369K, 20% free 15394K/19104K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 18.639MB for 1650320-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 1669K, 23% free 15966K/20716K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 1380K, 23% free 16050K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 20.067MB for 2475476-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 1870K, 28% free 16773K/23136K, paused 1ms+3ms, total 39ms
,D/dalvikvm( 4000): GC_CONCURRENT freed 2385K, 27% free 16978K/23136K, paused 2ms+6ms, total 41ms
,D/dalvikvm( 4000): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 483K, 27% free 16893K/23136K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4000): Grow heap (frag case) to 22.071MB for 3713210-byte allocation
,D/dalvikvm( 4000): GC_CONCURRENT freed 291K, 24% free 20440K/26764K, paused 4ms+9ms, total 47ms
,D/dalvikvm( 4000): GC_FOR_ALLOC freed 3031K, 33% free 17968K/26764K, paused 27ms, total 28ms
,W/jxcore-log( 4000): Initializing JXcore engine
,W/jxcore-log( 4000): JXcore engine is ready
,D/dalvikvm( 4000): GC_CONCURRENT freed 355K, 24% free 20599K/26764K, paused 1ms+2ms, total 27ms
,D/dalvikvm( 4000): WAIT_FOR_CONCURRENT_GC blocked 24ms
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
D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=4000, uid=10500
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4000): Radios toggled
I/jxcore-log( 4000): 
D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4000): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4000): 
I/jxcore-log( 4000): Perf Test app loaded loaded
I/jxcore-log( 4000): 
,I/jxcore-log( 4000): check test folder
I/jxcore-log( 4000): 
,I/jxcore-log( 4000): found test : ./testFindPeers.js
I/jxcore-log( 4000): 
,D/TCMD    (  476): NL - Read 1000 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
,D/Tethering( 1021): InitialState.processMessage what=4
,V/ConnectivityService( 1021): WiFi NOT Tethered!
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,I/jxcore-log( 4000): found test : ./testSendData.js
I/jxcore-log( 4000): 
D/WifiP2pService( 1021): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  476): NL - Read 60 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 21
,D/TCMD    (  476): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 311936
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,I/jxcore-log( 4000): found test : ./testSendData2.js
I/jxcore-log( 4000): 
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x61221cb0 clazz=0x63a00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1021): DisconnectingState
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1021): handleMessage: X
E/jxcore  ( 4000): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4000): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
I/Choreographer( 4000): Skipped 111 frames!  The application may be doing too much work on its main thread.
I/chromium( 4000): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection lost
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1363): Read error: ssl=0x62ee2c58: I/O error during system call, Connection timed out
,V/NativeCrypto( 1363): SSL shutdown failed: ssl=0x62ee2c58: I/O error during system call, Broken pipe
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1021): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1217): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1217): INET_CONDITION=0 ,activeNet=null
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
,I/ModemStatsDSDetect( 1217): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1217): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1217): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1217): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1152): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
,D/TCMD    (  476): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1152): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1152): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1152): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  476): NL - Read 312 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 192 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 1000 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1152): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
,D/TCMD    (  476): Listening for incoming client connection request
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,I/wpa_supplicant( 1152): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  476): NL - Read 1000 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
,D/TCMD    (  476): Listening for incoming client connection request
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195848880
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
,E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection established
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1021): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-52ms what=147462 obj=android.net.wifi.StateChangeResult@429fdda0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-37ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43963308 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427d7618 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427d7618 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 b
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 b
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 0c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 0c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 b8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 b8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428015f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428015f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@428015f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/TCMD    (  476): NL - Read 60 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 20
,D/TCMD    (  476): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): DHCP successful
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1021): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1021): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1021): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState enter
D/WifiStateMachine( 1021): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1021): WiFi NOT Tethered!
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@420bf4d0
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1217): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1217): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1217): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1021): WiFi NOT Tethered!
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@420bf4d0
I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1217): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1217): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1217): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1309): No entry in secure settings for enhanced location services: false
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1570): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1309): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/openssl ( 3911): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3911): Crypto mode 0 already enabled
,E/ActivityThread( 1570): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1570): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1570): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1570): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1570): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1570): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1570): [debug] > CusSM.onRadioDown
I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4140 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/dalvikvm( 1021): GC_EXPLICIT freed 1648K, 65% free 17966K/50484K, paused 4ms+10ms, total 92ms
,V/MmsConfig( 4140): mnc/mcc: 
V/MmsConfig( 4140): tag: bool value: enabledMMS - true
,V/MmsConfig( 4140): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4140): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4140): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4140): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4140): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4140): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4140): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4140): tag: int value: recipientLimit - 20
V/MmsConfig( 4140): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4140): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4140): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4140): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4140): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4140): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4140): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4140): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4140): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4164 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 3759:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4164): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4164): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4164): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4164): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4179 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3834:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1414): Checkin interval check for package: unspecified last checkin: 1450655432594 min interval config: 0 actual interval: 300026
,I/CheckinService( 1414): Checking schedule, now: 1450655732629 next: 1450655462555
,I/CheckinService( 1414): active receiver: enabled
,I/CheckinService( 1414): Preparing to send checkin request
,I/EventLogService( 1414): Accumulating logs since 1450655429005
,I/CheckinRequestBuilder( 1414): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1414): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4196 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3851:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+4ms, total 28ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 3ms+2ms, total 21ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4196): Binding Chromium to main looper Looper (main, tid 1) {41fe3b70}
,I/LibraryLoader( 4196): Expected native library version number "",actual native library version number ""
,I/chromium( 4196): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4196): Initializing chromium process, renderers=0
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4213 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
E/AudioManagerAndroid( 4196): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4196): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4196): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4196): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4196): Local Branch: 
I/Adreno-EGL( 4196): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4196): Local Patches: NONE
I/Adreno-EGL( 4196): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/dalvikvm( 4213): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4213): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4213): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4213): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4213): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4213): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4213): install
,I/MultiDex( 4213): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4213): loading existing secondary dex files
,I/MultiDex( 4213): load found 3 secondary dex files
,I/MultiDex( 4213): install done
,W/chromium( 4196): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/dalvikvm( 4213): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4213): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4213): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4213): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4213): VFY: unable to resolve instance field 36
,D/dalvikvm( 4213): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4213): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4213): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4213): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4213): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4213): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4213): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fde080
,D/dalvikvm( 4213): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fde080
,D/dalvikvm( 4213): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fde080, skipping init
D/dalvikvm( 4213): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fde080
,D/dalvikvm( 4213): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fde080
,V/JNIHelp ( 4213): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAV2    ( 4196): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  263): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4196): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4213): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fde080
,D/dalvikvm( 4213): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fde080
D/dalvikvm( 4213): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fde080
,D/dalvikvm( 4213): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fde080
,I/ProviderInstaller( 4213): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 4196): Starting up...
,I/dalvikvm( 4213): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4213): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4213): VFY: replacing opcode 0x6e at 0x00ce
,I/ImageResourceManager( 3891): ImageResourceManager: uninitalized
I/dalvikvm( 4213): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4213): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4213): VFY: replacing opcode 0x6e at 0x000d
,I/iu.Environment( 3891): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1021): Killing 3866:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 3911): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3911): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4164): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4164): onReceive CONNECTIVITY_CHANGE networkType=1
,I/dalvikvm( 4213): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4213): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4213): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4213): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4213): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4213): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4213): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4213): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4213): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4213): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4213): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/iu.Environment( 3891): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DEBUG   ( 1570): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1570): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1570): bindWebServices(): registering our AIDL callback...
D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb511c000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb511c000
I/SundryService( 1570): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1570): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1570): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1570): onServiceConnected()
D/GetNotificationsWS( 1570): onServiceConnected(): Registered for remote service callbacks...
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,D/GetNotificationsWS( 1570): unbindWebServices(): un-registering our AIDL callback...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/WearableService( 1239): callingUid 10022, callindPid: 1239
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,E/MDM     ( 1239): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1363): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1363): Proximity feature is not enabled.
,D/LocationInitializer( 1414): Restart initialization of location
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1517282012
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/GCoreFlp( 1239): No location to return for getLastLocation()
,W/FusedLocationProvider( 1239): location=null
,D/NativeLibraryUtils( 4213): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4213): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4220a510
D/dalvikvm( 4213): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4220a510
,D/dalvikvm( 4213): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4220a510, skipping init
,D/WifiStateMachine( 1021): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/WifiStateMachine( 1021): handleMessage: X
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
D/ConnectivityService( 1021): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1021):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,W/Settings( 4213): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4213): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4269): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 4213): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4213): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 89ms
,I/Adreno-EGL( 4213): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4213): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4213): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4213): Local Branch: 
I/Adreno-EGL( 4213): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4213): Local Patches: NONE
I/Adreno-EGL( 4213): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1570): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1309): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/PollingManager( 1570): now: 341633 ,futureTime: 71437797
,D/PollingManager( 1570): Polling alarm set to expire at: 71437797 Current Time: 341633
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1309): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1570): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1570): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1570): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1570): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1570): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1570): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1570): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,I/Adreno-EGL( 4213): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4213): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4213): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4213): Local Branch: 
I/Adreno-EGL( 4213): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4213): Local Patches: NONE
I/Adreno-EGL( 4213): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/OtaApp  ( 1570): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1570): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/PollingManager( 1570): now: 341691 ,futureTime: 71437797
,D/PollingManager( 1570): Polling alarm set to expire at: 71437797 Current Time: 341691
,E/ActivityThread( 1570): Failed to find provider info for com.motorola.blur.setupprovider
I/openssl ( 3911): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3911): Crypto mode 0 already enabled
D/OtaApp  ( 1570): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1570): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1570): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1570): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1570): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1570): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1570): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1570): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MobileConnectivityChangeReceiver( 4164): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4164): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1570): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3891): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1414): Checkin interval check for package: unspecified last checkin: 1450655432594 min interval config: 0 actual interval: 301420
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/dalvikvm( 3891): GC_FOR_ALLOC freed 602K, 5% free 16434K/17224K, paused 22ms, total 27ms
,D/DEBUG   ( 1570): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1570): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1570): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1570): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,I/SundryService( 1570): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1570): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1570): onServiceConnected()
,D/GetNotificationsWS( 1570): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1570): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3911): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3911): Crypto mode 0 already enabled
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/MobileConnectivityChangeReceiver( 4164): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4164): onReceive CONNECTIVITY_CHANGE networkType=1
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/dalvikvm( 3891): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 11ms, total 11ms
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3413385231
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/iu.Environment( 3891): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1414): Checkin interval check for package: unspecified last checkin: 1450655432594 min interval config: 0 actual interval: 301502
,I/dalvikvm( 4000): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4000): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4000): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4000): Shutting down VM
,W/dalvikvm( 4000): threadid=1: thread exiting with uncaught exception (group=0x4170ed40)
,E/AndroidRuntime( 4000): FATAL EXCEPTION: main
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
D/DEBUG   ( 1570): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1570): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1570): bindWebServices(): registering our AIDL callback...
,W/ActivityManager( 1021):   Force finishing activity com.test.thalitest/.MainActivity
D/EmailService.MarketingOptInSetter( 1570): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1570): onServiceConnected()
,D/GetNotificationsWS( 1570): onServiceConnected(): Registered for remote service callbacks...
I/ActivityManager( 1021): Killing 3812:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4000): Sending signal. PID: 4000 SIG: 9
I/SundryService( 1570): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1570): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1570): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1570
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/WaitableIntentService( 1570): ServiceHandler.handleMessage: mWaitCount=0
,I/OtaApp  ( 1570): [info] > Updatetime from metadata: 10
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1570): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1570): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1570): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1570): [info] > Updatetime from metadata: 10
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1570): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1570): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
I/ActivityManager( 1021): Process com.test.thalitest (pid 4000) has died.
D/WifiService( 1021): Client connection lost with reason: 4
I/WindowState( 1021): WIN DEATH: Window{4208c650 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/OtaApp  ( 1570): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1570): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1570
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1570): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1570): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 4000 uid 10500
W/Binder  ( 1205): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1205): java.lang.NullPointerException
W/Binder  ( 1205): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1205): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1205): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1205): 	at dalvik.system.NativeStart.run(Native Method)
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/OtaApp  ( 1570): [info] > Updatetime from metadata: 10
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1570): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1570): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1570): [info] > Updatetime from metadata: 10
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1570): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1570): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1570): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1021): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,194
D/OtaApp  ( 1570): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1570): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1021): Activity reported stop, but no longer stopping: ActivityRecord{4286afa0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/Adreno-EGL( 4213): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4213): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4213): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4213): Local Branch: 
I/Adreno-EGL( 4213): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4213): Local Patches: NONE
I/Adreno-EGL( 4213): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4213): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4213): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4213): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4213): Local Branch: 
I/Adreno-EGL( 4213): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4213): Local Patches: NONE
I/Adreno-EGL( 4213): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
,V/NativeCrypto( 1414): SSL shutdown failed: ssl=0x6aac3c60: I/O error during system call, Connection timed out
,I/CheckinTask( 1414): Sending checkin request (11756 bytes)
,I/CheckinRequestBuilder( 1414): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1414): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1021): GC_EXPLICIT freed 760K, 65% free 17934K/50484K, paused 4ms+8ms, total 92ms
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
,I/CheckinTask( 1414): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1414): Checking schedule, now: 1450655735672 next: 1451248805669
,I/CheckinService( 1414): active receiver: disabled
,I/CheckinService( 1414): Checking schedule, now: 1450655735687 next: 1451248805669
,I/CheckinService( 1414): active receiver: disabled
,D/CheckinService( 1414): Recording last checkin time for package unspecified as 1450655735691
,D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1217): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1217): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1217): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1217): onReceive() - done, currentInetCondition=100
,I/GAV2    ( 4196): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4326 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/Launcher( 1321): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/Launcher( 1321): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/GCoreNlp( 1239): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4326): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4326): MmsConfig.loadMmsSettings
I/Babel   ( 4326): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4326): MmsConfig.loadFromDatabase
,E/Babel   ( 4326): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4326): MmsConfig.loadFromResources
,E/Babel   ( 4326): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4326): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4362 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1021): Killing 3498:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4383 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3911:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2337): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1021): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4401 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4140:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4362): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4401): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4401): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4401): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2337): UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
,I/dalvikvm( 4401): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4401): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4401): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4401): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4401): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4401): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4401): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4401): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4401): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4401): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4401): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4401): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4401): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4401): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4401): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4435 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4401): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4401): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4401): Skipping gmscore version check
,D/Finsky  ( 4401): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4401): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4401): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4401): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4401): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1021): Killing 4164:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1414): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1414): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1414): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4435): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe53b0, skipping init
I/openssl ( 4435): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4435): Crypto mode 0 already enabled
,I/ActivityManager( 1021): Killing 4179:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4401): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4401): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1414): GC_CONCURRENT freed 2112K, 30% free 12072K/17224K, paused 4ms+4ms, total 38ms
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1021): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1021): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1021): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1021): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1021): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/Icing   ( 1414): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1414): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450655744
,V/AlarmManager( 1021): sending alarm Alarm{4233f798 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{435965a0 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{436408a0 type 3 android}
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
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8
,V/AlarmManager( 1021): sending alarm Alarm{43e5d090 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43e445d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4231f148 type 0 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{4231c570 type 1 com.android.deskclock}
,I/ActivityManager( 1021): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4478 uid=10015 gids={50015, 1028}
,I/EventLogService( 1414): Aggregate from 1450655732653 (log), 1450654064962 (data)
,I/ActivityManager( 1021): Killing 4196:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1363): GC_EXPLICIT freed 783K, 41% free 10291K/17224K, paused 2ms+5ms, total 31ms
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
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{429955b0 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43629bf0 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43a87ca0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{429fecf8 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{429feda8 type 0 com.google.android.gms}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,I/Icing   ( 1414): Performing maintenance.
,I/Icing   ( 1414): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 1414): Performing maintenance usage 2277355 budget 1813110773 free 99.874% index free 99.915% purge? false target 1269177541
,D/dalvikvm( 1414): GC_CONCURRENT freed 2160K, 31% free 11944K/17224K, paused 3ms+5ms, total 43ms
,I/dalvikvm( 1414): Total arena pages for JIT: 15
,I/Icing   ( 1414): Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
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
,V/AlarmManager( 1021): sending alarm Alarm{4280cd98 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43629210 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43d35a48 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43588b68 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4399aa88 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43d82cd0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43e11c58 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{429fedf8 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1217): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1217): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1217): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
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
,V/AlarmManager( 1021): sending alarm Alarm{43630110 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{436c6e50 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4293df68 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4362e878 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{439d2c78 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{436301e8 type 1 com.android.deskclock}
,V/AlarmManager( 1021): sending alarm Alarm{436302c0 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,V/AlarmManager( 1021): sending alarm Alarm{434980d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42996410 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428814d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43a11e88 type 3 android}
,D/dalvikvm( 1021): GC_CONCURRENT freed 1949K, 65% free 18128K/50484K, paused 5ms+9ms, total 96ms
,V/AlarmManager( 1021): sending alarm Alarm{4319ad38 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{44117778 type 3 android}
,I/ProcessStatsService( 1021): Prepared write state in 23ms
,I/ProcessStatsService( 1021): Prepared write state in 23ms
,I/ProcessStatsService( 1021): Prepared write state in 18ms
,I/ProcessStatsService( 1021): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-39-23.bin
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
,V/AlarmManager( 1021): sending alarm Alarm{43e1be50 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43ca49a8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43a80458 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{437ad390 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4556): 
D/AndroidRuntime( 4556): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4556): CheckJNI is OFF
D/dalvikvm( 4556): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4556): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4556): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4556): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4556): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4556): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4556): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4556): failed to load memtrack module: -2
D/AndroidRuntime( 4556): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10500 user=-1: uninstall pkg
W/PackageSettings( 1021): Skipping PackageSetting{4229f218 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10500 user=0: pkg removed
D/dalvikvm( 2300): GC_EXPLICIT freed 5390K, 44% free 9648K/17224K, paused 3ms+6ms, total 52ms
D/dalvikvm( 1021): GC_EXPLICIT freed 832K, 65% free 17877K/50452K, paused 4ms+8ms, total 112ms
D/dalvikvm( 1414): GC_EXPLICIT freed 211K, 31% free 11902K/17224K, paused 56ms+5ms, total 127ms
W/SQLiteConnectionPool( 1414): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1321): GC_EXPLICIT freed 3241K, 33% free 11594K/17224K, paused 2ms+5ms, total 128ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/Launcher( 1321): Deferring update until onResume
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2337): GC_EXPLICIT freed 2675K, 44% free 9777K/17224K, paused 2ms+5ms, total 123ms
D/dalvikvm( 1021): GC_EXPLICIT freed 75K, 65% free 17886K/50452K, paused 4ms+10ms, total 109ms
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
W/GeofencerStateMachine( 1239): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 4362): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/Launcher( 1321): Deferring update until onResume
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10500 #1
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450657536
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
D/AndroidRuntime( 4556): Shutting down VM
D/dalvikvm( 4556): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
I/InternalIcingCorporaPro( 2337): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4585 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450657536
I/InternalIcingCorporaPro( 2337): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
V/AlarmManager( 1021): sending alarm Alarm{43630398 type 3 android}
V/AlarmManager( 1021): sending alarm Alarm{439f17f8 type 3 com.google.android.gms}
V/AlarmManager( 1021): sending alarm Alarm{439f1848 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1021): sending alarm Alarm{43a80038 type 2 com.google.android.gms}
W/ActiveOrDefaultContextProvider( 4585): Missing scope.enter somewhere. Returning default context
E/SQLiteDatabase( 4585): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4585): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4585): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 4585): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 4585): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 4585): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4585): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 4585): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 4585): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4585): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 4585): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4585): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 4585): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4585): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4585): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4585): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4585): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4585): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4585): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4585): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4585): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 4585): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 4585): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4585): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 4585): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 4585): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4585): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4585): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 4585): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 4585): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4585): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4585): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4585): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 4585): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4585): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4585): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4585): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4585): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4585): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4585): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4585): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4585): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4585): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4585): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 4585): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 4585): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 4585): threadid=11: thread exiting with uncaught exception (group=0x4170ed40)
E/AndroidRuntime( 4585): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4585): Process: com.google.android.apps.docs, PID: 4585
E/AndroidRuntime( 4585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4585): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4585): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4585): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 4585): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 4585): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 4585): 	at WT.run(AbstractDatabaseInstance.java:411)
I/Process ( 4585): Sending signal. PID: 4585 SIG: 9
E/DropBoxManagerService( 1021): Can't write: system_app_crash
E/DropBoxManagerService( 1021): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1021): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1021): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1021): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1021): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1021): 	... 5 more

```
