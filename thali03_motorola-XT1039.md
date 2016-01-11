#### Test 55613145e2b298d_thali03_motorola-XT1039 Logs


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
D/AndroidRuntime( 4510): 
D/AndroidRuntime( 4510): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4510): CheckJNI is OFF
D/dalvikvm( 4510): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4510): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4510): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4510): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4510): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4510): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4510): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4510): failed to load memtrack module: -2
D/AndroidRuntime( 4510): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1010): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4510
W/WindowManager( 1010): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1010): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4533 uid=10539 gids={50539, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4510): Shutting down VM
D/dalvikvm( 4510): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4533): Binding Chromium to main looper Looper (main, tid 1) {41f0ada0}
I/LibraryLoader( 4533): Expected native library version number "",actual native library version number ""
I/chromium( 4533): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4533): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1010): Message: 20
D/BluetoothManagerService( 1010): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4401c5b8:true
I/Adreno-EGL( 4533): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4533): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4533): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4533): Local Branch: 
I/Adreno-EGL( 4533): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4533): Local Patches: NONE
I/Adreno-EGL( 4533): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4533): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4533): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4533): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4533): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4533): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4533): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4533): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4533): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4533): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4533): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4533): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4533): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4533): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 4533): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4533): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4533): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4533): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4533): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4533): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4533): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4533): Enabling debug mode 0
,W/AwContents( 4533): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4533): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1010): Displayed com.test.thalitest/.MainActivity,cp,ca,379
I/ActivityManager( 1010): Displayed com.test.thalitest/.MainActivity: +351ms (total +379ms)
,D/JsMessageQueue( 4533): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4533): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f0f070
,D/dalvikvm( 4533): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f0f070
,D/jxcore_app_log( 4533): JniHelper::setJavaVM(0x41557fa8), pthread_self() = 1613869640
,D/JX-Cordova( 4533): jxcore cordova android initializing
,D/dalvikvm( 4533): GC_CONCURRENT freed 2787K, 17% free 14402K/17224K, paused 2ms+2ms, total 49ms
,D/dalvikvm( 4533): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4533): GC_FOR_ALLOC freed 127K, 17% free 14406K/17224K, paused 24ms, total 24ms
,D/dalvikvm( 4533): GC_FOR_ALLOC freed 128K, 17% free 14424K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4533): Grow heap (frag case) to 16.210MB for 96598-byte allocation
,D/dalvikvm( 4533): GC_FOR_ALLOC freed 179K, 17% free 14458K/17320K, paused 24ms, total 25ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 16.291MB for 144892-byte allocation
D/dalvikvm( 4533): GC_FOR_ALLOC freed 253K, 17% free 14506K/17464K, paused 24ms, total 24ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 16.406MB for 217334-byte allocation
D/dalvikvm( 4533): GC_FOR_ALLOC freed 369K, 18% free 14581K/17680K, paused 25ms, total 25ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 16.583MB for 325996-byte allocation
D/dalvikvm( 4533): GC_FOR_ALLOC freed 568K, 19% free 14702K/18000K, paused 25ms, total 25ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 16.856MB for 488990-byte allocation
D/dalvikvm( 4533): GC_FOR_ALLOC freed 866K, 20% free 14879K/18480K, paused 26ms, total 27ms
D/dalvikvm( 4533): GC_FOR_ALLOC freed 1287K, 19% free 15136K/18480K, paused 27ms, total 27ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 17.863MB for 1100216-byte allocation
D/dalvikvm( 4533): GC_CONCURRENT freed 1750K, 21% free 15520K/19556K, paused 2ms+3ms, total 34ms
D/dalvikvm( 4533): GC_FOR_ALLOC freed 306K, 21% free 15458K/19556K, paused 26ms, total 26ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 18.702MB for 1650320-byte allocation
D/dalvikvm( 4533): GC_CONCURRENT freed 1757K, 25% free 16043K/21168K, paused 2ms+5ms, total 43ms
D/dalvikvm( 4533): GC_FOR_ALLOC freed 1259K, 24% free 16096K/21168K, paused 29ms, total 29ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 20.112MB for 2475476-byte allocation
D/dalvikvm( 4533): GC_CONCURRENT freed 229K, 22% free 18401K/23588K, paused 5ms+3ms, total 34ms
D/dalvikvm( 4533): GC_CONCURRENT freed 4388K, 28% free 17109K/23588K, paused 2ms+8ms, total 41ms
D/dalvikvm( 4533): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/dalvikvm-heap( 4533): Grow heap (frag case) to 22.282MB for 3713210-byte allocation
,D/dalvikvm( 4533): GC_CONCURRENT freed 422K, 25% free 20607K/27216K, paused 4ms+6ms, total 52ms
,D/dalvikvm( 4533): GC_FOR_ALLOC freed 3163K, 34% free 18059K/27216K, paused 27ms, total 27ms
,W/jxcore-log( 4533): Initializing JXcore engine
,W/jxcore-log( 4533): JXcore engine is ready
,D/dalvikvm( 4533): GC_CONCURRENT freed 374K, 25% free 20679K/27216K, paused 1ms+2ms, total 30ms
,D/dalvikvm( 4533): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4533): Starting JXcore engine
,W/jxcore-log( 4533): Platform android
W/jxcore-log( 4533): 
,W/jxcore-log( 4533): Process ARCH arm
W/jxcore-log( 4533): 
,I/jxcore-log( 4533): JXcore Cordova bridge is ready!
I/jxcore-log( 4533): 
,W/jxcore-log( 4533): JXcore engine is started
,I/chromium( 4533): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4533): Toggling radios to true
I/jxcore-log( 4533): 
,D/BluetoothAdapter( 4533): enable(): BT is already enabled..!
D/WifiService( 1010): New client listening to asynchronous messages
D/WifiService( 1010): setWifiEnabled: true pid=4533, uid=10539
,E/WifiService( 1010): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1010): handleMessage: E msg.what=131145
D/WifiStateMachine( 1010): processMsg: ConnectedState
D/WifiStateMachine( 1010): processMsg: L2ConnectedState
I/jxcore-log( 4533): Radios toggled
I/jxcore-log( 4533): 
D/BluetoothManagerService( 1010): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1010): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4533): Received device characteristics:
I/jxcore-log( 4533): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4533): Bluetooth name: XT1039
I/jxcore-log( 4533): Device name: motorola-XT1039
I/jxcore-log( 4533): 
I/jxcore-log( 4533): Perf Test app loaded loaded
I/jxcore-log( 4533): 
,I/jxcore-log( 4533): check test folder
I/jxcore-log( 4533): 
,I/jxcore-log( 4533): found test : ./testFindPeers.js
I/jxcore-log( 4533): 
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
,D/Tethering( 1010): InitialState.processMessage what=4
D/WifiStateMachine( 1010): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1010): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1010): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1010): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1010): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine( 1010): Stopping DHCP and clearing IP
,V/ConnectivityService( 1010): WiFi NOT Tethered!
D/Tethering( 1010): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiStateMachine( 1010): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1010): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1010): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  425): NL - Read 60 bytes from update socket.
D/TCMD    (  425): NL - ignore NL message, type = 21
,D/TCMD    (  425): Listening for incoming client connection request
,D/WifiStateMachine( 1010): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1010): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1010): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
I/jxcore-log( 4533): found test : ./testSendData.js
I/jxcore-log( 4533): 
,D/WifiMetrics( 1010): connected time updated 293113
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1010): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1010): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1010): Attempting to switch to mobile
D/ConnectivityService( 1010): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1010): Attempting to switch to ETHERNET
,D/ConnectivityService( 1010): resetConnections(wlan0, 3)
D/NetUtils( 1010): android_net_utils_resetConnections in env=0x61146260 clazz=0x62700001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1010): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1010): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
,D/WifiStateMachine( 1010): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1010): DisconnectingState
,D/Checkin ( 1010): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=131146
D/WifiStateMachine( 1010): processMsg: DisconnectingState
,D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=147460
D/WifiStateMachine( 1010): processMsg: DisconnectingState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): Network connection lost
D/WifiStateMachine( 1010): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1010): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1391): Read error: ssl=0x6300d000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1391): SSL shutdown failed: ssl=0x6300d000: I/O error during system call, Broken pipe
D/WifiP2pService( 1010): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1010): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1010): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1010): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1010): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1010): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1010): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1010): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1010): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1010): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=131101
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
D/WifiStateMachine( 1010): processMsg: DefaultState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=131216
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
D/WifiStateMachine( 1010): processMsg: DefaultState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=131216
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
D/WifiStateMachine( 1010): processMsg: DefaultState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): handleMessage: X
D/Checkin ( 1010): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Nat464Xlat( 1010): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1010): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1010): Attempting to switch to mobile
D/ConnectivityService( 1010): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1010): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1010): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1010): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
,I/Choreographer( 4533): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4533): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1010): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1010): processMsg: DisconnectedState
,D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  425): NL - Read 56 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK,
,D/TCMD    (  425): Listening for incoming client connection request
,D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): handleMessage: X
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  425): NL - Read 312 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 192 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  425): NL - Read 80 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
,D/TCMD    (  425): NL - Read 80 bytes from update socket.,
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
,D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1010): processMsg: DisconnectedState
,D/WifiStateMachine( 1010): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
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
,I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1211905200
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
,D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
,E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1010): processMsg: DisconnectedState
,D/WifiStateMachine( 1010): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): handleMessage: X
,D/WifiStateMachine( 1010): handleMessage: E msg.what=147459
D/WifiStateMachine( 1010): processMsg: DisconnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): Network connection established
,D/WifiStateMachine( 1010): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1010): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1010): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1010): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1010): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1010): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1010): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1010): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1010): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1010): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1010): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1010): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=147462
D/WifiStateMachine( 1010): processMsg: ObtainingIpState
D/WifiStateMachine( 1010): ObtainingIpState{ when=-41ms what=147462 obj=android.net.wifi.StateChangeResult@44575118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1010): processMsg: L2ConnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): handleMessage: X
,D/WifiStateMachine( 1010): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1010): processMsg: ObtainingIpState
D/WifiStateMachine( 1010): ObtainingIpState{ when=-35ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@445d6858 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1010): processMsg: L2ConnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
,D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
D/WifiStateMachine( 1010): processMsg: DefaultState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1010): processMsg: ObtainingIpState
D/WifiStateMachine( 1010): ObtainingIpState{ when=-12ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1010): processMsg: L2ConnectedState
,D/WifiStateMachine( 1010): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1010): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1010): handleMessage: X
D/WifiP2pService( 1010): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426ff1f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1010): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426ff1f0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  425): NL - Read 56 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 0c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 0c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 fc
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 fc
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fe
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 fe
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 80
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 80
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiP2pService( 1010): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1010): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1010): processMsg: ObtainingIpState
D/WifiP2pService( 1010): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1010): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1010): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4474a678 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1010): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4474a678 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1010): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4474a678 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1010): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1010): processMsg: L2ConnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1010): handleMessage: X
,D/TCMD    (  425): NL - Read 60 bytes from update socket.
D/TCMD    (  425): NL - ignore NL message, type = 20
,D/TCMD    (  425): Listening for incoming client connection request
,D/WifiStateMachine( 1010): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1010): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1010): processMsg: ObtainingIpState
,D/WifiStateMachine( 1010): ObtainingIpState{ when=-7ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1010): processMsg: L2ConnectedState
,D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): processMsg: DriverStartedState
,D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1010): processMsg: DefaultState
,D/WifiStateMachine( 1010): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1010): handleMessage: X
,D/WifiStateMachine( 1010): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1010): processMsg: ObtainingIpState
,D/WifiStateMachine( 1010): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1010): processMsg: L2ConnectedState
,D/WifiStateMachine( 1010): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1010): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1010): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1010): DHCP successful
,D/WifiStateMachine( 1010): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1010): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1010): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1010): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1010): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1010): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1010): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1010): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1010): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine( 1010): VerifyingLinkState enter
,D/WifiStateMachine( 1010): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1010): processMsg: VerifyingLinkState
D/WifiStateMachine( 1010): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1010): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1010): handleMessage: X
,D/WifiStateMachine( 1010): handleMessage: E msg.what=135190
D/WifiStateMachine( 1010): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1010): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1010): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1010): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1010): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1010): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1010): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1010): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1010): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1010): CaptivePortalCheckState enter
,D/WifiStateMachine( 1010): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1010): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1010): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1010): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1010): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1010): handleMessage: X
,D/WifiStateMachine( 1010): handleMessage: E msg.what=131092
D/WifiStateMachine( 1010): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1010): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1010): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1010): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1010): WiFi NOT Tethered!
,E/ConnectivityService( 1010): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff0f98
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1010): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1010): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1010): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1010): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1010): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1010): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1010): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1010): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1010): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1010): handleMessage: X
D/WifiStateMachine( 1010): handleMessage: E msg.what=131092
D/WifiStateMachine( 1010): processMsg: ConnectedState
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1010): processMsg: L2ConnectedState
,D/WifiStateMachine( 1010): processMsg: ConnectModeState
D/WifiStateMachine( 1010): processMsg: DriverStartedState
D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
D/WifiStateMachine( 1010): processMsg: DefaultState
,D/WifiStateMachine( 1010): handleMessage: X
D/ConnectivityService( 1010): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1010): WiFi NOT Tethered!
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1010): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff0f98
D/ConnectivityService( 1010): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1010): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1298): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1010): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1010): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1010): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1010): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4663 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 24ms
,D/Tethering( 1010): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1010): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1578): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1578): Registering with Alarm Manager to restart CCE
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
,D/OtaApp  ( 1578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1578): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/dalvikvm( 4663): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f12b08, skipping init
I/openssl ( 4663): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4663): Crypto mode 0 already enabled
,I/ActivityManager( 1010): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4693 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1010): Killing 4342:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4693): mnc/mcc: 
V/MmsConfig( 4693): tag: bool value: enabledMMS - true
,V/MmsConfig( 4693): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4693): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4693): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4693): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4693): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4693): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4693): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4693): tag: int value: recipientLimit - 20
V/MmsConfig( 4693): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4693): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4693): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4693): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4693): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4693): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4693): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4693): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4693): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1010): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4712 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1010): Killing 4329:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4712): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4712): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4712): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4712): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1010): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4726 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1010): Killing 4009:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1420): Checkin interval check for package: unspecified last checkin: 1452523191582 min interval config: 0 actual interval: 231273
,I/CheckinService( 1420): Checking schedule, now: 1452523422861 next: 1452523221564
,I/CheckinService( 1420): active receiver: enabled
,I/CheckinService( 1420): Preparing to send checkin request
,I/EventLogService( 1420): Accumulating logs since 1452523188593
,I/CheckinRequestBuilder( 1420): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1420): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1010): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4743 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1010): Killing 4408:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/GLSActivity( 1391): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1391): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1010): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4756 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4756): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4756): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4756): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4756): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4756): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4756): install
,I/MultiDex( 4756): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4756): loading existing secondary dex files
,I/MultiDex( 4756): load found 3 secondary dex files
,I/jxcore-log( 4533): Connected to the server!
I/jxcore-log( 4533): 
,I/MultiDex( 4756): install done
D/ConnectivityService( 1010): NetTransition Wakelock for ConnectedState released by timeout
,I/chromium( 4533): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 4756): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4756): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4756): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4756): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4756): VFY: unable to resolve instance field 36
,D/dalvikvm( 4756): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4756): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4756): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4756): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4756): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4756): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0aac0
D/dalvikvm( 4756): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0aac0
,D/dalvikvm( 4756): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0aac0, skipping init
,D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f0aac0
D/dalvikvm( 4756): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f0aac0
,V/JNIHelp ( 4756): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 1010): GC_EXPLICIT freed 23455K, 65% free 18102K/50544K, paused 6ms+11ms, total 170ms
,V/WebViewChromiumFactoryProvider( 4743): Binding Chromium to main looper Looper (main, tid 1) {41f03d20}
,I/LibraryLoader( 4743): Expected native library version number "",actual native library version number ""
,I/chromium( 4743): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4743): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4743): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4743): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4743): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4743): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4743): Local Branch: 
I/Adreno-EGL( 4743): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4743): Local Patches: NONE
I/Adreno-EGL( 4743): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f0aac0
,D/dalvikvm( 4756): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f0aac0
D/dalvikvm( 4756): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f0aac0
,D/dalvikvm( 4756): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f0aac0
,W/chromium( 4743): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4743): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4743): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ProviderInstaller( 4756): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4756): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4756): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4756): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4756): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4756): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4756): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4756): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4756): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4756): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4756): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4756): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4756): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4756): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4756): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4756): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52f5000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52f5000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,I/NSApplication( 4743): Starting up...
D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  278): PrepareKeyRequest: nonce=2948681126
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ImageResourceManager( 4046): ImageResourceManager: uninitalized
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/iu.Environment( 4046): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1010): Killing 4028:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4663): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4663): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4712): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4712): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4046): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1578): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1578): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1578): bindWebServices(): registering our AIDL callback...
I/SundryService( 1578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1578): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1578): onServiceConnected()
D/GetNotificationsWS( 1578): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1578): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1224): callingUid 10022, callindPid: 1224
,E/MDM     ( 1224): [68] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1391): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1391): Proximity feature is not enabled.
,D/LocationInitializer( 1420): Restart initialization of location
,V/GLSActivity( 1391): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
,D/dalvikvm( 4756): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420fc6c0
D/dalvikvm( 4756): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420fc6c0
,D/dalvikvm( 4756): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420fc6c0, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/NativeLibraryUtils( 4756): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  278): PrepareKeyRequest: nonce=1400006777
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 4756): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4756): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4822): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4756): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4756): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 72ms
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4756): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4756): Local Patches: NONE
I/Adreno-EGL( 4756): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4756): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4756): Local Patches: NONE
I/Adreno-EGL( 4756): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4533): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4533): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4533): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4533): Shutting down VM
,W/dalvikvm( 4533): threadid=1: thread exiting with uncaught exception (group=0x41636d40)
E/AndroidRuntime( 4533): FATAL EXCEPTION: main
E/AndroidRuntime( 4533): Process: com.test.thalitest, PID: 4533
E/AndroidRuntime( 4533): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4533): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4533): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4533): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4533): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4533): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4533): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4533): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4533): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4533): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4533): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4533): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4533): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4533): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4533): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4533): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4533): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4533): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4533): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1010):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager( 1010): Killing 4432:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4533): Sending signal. PID: 4533 SIG: 9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1010): Process com.test.thalitest (pid 4533) has died.
,D/WifiService( 1010): Client connection lost with reason: 4,
,I/WindowState( 1010): WIN DEATH: Window{4222cee0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/WifiStateMachine( 1010): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1010): handleMessage: E msg.what=131215
D/WifiStateMachine( 1010): processMsg: ConnectedState
D/WifiStateMachine( 1010): processMsg: L2ConnectedState
D/WifiStateMachine( 1010): processMsg: ConnectModeState
,D/WifiStateMachine( 1010): processMsg: DriverStartedState
D/WifiStateMachine( 1010): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1010): processMsg: DefaultState
,D/WifiStateMachine( 1010): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1010): handleMessage: X
D/ConnectivityService( 1010): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1010):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1010): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1010): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1010): requiresClat: netType=1, hasIPv4Address=true
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1010): Got RemoteException sending setActive(false) notification to pid 4533 uid 10539
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4756): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4756): Local Patches: NONE
I/Adreno-EGL( 4756): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4756): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4756): Local Patches: NONE
I/Adreno-EGL( 4756): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1420): Classify the device as Phone.
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,D/Tethering( 1010): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1010): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1578): now: 326319 ,futureTime: 23756624
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1578): Polling alarm set to expire at: 23756624 Current Time: 326322
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1578): now: 326329 ,futureTime: 23756624
D/PollingManager( 1578): Polling alarm set to expire at: 23756624 Current Time: 326329
D/Tethering( 1010): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1010): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1578): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/openssl ( 4663): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4663): Crypto mode 0 already enabled
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1578): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4712): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4712): onReceive CONNECTIVITY_CHANGE networkType=1
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/OtaApp  ( 1578): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 4046): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1578): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1420): Checkin interval check for package: unspecified last checkin: 1452523191582 min interval config: 0 actual interval: 233720
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/dalvikvm( 4046): GC_FOR_ALLOC freed 610K, 5% free 16439K/17224K, paused 26ms, total 27ms
I/openssl ( 4663): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4663): Crypto mode 0 already enabled
I/dalvikvm-heap( 4046): Grow heap (frag case) to 19.823MB for 1821008-byte allocation
D/MobileConnectivityChangeReceiver( 4712): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4712): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4046): GC_FOR_ALLOC freed 36K, 5% free 18184K/19004K, paused 10ms, total 10ms
,I/iu.Environment( 4046): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1420): Checkin interval check for package: unspecified last checkin: 1452523191582 min interval config: 0 actual interval: 233786
,D/DEBUG   ( 1578): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1578): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1578): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1578): onServiceConnected()
D/GetNotificationsWS( 1578): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1578): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1578): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1578): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1578): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1578): bindWebServices(): registering our AIDL callback...
I/SundryService( 1578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1578): onServiceConnected()
,D/GetNotificationsWS( 1578): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1578): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1578): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1578): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1010): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1578
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1578): unbindWebServices(): un-registering our AIDL callback...
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1578): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1578): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1010): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1578
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1010): Activity reported stop, but no longer stopping: ActivityRecord{4200cd30 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinTask( 1420): Sending checkin request (11795 bytes)
,I/CheckinRequestBuilder( 1420): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1420): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1391): GC_EXPLICIT freed 1233K, 40% free 10374K/17224K, paused 2ms+4ms, total 33ms
,I/CheckinRequestBuilder( 1420): Classify the device as Phone.
,I/CheckinTask( 1420): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1420): Checking schedule, now: 1452523426620 next: 1453116496611
,I/CheckinService( 1420): active receiver: disabled
,I/CheckinService( 1420): Checking schedule, now: 1452523426665 next: 1453116496611
,I/CheckinService( 1420): active receiver: disabled
,D/CheckinService( 1420): Recording last checkin time for package unspecified as 1452523426672
,D/GCM     ( 1391): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 4743): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService( 1010): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1298): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1298): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/InputReader( 1010): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "sms"
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager( 1010): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4887 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "smsto"
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mms"
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mmsto"
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "sms"
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "smsto"
,I/Launcher( 1311): Deferring update until onResume
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mms"
,I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mmsto"
,I/Launcher( 1311): Deferring update until onResume
,I/Babel   ( 4887): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4887): MmsConfig.loadMmsSettings
I/Babel   ( 4887): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4887): MmsConfig.loadFromDatabase
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel   ( 4887): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4887): MmsConfig.loadFromResources
,E/Babel   ( 4887): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4887): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4887): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1010): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4925 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1010): Killing 3936:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1010): Killing 4663:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1010): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4944 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2348): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1010): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4963 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1010): Killing 4693:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4925): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 1010): GC_EXPLICIT freed 1499K, 65% free 18147K/50544K, paused 5ms+10ms, total 96ms
,I/dalvikvm( 4963): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4963): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4963): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2348): UpdateCorporaTask done [took 296 ms] updated apps [took 296 ms] 
,I/dalvikvm( 4963): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4963): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4963): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4963): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4963): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4963): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4963): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4963): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4963): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4963): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4963): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4963): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4963): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4963): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4963): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1010): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5000 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4963): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4963): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4963): Skipping gmscore version check
,D/Finsky  ( 4963): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4963): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4963): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4963): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4963): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1010): Killing 4712:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1420): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1420): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1420): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 5000): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f10fd0, skipping init
I/openssl ( 5000): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 5000): Crypto mode 0 already enabled
D/dalvikvm( 1420): GC_CONCURRENT freed 1972K, 30% free 12129K/17224K, paused 5ms+9ms, total 53ms
D/dalvikvm( 1420): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 1420): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/Finsky  ( 4963): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4963): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1010): Killing 4726:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1420): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1420): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452523435
,D/CaptivePortalTracker( 1010): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1010): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1010): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1010): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1010): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1010): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1010): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1010): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1010): sending alarm Alarm{4402a698 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{4271ab60 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{4402a710 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1010): cleanup(): cleared. Last call was 67327 ms ago
,I/ActivityManager( 1010): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5047 uid=10015 gids={50015, 1028}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 37ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,I/ActivityManager( 1010): Killing 4743:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1010): sending alarm Alarm{4204a428 type 3 android}
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
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 9
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
,V/AlarmManager( 1010): sending alarm Alarm{42754c30 type 3 android}
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
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [7c:f9:0e:51:18:22]: 7, f, 610c
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1010): sending alarm Alarm{42357868 type 3 android}
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
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
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1010): sending alarm Alarm{44031d30 type 2 android}
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
D/        ( 1807): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
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
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1010): sending alarm Alarm{4284aef0 type 3 android}
,W/bt-l2cap( 1807): l2cu_get_conn_role 1
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [7c:f9:0e:51:18:22]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [58:3f:54:73:64:c0]: 0, 0, 0
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1807): tBTM_SEC_DEV:0x5f1f91b0 rs_disc_pending=1
,W/bt-btif ( 1807): bta_dm_check_av:0
,W/bt-btif ( 1807): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1807): l2cu_get_conn_role 0
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1807): l2cu_get_conn_role 0
,W/bt-btif ( 1807): info:x10
,D/        ( 1807): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
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
,D/btif_config_util( 1807): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
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
,E/bt-btm  ( 1807): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1807): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1010): sending alarm Alarm{41fec208 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{446ec4d8 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{4403a868 type 2 android}
,D/ConnectivityService( 1010): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1010): sending alarm Alarm{44041d50 type 0 com.google.android.gms}
,D/ConnectivityService( 1010): Done.
,D/ConnectivityService( 1010): Setting timer for 720seconds
,I/EventLogService( 1420): Aggregate from 1452523422892 (log), 1452522109847 (data)
,V/AlarmManager( 1010): sending alarm Alarm{4451c1f0 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{428be640 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{4272d280 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{42dee6c8 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{431f4968 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{435588b0 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{428f3c00 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{4336f458 type 2 com.google.android.gms}
,D/ConnectivityService( 1010): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1298): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1298): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1298): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1010): sending alarm Alarm{44709a38 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{432af470 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{430f5d88 type 1 com.android.deskclock}
,V/AlarmManager( 1010): sending alarm Alarm{4347eb70 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{432596f0 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{43191258 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{430f5e48 type 2 android}
,D/ConnectivityService( 1010): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1010): Done.
,D/ConnectivityService( 1010): Setting timer for 720seconds
,V/AlarmManager( 1010): sending alarm Alarm{43d628c8 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{42907f58 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{445bd448 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{43d7cad8 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{42833e80 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{432338b0 type 3 android}
,I/ProcessStatsService( 1010): Prepared write state in 26ms
,I/ProcessStatsService( 1010): Prepared write state in 31ms
,I/ProcessStatsService( 1010): Prepared write state in 17ms
,I/ProcessStatsService( 1010): Pruning old procstats: /data/system/procstats/state-2016-01-10-21-11-04.bin
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
,V/AlarmManager( 1010): sending alarm Alarm{434a0ab8 type 3 android}
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
,V/AlarmManager( 1010): sending alarm Alarm{433f3d18 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{42e1c6f8 type 3 android}
,V/AlarmManager( 1010): sending alarm Alarm{430ff5e8 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5113): 
D/AndroidRuntime( 5113): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5113): CheckJNI is OFF
D/dalvikvm( 5113): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5113): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5113): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5113): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5113): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5113): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5113): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5113): failed to load memtrack module: -2
D/AndroidRuntime( 5113): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1010): Force stopping com.test.thalitest appid=10539 user=-1: uninstall pkg
W/PackageSettings( 1010): Skipping PackageSetting{421d1c80 com.example.hello/10529} due to missing metadata
I/ActivityManager( 1010): Force stopping com.test.thalitest appid=10539 user=0: pkg removed
D/dalvikvm( 2313): GC_EXPLICIT freed 5565K, 44% free 9651K/17224K, paused 3ms+5ms, total 64ms
D/dalvikvm( 2348): GC_EXPLICIT freed 3627K, 43% free 9860K/17224K, paused 1ms+4ms, total 98ms
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "sms"
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1010): GC_EXPLICIT freed 1959K, 64% free 18209K/50544K, paused 6ms+18ms, total 131ms
D/dalvikvm( 1010): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/InputReader( 1010): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1420): GC_EXPLICIT freed 1032K, 31% free 11997K/17224K, paused 4ms+39ms, total 164ms
D/dalvikvm( 1311): GC_EXPLICIT freed 3439K, 33% free 11598K/17224K, paused 2ms+5ms, total 139ms
I/Launcher( 1311): Deferring update until onResume
D/dalvikvm( 1010): GC_EXPLICIT freed 184K, 65% free 18053K/50544K, paused 12ms+8ms, total 105ms
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "smsto"
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452525226
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mms"
D/VoicemailCleanupService( 4925): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mmsto"
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "sms"
I/Launcher( 1311): Deferring update until onResume
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "smsto"
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mms"
I/PackageManager( 1010): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1010):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1010):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1010):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2348): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/AndroidRuntime( 5113): Shutting down VM
D/dalvikvm( 5113): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
I/ActivityManager( 1010): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5145 uid=10059 gids={50059, 3003, 1028, 1015}
D/BackupManagerService( 1010): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1010): removePackageParticipantsLocked: uid=10539 #1
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452525227
I/InternalIcingCorporaPro( 2348): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
W/ActiveOrDefaultContextProvider( 5145): Missing scope.enter somewhere. Returning default context
E/SQLiteDatabase( 5145): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5145): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5145): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5145): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5145): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 5145): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 5145): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 5145): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 5145): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5145): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 5145): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 5145): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5145): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 5145): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5145): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 5145): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 5145): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 5145): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5145): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 5145): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5145): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5145): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 5145): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5145): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5145): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 5145): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 5145): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5145): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5145): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 5145): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 5145): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5145): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 5145): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 5145): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 5145): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5145): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 5145): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 5145): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5145): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5145): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 5145): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 5145): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5145): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5145): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5145): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 5145): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 5145): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 5145): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5145): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 5145): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5145): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5145): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 5145): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5145): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5145): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 5145): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 5145): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5145): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5145): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5145): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5145): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5145): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5145): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5145): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 5145): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 5145): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 5145): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 5145): threadid=11: thread exiting with uncaught exception (group=0x41636d40)
E/AndroidRuntime( 5145): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5145): Process: com.google.android.apps.docs, PID: 5145
E/AndroidRuntime( 5145): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5145): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5145): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5145): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5145): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 5145): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 5145): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 5145): 	at WT.run(AbstractDatabaseInstance.java:411)
I/Process ( 5145): Sending signal. PID: 5145 SIG: 9
E/DropBoxManagerService( 1010): Can't write: system_app_crash
E/DropBoxManagerService( 1010): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1010): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1010): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1010): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1010): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1010): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1010): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1010): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1010): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1010): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1010): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1010): 	... 5 more
I/ActivityManager( 1010): Process com.google.android.apps.docs (pid 5145) has died.

```
