#### Test 56204092c98eeae_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 4718): 
D/AndroidRuntime( 4718): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4718): CheckJNI is OFF
D/dalvikvm( 4718): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4718): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4718): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4718): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4718): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4718): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4718): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4718): failed to load memtrack module: -2
D/AndroidRuntime( 4718): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4718
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4734 uid=10114 gids={50114, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4718): Shutting down VM
D/dalvikvm( 4718): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 3ms
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4734): Binding Chromium to main looper Looper (main, tid 1) {428fbc18}
I/LibraryLoader( 4734): Expected native library version number "",actual native library version number ""
I/chromium( 4734): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4734): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a61da0:true
I/Adreno-EGL( 4734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4734): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4734): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4734): Local Branch: 
I/Adreno-EGL( 4734): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4734): Local Patches: NONE
I/Adreno-EGL( 4734): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4734): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4734): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4734): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4734): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4734): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4734): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4734): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4734): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4734): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4734): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4734): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4734): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4734): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4734): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4734): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4734): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4734): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4734): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4734): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4734): CordovaWebView is running on device made by: motorola
D/OpenGLRenderer( 4734): Enabling debug mode 0
W/AwContents( 4734): nativeOnDraw failed; clearing to background color.
I/Keyboard.Facilitator( 1220): onFinishInput()
W/IInputConnectionWrapper( 4734): showStatusIcon on inactive InputConnection
I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,470
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +442ms (total +470ms)
D/JsMessageQueue( 4734): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4734): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428ffee8
D/dalvikvm( 4734): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428ffee8
D/jxcore_app_log( 4734): JniHelper::setJavaVM(0x4201df78), pthread_self() = 1615517920
D/JX-Cordova( 4734): jxcore cordova android initializing
D/dalvikvm( 4734): GC_CONCURRENT freed 2642K, 16% free 14547K/17224K, paused 2ms+3ms, total 39ms
D/dalvikvm( 4734): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/dalvikvm( 4734): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 331K, 14% free 14822K/17224K, paused 27ms, total 28ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 70K, 14% free 14827K/17224K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 16.552MB for 42938-byte allocation
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 93K, 15% free 14845K/17268K, paused 26ms, total 26ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 126K, 14% free 14865K/17268K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 16.641MB for 96598-byte allocation
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 180K, 15% free 14900K/17364K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 16.721MB for 144892-byte allocation
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 255K, 15% free 14947K/17508K, paused 26ms, total 26ms
I/dalvikvm-heap( 4734): Grow heap (frag case) to 16.836MB for 217334-byte allocation
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 371K, 16% free 15022K/17724K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 17.013MB for 325996-byte allocation
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 571K, 17% free 15143K/18044K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 17.287MB for 488990-byte allocation
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 871K, 18% free 15321K/18524K, paused 28ms, total 29ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 1224K, 16% free 15571K/18524K, paused 28ms, total 28ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 82K, 16% free 15563K/18524K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 18.280MB for 1100216-byte allocation
,D/dalvikvm( 4734): GC_CONCURRENT freed 1871K, 19% free 15988K/19600K, paused 1ms+6ms, total 49ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 168K, 19% free 15909K/19600K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 19.142MB for 1650320-byte allocation
,D/dalvikvm( 4734): GC_CONCURRENT freed 1926K, 23% free 16514K/21212K, paused 1ms+6ms, total 50ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 1021K, 23% free 16474K/21212K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 20.481MB for 2475476-byte allocation
,D/dalvikvm( 4734): GC_CONCURRENT freed 273K, 21% free 18846K/23632K, paused 4ms+3ms, total 41ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 4264K, 26% free 17526K/23632K, paused 37ms, total 37ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 22.689MB for 3713210-byte allocation
,D/dalvikvm( 4734): GC_CONCURRENT freed 405K, 23% free 21010K/27260K, paused 5ms+7ms, total 70ms
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 4252K, 32% free 18617K/27260K, paused 33ms, total 33ms
,W/jxcore-log( 4734): Initializing JXcore engine
,W/jxcore-log( 4734): JXcore engine is ready
,D/dalvikvm( 4734): GC_CONCURRENT freed 401K, 22% free 21422K/27260K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 4734): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 4734): Starting JXcore engine
,D/dalvikvm( 4734): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4734): Platform android
W/jxcore-log( 4734): 
,W/jxcore-log( 4734): Process ARCH arm
W/jxcore-log( 4734): 
,I/jxcore-log( 4734): JXcore Cordova bridge is ready!
I/jxcore-log( 4734): 
,W/jxcore-log( 4734): JXcore engine is started
,I/chromium( 4734): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4734): Toggling radios to true
I/jxcore-log( 4734): 
,D/BluetoothAdapter( 4734): enable(): BT is already enabled..!
,D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=4734, uid=10114
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 4734): Radios toggled
I/jxcore-log( 4734): 
D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4734): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4734): 
I/jxcore-log( 4734): Perf Test app loaded loaded
I/jxcore-log( 4734): 
,I/jxcore-log( 4734): check test folder
I/jxcore-log( 4734): 
,I/jxcore-log( 4734): found test : ./testFindPeers.js
I/jxcore-log( 4734): 
,I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/TCMD    (  443): NL - Read 1000 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request
I/MDMCTBK (  277): send SAR ctrl over QMI
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/Tethering( 1020): InitialState.processMessage what=4
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1020): WiFi NOT Tethered!
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/jxcore-log( 4734): found test : ./testSendData.js
I/jxcore-log( 4734): 
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  443): NL - Read 60 bytes from update socket.
D/TCMD    (  443): NL - ignore NL message, type = 21
,D/TCMD    (  443): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1020): connected time updated 297068
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x6162d488 clazz=0x62e00001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1020): DisconnectingState
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT],
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1369): Read error: ssl=0x61533bd8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1369): SSL shutdown failed: ssl=0x61533bd8: I/O error during system call, Broken pipe
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
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
D/WifiStateMachine( 1020): processMsg: DefaultState
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
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,I/chromium( 4734): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1166): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,E/wpa_supplicant( 1166): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  443): NL - Read 56 bytes from update socket.
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
,D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,I/wpa_supplicant( 1166): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1166): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  443): NL - Read 312 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 192 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 1000 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1166): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  443): NL - Read 80 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 80 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  443): NL - Read 1000 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1209054384
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,I/MDMCTBK (  277): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
I/MDMCTBK (  277): send SAR ctrl over QMI
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
,D/WifiStateMachine( 1020): handleMessage: X
E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
,D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-45ms what=147462 obj=android.net.wifi.StateChangeResult@43d51b48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-38ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43cd69f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiStateMachine( 1020): handleMessage: X
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43170cf0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43170cf0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 a
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 a
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/TCMD    (  443): NL - Read 56 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c2,
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0,
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c0,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38,
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64,
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 a0,
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 a0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06,
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i,
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiP2pService( 1020): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e25868 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e25868 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e25868 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): handleMessage: X
D/TCMD    (  443): NL - Read 60 bytes from update socket.
D/TCMD    (  443): NL - ignore NL message, type = 20
,D/TCMD    (  443): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-3ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): DHCP successful
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState enter
D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine( 1020): handleMessage: X
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@429ccad0
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@429ccad0
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1294): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1094): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1605): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1020): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4882 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,E/ActivityThread( 1605): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
D/CCE     ( 1605): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1294): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/PollingManager( 1605): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1605): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
E/ActivityThread( 1605): Failed to find provider info for com.motorola.blur.setupprovider
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/OtaApp  ( 1605): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1605): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/dalvikvm( 4882): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42903dc8, skipping init
I/openssl ( 4882): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4882): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4919 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4495:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4919): mnc/mcc: 
V/MmsConfig( 4919): tag: bool value: enabledMMS - true
V/MmsConfig( 4919): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4919): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4919): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4919): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4919): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4919): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4919): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4919): tag: int value: recipientLimit - 20
V/MmsConfig( 4919): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4919): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4919): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4919): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4919): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4919): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4919): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4919): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4919): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4938 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 4575:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4938): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4938): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4938): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4938): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4951 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4203:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1452883468938 min interval config: 0 actual interval: 233751
,I/CheckinService( 1758): Checking schedule, now: 1452883702698 next: 1452883498921
,I/CheckinService( 1758): active receiver: enabled
,I/CheckinService( 1758): Preparing to send checkin request
,I/EventLogService( 1758): Accumulating logs since 1452883465738
,I/CheckinRequestBuilder( 1758): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1758): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 4734): Connected to the server!
I/jxcore-log( 4734): 
,I/chromium( 4734): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/WebViewChromiumFactoryProvider( 4951): Binding Chromium to main looper Looper (main, tid 1) {428ff8b0}
,I/LibraryLoader( 4951): Expected native library version number "",actual native library version number ""
,I/chromium( 4951): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4951): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4951): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4951): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4951): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4951): Local Branch: 
I/Adreno-EGL( 4951): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4951): Local Patches: NONE
I/Adreno-EGL( 4951): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4951): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/dalvikvm( 1020): GC_EXPLICIT freed 25209K, 66% free 18434K/52836K, paused 5ms+15ms, total 175ms
,W/GAV2    ( 4951): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4951): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4989 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4989): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4989): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4989): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4989): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4989): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4989): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4989): install
,I/MultiDex( 4989): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4989): loading existing secondary dex files
,I/MultiDex( 4989): load found 3 secondary dex files
,I/NSApplication( 4951): Starting up...
,I/ActivityManager( 1020): Killing 4224:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MultiDex( 4989): install done
,D/dalvikvm( 4989): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4989): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4989): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4989): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4989): VFY: unable to resolve instance field 36
,D/dalvikvm( 4989): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4989): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4989): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4989): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4989): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4989): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4989): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429059b8
,D/dalvikvm( 4989): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429059b8
,D/dalvikvm( 4989): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429059b8, skipping init
D/dalvikvm( 4989): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429059b8
,D/dalvikvm( 4989): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429059b8
,V/JNIHelp ( 4989): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4989): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429059b8
,D/dalvikvm( 4989): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x429059b8
D/dalvikvm( 4989): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429059b8
,D/dalvikvm( 4989): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429059b8
,I/ProviderInstaller( 4989): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=5011 uid=10056 gids={50056, 3003, 1028, 1015}
,I/dalvikvm( 4989): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4989): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4989): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4989): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4989): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4989): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4989): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4989): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4989): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4989): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4989): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4989): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4989): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4989): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4989): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4989): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4989): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 5011): VFY: unable to resolve instance field 68
,D/dalvikvm( 5011): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 5011): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 5011): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1605): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 5011): VFY: unable to resolve instance field 68
,D/dalvikvm( 5011): VFY: replacing opcode 0x54 at 0x0011
,W/ContextImpl( 1605): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 5011): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 5011): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5011): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/GetNotificationsWS( 1605): bindWebServices(): registering our AIDL callback...
,I/ActivityManager( 1020): Killing 4614:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/EmailService.MarketingOptInSetter( 1605): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1605): onServiceConnected()
D/GetNotificationsWS( 1605): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1605): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1605): ServiceHandler.handleMessage: mWaitCount=0
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/GetNotificationsWS( 1605): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 4882): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4882): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4938): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4938): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5120000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5120000
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
I/ActivityManager( 1020): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: pid=5032 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=3733664966
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/dalvikvm( 5032): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 5032): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 5032): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Lefj;
,D/dalvikvm( 5032): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 5032): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 5032): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 5032): Unable to resolve superclass of Lcm; (800)
,W/dalvikvm( 5032): Link of class 'Lcm;' failed
,E/dalvikvm( 5032): Could not find class 'cm', referenced from method efj.a
,W/dalvikvm( 5032): VFY: unable to resolve new-instance 2378 (Lcm;) in Lefj;
,D/dalvikvm( 5032): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 5032): Unable to resolve superclass of Lco; (800)
,W/dalvikvm( 5032): Link of class 'Lco;' failed
E/dalvikvm( 5032): Could not find class 'co', referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve new-instance 2432 (Lco;) in Lefj;
D/dalvikvm( 5032): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 5032): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 5032): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve virtual method 5756: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5032): Could not find method android.view.View.getTransitionName, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve virtual method 5560: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 5032): VFY: unable to find class referenced in signature (Lx;)
,I/dalvikvm( 5032): Could not find method android.transition.Transition.getTargetNames, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve virtual method 5213: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 5032): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve interface method 5806: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 5032): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 5032): Could not find method android.view.ViewParent.onNestedFling, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve interface method 5805: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 5032): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5032): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve interface method 5807: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 5032): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 5032): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5032): Could not find class 'android.app.RemoteInput[]', referenced from method efj.a
W/dalvikvm( 5032): VFY: unable to resolve new-array 13337 ([Landroid/app/RemoteInput;) in Lefj;
,D/dalvikvm( 5032): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 5032): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.b
,W/dalvikvm( 5032): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x0009
,D/dalvikvm( 4989): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ae4008
D/dalvikvm( 4989): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ae4008
,D/dalvikvm( 4989): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ae4008, skipping init
,D/NativeLibraryUtils( 4989): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,W/dalvikvm( 5032): VFY: unable to find class referenced in signature (Lx;)
,D/dalvikvm( 5032): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
,D/dalvikvm( 5032): DexOpt: unable to opt direct call 0x0d49 at 0x0e in Lefj;.a
,D/dalvikvm( 5032): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
W/dalvikvm( 5032): Unable to resolve superclass of Lcm; (800)
,W/dalvikvm( 5032): Link of class 'Lcm;' failed
D/dalvikvm( 5032): DexOpt: unable to opt direct call 0x39db at 0x08 in Lefj;.a
W/dalvikvm( 5032): Unable to resolve superclass of Lco; (800)
,W/dalvikvm( 5032): Link of class 'Lco;' failed
,D/dalvikvm( 5032): DexOpt: unable to opt direct call 0x3b51 at 0x30 in Lefj;.a
,D/dalvikvm( 5032): DexOpt: unable to opt direct call 0x0a18 at 0x13 in Lefj;.a
,D/dalvikvm( 4989): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/dalvikvm( 5032): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.a
W/dalvikvm( 5032): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x023c
,I/dalvikvm( 5032): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eer.a
W/dalvikvm( 5032): VFY: unable to resolve virtual method 2906: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x000f
,W/XTWiFiOS( 1294): No entry in secure settings for enhanced location services: false
D/Tethering( 1020): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/dalvikvm( 5032): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.c
W/dalvikvm( 5032): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5032): VFY: replacing opcode 0x6e at 0x0207
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/PollingManager( 1605): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1605): now: 330277 ,futureTime: 48314970
,D/PollingManager( 1605): Polling alarm set to expire at: 48314970 Current Time: 330277
,E/ActivityThread( 1605): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1605): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1605): now: 330290 ,futureTime: 48314970
D/PollingManager( 1605): Polling alarm set to expire at: 48314970 Current Time: 330290
D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/OtaApp  ( 1605): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1605): [debug] > CusSM.onRadioUp
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/OtaApp  ( 1605): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/ActivityThread( 1605): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1605): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/XTWiFiOS( 1294): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/dalvikvm( 5032): Trying to load lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x4290b800
,D/dalvikvm( 5032): Added shared lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x4290b800
,D/OtaApp  ( 1605): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1605): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1605): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1605): [debug] > CusSM.runStateMachine: server told to :continue
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/OtaApp  ( 1605): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1605): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1605): GC_CONCURRENT freed 6388K, 38% free 10806K/17224K, paused 5ms+13ms, total 64ms
,D/dalvikvm( 5051): DexOpt: load 6ms, verify+opt 10ms, 128132 bytes
,D/OtaApp  ( 1605): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1605): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1605): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1605): [debug] > CusSM.runStateMachine: server told to :continue
,D/WearableService( 1239): callingUid 10022, callindPid: 1239
,D/dalvikvm( 4989): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4989): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 129ms
I/ActivityManager( 1020): Killing 4646:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/MDM     ( 1239): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1369): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1369): Proximity feature is not enabled.
D/LocationInitializer( 1758): Restart initialization of location
,I/Adreno-EGL( 4989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4989): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4989): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4989): Local Branch: 
I/Adreno-EGL( 4989): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4989): Local Patches: NONE
I/Adreno-EGL( 4989): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1239): No location to return for getLastLocation()
,W/FusedLocationProvider( 1239): location=null
I/openssl ( 4882): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4882): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4938): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4938): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1452883468938 min interval config: 0 actual interval: 235131
,D/DEBUG   ( 1605): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1605): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1605): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1605): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1605): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1605): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1605): onServiceConnected()
D/GetNotificationsWS( 1605): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1605): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4882): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4882): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4938): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4938): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1452883468938 min interval config: 0 actual interval: 235191
,I/Adreno-EGL( 4989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4989): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4989): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4989): Local Branch: 
I/Adreno-EGL( 4989): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4989): Local Patches: NONE
I/Adreno-EGL( 4989): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/DEBUG   ( 1605): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1605): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1605): bindWebServices(): registering our AIDL callback...
I/dalvikvm( 4734): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4734): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4734): VFY: replacing opcode 0x6e at 0x0002
,D/EmailService.MarketingOptInSetter( 1605): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1605): onServiceConnected()
I/SundryService( 1605): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1605): onServiceConnected(): Registered for remote service callbacks...
D/AndroidRuntime( 4734): Shutting down VM
,W/dalvikvm( 4734): threadid=1: thread exiting with uncaught exception (group=0x4202fd40)
,E/AndroidRuntime( 4734): FATAL EXCEPTION: main
E/AndroidRuntime( 4734): Process: com.test.thalitest, PID: 4734
E/AndroidRuntime( 4734): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4734): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4734): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4734): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4734): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4734): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4734): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4734): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4734): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4734): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4734): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4734): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4734): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4734): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4734): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4734): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4734): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4734): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4734): 	at dalvik.system.NativeStart.main(Native Method)
D/WaitableIntentService( 1605): ServiceHandler.handleMessage: mWaitCount=0
D/OtaApp  ( 1605): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/GetNotificationsWS( 1605): unbindWebServices(): un-registering our AIDL callback...
,W/ActivityManager( 1020):   Force finishing activity com.test.thalitest/.MainActivity
D/OtaApp  ( 1605): [debug] > Received start id 2: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
D/OtaApp  ( 1605): [debug] > handle intent : null
,D/OtaApp  ( 1605): [debug] > supress duplicated intent, nextPompt: 1452969825252 and mNotificationInStatusBar: true
I/ActivityManager( 1020): Killing 4678:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4734): Sending signal. PID: 4734 SIG: 9
D/OtaApp  ( 1605): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
D/OtaApp  ( 1605): [debug] > Received start id 3: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
D/OtaApp  ( 1605): [debug] > handle intent : null
D/OtaApp  ( 1605): [debug] > supress duplicated intent, nextPompt: 1452969825252 and mNotificationInStatusBar: true
,I/ActivityManager( 1020): Process com.test.thalitest (pid 4734) has died.
,D/WifiService( 1020): Client connection lost with reason: 4
,I/WindowState( 1020): WIN DEATH: Window{45335330 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/Settings( 4989): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=1306347958
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4989): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4989): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4989): Local Branch: 
I/Adreno-EGL( 4989): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4989): Local Patches: NONE
I/Adreno-EGL( 4989): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4989): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4989): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4989): Local Branch: 
I/Adreno-EGL( 4989): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4989): Local Patches: NONE
I/Adreno-EGL( 4989): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1758): Classify the device as Phone.
,I/CheckinTask( 1758): Sending checkin request (11807 bytes)
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1020): processMsg: ConnectedState
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1020): handleMessage: X
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1758): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1758): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1369): GC_EXPLICIT freed 352K, 40% free 10351K/17224K, paused 2ms+4ms, total 28ms
,I/CheckinRequestBuilder( 1758): Classify the device as Phone.
,I/CheckinTask( 1758): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/dalvikvm( 1758): GC_CONCURRENT freed 2045K, 30% free 12217K/17224K, paused 4ms+5ms, total 47ms
I/CheckinService( 1758): Checking schedule, now: 1452883706490 next: 1453433360466
,I/CheckinService( 1758): active receiver: disabled
,I/CheckinService( 1758): Checking schedule, now: 1452883706510 next: 1453433360466
,I/CheckinService( 1758): active receiver: disabled
,D/CheckinService( 1758): Recording last checkin time for package unspecified as 1452883706514
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1020): GC_EXPLICIT freed 825K, 66% free 18305K/52836K, paused 4ms+10ms, total 94ms
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
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
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1094): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1208): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): Inetcondition changed, white->blue
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=100
,I/GAV2    ( 4951): Thread[GAThread,5,main]: No campaign data found.
,I/Launcher( 1307): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/Launcher( 1307): Deferring update until onResume
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5128 uid=10033 gids={50033, 3003, 1028, 1015}
,I/GCoreNlp( 1239): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/InternalIcingCorporaPro( 2349): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1020): Killing 4882:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 4734 uid 10114
,W/Binder  ( 1220): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1220): java.lang.NullPointerException
W/Binder  ( 1220): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1220): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1220): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1220): 	at dalvik.system.NativeStart.run(Native Method)
,I/Keyboard.Facilitator( 1220): onFinishInput()
,D/PackageBroadcastService( 1758): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1758): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1758): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2349): UpdateCorporaTask done [took 307 ms] updated apps [took 307 ms] 
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1020): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1020): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1020): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1020): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1020): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/Icing   ( 1758): Indexing 08D2302403BBE76D1189E62A66162DB0256D4E65 from com.google.android.gms
,I/Icing   ( 1758): Indexing done 08D2302403BBE76D1189E62A66162DB0256D4E65
,V/AlarmManager( 1020): sending alarm Alarm{43239538 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1220): run()
,I/Keyboard.Facilitator( 1220): flushDynamicLanguageModels()
,I/ConfigService( 1239): onCreate
,I/ConfigService( 1239): onDestroy
,V/AlarmManager( 1020): sending alarm Alarm{43c26ea0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{432818b0 type 3 android}
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
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 8
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
,V/AlarmManager( 1020): sending alarm Alarm{43bd0908 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{43c18f30 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{4323a798 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{432d73c0 type 3 android}
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
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44b55ad8 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44ce5d78 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{4516e670 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{45314ba8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444a28d8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4322e078 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{4322cee8 type 1 com.android.deskclock}
,D/ConnectivityService( 1020): Done.
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5183 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1020): Setting timer for 720seconds
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+10ms, total 39ms
,I/ActivityManager( 1020): Killing 4919:com.android.mms/u0a30 (adj 15): empty #9
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 5ms+3ms, total 35ms
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+11ms, total 33ms
,V/AlarmManager( 1020): sending alarm Alarm{44a72ca8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44a59db0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43114228 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42f79888 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1208): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=100
,V/AlarmManager( 1020): sending alarm Alarm{4486a528 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444847f0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44632480 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{452b1738 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43b16600 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44422840 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44cb8690 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4313afa0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43d28a38 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43c74ba0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{444385d0 type 3 android}
,I/ProcessStatsService( 1020): Prepared write state in 15ms
,I/ProcessStatsService( 1020): Prepared write state in 25ms
,I/ProcessStatsService( 1020): Prepared write state in 14ms
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2016-01-15-04-23-03.bin
,V/AlarmManager( 1020): sending alarm Alarm{44c75738 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4486a600 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{431e6660 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{431e66b0 type 3 com.google.android.gms}
V/AlarmManager( 1020): sending alarm Alarm{431e6810 type 0 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{4486a6d8 type 1 com.android.deskclock}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/EventLogService( 1758): Aggregate from 1452883702722 (log), 1452883001145 (data)
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1369): SSL shutdown failed: ssl=0x615571b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1369): SSL shutdown failed: ssl=0x637f5898: I/O error during system call, Connection timed out
,V/AlarmManager( 1020): sending alarm Alarm{452c6f68 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{45303350 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44cf0d60 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5245): 
D/AndroidRuntime( 5245): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5245): CheckJNI is OFF
D/dalvikvm( 5245): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5245): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5245): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5245): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5245): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5245): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5245): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5245): failed to load memtrack module: -2
D/AndroidRuntime( 5245): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10114 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 5011:com.android.chrome/u0a56 (adj 15): empty for 1800s
I/ActivityManager( 1020): Killing 4951:com.google.android.apps.magazines/u0a76 (adj 15): empty for 1800s
I/ActivityManager( 1020): Killing 4938:com.google.android.setupwizard/u0a41 (adj 15): empty for 1800s
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1020): GC_CONCURRENT freed 2185K, 66% free 18451K/52836K, paused 5ms+10ms, total 108ms
D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 77ms
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10114 user=0: pkg removed
I/Keyboard.Facilitator( 1220): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1239): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1220): run()
I/Decoder ( 1220): createOrResetDecoder
D/VoicemailCleanupService( 1193): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1307): GC_EXPLICIT freed 3639K, 32% free 11723K/17224K, paused 2ms+7ms, total 55ms
D/dalvikvm( 1758): GC_EXPLICIT freed 1655K, 30% free 12065K/17224K, paused 10ms+9ms, total 71ms
I/Launcher( 1307): Deferring update until onResume
D/dalvikvm( 2349): GC_EXPLICIT freed 5280K, 42% free 10149K/17224K, paused 3ms+5ms, total 86ms
D/dalvikvm( 2317): GC_EXPLICIT freed 5343K, 44% free 9654K/17224K, paused 2ms+6ms, total 47ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/dalvikvm( 1020): GC_EXPLICIT freed 728K, 66% free 18370K/52836K, paused 8ms+13ms, total 168ms
I/ConfigService( 1239): onCreate
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/Launcher( 1307): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10114 #1
I/InternalIcingCorporaPro( 2349): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/AndroidRuntime( 5245): Shutting down VM
D/dalvikvm( 5245): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5276 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Keyboard.Facilitator.MainLanguageModelLoader( 1220): run()
W/ContextImpl( 5276): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4140): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4140): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1758): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1758): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1758): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1758): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1220): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1220): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1220): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1220): run()
I/StatsUtilsManager( 1220): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1220): shouldRecordStats() = Too Soon
E/NetworkScheduler.SchedulerReceiver( 1369): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1369): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1758): Module APK com.google.android.play.games already loaded
V/AlarmManager( 1020): sending alarm Alarm{43142398 type 2 com.motorola.ccc.cce}
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5301 uid=10059 gids={50059, 1028, 3003, 1015}
D/gH_CompatibleDatabase( 1758): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1758): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1758): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1758): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/InternalIcingCorporaPro( 2349): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
I/Icing   ( 1758): doRemovePackageData com.test.thalitest
I/dalvikvm( 1758): Jit: resizing JitTable from 4096 to 8192
D/gH_CompatibleDatabase( 1758): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1758): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1758): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1758): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1758): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1758): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1758): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1758): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1758): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/dalvikvm( 5301): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 5301): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5301): VFY: replacing opcode 0x6e at 0x000f
I/GAv4    ( 5301): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5301):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5301):   adb logcat -s GAv4
W/GAv4    ( 5301): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/dalvikvm( 5301): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 5301): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 5301): VFY: replacing opcode 0x6e at 0x001b
E/SQLiteDatabase( 5301): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5301): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5301): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5301): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5301): 	at avm.getWritableDatabase(PG:244)
E/SQLiteDatabase( 5301): 	at avc.a(PG:1573)
E/SQLiteDatabase( 5301): 	at jep$b.a(PG:131)
E/SQLiteDatabase( 5301): 	at ave.run(PG:588)
W/dalvikvm( 5301): threadid=11: thread exiting with uncaught exception (group=0x4202fd40)
I/dalvikvm( 5301): Could not find method android.app.Activity.finishAfterTransition, referenced from method ce.onBackPressed
W/dalvikvm( 5301): VFY: unable to resolve virtual method 1245: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 5301): VFY: replacing opcode 0x6e at 0x0012
E/SharedPreferencesImpl( 5301): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5301): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5301): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 5301): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 5301): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/CAKEMIX_CRASHED( 5301): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/CAKEMIX_CRASHED( 5301): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/CAKEMIX_CRASHED( 5301): 	at avm.getWritableDatabase(PG:244)
E/CAKEMIX_CRASHED( 5301): 	at avc.a(PG:1573)
E/CAKEMIX_CRASHED( 5301): 	at jep$b.a(PG:131)
E/CAKEMIX_CRASHED( 5301): 	at ave.run(PG:588)
W/GAv4    ( 5301): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5301): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5301): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5301): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5301): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5301): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5301): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5301): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5301): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 5301): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 5301): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 5301): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 5301): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 5301): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5301): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5301): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5301): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5301): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5301): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 5301): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 5301): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 5301): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
I/ActivityManager( 1020): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from pid 5301

```
