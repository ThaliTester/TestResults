#### Test 55431344e5dd625_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = ,
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4112): 
D/AndroidRuntime( 4112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4112): CheckJNI is OFF
D/dalvikvm( 4112): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4112): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4112): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4112): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4112): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4112): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4112): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4112): failed to load memtrack module: -2
D/AndroidRuntime( 4112): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4112
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4128 uid=10521 gids={50521, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4112): Shutting down VM
D/dalvikvm( 4112): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 21ms
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+5ms, total 22ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
V/WebViewChromiumFactoryProvider( 4128): Binding Chromium to main looper Looper (main, tid 1) {41f11848}
I/LibraryLoader( 4128): Expected native library version number "",actual native library version number ""
I/chromium( 4128): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4128): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d9bfa0:true
I/Adreno-EGL( 4128): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4128): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4128): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4128): Local Branch: 
I/Adreno-EGL( 4128): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4128): Local Patches: NONE
I/Adreno-EGL( 4128): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4128): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4128): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4128): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4128): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4128): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4128): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4128): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4128): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4128): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4128): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4128): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4128): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4128): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4128): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4128): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4128): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4128): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4128): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4128): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4128): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4128): Enabling debug mode 0
,W/AwContents( 4128): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4128): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,410
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +379ms (total +410ms)
,D/JsMessageQueue( 4128): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4128): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f15de8
,D/dalvikvm( 4128): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f15de8
,D/jxcore_app_log( 4128): JniHelper::setJavaVM(0x4155dfa8), pthread_self() = 1615713744
,D/JX-Cordova( 4128): jxcore cordova android initializing
,D/dalvikvm( 4128): GC_CONCURRENT freed 2762K, 17% free 14414K/17224K, paused 2ms+2ms, total 49ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 150K, 17% free 14399K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 129K, 17% free 14416K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 16.203MB for 96598-byte allocation
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 178K, 17% free 14450K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 16.282MB for 144892-byte allocation
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 252K, 17% free 14498K/17464K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 16.398MB for 217334-byte allocation
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 369K, 18% free 14572K/17680K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 16.575MB for 325996-byte allocation
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 568K, 19% free 14694K/18000K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 16.848MB for 488990-byte allocation
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 866K, 20% free 14871K/18480K, paused 25ms, total 26ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 1283K, 19% free 15129K/18480K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 17.856MB for 1100216-byte allocation
,D/dalvikvm( 4128): GC_CONCURRENT freed 1747K, 21% free 15510K/19556K, paused 1ms+5ms, total 34ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 280K, 21% free 15473K/19556K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 18.717MB for 1650320-byte allocation
,D/dalvikvm( 4128): GC_CONCURRENT freed 1690K, 25% free 16030K/21168K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 1341K, 24% free 16097K/21168K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 20.113MB for 2475476-byte allocation
,D/dalvikvm( 4128): GC_CONCURRENT freed 1802K, 29% free 16824K/23588K, paused 4ms+4ms, total 38ms
,D/dalvikvm( 4128): GC_CONCURRENT freed 2387K, 28% free 17045K/23588K, paused 2ms+6ms, total 40ms
,D/dalvikvm( 4128): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 723K, 29% free 16820K/23588K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4128): Grow heap (frag case) to 22.000MB for 3713210-byte allocation
,D/dalvikvm( 4128): GC_CONCURRENT freed 2630K, 34% free 18017K/27216K, paused 5ms+3ms, total 43ms
,D/dalvikvm( 4128): GC_FOR_ALLOC freed 664K, 34% free 18042K/27216K, paused 27ms, total 27ms
,W/jxcore-log( 4128): Initializing JXcore engine
,W/jxcore-log( 4128): JXcore engine is ready
,D/dalvikvm( 4128): GC_CONCURRENT freed 327K, 24% free 20705K/27216K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 4128): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4128): Starting JXcore engine
,W/jxcore-log( 4128): Platform android
W/jxcore-log( 4128): 
,W/jxcore-log( 4128): Process ARCH arm
W/jxcore-log( 4128): 
,I/jxcore-log( 4128): JXcore Cordova bridge is ready!
I/jxcore-log( 4128): 
,W/jxcore-log( 4128): JXcore engine is started
,I/chromium( 4128): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4128): Toggling radios to true
I/jxcore-log( 4128): 
,D/BluetoothAdapter( 4128): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4128, uid=10521
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4128): Radios toggled
I/jxcore-log( 4128): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4128): Received device characteristics:
I/jxcore-log( 4128): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4128): Bluetooth name: XT1039
I/jxcore-log( 4128): Device name: motorola-XT1039
I/jxcore-log( 4128): 
I/jxcore-log( 4128): Perf Test app loaded loaded
I/jxcore-log( 4128): 
,I/jxcore-log( 4128): check test folder
I/jxcore-log( 4128): 
,I/jxcore-log( 4128): found test : ./testFindPeers.js
I/jxcore-log( 4128): 
,D/TCMD    (  398): NL - Read 1000 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
D/TCMD    (  398): Listening for incoming client connection request
D/TCMD    (  398): NL - Read 68 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
D/TCMD    (  398): Listening for incoming client connection request
D/TCMD    (  398): NL - Read 68 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
,I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276):  STA Disconnected !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4128): found test : ./testSendData.js
I/jxcore-log( 4128): 
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  398): NL - Read 60 bytes from update socket.
D/TCMD    (  398): NL - ignore NL message, type = 21
,D/TCMD    (  398): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 333449
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1019): DisconnectingState
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
,D/WifiStateMachine( 1019): processMsg: DisconnectingState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x5fea9248 clazz=0x63700001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1359): Read error: ssl=0x61533a30: I/O error during system call, Connection timed out
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x61533a30: I/O error during system call, Broken pipe
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
,I/Choreographer( 4128): Skipped 134 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4128): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1151): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/TCMD    (  398): NL - Read 56 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
D/TCMD    (  398): Listening for incoming client connection request
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
E/wpa_supplicant( 1151): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1151): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1151): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  398): NL - Read 312 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
D/TCMD    (  398): Listening for incoming client connection request
D/TCMD    (  398): NL - Read 192 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
,D/TCMD    (  398): NL - Read 68 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
D/TCMD    (  398): NL - Read 1000 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
I/wpa_supplicant( 1151): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  398): NL - Read 80 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
D/TCMD    (  398): Listening for incoming client connection request
D/TCMD    (  398): NL - Read 80 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
D/TCMD    (  398): Listening for incoming client connection request
D/TCMD    (  398): NL - Read 68 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1151): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  398): NL - Read 1000 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  276): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  276): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213537528
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter,
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-14ms what=147462 obj=android.net.wifi.StateChangeResult@44702f48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41fc1d40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41fc1d40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  398): NL - Read 56 bytes from update socket.
D/TCMD    (  398): NL - message type is RTM_NEWLINK
,D/TCMD    (  398): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@446185b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@446185b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiP2pService( 1019): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@446185b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  398): NL - Read 60 bytes from update socket.
D/TCMD    (  398): NL - ignore NL message, type = 20
,D/TCMD    (  398): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
,D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@41fe65b8
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@41fe65b8
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4272 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1566): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1566): Registering with Alarm Manager to restart CCE
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1566): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4272): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f0efb0, skipping init
I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4272): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4308 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3944:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4308): mnc/mcc: 
V/MmsConfig( 4308): tag: bool value: enabledMMS - true
V/MmsConfig( 4308): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4308): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4308): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4308): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4308): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4308): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4308): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4308): tag: int value: recipientLimit - 20
V/MmsConfig( 4308): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4308): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4308): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4308): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4308): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4308): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4308): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4308): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4308): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4328 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3498:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4128): Connected to the server!
I/jxcore-log( 4128): 
,D/MobileConnectivityChangeReceiver( 4328): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4328): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4328): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4328): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4342 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3996:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/chromium( 4128): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1452237922766 min interval config: 0 actual interval: 320659
,I/CheckinService( 1401): Checking schedule, now: 1452238243434 next: 1452237952655
,I/CheckinService( 1401): active receiver: enabled
,I/CheckinService( 1401): Preparing to send checkin request
,I/EventLogService( 1401): Accumulating logs since 1452237917215
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4357 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3516:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 1019): GC_EXPLICIT freed 23647K, 65% free 18138K/50600K, paused 6ms+10ms, total 142ms
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4357): Binding Chromium to main looper Looper (main, tid 1) {41f0b568}
,I/LibraryLoader( 4357): Expected native library version number "",actual native library version number ""
,I/chromium( 4357): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4357): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4357): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4357): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4357): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4357): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4357): Local Branch: 
I/Adreno-EGL( 4357): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4357): Local Patches: NONE
I/Adreno-EGL( 4357): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4381 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 4357): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4381): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4381): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4381): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4381): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4381): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4381): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4381): install
,I/MultiDex( 4381): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4381): loading existing secondary dex files
,I/MultiDex( 4381): load found 3 secondary dex files
,I/MultiDex( 4381): install done
,W/GAV2    ( 4357): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4357): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4381): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4381): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4381): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4381): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4381): VFY: unable to resolve instance field 36
,D/dalvikvm( 4381): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4381): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4381): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4381): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4381): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4381): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4381): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f11ab8
D/dalvikvm( 4381): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f11ab8
,D/dalvikvm( 4381): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f11ab8, skipping init
,D/dalvikvm( 4381): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f11ab8
D/dalvikvm( 4381): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f11ab8
,V/JNIHelp ( 4381): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4381): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f11ab8
,D/dalvikvm( 4381): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f11ab8
D/dalvikvm( 4381): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f11ab8
,D/dalvikvm( 4381): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f11ab8
,I/ProviderInstaller( 4381): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 4357): Starting up...
,I/ImageResourceManager( 3532): ImageResourceManager: uninitalized
I/dalvikvm( 4381): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4381): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4381): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4381): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4381): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4381): VFY: replacing opcode 0x6e at 0x000d
,I/iu.Environment( 3532): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 4023:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4272): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4328): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4328): onReceive CONNECTIVITY_CHANGE networkType=1
I/dalvikvm( 4381): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4381): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/dalvikvm( 4381): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4381): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4381): VFY: replacing opcode 0x22 at 0x0000
,I/iu.Environment( 3532): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4381): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
,W/dalvikvm( 4381): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4381): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4381): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4381): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4381): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1566): onServiceConnected()
D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 3532): GC_CONCURRENT freed 634K, 5% free 16440K/17224K, paused 4ms+4ms, total 35ms
,D/WearableService( 1246): callingUid 10022, callindPid: 1246
,E/MDM     ( 1246): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5362000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5362000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
,D/LocationInitializer( 1401): Restart initialization of location
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,W/GCoreFlp( 1246): No location to return for getLastLocation()
,W/FusedLocationProvider( 1246): location=null
D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2577065948
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4381): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4381): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42134aa0
D/dalvikvm( 4381): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42134aa0
,D/dalvikvm( 4381): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42134aa0, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4381): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4437): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 4381): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4381): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 113ms
,I/Adreno-EGL( 4381): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4381): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4381): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4381): Local Branch: 
I/Adreno-EGL( 4381): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4381): Local Patches: NONE
I/Adreno-EGL( 4381): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4381): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4381): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4381): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4381): Local Branch: 
I/Adreno-EGL( 4381): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4381): Local Patches: NONE
I/Adreno-EGL( 4381): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/dalvikvm( 4128): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4128): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4128): VFY: replacing opcode 0x6e at 0x0002
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/AndroidRuntime( 4128): Shutting down VM
W/dalvikvm( 4128): threadid=1: thread exiting with uncaught exception (group=0x4163cd40)
E/AndroidRuntime( 4128): FATAL EXCEPTION: main
E/AndroidRuntime( 4128): Process: com.test.thalitest, PID: 4128
E/AndroidRuntime( 4128): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4128): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4128): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4128): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4128): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4128): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4128): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4128): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4128): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4128): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4128): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4128): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4128): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4128): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4128): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4128): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4128): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4128): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4128): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager( 1019):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager( 1019): Killing 3563:com.android.vending/u0a38 (adj 15): empty #9
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4128): Sending signal. PID: 4128 SIG: 9
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager( 1019): Process com.test.thalitest (pid 4128) has died.
,I/WindowState( 1019): WIN DEATH: Window{445ef0f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,I/SFPerfTracer(  277):      triggers: (rate: 3:31) (compose: 0:4) (post: 0:1) (render: 0:5) (0:114 frames) (1:554)
,D/SFPerfTracer(  277):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:213)* (NavigationBar: 0:40)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:17)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:4)* 
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 4128 uid 10521
,W/Binder  ( 1217): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1217): java.lang.NullPointerException
W/Binder  ( 1217): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1217): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1217): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1217): 	at dalvik.system.NativeStart.run(Native Method)
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3124504235
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,W/Settings( 4381): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
D/PollingManager( 1566): now: 365621 ,futureTime: 51893961
,D/PollingManager( 1566): Polling alarm set to expire at: 51893961 Current Time: 365621
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1566): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1566): now: 365651 ,futureTime: 51893961
,D/PollingManager( 1566): Polling alarm set to expire at: 51893961 Current Time: 365652
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/openssl ( 4272): Crypto mode 0 already enabled
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
I/OtaApp  ( 1566): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4328): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4328): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1566): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1566): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,D/dalvikvm( 3532): GC_FOR_ALLOC freed 37K, 5% free 16405K/17224K, paused 17ms, total 18ms
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/dalvikvm-heap( 3532): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,I/iu.Environment( 3532): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1452237922766 min interval config: 0 actual interval: 322991
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1566): onServiceConnected()
D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/dalvikvm( 3532): GC_FOR_ALLOC freed 4K, 5% free 18184K/19004K, paused 20ms, total 25ms
,D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4272): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4328): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4328): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3532): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1452237922766 min interval config: 0 actual interval: 323036
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1566): onServiceConnected()
,D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1566): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,I/Adreno-EGL( 4381): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4381): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4381): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4381): Local Branch: 
I/Adreno-EGL( 4381): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4381): Local Patches: NONE
I/Adreno-EGL( 4381): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/OtaApp  ( 1566): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1566
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1566): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1566): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1566
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,I/Adreno-EGL( 4381): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4381): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4381): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4381): Local Branch: 
I/Adreno-EGL( 4381): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4381): Local Patches: NONE
I/Adreno-EGL( 4381): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1566): GC_CONCURRENT freed 2078K, 38% free 10747K/17224K, paused 2ms+4ms, total 37ms
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429057c8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,V/NativeCrypto( 1401): SSL shutdown failed: ssl=0x6d2fc478: I/O error during system call, Connection timed out
,D/dalvikvm( 1401): GC_CONCURRENT freed 1816K, 30% free 12112K/17224K, paused 4ms+6ms, total 45ms
,I/CheckinTask( 1401): Sending checkin request (11742 bytes)
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1359): GC_EXPLICIT freed 1539K, 40% free 10354K/17224K, paused 2ms+4ms, total 34ms
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1401): Checking schedule, now: 1452238247062 next: 1452831317054
,I/CheckinService( 1401): active receiver: disabled
,I/CheckinService( 1401): Checking schedule, now: 1452238247083 next: 1452831317054
,I/CheckinService( 1401): active receiver: disabled
,D/CheckinService( 1401): Recording last checkin time for package unspecified as 1452238247088
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.,
,I/ModemStatsDSDetect( 1198): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1198): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4357): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4515 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1319): Deferring update until onResume
,I/Launcher( 1319): Deferring update until onResume
,I/GCoreNlp( 1246): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4515): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4515): MmsConfig.loadMmsSettings
I/Babel   ( 4515): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4515): MmsConfig.loadFromDatabase
,E/Babel   ( 4515): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4515): MmsConfig.loadFromResources
,E/Babel   ( 4515): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4515): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4515): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1019): GC_EXPLICIT freed 1526K, 65% free 18131K/50600K, paused 4ms+10ms, total 96ms
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4551 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 4095:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4572 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4272:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2309): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4594 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4308:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4594): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4594): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4551): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4594): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2309): UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
,I/dalvikvm( 4594): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4594): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4594): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4594): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4594): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4594): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4594): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4594): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4594): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4594): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4594): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4594): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4594): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4594): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4594): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4629 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,I/dalvikvm( 4594): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4594): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/Ads     ( 4594): Skipping gmscore version check
,D/Finsky  ( 4594): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4594): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4594): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4594): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1019): Killing 4328:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1401): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1401): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4629): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f17fc8, skipping init
I/openssl ( 4629): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4629): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Killing 4342:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4594): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4594): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1401): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1401): GC_CONCURRENT freed 1963K, 30% free 12153K/17224K, paused 4ms+8ms, total 44ms
,I/Icing   ( 1401): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/LatinIME:LogUtils( 1217): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452238255
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{427d9378 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42266308 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42074768 type 3 android}
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3
,V/AlarmManager( 1019): sending alarm Alarm{4280e180 type 3 android}

```
