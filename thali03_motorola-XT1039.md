#### Test 5531115118861c0_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4099): 
D/AndroidRuntime( 4099): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4099): CheckJNI is OFF
D/dalvikvm( 4099): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4099): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4099): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4099): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4099): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4099): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4099): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4099): failed to load memtrack module: -2
D/AndroidRuntime( 4099): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4099
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4115 uid=10520 gids={50520, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4099): Shutting down VM
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+4ms, total 21ms
D/dalvikvm( 4099): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 3ms
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
V/WebViewChromiumFactoryProvider( 4115): Binding Chromium to main looper Looper (main, tid 1) {423859b0}
I/LibraryLoader( 4115): Expected native library version number "",actual native library version number ""
I/chromium( 4115): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4115): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d1fc98:true
I/Adreno-EGL( 4115): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4115): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4115): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4115): Local Branch: 
I/Adreno-EGL( 4115): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4115): Local Patches: NONE
I/Adreno-EGL( 4115): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4115): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4115): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4115): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4115): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4115): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4115): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4115): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4115): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4115): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4115): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4115): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4115): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4115): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4115): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4115): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4115): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4115): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4115): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4115): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4115): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4115): Enabling debug mode 0
,W/AwContents( 4115): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4115): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1022): Displayed com.test.thalitest/.MainActivity,cp,ca,403
I/ActivityManager( 1022): Displayed com.test.thalitest/.MainActivity: +372ms (total +404ms)
W/IInputConnectionWrapper( 4115): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4115): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4115): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42389e60
,D/dalvikvm( 4115): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42389e60
D/jxcore_app_log( 4115): JniHelper::setJavaVM(0x41a9ef78), pthread_self() = 1615450720
,D/JX-Cordova( 4115): jxcore cordova android initializing
,D/dalvikvm( 4115): GC_CONCURRENT freed 2720K, 17% free 14415K/17224K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 205K, 17% free 14448K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 136K, 17% free 14458K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 16.244MB for 96598-byte allocation
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 179K, 17% free 14492K/17320K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 16.324MB for 144892-byte allocation
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 253K, 17% free 14540K/17464K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 16.439MB for 217334-byte allocation
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 369K, 18% free 14614K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 16.616MB for 325996-byte allocation
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 568K, 19% free 14736K/18000K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 16.890MB for 488990-byte allocation
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 866K, 20% free 14913K/18480K, paused 26ms, total 26ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 1283K, 18% free 15170K/18480K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 17.897MB for 1100216-byte allocation
,D/dalvikvm( 4115): GC_CONCURRENT freed 1749K, 21% free 15554K/19556K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 267K, 21% free 15528K/19556K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 18.771MB for 1650320-byte allocation
,D/dalvikvm( 4115): GC_CONCURRENT freed 1763K, 25% free 16072K/21168K, paused 3ms+3ms, total 33ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 1287K, 24% free 16133K/21168K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 20.149MB for 2475476-byte allocation
,D/dalvikvm( 4115): GC_CONCURRENT freed 283K, 22% free 18468K/23588K, paused 4ms+4ms, total 46ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 4338K, 28% free 17130K/23588K, paused 34ms, total 35ms
,I/dalvikvm-heap( 4115): Grow heap (frag case) to 22.302MB for 3713210-byte allocation
,D/dalvikvm( 4115): GC_CONCURRENT freed 368K, 24% free 20687K/27216K, paused 4ms+10ms, total 65ms
,D/dalvikvm( 4115): GC_FOR_ALLOC freed 3307K, 34% free 18085K/27216K, paused 28ms, total 33ms
,W/jxcore-log( 4115): Initializing JXcore engine
,W/jxcore-log( 4115): JXcore engine is ready
,D/dalvikvm( 4115): GC_CONCURRENT freed 366K, 24% free 20737K/27216K, paused 1ms+3ms, total 27ms
,D/dalvikvm( 4115): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4115): Starting JXcore engine
,W/jxcore-log( 4115): Platform android
W/jxcore-log( 4115): 
,W/jxcore-log( 4115): Process ARCH arm
W/jxcore-log( 4115): 
,I/jxcore-log( 4115): JXcore Cordova bridge is ready!
I/jxcore-log( 4115): 
,W/jxcore-log( 4115): JXcore engine is started
,I/chromium( 4115): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4115): Toggling radios to true
I/jxcore-log( 4115): 
,D/BluetoothAdapter( 4115): enable(): BT is already enabled..!
D/WifiService( 1022): New client listening to asynchronous messages
D/WifiService( 1022): setWifiEnabled: true pid=4115, uid=10520
,E/WifiService( 1022): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1022): handleMessage: E msg.what=131145
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
I/jxcore-log( 4115): Radios toggled
I/jxcore-log( 4115): 
D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4115): Received device characteristics:
I/jxcore-log( 4115): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4115): Bluetooth name: XT1039
I/jxcore-log( 4115): Device name: motorola-XT1039
I/jxcore-log( 4115): 
I/jxcore-log( 4115): Perf Test app loaded loaded
I/jxcore-log( 4115): 
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1022): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1022): connected time updated 301666
,D/TCMD    (  477): NL - Read 1000 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 60 bytes from update socket.
D/TCMD    (  477): NL - ignore NL message, type = 21
,D/TCMD    (  477): Listening for incoming client connection request
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/Tethering( 1022): InitialState.processMessage what=4
,I/jxcore-log( 4115): check test folder
I/jxcore-log( 4115): 
,D/ConnectivityService( 1022): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/jxcore-log( 4115): found test : ./testFindPeers.js
I/jxcore-log( 4115): 
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1022): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1022): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1022): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1022): DisconnectingState
,D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131146
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1022): processMsg: DisconnectingState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection lost
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/ConnectivityService( 1022): resetConnections(wlan0, 3)
D/NetUtils( 1022): android_net_utils_resetConnections in env=0x60143a90 clazz=0x63300001 iface=wlan0 mask=0x3
,I/jxcore-log( 4115): found test : ./testSendData.js
I/jxcore-log( 4115): 
,V/NativeCrypto( 1366): Read error: ssl=0x62f1b3a0: I/O error during system call, Connection timed out
,D/WifiP2pService( 1022): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1022): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1022): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
,I/Choreographer( 4115): Skipped 116 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4115): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 1022): GC_EXPLICIT freed 22853K, 65% free 18048K/51012K, paused 4ms+11ms, total 183ms
,V/NativeCrypto( 1366): SSL shutdown failed: ssl=0x62f1b3a0: I/O error during system call, Broken pipe
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  477): NL - Read 56 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiP2pService( 1022): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@423f3ed8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@423f3ed8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@423f3ed8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: X
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1591): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1274): Active network info is not available
,D/CaptivePortalTracker( 1022): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1274): Active network info is not available
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1591): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1591): Registering with Alarm Manager to restart CCE
D/PollingManager( 1591): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1591): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1591): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4212 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,V/MmsConfig( 4212): mnc/mcc: 
V/MmsConfig( 4212): tag: bool value: enabledMMS - true
,V/MmsConfig( 4212): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4212): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4212): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4212): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4212): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4212): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4212): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4212): tag: int value: recipientLimit - 20
V/MmsConfig( 4212): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4212): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4212): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 4212): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4212): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4212): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4212): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4212): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4212): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1022): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4232 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1022): Killing 3913:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4232): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4232): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4232): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4232): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4245 uid=10056 gids={50056, 3003, 1028, 1015}
I/ActivityManager( 1022): Killing 3929:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4258 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3945:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4258): Binding Chromium to main looper Looper (main, tid 1) {4237eac8}
,I/LibraryLoader( 4258): Expected native library version number "",actual native library version number ""
,I/chromium( 4258): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4258): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4258): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4258): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4258): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4258): Local Branch: 
I/Adreno-EGL( 4258): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4258): Local Patches: NONE
I/Adreno-EGL( 4258): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4258): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4258): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4258): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4258): Starting up...
,I/ImageResourceManager( 3971): ImageResourceManager: uninitalized
,I/iu.Environment( 3971): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3971): SYNC; picasa accounts
I/ActivityManager( 1022): Killing 3889:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1393): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1393): num queued entries: 0
,I/iu.UploadsManager( 1393): num updated entries: 0
,I/iu.SyncManager( 1393): NEXT; no task
,D/DEBUG   ( 1591): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1591): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1591): bindWebServices(): registering our AIDL callback...
,I/iu.UploadsManager( 3971): num queued entries: 0
,I/iu.UploadsManager( 3971): num updated entries: 0
,D/EmailService.MarketingOptInSetter( 1591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/iu.SyncManager( 3971): NEXT; no task
,D/WaitableIntentService( 1591): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1591): onServiceConnected()
D/GetNotificationsWS( 1591): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1591): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4232): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4232): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3971): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/dalvikvm( 4115): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4115): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4115): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4115): Shutting down VM
,W/dalvikvm( 4115): threadid=1: thread exiting with uncaught exception (group=0x41ab0d40)
E/AndroidRuntime( 4115): FATAL EXCEPTION: main
E/AndroidRuntime( 4115): Process: com.test.thalitest, PID: 4115
E/AndroidRuntime( 4115): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4115): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4115): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4115): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4115): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4115): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4115): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4115): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4115): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4115): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4115): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4115): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4115): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4115): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4115): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4115): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4115): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1022):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1022): Killing 3481:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4115): Sending signal. PID: 4115 SIG: 9
,I/ActivityManager( 1022): Process com.test.thalitest (pid 4115) has died.
,I/WindowState( 1022): WIN DEATH: Window{4485ac90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1022): Client connection lost with reason: 4
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1591): [info] > Updatetime from metadata: 10
,D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1591): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1591): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1022): Got RemoteException sending setActive(false) notification to pid 4115 uid 10520
,W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
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
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/GAV2    ( 4258): Thread[GAThread,5,main]: No campaign data found.
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
,D/TCMD    (  477): NL - Read 56 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
,D/TCMD    (  477): Listening for incoming client connection request
I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  477): NL - Read 312 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
,D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 88 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs=',
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
,D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 1000 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
,D/TCMD    (  477): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  477): NL - Read 80 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 80 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/TCMD    (  477): NL - Read 68 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  477): NL - Read 1000 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
,D/TCMD    (  477): Listening for incoming client connection request
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1219536048
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147459
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection established
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1022): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-50ms what=147462 obj=android.net.wifi.StateChangeResult@4243c560 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-42ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@424c1df8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=196612
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1022): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426b9a68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426b9a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/WifiP2pService( 1022): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/TCMD    (  477): NL - Read 56 bytes from update socket.
D/TCMD    (  477): NL - message type is RTM_NEWLINK
D/TCMD    (  477): Listening for incoming client connection request
D/WifiStateMachine( 1022): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): handleMessage: X
,D/TCMD    (  477): NL - Read 60 bytes from update socket.
D/TCMD    (  477): NL - ignore NL message, type = 20
,D/TCMD    (  477): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-6ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1022): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): DHCP successful
D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1022): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1022): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1022): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState enter
D/WifiStateMachine( 1022): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=151572
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1022): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=135190
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1022): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1022): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState enter
,D/WifiStateMachine( 1022): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1022): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@4248aae0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1022): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,V/ConnectivityService( 1022): WiFi NOT Tethered!
,D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@4248aae0
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
I/CheckinService( 1393): Checkin interval check for package: unspecified last checkin: 1452159770954 min interval config: 0 actual interval: 304632
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/CheckinService( 1393): Checking schedule, now: 1452160075600 next: 1452159800930
,I/CheckinService( 1393): active receiver: enabled
,I/CheckinService( 1393): Preparing to send checkin request
,I/EventLogService( 1393): Accumulating logs since 1452159767347
,I/CheckinRequestBuilder( 1393): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1393): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1022): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4397 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4397): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4397): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4397): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4397): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4397): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4397): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4397): install
,I/MultiDex( 4397): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4397): loading existing secondary dex files
,I/MultiDex( 4397): load found 3 secondary dex files
,I/MultiDex( 4397): install done
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4397): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4397): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4397): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4397): VFY: unable to resolve instance field 36
,D/dalvikvm( 4397): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4397): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4397): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4397): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4397): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4397): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42384ad8
D/dalvikvm( 4397): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42384ad8
,D/dalvikvm( 4397): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42384ad8, skipping init
,D/dalvikvm( 4397): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42384ad8
D/dalvikvm( 4397): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42384ad8
,V/JNIHelp ( 4397): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4397): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42384ad8
D/dalvikvm( 4397): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42384ad8
,D/dalvikvm( 4397): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42384ad8
,D/dalvikvm( 4397): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42384ad8
,I/ProviderInstaller( 4397): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1225): callingUid 10022, callindPid: 1225
,E/MDM     ( 1225): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1366): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1366): Proximity feature is not enabled.
,D/LocationInitializer( 1393): Restart initialization of location
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
,I/dalvikvm( 4397): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4397): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4397): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4397): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4397): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4397): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4397): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4397): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4397): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4397): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4397): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4397): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4397): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4397): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4397): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4397): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4397): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52ad000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52ad000
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
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=1717859451
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4397): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4257b238
,D/dalvikvm( 4397): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4257b238
,D/dalvikvm( 4397): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4257b238, skipping init
,D/NativeLibraryUtils( 4397): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4397): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityService( 1022): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4435): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4397): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4397): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 90ms
,I/Adreno-EGL( 4397): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4397): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4397): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4397): Local Branch: 
I/Adreno-EGL( 4397): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4397): Local Patches: NONE
I/Adreno-EGL( 4397): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4397): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4397): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4397): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4397): Local Branch: 
I/Adreno-EGL( 4397): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4397): Local Patches: NONE
I/Adreno-EGL( 4397): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=73037502
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0,
,W/Settings( 4397): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/Adreno-EGL( 4397): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4397): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4397): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4397): Local Branch: 
I/Adreno-EGL( 4397): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4397): Local Patches: NONE
I/Adreno-EGL( 4397): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4397): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4397): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4397): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4397): Local Branch: 
I/Adreno-EGL( 4397): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4397): Local Patches: NONE
I/Adreno-EGL( 4397): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1393): Classify the device as Phone.
,V/NativeCrypto( 1393): SSL shutdown failed: ssl=0x6b9e1b60: I/O error during system call, Connection timed out
,I/CheckinTask( 1393): Sending checkin request (11805 bytes)
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4380
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4381
W/ProcessCpuTracker( 1022): Skipping unknown process pid 4383
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4426
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4451
,D/WifiStateMachine( 1022): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
D/WifiStateMachine( 1022): processMsg: ConnectedState
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1022): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1022):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1022): handleMessage: X
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1393): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1393): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1393): Classify the device as Phone.
,I/CheckinTask( 1393): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1393): Checking schedule, now: 1452160078521 next: 1452753148509
,I/CheckinService( 1393): active receiver: disabled
,D/CheckinService( 1393): Recording last checkin time for package unspecified as 1452160078537
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1591): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1591): now: 348150 ,futureTime: 44641624
,D/PollingManager( 1591): Polling alarm set to expire at: 44641624 Current Time: 348151
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1591): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1591): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1591): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1591): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
D/PollingManager( 1591): now: 348202 ,futureTime: 44641624
,D/PollingManager( 1591): Polling alarm set to expire at: 44641624 Current Time: 348203
,I/openssl ( 3993): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3993): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4232): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/dalvikvm( 1591): GC_CONCURRENT freed 2013K, 38% free 10703K/17224K, paused 7ms+3ms, total 42ms
D/dalvikvm( 1591): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 1591): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/OtaApp  ( 1591): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1591): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MobileConnectivityChangeReceiver( 4232): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 1022): GC_EXPLICIT freed 1453K, 65% free 18018K/51012K, paused 6ms+10ms, total 97ms
,E/ActivityThread( 1591): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1591): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1254): Column apn id key is 'apn_id'
,I/iu.Environment( 3971): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/OtaApp  ( 1591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1591): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,I/iu.UploadsManager( 3971): num queued entries: 0
,I/iu.UploadsManager( 3971): num updated entries: 0
,I/iu.SyncManager( 3971): NEXT; no task
,D/OtaApp  ( 1591): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1591): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.Environment( 1393): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1393): num queued entries: 0
D/OtaApp  ( 1591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.UploadsManager( 1393): num updated entries: 0
,D/DEBUG   ( 1591): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.SyncManager( 1393): NEXT; no task
,W/ContextImpl( 1591): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1591): bindWebServices(): registering our AIDL callback...
I/SundryService( 1591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1591): onServiceConnected()
,D/GetNotificationsWS( 1591): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1591): ServiceHandler.handleMessage: mWaitCount=0
,D/dalvikvm( 3971): GC_CONCURRENT freed 635K, 5% free 16459K/17224K, paused 2ms+2ms, total 32ms
D/dalvikvm( 3971): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/GetNotificationsWS( 1591): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3993): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3993): Crypto mode 0 already enabled
I/dalvikvm-heap( 3971): Grow heap (frag case) to 19.842MB for 1821008-byte allocation
,D/MobileConnectivityChangeReceiver( 4232): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4232): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3971): GC_FOR_ALLOC freed 40K, 5% free 18199K/19004K, paused 11ms, total 11ms
,I/iu.Environment( 3971): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1591): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1591): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1591): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1591): onServiceConnected()
,D/WaitableIntentService( 1591): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1591): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1591): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1591
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1591): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1591): [info] > Updatetime from metadata: 10
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1591): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1591): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1591): [info] > Updatetime from metadata: 10
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1591): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1591): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
D/OtaApp  ( 1591): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1591
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1591): [info] > Updatetime from metadata: 10
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1591): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1591): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1591): [info] > Updatetime from metadata: 10
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1591): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1591): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1022): Activity reported stop, but no longer stopping: ActivityRecord{42d91400 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1298): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1298): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1022): sending alarm Alarm{440cdf78 type 3 android}
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4494 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/Launcher( 1310): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/Launcher( 1310): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4494): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4494): MmsConfig.loadMmsSettings
,I/Babel   ( 4494): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4494): MmsConfig.loadFromDatabase
,E/Babel   ( 4494): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4494): MmsConfig.loadFromResources
,E/Babel   ( 4494): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4494): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4494): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1022): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4530 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1022): Killing 4082:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4548 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3993:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2311): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4567 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4212:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4530): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4567): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4567): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4567): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4567): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4567): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x01d3
,I/InternalIcingCorporaPro( 2311): UpdateCorporaTask done [took 211 ms] updated apps [took 211 ms] 
,I/dalvikvm( 4567): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4567): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4567): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4567): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4567): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4567): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4567): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4567): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4567): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4567): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4567): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4567): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4567): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1022): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4601 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4567): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4567): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4567): Skipping gmscore version check
,D/Finsky  ( 4567): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4567): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4567): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4567): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1022): Killing 4232:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1393): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1393): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1393): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4601): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4238b088, skipping init
I/openssl ( 4601): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4601): Crypto mode 0 already enabled
,I/ActivityManager( 1022): Killing 4245:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4567): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4567): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1393): GC_CONCURRENT freed 2112K, 31% free 12052K/17224K, paused 3ms+5ms, total 38ms
,I/Icing   ( 1393): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1393): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452160087
,D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1022): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker( 1022): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1022): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1022): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1022): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1022): sending alarm Alarm{440c63f8 type 2 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{42bcc3f8 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{43f76718 type 3 android}
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
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4
,V/AlarmManager( 1022): sending alarm Alarm{44163920 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4411db78 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4306aef8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{44c6f2b8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42c2e1b0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43f6e388 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42bce9a8 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{441b6898 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{44959f48 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42c70378 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{440c5960 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{440c58d0 type 1 com.android.deskclock}
,D/ConnectivityService( 1022): Done.
,I/LaunchCheckinHandler( 1022): cleanup(): cleared. Last call was 714671 ms ago
,I/ActivityManager( 1022): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4661 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1022): Setting timer for 720seconds
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+8ms, total 39ms
,I/ActivityManager( 1022): Killing 4258:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+7ms, total 38ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+4ms, total 20ms
,V/AlarmManager( 1022): sending alarm Alarm{42c99c90 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{442ceda8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42bd64d8 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1298): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1022): sending alarm Alarm{4451b5c8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{448461c0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42c1f6b0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{444f7250 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42d7c7d0 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{437f7eb0 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{447ab578 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{425c88f8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{447b71d8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{448b5938 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43e2c6d0 type 3 android}
,I/ProcessStatsService( 1022): Prepared write state in 19ms
,I/ProcessStatsService( 1022): Prepared write state in 22ms
,I/ProcessStatsService( 1022): Pruning old procstats: /data/system/procstats/state-2016-01-06-11-20-42.bin
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
,V/AlarmManager( 1022): sending alarm Alarm{4482c548 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{4350e688 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4451b778 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{4451b7c8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4451b818 type 3 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{44851c38 type 0 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{4451b6a0 type 1 com.android.deskclock}
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,D/dalvikvm( 1022): GC_CONCURRENT freed 2086K, 65% free 18152K/51012K, paused 25ms+9ms, total 124ms
,I/EventLogService( 1393): Aggregate from 1452160075619 (log), 1452159577374 (data)
,D/dalvikvm( 1366): GC_EXPLICIT freed 1350K, 41% free 10314K/17224K, paused 3ms+5ms, total 34ms
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{4482d2c0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42c1f400 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4723): 
D/AndroidRuntime( 4723): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4723): CheckJNI is OFF
D/dalvikvm( 4723): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4723): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4723): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4723): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4723): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4723): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4723): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4723): failed to load memtrack module: -2
D/AndroidRuntime( 4723): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10520 user=-1: uninstall pkg
W/PackageSettings( 1022): Skipping PackageSetting{4264c3e8 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10520 user=0: pkg removed
D/dalvikvm( 2279): GC_EXPLICIT freed 5391K, 44% free 9649K/17224K, paused 2ms+5ms, total 37ms
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452161862
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2311): GC_EXPLICIT freed 2757K, 43% free 9817K/17224K, paused 2ms+8ms, total 123ms
D/dalvikvm( 1393): GC_EXPLICIT freed 804K, 31% free 11925K/17224K, paused 4ms+6ms, total 152ms
W/SQLiteConnectionPool( 1393): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1022): GC_EXPLICIT freed 804K, 65% free 17978K/51008K, paused 4ms+12ms, total 149ms
D/dalvikvm( 1310): GC_EXPLICIT freed 3236K, 33% free 11594K/17224K, paused 2ms+6ms, total 149ms
I/Launcher( 1310): Deferring update until onResume
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
D/VoicemailCleanupService( 4530): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/Launcher( 1310): Deferring update until onResume
I/InternalIcingCorporaPro( 2311): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452161862
I/ActivityManager( 1022): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4755 uid=10059 gids={50059, 3003, 1028, 1015}
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10520 #1
D/dalvikvm( 1022): GC_EXPLICIT freed 567K, 65% free 18041K/51008K, paused 5ms+15ms, total 182ms
I/InternalIcingCorporaPro( 2311): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
D/AndroidRuntime( 4723): Shutting down VM
D/dalvikvm( 4723): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4755): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 4755): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4777 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 4777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4567): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4567): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1393): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1393): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1393): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1393): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1393): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1393): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1393): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1393): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1393): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/NetworkScheduler.SchedulerReceiver( 1366): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1366): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Icing   ( 1393): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1393): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/gH_CompatibleDatabase( 1393): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1393): threadid=53: thread exiting with uncaught exception (group=0x41ab0d40)
W/dalvikvm( 1393): threadid=47: thread exiting with uncaught exception (group=0x41ab0d40)
I/Process ( 1393): Sending signal. PID: 1393 SIG: 9
E/SQLiteLog( 1393): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager( 1022): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4806 uid=10058 gids={50058}
E/JavaBinder( 1022): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 1000ms
V/AlarmManager( 1022): sending alarm Alarm{4267b630 type 2 com.motorola.ccc.cce}
W/ActivityManager( 1022): Exception when starting service com.google.android.gms/.icing.proxy.AppsMonitorIntentService
W/ActivityManager( 1022): android.os.TransactionTooLargeException
W/ActivityManager( 1022): 	at android.os.BinderProxy.transact(Native Method)
W/ActivityManager( 1022): 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:858)
W/ActivityManager( 1022): 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1414)
W/ActivityManager( 1022): 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1324)
W/ActivityManager( 1022): 	at com.android.server.am.ActiveServices.startServiceInnerLocked(ActiveServices.java:399)
W/ActivityManager( 1022): 	at com.android.server.am.ActiveServices.startServiceLocked(ActiveServices.java:386)
W/ActivityManager( 1022): 	at com.android.server.am.ActivityManagerService.startService(ActivityManagerService.java:12820)
W/ActivityManager( 1022): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:814)
W/ActivityManager( 1022): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2140)
W/ActivityManager( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
W/ActivityManager( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/SQLiteDatabase( 4777): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4777): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4777): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4777): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4777): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4777): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4777): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4777): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4777): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4777): threadid=10: thread exiting with uncaught exception (group=0x41ab0d40)
E/AndroidRuntime( 4777): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4777): Process: com.android.keychain, PID: 4777
E/AndroidRuntime( 4777): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4777): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4777): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4777): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4777): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4777): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4777): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4777): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4777): Sending signal. PID: 4777 SIG: 9
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 5 more
I/ActivityManager( 1022): Process com.google.android.gms (pid 1393) has died.
D/WifiService( 1022): Client connection lost with reason: 4
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10964ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10963ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10963ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10963ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10963ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10962ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20962ms
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20962ms
I/ActivityManager( 1022): Process com.android.keychain (pid 4777) has died.
W/ActivityManager( 1022): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 30960ms
D/Documents( 4806): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4806): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4806): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4806): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4806): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4806): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4806): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4806): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4806): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4806): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4806): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4806): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4806): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4806): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4806): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4806): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4806): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4806): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4806): Shutting down VM
W/dalvikvm( 4806): threadid=1: thread exiting with uncaught exception (group=0x41ab0d40)
D/Documents( 4806): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4806): FATAL EXCEPTION: main
E/AndroidRuntime( 4806): Process: com.android.documentsui, PID: 4806
E/AndroidRuntime( 4806): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4806): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4806): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4806): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4806): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4806): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4806): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4806): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4806): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4806): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4806): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4806): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4806): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4806): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4806): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4806): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4806): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4806): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4806): 	... 10 more
I/ActivityManager( 1022): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4826 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager( 1022): Killing 4397:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 5 more

```
