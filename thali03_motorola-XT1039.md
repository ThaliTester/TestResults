#### Test 50650278e989a4f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4142): 
D/AndroidRuntime( 4142): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4142): CheckJNI is OFF
D/dalvikvm( 4142): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4142): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4142): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4142): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4142): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4142): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4142): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4142): failed to load memtrack module: -2
D/AndroidRuntime( 4142): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4142
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4158 uid=10483 gids={50483, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4142): Shutting down VM
D/dalvikvm( 4142): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4158): Binding Chromium to main looper Looper (main, tid 1) {41fb1d08}
I/LibraryLoader( 4158): Expected native library version number "",actual native library version number ""
I/chromium( 4158): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4158): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427a8298:true
I/Adreno-EGL( 4158): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4158): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4158): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4158): Local Branch: 
I/Adreno-EGL( 4158): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4158): Local Patches: NONE
I/Adreno-EGL( 4158): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4158): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4158): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4158): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4158): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4158): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4158): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4158): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4158): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4158): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4158): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4158): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4158): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4158): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4158): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4158): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4158): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4158): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4158): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4158): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4158): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4158): Enabling debug mode 0
,W/AwContents( 4158): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4158): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1016): Displayed com.test.thalitest/.MainActivity,cp,ca,345
I/ActivityManager( 1016): Displayed com.test.thalitest/.MainActivity: +316ms (total +345ms)
,D/JsMessageQueue( 4158): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4158): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fb5fd8
,D/dalvikvm( 4158): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fb5fd8
,D/jxcore_app_log( 4158): JniHelper::setJavaVM(0x41607fa8), pthread_self() = 1614534200
,D/JX-Cordova( 4158): jxcore cordova android initializing
,D/dalvikvm( 4158): GC_CONCURRENT freed 2811K, 17% free 14377K/17224K, paused 2ms+2ms, total 55ms
,D/dalvikvm( 4158): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 163K, 17% free 14386K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 190K, 17% free 14412K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 16.245MB for 144892-byte allocation
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 256K, 17% free 14458K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 16.360MB for 217334-byte allocation
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 367K, 18% free 14532K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 16.535MB for 325996-byte allocation
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 568K, 19% free 14654K/17904K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 16.809MB for 488990-byte allocation
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 865K, 20% free 14831K/18384K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 17.215MB for 733480-byte allocation
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 1284K, 22% free 15089K/19104K, paused 27ms, total 27ms
,D/dalvikvm( 4158): GC_CONCURRENT freed 1677K, 20% free 15460K/19104K, paused 3ms+3ms, total 37ms
,D/dalvikvm( 4158): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 368K, 20% free 15418K/19104K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 18.663MB for 1650320-byte allocation
,D/dalvikvm( 4158): GC_CONCURRENT freed 1681K, 23% free 15991K/20716K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 1367K, 23% free 16071K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 20.088MB for 2475476-byte allocation
,D/dalvikvm( 4158): GC_CONCURRENT freed 282K, 21% free 18375K/23136K, paused 4ms+4ms, total 39ms
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 4325K, 27% free 17044K/23136K, paused 35ms, total 38ms
,I/dalvikvm-heap( 4158): Grow heap (frag case) to 22.218MB for 3713210-byte allocation
,D/dalvikvm( 4158): GC_CONCURRENT freed 443K, 24% free 20532K/26764K, paused 5ms+5ms, total 61ms
,D/dalvikvm( 4158): GC_FOR_ALLOC freed 3059K, 33% free 17985K/26764K, paused 27ms, total 32ms
,W/jxcore-log( 4158): Initializing JXcore engine
,W/jxcore-log( 4158): JXcore engine is ready
,D/dalvikvm( 4158): GC_CONCURRENT freed 348K, 24% free 20606K/26764K, paused 12ms+2ms, total 42ms
,D/dalvikvm( 4158): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 4158): Starting JXcore engine
,W/jxcore-log( 4158): Platform android
W/jxcore-log( 4158): 
,W/jxcore-log( 4158): Process ARCH arm
W/jxcore-log( 4158): 
,I/jxcore-log( 4158): JXcore Cordova bridge is ready!
I/jxcore-log( 4158): 
,W/jxcore-log( 4158): JXcore engine is started
,I/chromium( 4158): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4158): Toggling radios to true
I/jxcore-log( 4158): 
,D/BluetoothAdapter( 4158): enable(): BT is already enabled..!
D/WifiService( 1016): New client listening to asynchronous messages
D/WifiService( 1016): setWifiEnabled: true pid=4158, uid=10483
,E/WifiService( 1016): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1016): handleMessage: E msg.what=131145
D/WifiStateMachine( 1016): processMsg: ConnectedState
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
I/jxcore-log( 4158): Radios toggled
I/jxcore-log( 4158): 
D/BluetoothManagerService( 1016): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4158): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4158): 
I/jxcore-log( 4158): Perf Test app loaded loaded
I/jxcore-log( 4158): 
,I/jxcore-log( 4158): check test folder
I/jxcore-log( 4158): 
,I/jxcore-log( 4158): found test : ./testFindPeers.js
I/jxcore-log( 4158): 
,I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  440): NL - Read 1000 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
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
D/TCMD    (  440): NL - Read 1000 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
D/TCMD    (  440): NL - Read 68 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
D/TCMD    (  440): NL - Read 68 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
,D/TCMD    (  440): Listening for incoming client connection request
D/WifiStateMachine( 1016): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1016): invokeExitMethods: ConnectedState
,D/Tethering( 1016): InitialState.processMessage what=4
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1016): WiFi NOT Tethered!
D/WifiStateMachine( 1016): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1016): Stopping DHCP and clearing IP
D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1016): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/jxcore-log( 4158): found test : ./testSendData.js
I/jxcore-log( 4158): 
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  440): NL - Read 60 bytes from update socket.
D/TCMD    (  440): NL - ignore NL message, type = 21
,D/TCMD    (  440): Listening for incoming client connection request
,D/WifiStateMachine( 1016): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1016): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1016): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1016): connected time updated 333368
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1016): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1016): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1016): Attempting to switch to mobile
D/ConnectivityService( 1016): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1016): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1016): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1016): DisconnectingState
D/Checkin ( 1016): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131146
D/WifiStateMachine( 1016): processMsg: DisconnectingState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147460
D/WifiStateMachine( 1016): processMsg: DisconnectingState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): Network connection lost
D/WifiStateMachine( 1016): Stopping DHCP and clearing IP
D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1016): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1016): resetConnections(wlan0, 3)
D/NetUtils( 1016): android_net_utils_resetConnections in env=0x611f73d8 clazz=0x62600001 iface=wlan0 mask=0x3
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
V/NativeCrypto( 1370): Read error: ssl=0x62ffb458: I/O error during system call, Connection timed out
V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x62ffb458: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1016): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1016): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1016): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1016): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1016): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131216
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131216
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1016): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1016): Attempting to switch to mobile
D/ConnectivityService( 1016): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1016): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
I/chromium( 4158): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1165): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  440): NL - Read 56 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147461
D/WifiStateMachine( 1016): processMsg: DisconnectedState
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
,D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1165): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
,D/TCMD    (  440): NL - Read 312 bytes from update socket.
I/wpa_supplicant( 1165): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
D/TCMD    (  440): NL - Read 192 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
,D/TCMD    (  440): Listening for incoming client connection request
D/TCMD    (  440): NL - Read 68 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
,I/wpa_supplicant( 1165): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  440): NL - Read 1000 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
,D/TCMD    (  440): Listening for incoming client connection request
,D/Tethering( 1016): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  440): NL - Read 80 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
,D/TCMD    (  440): Listening for incoming client connection request
D/TCMD    (  440): NL - Read 80 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 1165): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  440): NL - Read 68 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
D/TCMD    (  440): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1016): handleMessage: E msg.what=131101
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
,D/WifiStateMachine( 1016): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  440): NL - Read 1000 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
,D/TCMD    (  440): Listening for incoming client connection request
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147459
D/WifiStateMachine( 1016): processMsg: DisconnectedState
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1214919856
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): Network connection established
D/WifiStateMachine( 1016): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1016): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1016): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1016): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1016): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1016): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
D/WifiStateMachine( 1016): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@435fede0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=196612
D/WifiStateMachine( 1016): processMsg: ObtainingIpState
D/WifiStateMachine( 1016): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1016): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1016): handleMessage: X
D/WifiP2pService( 1016): InactiveState{ when=-5ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41ff1950 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): P2pEnabledState{ when=-6ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41ff1950 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  440): NL - Read 56 bytes from update socket.
D/TCMD    (  440): NL - message type is RTM_NEWLINK
,D/TCMD    (  440): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 3
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1016): handleMessage: E msg.what=147461
D/WifiStateMachine( 1016): processMsg: ObtainingIpState
,D/WifiStateMachine( 1016): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1016): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
,D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiP2pService( 1016): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43cd0d70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43cd0d70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43cd0d70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): handleMessage: X
,D/TCMD    (  440): NL - Read 60 bytes from update socket.
D/TCMD    (  440): NL - ignore NL message, type = 20
,D/TCMD    (  440): Listening for incoming client connection request
,D/WifiStateMachine( 1016): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1016): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
D/WifiStateMachine( 1016): ObtainingIpState{ when=-7ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1016): handleMessage: X
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1016): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/ConnectivityService( 1016): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1292): Active network info is not available
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,D/WifiStateMachine( 1016): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
D/WifiStateMachine( 1016): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1016): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1292): Active network info is not available
D/WifiP2pService( 1016): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
,D/WifiStateMachine( 1016): DHCP successful
D/WifiStateMachine( 1016): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1016): Calling ARP set with IP = 192.168.1.127
,D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
D/WifiStateMachine( 1016): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1016): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1016): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1016): VerifyingLinkState enter
D/WifiStateMachine( 1016): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=151572
D/WifiStateMachine( 1016): processMsg: VerifyingLinkState
D/WifiStateMachine( 1016): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4276 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,V/MmsConfig( 4276): mnc/mcc: 
,V/MmsConfig( 4276): tag: bool value: enabledMMS - true
V/MmsConfig( 4276): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4276): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4276): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4276): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4276): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4276): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4276): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4276): tag: int value: recipientLimit - 20
V/MmsConfig( 4276): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4276): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4276): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4276): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4276): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4276): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4276): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4276): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4276): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1016): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4299 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1016): Killing 3955:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=135190
D/WifiStateMachine( 1016): processMsg: VerifyingLinkState
D/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1016): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1016): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1016): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1016): CaptivePortalCheckState enter
,D/WifiStateMachine( 1016): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1016): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1016): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1016): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1016): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131092
D/WifiStateMachine( 1016): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1016): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1016): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1016): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1016): WiFi NOT Tethered!
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1016): Unexpected mtu value: android.net.wifi.WifiStateTracker@420906f0
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Checkin ( 1016): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1016): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1016): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1016): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131092
D/WifiStateMachine( 1016): processMsg: ConnectedState
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
,D/WifiStateMachine( 1016): handleMessage: X
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1016): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1016): WiFi NOT Tethered!
,E/ConnectivityService( 1016): Unexpected mtu value: android.net.wifi.WifiStateTracker@420906f0
I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1016): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1214): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=0
D/MobileConnectivityChangeReceiver( 4299): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4299): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4299): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4299): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4317 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 4001:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1406): Checkin interval check for package: unspecified last checkin: 1450232973772 min interval config: 0 actual interval: 322196
,I/CheckinService( 1406): Checking schedule, now: 1450233295976 next: 1450233003750
,I/CheckinService( 1406): active receiver: enabled
,I/CheckinService( 1406): Preparing to send checkin request
,I/EventLogService( 1406): Accumulating logs since 1450232969302
,D/dalvikvm( 1016): GC_EXPLICIT freed 1589K, 65% free 18069K/50756K, paused 6ms+10ms, total 97ms
,I/CheckinRequestBuilder( 1406): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1406): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4331 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 3475:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4331): Binding Chromium to main looper Looper (main, tid 1) {41fb5ab0}
,I/LibraryLoader( 4331): Expected native library version number "",actual native library version number ""
,I/chromium( 4331): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4331): Initializing chromium process, renderers=0
I/ActivityManager( 1016): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4347 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,E/AudioManagerAndroid( 4331): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4331): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4331): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4331): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4331): Local Branch: 
I/Adreno-EGL( 4331): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4331): Local Patches: NONE
I/Adreno-EGL( 4331): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/dalvikvm( 4347): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4347): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4347): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4347): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4347): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4347): install
,I/MultiDex( 4347): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4347): loading existing secondary dex files
,I/MultiDex( 4347): load found 3 secondary dex files
,I/MultiDex( 4347): install done
,W/chromium( 4331): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/dalvikvm( 4347): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4347): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4347): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4347): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4347): VFY: unable to resolve instance field 36
,D/dalvikvm( 4347): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4347): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4347): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4347): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4347): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4347): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbbb08
,D/dalvikvm( 4347): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbbb08
D/dalvikvm( 4347): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbbb08, skipping init
,D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fbbb08
D/dalvikvm( 4347): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fbbb08
W/GAV2    ( 4331): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/JNIHelp ( 4347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4331): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbbb08
,D/dalvikvm( 4347): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fbbb08
D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fbbb08
,D/dalvikvm( 4347): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fbbb08
,I/ProviderInstaller( 4347): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 4331): Starting up...
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/ImageResourceManager( 4054): ImageResourceManager: uninitalized
,I/iu.Environment( 4054): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1016): Killing 4027:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4347): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4347): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x00ce
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/dalvikvm( 4347): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4347): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x000d
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4074): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4074): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4299): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4299): onReceive CONNECTIVITY_CHANGE networkType=1
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/iu.Environment( 4054): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4347): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4347): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4347): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4347): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4347): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4347): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4347): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4347): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4347): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4347): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5214000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5214000
,D/LocationInitializer( 1406): Restart initialization of location
,D/WearableService( 1231): callingUid 10022, callindPid: 1231
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,E/MDM     ( 1231): [131] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,W/GCoreFlp( 1231): No location to return for getLastLocation()
,W/FusedLocationProvider( 1231): location=null
D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3773210869
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1016): NetTransition Wakelock for ConnectedState released by timeout
D/NativeLibraryUtils( 4347): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4347): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421c4ab8
,D/dalvikvm( 4347): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421c4ab8
,D/dalvikvm( 4347): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421c4ab8, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/jxcore-log( 4158): Connected to the server!
I/jxcore-log( 4158): 
,I/chromium( 4158): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 4347): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4422): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4347): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4347): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 68ms
,I/Adreno-EGL( 4347): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4347): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4347): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4347): Local Branch: 
I/Adreno-EGL( 4347): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4347): Local Patches: NONE
I/Adreno-EGL( 4347): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4347): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4347): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4347): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4347): Local Branch: 
I/Adreno-EGL( 4347): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4347): Local Patches: NONE
I/Adreno-EGL( 4347): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4158): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4158): 
,W/Settings( 4347): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4347): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4347): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4347): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4347): Local Branch: 
I/Adreno-EGL( 4347): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4347): Local Patches: NONE
I/Adreno-EGL( 4347): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4347): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4347): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4347): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4347): Local Branch: 
I/Adreno-EGL( 4347): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4347): Local Patches: NONE
I/Adreno-EGL( 4347): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1787456436
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1406): Classify the device as Phone.
,V/NativeCrypto( 1406): SSL shutdown failed: ssl=0x6becb8c8: I/O error during system call, Connection timed out
,I/CheckinTask( 1406): Sending checkin request (11790 bytes)
,D/dalvikvm( 1406): GC_CONCURRENT freed 1869K, 30% free 12061K/17224K, paused 4ms+5ms, total 44ms
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1016): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): now: 367085 ,futureTime: 61885005
,D/PollingManager( 1562): Polling alarm set to expire at: 61885005 Current Time: 367086
,D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/PollingManager( 1562): now: 367120 ,futureTime: 61885005
D/PollingManager( 1562): Polling alarm set to expire at: 61885005 Current Time: 367120
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4074): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4074): Crypto mode 0 already enabled
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MobileConnectivityChangeReceiver( 4299): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4299): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1016): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1262): Column apn id key is 'apn_id'
,D/dalvikvm( 4054): GC_FOR_ALLOC freed 615K, 5% free 16436K/17224K, paused 17ms, total 17ms
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/dalvikvm-heap( 4054): Grow heap (frag case) to 19.820MB for 1821008-byte allocation
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 4054): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1406): Checkin interval check for package: unspecified last checkin: 1450232973772 min interval config: 0 actual interval: 325312
,D/dalvikvm( 4054): GC_FOR_ALLOC freed 30K, 5% free 18186K/19004K, paused 12ms, total 12ms
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4074): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4074): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4299): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4299): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4054): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1406): Checkin interval check for package: unspecified last checkin: 1450232973772 min interval config: 0 actual interval: 325364
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1016): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1016): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/WifiStateMachine( 1016): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1016): handleMessage: E msg.what=131215
D/WifiStateMachine( 1016): processMsg: ConnectedState
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1016): handleMessage: X
D/ConnectivityService( 1016): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1016):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
D/ConnectivityService( 1016): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/CheckinRequestBuilder( 1406): Checkin reason type: 8 attempt count: 1
W/IInputConnectionWrapper( 4158): showStatusIcon on inactive InputConnection
E/ActivityThread( 1406): Failed to find provider info for com.google.android.wearable.settings
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1016): Activity reported stop, but no longer stopping: ActivityRecord{420f3430 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1016): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,140
,I/CheckinRequestBuilder( 1406): Classify the device as Phone.
,I/CheckinTask( 1406): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1406): Checking schedule, now: 1450233299377 next: 1450826369374
,I/CheckinService( 1406): active receiver: disabled
,I/CheckinService( 1406): Checking schedule, now: 1450233299398 next: 1450826369374
,I/CheckinService( 1406): active receiver: disabled
,D/CheckinService( 1406): Recording last checkin time for package unspecified as 1450233299406
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/AlarmManager( 1016): sending alarm Alarm{421edab0 type 3 android}
,D/ConnectivityService( 1016): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1214): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1214): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4331): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1016): Killing 3459:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4474 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/Launcher( 1305): Deferring update until onResume
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/Launcher( 1305): Deferring update until onResume
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
,I/Babel   ( 4474): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4474): MmsConfig.loadMmsSettings
I/Babel   ( 4474): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4474): MmsConfig.loadFromDatabase
,E/Babel   ( 4474): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4474): MmsConfig.loadFromResources
E/Babel   ( 4474): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4474): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1231): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 1016): GC_EXPLICIT freed 1484K, 65% free 18097K/50756K, paused 3ms+11ms, total 92ms
,W/Settings( 4474): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1016): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4512 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1016): Killing 3511:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1016): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4531 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 4074:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2326): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4550 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 4276:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4550): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4550): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4512): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4550): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2326): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,I/dalvikvm( 4550): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4550): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4550): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4550): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4550): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4550): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4550): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4550): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4550): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4550): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4550): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4550): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4550): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4550): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4550): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1016): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4585 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4550): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4550): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 17ms
,D/dalvikvm( 1370): GC_EXPLICIT freed 1114K, 40% free 10344K/17224K, paused 1ms+4ms, total 30ms
,D/Ads     ( 4550): Skipping gmscore version check
,D/Finsky  ( 4550): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4550): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4550): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4550): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1016): Killing 4299:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1406): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1406): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1406): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4585): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fc20c0, skipping init
I/openssl ( 4585): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4585): Crypto mode 0 already enabled
,I/ActivityManager( 1016): Killing 4317:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4550): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4550): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1406): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1406): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450233308
,D/CaptivePortalTracker( 1016): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1016): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1016): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1016): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1016): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1016): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1016): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1016): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{428bb960 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{425b60d0 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{420734f0 type 3 android}
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{423b45c8 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{440d7d70 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{427e52b8 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
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
,V/AlarmManager( 1016): sending alarm Alarm{428a79d8 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{420e52d0 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{421d1b10 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4410fec0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{427c5f50 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{427c6010 type 1 com.android.deskclock}
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,I/ActivityManager( 1016): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4637 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1016): Killing 4331:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4299be10 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1016): sending alarm Alarm{42986080 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4283caa0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{427c6060 type 2 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{44109f88 type 2 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4310ca90 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4217cc90 type 2 com.google.android.gms}
,V/AlarmManager( 1016): sending alarm Alarm{428d11d8 type 3 android}
,D/ConnectivityService( 1016): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1214): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1214): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1214): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{43601838 type 3 android}
,I/jxcore-log( 4158): teardown
I/jxcore-log( 4158): 
,E/jxcore  ( 4158): Error!: self.currentTest is undefined
E/jxcore  ( 4158): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:159:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 4158): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{428189a0 type 3 android}
,I/jxcore-log( 4158): Connected to the server!
I/jxcore-log( 4158): 
,I/chromium( 4158): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1016): sending alarm Alarm{4231c480 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428028a0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4417c2d8 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{43118f10 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{42998460 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{44173540 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4391b7e8 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{43e6bae0 type 3 android}
,I/ProcessStatsService( 1016): Prepared write state in 29ms
,I/ProcessStatsService( 1016): Prepared write state in 19ms
,I/ProcessStatsService( 1016): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-17-14.bin
,V/AlarmManager( 1016): sending alarm Alarm{440ecbd8 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{440ecc28 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4299b300 type 3 com.google.android.gms}
,V/AlarmManager( 1016): sending alarm Alarm{4299b410 type 0 com.google.android.gms}
,V/AlarmManager( 1016): sending alarm Alarm{428d12b0 type 1 com.android.deskclock}
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,I/EventLogService( 1406): Aggregate from 1450233296078 (log), 1450232632885 (data)
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x62fa6528: I/O error during system call, Connection timed out
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{43603660 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4382ef60 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4310b268 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43575f88 type 3 android}
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4725): 
D/AndroidRuntime( 4725): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4725): CheckJNI is OFF
D/dalvikvm( 4725): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4725): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4725): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4725): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4725): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4725): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4725): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4725): failed to load memtrack module: -2
D/AndroidRuntime( 4725): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10483 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 4158:com.test.thalitest/u0a483 (adj 9): stop com.test.thalitest
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/InputDispatcher( 1016): channel '420f9900 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1016): channel '420f9900 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager( 1016):   Force finishing activity ActivityRecord{4231adf0 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1016): WIN DEATH: Window{420f9900 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1016): Client connection lost with reason: 4
W/InputDispatcher( 1016): Attempted to unregister already unregistered input channel '420f9900 com.test.thalitest/com.test.thalitest.MainActivity (server)'
D/dalvikvm( 1016): GC_CONCURRENT freed 2171K, 65% free 18206K/50756K, paused 42ms+9ms, total 121ms
D/dalvikvm( 1016): WAIT_FOR_CONCURRENT_GC blocked 49ms
W/PackageSettings( 1016): Skipping PackageSetting{42277c98 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10483 user=0: pkg removed
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
D/dalvikvm( 2292): GC_EXPLICIT freed 5627K, 44% free 9652K/17224K, paused 14ms+5ms, total 64ms
I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
D/VoicemailCleanupService( 4512): Cleaning up data for package: com.test.thalitest
W/GeofencerStateMachine( 1231): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1305): GC_EXPLICIT freed 3342K, 33% free 11632K/17224K, paused 2ms+5ms, total 99ms
I/Launcher( 1305): Deferring update until onResume
I/Launcher( 1305): Deferring update until onResume
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
D/dalvikvm( 2326): GC_EXPLICIT freed 3022K, 43% free 9824K/17224K, paused 53ms+3ms, total 175ms
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
D/dalvikvm( 1406): GC_CONCURRENT freed 1982K, 31% free 11999K/17224K, paused 56ms+16ms, total 191ms
D/dalvikvm( 1406): WAIT_FOR_CONCURRENT_GC blocked 135ms
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/InternalIcingCorporaPro( 2326): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1016): removePackageParticipantsLocked: uid=10483 #1
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4756 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450235098
D/dalvikvm( 1406): GC_EXPLICIT freed 97K, 31% free 11907K/17224K, paused 14ms+6ms, total 77ms
I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450235098
I/InternalIcingCorporaPro( 2326): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
D/dalvikvm( 1016): GC_EXPLICIT freed 940K, 65% free 18081K/50756K, paused 4ms+16ms, total 273ms
D/AndroidRuntime( 4725): Shutting down VM
D/dalvikvm( 4725): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4756): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 4756): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4781 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 4781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4550): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4550): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4550): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1406): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1406): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1406): Loading module com.google.android.gms.games from APK com.google.android.play.games
E/SQLiteLog( 1406): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1406): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraModuleLdr( 1406): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 1406): disk I/O error (code 3850)
E/DriveAsyncService( 1406): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1406): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1406): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1406): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1406): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1406): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1406): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1406): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1406): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1406): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1406): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1406): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1406): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1406): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1406): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1406): 	at java.lang.Thread.run(Thread.java:841)
D/ChimeraCfgMgr( 1406): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1406): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1370): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteLog( 1406): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/AndroidRuntime( 1370): Shutting down VM
W/dalvikvm( 1370): threadid=1: thread exiting with uncaught exception (group=0x416e6d40)
E/SQLiteDatabase( 1406): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1406): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1406): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1406): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1406): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1406): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1406): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 1406): threadid=52: thread exiting with uncaught exception (group=0x416e6d40)
E/SQLiteDatabase( 1406): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1406): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1406): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1406): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1406): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1406): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1406): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1406): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1406): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1406): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1406): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1406): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1406): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1406): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1406): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1406): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1406): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1406): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1406): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1406): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1406): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1406): threadid=51: thread exiting with uncaught exception (group=0x416e6d40)
I/Process ( 1406): Sending signal. PID: 1406 SIG: 9
E/AndroidRuntime( 1370): FATAL EXCEPTION: main
E/AndroidRuntime( 1370): Process: com.google.process.gapps, PID: 1370
E/AndroidRuntime( 1370): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1370): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1370): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1370): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1370): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1370): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1370): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1370): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1370): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1370): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1370): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1370): 	... 10 more
E/SQLiteDatabase( 4781): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4781): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4781): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4781): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4781): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4781): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4781): threadid=10: thread exiting with uncaught exception (group=0x416e6d40)
I/Process ( 1370): Sending signal. PID: 1370 SIG: 9
E/DropBoxManagerService( 1016): Can't write: system_app_crash
E/DropBoxManagerService( 1016): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1016): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1016): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1016): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1016): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1016): 	... 5 more
E/AndroidRuntime( 4781): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4781): Process: com.android.keychain, PID: 4781
E/AndroidRuntime( 4781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4781): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4781): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4781): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4781): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4781): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
