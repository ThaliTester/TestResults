#### Test 50650278cd699a4_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4026): 
D/AndroidRuntime( 4026): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4026): CheckJNI is OFF
D/dalvikvm( 4026): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4026): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4026): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4026): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4026): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4026): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4026): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4026): failed to load memtrack module: -2
D/AndroidRuntime( 4026): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4026
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4042 uid=10485 gids={50485, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4026): Shutting down VM
D/dalvikvm( 4026): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4042): Binding Chromium to main looper Looper (main, tid 1) {41f4dd60}
I/LibraryLoader( 4042): Expected native library version number "",actual native library version number ""
I/chromium( 4042): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4042): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41fb4c78:true
I/Adreno-EGL( 4042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4042): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4042): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4042): Local Branch: 
I/Adreno-EGL( 4042): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4042): Local Patches: NONE
I/Adreno-EGL( 4042): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4042): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4042): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4042): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4042): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4042): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4042): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4042): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4042): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4042): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4042): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4042): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4042): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4042): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4042): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4042): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4042): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4042): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4042): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4042): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4042): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4042): Enabling debug mode 0
,W/AwContents( 4042): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4042): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,384
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +360ms (total +385ms)
,D/JsMessageQueue( 4042): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4042): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f52470
,D/dalvikvm( 4042): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f52470
D/jxcore_app_log( 4042): JniHelper::setJavaVM(0x415a3fa8), pthread_self() = 1614112448
,D/JX-Cordova( 4042): jxcore cordova android initializing
,D/dalvikvm( 4042): GC_CONCURRENT freed 2812K, 17% free 14377K/17224K, paused 3ms+2ms, total 57ms
,D/dalvikvm( 4042): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 169K, 17% free 14380K/17224K, paused 24ms, total 24ms
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 180K, 17% free 14416K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 16.249MB for 144892-byte allocation
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 260K, 17% free 14458K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 16.359MB for 217334-byte allocation
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 367K, 18% free 14532K/17584K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 16.535MB for 325996-byte allocation
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 568K, 19% free 14654K/17904K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 16.809MB for 488990-byte allocation
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 865K, 20% free 14831K/18384K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 17.215MB for 733480-byte allocation
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 1284K, 22% free 15089K/19104K, paused 26ms, total 27ms
,D/dalvikvm( 4042): GC_CONCURRENT freed 1675K, 20% free 15460K/19104K, paused 1ms+3ms, total 30ms
,D/dalvikvm( 4042): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 369K, 20% free 15417K/19104K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 18.663MB for 1650320-byte allocation
,D/dalvikvm( 4042): GC_CONCURRENT freed 1682K, 23% free 15990K/20716K, paused 1ms+3ms, total 34ms
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 1367K, 23% free 16070K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 20.086MB for 2475476-byte allocation
,D/dalvikvm( 4042): GC_CONCURRENT freed 281K, 21% free 18387K/23136K, paused 5ms+3ms, total 45ms
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 4332K, 27% free 17042K/23136K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4042): Grow heap (frag case) to 22.216MB for 3713210-byte allocation
,D/dalvikvm( 4042): GC_CONCURRENT freed 390K, 24% free 20587K/26764K, paused 5ms+4ms, total 55ms
,D/dalvikvm( 4042): GC_FOR_ALLOC freed 3108K, 33% free 17987K/26764K, paused 27ms, total 27ms
,W/jxcore-log( 4042): Initializing JXcore engine
,W/jxcore-log( 4042): JXcore engine is ready
,D/dalvikvm( 4042): GC_CONCURRENT freed 350K, 24% free 20606K/26764K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 4042): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4042): Starting JXcore engine
,W/jxcore-log( 4042): Platform android
W/jxcore-log( 4042): 
,W/jxcore-log( 4042): Process ARCH arm
W/jxcore-log( 4042): 
,I/jxcore-log( 4042): JXcore Cordova bridge is ready!
I/jxcore-log( 4042): 
,W/jxcore-log( 4042): JXcore engine is started
,I/chromium( 4042): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4042): Toggling radios to true
I/jxcore-log( 4042): 
,D/BluetoothAdapter( 4042): enable(): BT is already enabled..!
D/WifiService( 1017): New client listening to asynchronous messages
D/WifiService( 1017): setWifiEnabled: true pid=4042, uid=10485
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1017): handleMessage: E msg.what=131145
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
I/jxcore-log( 4042): Radios toggled
I/jxcore-log( 4042): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4042): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4042): 
I/jxcore-log( 4042): Perf Test app loaded loaded
I/jxcore-log( 4042): 
,I/jxcore-log( 4042): check test folder
I/jxcore-log( 4042): 
,I/jxcore-log( 4042): found test : ./testFindPeers.js
I/jxcore-log( 4042): 
,D/TCMD    (  455): NL - Read 1000 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering( 1017): InitialState.processMessage what=4
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1017): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
V/ConnectivityService( 1017): WiFi NOT Tethered!
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
I/jxcore-log( 4042): found test : ./testSendData.js
I/jxcore-log( 4042): 
D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 21
D/TCMD    (  455): Listening for incoming client connection request
D/WifiStateMachine( 1017): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1017): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1017): connected time updated 276273
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1017): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1017): resetConnections(wlan0, 3)
D/NetUtils( 1017): android_net_utils_resetConnections in env=0x611a6f38 clazz=0x5ff00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 2105): Read error: ssl=0x61177aa8: I/O error during system call, Connection timed out
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1017): DisconnectingState
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131146
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147460
D/WifiStateMachine( 1017): processMsg: DisconnectingState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): Network connection lost
,D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 2105): SSL shutdown failed: ssl=0x61177aa8: I/O error during system call, Broken pipe
,D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
,I/Choreographer( 4042): Skipped 117 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4042): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 9e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 9e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 9 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH ,
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
,D/WifiP2pService( 1017): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiP2pService( 1017): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): handleMessage: X
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1270): Active network info is not available
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1017): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4113 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1270): Active network info is not available
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1557): Registering with Alarm Manager to restart CCE
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.onRadioDown
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/dalvikvm( 4113): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f55f08, skipping init
I/openssl ( 4113): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4113): Crypto mode 0 already enabled
I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4143 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 2915:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4143): mnc/mcc: 
,V/MmsConfig( 4143): tag: bool value: enabledMMS - true
,V/MmsConfig( 4143): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4143): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4143): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4143): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4143): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4143): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4143): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4143): tag: int value: recipientLimit - 20
,V/MmsConfig( 4143): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4143): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4143): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 4143): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4143): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4143): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4143): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4143): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4143): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4163 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 3872:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4163): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4163): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4176 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3642:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4189 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3903:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4189): Binding Chromium to main looper Looper (main, tid 1) {41f52ee8}
,I/LibraryLoader( 4189): Expected native library version number "",actual native library version number ""
,I/chromium( 4189): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4189): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4189): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4189): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4189): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4189): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4189): Local Branch: 
I/Adreno-EGL( 4189): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4189): Local Patches: NONE
I/Adreno-EGL( 4189): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4189): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4189): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4189): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4189): Starting up...
,I/iu.Environment( 3228): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3228): SYNC; picasa accounts
I/ActivityManager( 1017): Killing 3660:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1393): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1393): num queued entries: 0
,I/iu.UploadsManager( 1393): num updated entries: 0
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.SyncManager( 1393): NEXT; no task
,I/iu.UploadsManager( 3228): num queued entries: 0
,I/iu.UploadsManager( 3228): num updated entries: 0
,I/iu.Environment( 3228): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.SyncManager( 3228): NEXT; no task
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
,I/jxcore-log( 4042): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4042): 
,I/GAV2    ( 4189): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 1168): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request,
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  274): Event received = Trying to associate with,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1168): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  455): NL - Read 312 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 192 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 1000 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  274): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  455): NL - Read 1000 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213589680
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
,E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147459
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): Network connection established
,D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1017): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1017): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1017): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-48ms what=147462 obj=android.net.wifi.StateChangeResult@44402118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-38ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@44404698 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=196612
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42783a38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42783a38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: X
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
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 10 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiP2pService( 1017): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: X
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 20
,D/TCMD    (  455): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): DHCP successful
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1017): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1017): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState enter
,D/WifiStateMachine( 1017): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=151572
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=135190
,D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1017): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1017): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState enter
,D/WifiStateMachine( 1017): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1017): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1017): WiFi NOT Tethered!
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@420345a0
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiStateMachine( 1017): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1017): WiFi NOT Tethered!
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@420345a0
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/ModemStatsDSDetect( 1292): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1393): Checkin interval check for package: unspecified last checkin: 1450240632036 min interval config: 0 actual interval: 287751
,I/CheckinService( 1393): Checking schedule, now: 1450240919800 next: 1450240662017
,I/CheckinService( 1393): active receiver: enabled
,I/CheckinService( 1393): Preparing to send checkin request
,I/EventLogService( 1393): Accumulating logs since 1450240628848
,I/CheckinRequestBuilder( 1393): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1393): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1017): GC_EXPLICIT freed 1750K, 65% free 18044K/50704K, paused 3ms+9ms, total 91ms
,V/GLSActivity( 2105): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2105): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{443cdb38 type 3 android}
,I/ActivityManager( 1017): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4318 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4318): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4318): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4318): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4318): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4318): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4318): install
,I/MultiDex( 4318): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4318): loading existing secondary dex files
,I/MultiDex( 4318): load found 3 secondary dex files
,I/MultiDex( 4318): install done
,D/dalvikvm( 4318): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4318): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4318): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4318): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4318): VFY: unable to resolve instance field 36
,D/dalvikvm( 4318): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4318): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4318): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4318): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4318): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4318): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f58ac0
,D/dalvikvm( 4318): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f58ac0
,D/dalvikvm( 4318): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f58ac0, skipping init
D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f58ac0
D/dalvikvm( 4318): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f58ac0
,V/JNIHelp ( 4318): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f58ac0
,D/dalvikvm( 4318): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f58ac0
D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f58ac0
,D/dalvikvm( 4318): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f58ac0
,I/ProviderInstaller( 4318): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1225): callingUid 10022, callindPid: 1225
,E/MDM     ( 1225): [70] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 2105): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 2105): Proximity feature is not enabled.
,D/LocationInitializer( 1393): Restart initialization of location
,V/GLSActivity( 2105): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
,I/dalvikvm( 4318): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4318): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4318): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4318): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4318): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4318): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4318): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4318): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4318): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4318): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4318): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4318): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4318): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4318): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5108000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5108000
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3016742159
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4318): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4318): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42165d50
D/dalvikvm( 4318): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42165d50
,D/dalvikvm( 4318): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42165d50, skipping init
,I/jxcore-log( 4042): Connected to the server!
I/jxcore-log( 4042): 
,I/chromium( 4042): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1017): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4318): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4369): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4318): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4318): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 82ms
,I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4318): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=2943128614
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1393): Classify the device as Phone.
,I/CheckinTask( 1393): Sending checkin request (11752 bytes)
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/PollingManager( 1557): now: 338920 ,futureTime: 54233850
,D/PollingManager( 1557): Polling alarm set to expire at: 54233850 Current Time: 338920
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/Tethering( 1017): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): now: 338952 ,futureTime: 54233850
,D/PollingManager( 1557): Polling alarm set to expire at: 54233850 Current Time: 338952
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4113): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4113): Crypto mode 0 already enabled
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
,I/iu.Environment( 3228): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/dalvikvm( 1557): GC_CONCURRENT freed 2165K, 39% free 10664K/17224K, paused 3ms+4ms, total 38ms
,I/CheckinService( 1393): Checkin interval check for package: unspecified last checkin: 1450240632036 min interval config: 0 actual interval: 290897
,I/iu.UploadsManager( 3228): num queued entries: 0
I/iu.UploadsManager( 3228): num updated entries: 0
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.SyncManager( 3228): NEXT; no task
,I/iu.Environment( 1393): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1393): num queued entries: 0
,I/iu.UploadsManager( 1393): num updated entries: 0
,I/iu.SyncManager( 1393): NEXT; no task
,I/openssl ( 4113): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4113): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3228): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1393): Checkin interval check for package: unspecified last checkin: 1450240632036 min interval config: 0 actual interval: 290943
,D/dalvikvm( 3228): GC_FOR_ALLOC freed 217K, 3% free 20654K/21204K, paused 13ms, total 13ms
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
,I/CheckinRequestBuilder( 1393): Checkin reason type: 8 attempt count: 1
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
E/ActivityThread( 1393): Failed to find provider info for com.google.android.wearable.settings
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4042): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1017): Activity reported stop, but no longer stopping: ActivityRecord{4279a7a0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1017): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,122
I/CheckinRequestBuilder( 1393): Classify the device as Phone.
,I/CheckinTask( 1393): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1393): Checking schedule, now: 1450240923152 next: 1450833993149
,I/CheckinService( 1393): active receiver: disabled
,I/CheckinService( 1393): Checking schedule, now: 1450240923168 next: 1450833993149
,I/CheckinService( 1393): active receiver: disabled
,D/CheckinService( 1393): Recording last checkin time for package unspecified as 1450240923173
,D/GCM     ( 2105): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1080): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1292): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1292): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/ConnectivityService( 1017): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1017):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager( 1017): Killing 3929:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1017): sending alarm Alarm{444975d8 type 2 android}
,V/AlarmManager( 1017): sending alarm Alarm{444976b0 type 0 com.google.android.gms}
,I/EventLogService( 1393): Aggregate from 1450240919817 (log), 1450238953376 (data)
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4426 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/Launcher( 1307): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/Launcher( 1307): Deferring update until onResume
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4426): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4426): MmsConfig.loadMmsSettings
I/Babel   ( 4426): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4426): MmsConfig.loadFromDatabase
,E/Babel   ( 4426): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4426): MmsConfig.loadFromResources
,E/Babel   ( 4426): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4426): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4426): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1017): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4463 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1017): Killing 3559:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1017): GC_EXPLICIT freed 1399K, 65% free 18041K/50704K, paused 4ms+10ms, total 91ms
I/ActivityManager( 1017): Killing 4113:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4482 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ContactLocale( 4463): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2281): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4500 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4143:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/dalvikvm( 4500): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4500): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4500): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4500): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4500): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4500): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4500): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2281): UpdateCorporaTask done [took 234 ms] updated apps [took 233 ms] 
,D/Finsky  ( 4500): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4500): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4500): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4500): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4500): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4500): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4500): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4500): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4500): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4500): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4500): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4534 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4500): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4500): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4500): Skipping gmscore version check
,D/Finsky  ( 4500): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4500): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4500): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4500): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4500): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1017): Killing 4163:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1393): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1393): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1393): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4534): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f54578, skipping init
I/openssl ( 4534): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4534): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Killing 4176:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4500): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4500): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/dalvikvm( 1393): GC_CONCURRENT freed 2207K, 31% free 12029K/17224K, paused 4ms+10ms, total 52ms
,D/dalvikvm( 1393): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 1393): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 1393): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/Icing   ( 1393): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1393): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450240931
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1017): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1017): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1017): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1017): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1017): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
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
,V/AlarmManager( 1017): sending alarm Alarm{444ac640 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{42822820 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4280fa80 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{444ac718 type 1 com.android.deskclock}
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4579 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 4189:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 10
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 11
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 11
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
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
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{427bfe98 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4273d090 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{424e1c48 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{444ac7f0 type 2 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{42271e30 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{444ac8c8 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,V/AlarmManager( 1017): sending alarm Alarm{42059de8 type 3 android}
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
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{41f7d1e0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4245da30 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{42435080 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4242ee50 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42418810 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{423fad08 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{423e5160 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{444ac9a0 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1292): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1292): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1292): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
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
,V/AlarmManager( 1017): sending alarm Alarm{42323710 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42066588 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4205e508 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42304fc0 type 1 com.android.deskclock}
,V/AlarmManager( 1017): sending alarm Alarm{42053820 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{422f76f8 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,V/AlarmManager( 1017): sending alarm Alarm{4202f040 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{44594390 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4459a090 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{445a3628 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{445ae2e8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{445af4a0 type 3 android}
,I/ProcessStatsService( 1017): Prepared write state in 32ms
,I/ProcessStatsService( 1017): Prepared write state in 21ms
,I/ProcessStatsService( 1017): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-46-03.bin
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
,V/AlarmManager( 1017): sending alarm Alarm{445c2cf8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{445cda70 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{445d5380 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{445db1e8 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms)
```
