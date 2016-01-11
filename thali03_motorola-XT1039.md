#### Test 55613145dd493c6_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4049): 
D/AndroidRuntime( 4049): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4049): CheckJNI is OFF
D/dalvikvm( 4049): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4049): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4049): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4049): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4049): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4049): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4049): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4049): failed to load memtrack module: -2
D/AndroidRuntime( 4049): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1000): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4049
W/WindowManager( 1000): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1000): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4065 uid=10537 gids={50537, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4049): Shutting down VM
D/dalvikvm( 4049): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4065): Binding Chromium to main looper Looper (main, tid 1) {41fa5868}
I/LibraryLoader( 4065): Expected native library version number "",actual native library version number ""
I/chromium( 4065): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4065): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1000): Message: 20
D/BluetoothManagerService( 1000): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4201bf50:true
I/Adreno-EGL( 4065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4065): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4065): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4065): Local Branch: 
I/Adreno-EGL( 4065): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4065): Local Patches: NONE
I/Adreno-EGL( 4065): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4065): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4065): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4065): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4065): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4065): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4065): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4065): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4065): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4065): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4065): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4065): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4065): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4065): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4065): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4065): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4065): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4065): Enabling debug mode 0
,W/AwContents( 4065): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4065): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1000): Displayed com.test.thalitest/.MainActivity,cp,ca,369
I/ActivityManager( 1000): Displayed com.test.thalitest/.MainActivity: +344ms (total +369ms)
,D/JsMessageQueue( 4065): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4065): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41faa150
,D/dalvikvm( 4065): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41faa150
D/jxcore_app_log( 4065): JniHelper::setJavaVM(0x415f7fa8), pthread_self() = 1614529320
,D/JX-Cordova( 4065): jxcore cordova android initializing
,D/dalvikvm( 4065): GC_CONCURRENT freed 2765K, 17% free 14423K/17224K, paused 2ms+2ms, total 43ms
,D/dalvikvm( 4065): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 131K, 17% free 14403K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 125K, 17% free 14423K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.209MB for 96598-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 179K, 17% free 14458K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.290MB for 144892-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 253K, 17% free 14506K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.406MB for 217334-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 369K, 18% free 14580K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.582MB for 325996-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 568K, 19% free 14702K/18000K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.856MB for 488990-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 866K, 20% free 14878K/18480K, paused 27ms, total 27ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 1283K, 19% free 15136K/18480K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 17.864MB for 1100216-byte allocation
,D/dalvikvm( 4065): GC_CONCURRENT freed 1756K, 21% free 15520K/19556K, paused 1ms+4ms, total 32ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 300K, 21% free 15456K/19556K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 18.700MB for 1650320-byte allocation
,D/dalvikvm( 4065): GC_CONCURRENT freed 1628K, 25% free 16033K/21168K, paused 3ms+4ms, total 34ms
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 1376K, 24% free 16107K/21168K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 20.123MB for 2475476-byte allocation
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4065): GC_CONCURRENT freed 1836K, 28% free 17004K/23588K, paused 4ms+10ms, total 75ms
,D/dalvikvm( 4065): GC_CONCURRENT freed 2594K, 28% free 17078K/23588K, paused 1ms+7ms, total 44ms
,D/dalvikvm( 4065): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 227K, 28% free 17082K/23588K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 22.255MB for 3713210-byte allocation
,D/dalvikvm( 4065): GC_CONCURRENT freed 2648K, 34% free 18224K/27216K, paused 4ms+5ms, total 41ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 915K, 34% free 18055K/27216K, paused 29ms, total 29ms
,W/jxcore-log( 4065): Initializing JXcore engine
,W/jxcore-log( 4065): JXcore engine is ready
,D/dalvikvm( 4065): GC_CONCURRENT freed 370K, 25% free 20678K/27216K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 4065): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4065): Starting JXcore engine
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
,W/jxcore-log( 4065): Platform android
W/jxcore-log( 4065): 
,W/jxcore-log( 4065): Process ARCH arm
W/jxcore-log( 4065): 
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
,I/jxcore-log( 4065): JXcore Cordova bridge is ready!
I/jxcore-log( 4065): 
,W/jxcore-log( 4065): JXcore engine is started
,I/chromium( 4065): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4065): Toggling radios to true
I/jxcore-log( 4065): 
,D/BluetoothAdapter( 4065): enable(): BT is already enabled..!
D/WifiService( 1000): New client listening to asynchronous messages
D/WifiService( 1000): setWifiEnabled: true pid=4065, uid=10537
,E/WifiService( 1000): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1000): handleMessage: E msg.what=131145
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
I/jxcore-log( 4065): Radios toggled
I/jxcore-log( 4065): 
D/BluetoothManagerService( 1000): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1000): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4065): Received device characteristics:
I/jxcore-log( 4065): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4065): Bluetooth name: XT1039
I/jxcore-log( 4065): Device name: motorola-XT1039
I/jxcore-log( 4065): 
I/jxcore-log( 4065): Perf Test app loaded loaded
I/jxcore-log( 4065): 
,I/jxcore-log( 4065): check test folder
I/jxcore-log( 4065): 
,I/jxcore-log( 4065): found test : ./testFindPeers.js
I/jxcore-log( 4065): 
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
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
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1000): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1000): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1000): invokeExitMethods: L2ConnectedState
,D/Tethering( 1000): InitialState.processMessage what=4
D/WifiStateMachine( 1000): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
,I/jxcore-log( 4065): found test : ./testSendData.js
I/jxcore-log( 4065): 
,V/ConnectivityService( 1000): WiFi NOT Tethered!
D/Tethering( 1000): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1000): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 21
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1000): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1000): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1000): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1000): connected time updated 301013
D/ConnectivityService( 1000): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1000): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1000): Attempting to switch to mobile
D/ConnectivityService( 1000): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1000): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1000): resetConnections(wlan0, 3)
D/NetUtils( 1000): android_net_utils_resetConnections in env=0x611ec260 clazz=0x62700001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1000): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1000): DisconnectingState
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,V/NativeCrypto( 1358): Read error: ssl=0x630d6248: I/O error during system call, Connection timed out
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131146
D/WifiStateMachine( 1000): processMsg: DisconnectingState
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147460
D/WifiStateMachine( 1000): processMsg: DisconnectingState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): Network connection lost
D/WifiStateMachine( 1000): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1358): SSL shutdown failed: ssl=0x630d6248: I/O error during system call, Broken pipe
,D/WifiP2pService( 1000): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1000): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1000): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=4
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
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131216
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
,D/WifiStateMachine( 1000): handleMessage: X
D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1314): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1000): Attempting to switch to mobile
D/ConnectivityService( 1000): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1000): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1000): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1314): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=0
,I/Choreographer( 4065): Skipped 135 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4065): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 38
D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiP2pService( 1000): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@427ef9c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427ef9c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427ef9c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): handleMessage: X
,W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1303): Active network info is not available
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1000): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager( 1000): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4151 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1000): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1573): Registering with Alarm Manager to restart CCE
W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1303): Active network info is not available
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1573): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/PollingManager( 1573): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1573): [debug] > CusSM.onRadioDown
E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,D/dalvikvm( 4151): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fadbf0, skipping init
I/openssl ( 4151): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4151): Crypto mode 0 already enabled
I/ActivityManager( 1000): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4182 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 3763:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4182): mnc/mcc: 
,V/MmsConfig( 4182): tag: bool value: enabledMMS - true
V/MmsConfig( 4182): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4182): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4182): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4182): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4182): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4182): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4182): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4182): tag: int value: recipientLimit - 20
V/MmsConfig( 4182): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4182): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4182): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4182): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4182): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4182): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4182): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4182): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4182): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1000): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4202 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1000): Killing 3896:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4202): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4202): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4202): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4202): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1000): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4215 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 3409:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1000): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4228 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 3938:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4228): Binding Chromium to main looper Looper (main, tid 1) {41faaa38}
,I/LibraryLoader( 4228): Expected native library version number "",actual native library version number ""
,I/chromium( 4228): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4228): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4228): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4228): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4228): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4228): Local Branch: 
I/Adreno-EGL( 4228): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4228): Local Patches: NONE
I/Adreno-EGL( 4228): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4228): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4228): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4228): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1000): GC_EXPLICIT freed 1214K, 65% free 18141K/51000K, paused 5ms+9ms, total 100ms
,I/NSApplication( 4228): Starting up...
,I/ImageResourceManager( 3439): ImageResourceManager: uninitalized
,I/iu.Environment( 3439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3439): SYNC; picasa accounts
I/ActivityManager( 1000): Killing 3424:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/DEBUG   ( 1573): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1573): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1573): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1573): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1573): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1573): onServiceConnected()
D/GetNotificationsWS( 1573): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1573): ServiceHandler.handleMessage: mWaitCount=0
,I/iu.UploadsManager( 1409): num queued entries: 0
,D/GetNotificationsWS( 1573): unbindWebServices(): un-registering our AIDL callback...
,I/iu.UploadsManager( 1409): num updated entries: 0
,I/iu.SyncManager( 1409): NEXT; no task
,D/MobileConnectivityChangeReceiver( 4202): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
I/iu.UploadsManager( 3439): num queued entries: 0
,D/MobileConnectivityChangeReceiver( 4202): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.UploadsManager( 3439): num updated entries: 0
,I/iu.SyncManager( 3439): NEXT; no task
,I/dalvikvm( 4065): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4065): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4065): Shutting down VM
,W/dalvikvm( 4065): threadid=1: thread exiting with uncaught exception (group=0x416d6d40)
,E/AndroidRuntime( 4065): FATAL EXCEPTION: main
E/AndroidRuntime( 4065): Process: com.test.thalitest, PID: 4065
E/AndroidRuntime( 4065): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4065): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4065): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4065): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4065): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4065): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4065): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4065): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4065): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4065): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4065): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4065): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4065): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4065): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4065): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4065): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4065): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1000):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1000): Killing 3964:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4065): Sending signal. PID: 4065 SIG: 9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1000): Process com.test.thalitest (pid 4065) has died.
,D/WifiService( 1000): Client connection lost with reason: 4
,I/WindowState( 1000): WIN DEATH: Window{4205f3b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SFPerfTracer(  275):      triggers: (rate: 2:30) (compose: 0:4) (post: 0:1) (render: 0:6) (0:100 frames) (1:543)
,D/SFPerfTracer(  275):        layers: (0:13) (FocusedStackFrame: 0:9)* (StatusBar: 0:199)* (NavigationBar: 0:35)* (com.android.systemui.ImageWallpaper: 0:6)* (com.android.launcher/com.android.launcher2.Launcher: 0:13)* (Starting com.motorola.ccc.ota: 0:32)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:4)* 
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1000): Got RemoteException sending setActive(false) notification to pid 4065 uid 10537
W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/GAV2    ( 4228): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request,
D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiP2pService( 1000): InactiveState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1000): handleMessage: X
,V/AlarmManager( 1000): sending alarm Alarm{43088ea0 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{43128958 type 1 com.android.deskclock}
,I/ActivityManager( 1000): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4314 uid=10015 gids={50015, 1028}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 30ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request,
D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState,
D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 312 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 192 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
,D/WifiStateMachine( 1000): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
,I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/WifiStateMachine( 1000): processMsg: DisconnectedState
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/WifiStateMachine( 1000): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1222845616
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147459
,D/Tethering( 1000): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1000): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): Network connection established
,D/WifiStateMachine( 1000): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1000): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1000): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1000): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1000): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-47ms what=147462 obj=android.net.wifi.StateChangeResult@41fdb4e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131101
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-38ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42443a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=196612
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
,D/WifiStateMachine( 1000): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1000): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1000): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420bd4f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420bd4f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/WifiP2pService( 1000): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 20
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
,D/WifiStateMachine( 1000): ObtainingIpState{ when=-4ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
,D/WifiStateMachine( 1000): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1000): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): DHCP successful
D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1000): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1000): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1000): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1000): VerifyingLinkState enter
D/WifiStateMachine( 1000): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=151572
D/WifiStateMachine( 1000): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1000): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=135190
D/WifiStateMachine( 1000): processMsg: VerifyingLinkState
D/WifiStateMachine( 1000): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1000): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1000): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1000): CaptivePortalCheckState enter
,D/WifiStateMachine( 1000): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1000): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1000): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131092
D/WifiStateMachine( 1000): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1000): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1000): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1000): WiFi NOT Tethered!
,E/ConnectivityService( 1000): Unexpected mtu value: android.net.wifi.WifiStateTracker@42080380
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1000): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1000): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131092
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
I/ModemStatsDSDetect( 1314): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1000): handleMessage: X
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1000): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1000): WiFi NOT Tethered!
E/ConnectivityService( 1000): Unexpected mtu value: android.net.wifi.WifiStateTracker@42080380
,D/ConnectivityService( 1000): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1314): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=0
I/CheckinService( 1409): Checkin interval check for package: unspecified last checkin: 1452516895481 min interval config: 0 actual interval: 317866
,I/CheckinService( 1409): Checking schedule, now: 1452517213357 next: 1452516925446
,I/CheckinService( 1409): active receiver: enabled
,I/CheckinService( 1409): Preparing to send checkin request
,I/EventLogService( 1409): Accumulating logs since 1452516890344
,I/CheckinRequestBuilder( 1409): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1409): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1000): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4388 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4388): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4388): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4388): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4388): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4388): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4388): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4388): install
,I/MultiDex( 4388): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4388): loading existing secondary dex files
,I/MultiDex( 4388): load found 3 secondary dex files
,I/MultiDex( 4388): install done
,D/dalvikvm( 4388): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4388): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4388): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4388): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4388): VFY: unable to resolve instance field 36
,D/dalvikvm( 4388): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4388): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4388): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4388): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4388): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4388): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4388): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa6580
D/dalvikvm( 4388): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa6580
,D/dalvikvm( 4388): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa6580, skipping init
,D/dalvikvm( 4388): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fa6580
D/dalvikvm( 4388): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fa6580
,V/JNIHelp ( 4388): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4388): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa6580
,D/dalvikvm( 4388): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fa6580
D/dalvikvm( 4388): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fa6580
,D/dalvikvm( 4388): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fa6580
,I/ProviderInstaller( 4388): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 1409): Restart initialization of location
D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,D/WearableService( 1238): callingUid 10022, callindPid: 1238
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1238): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1238): No location to return for getLastLocation()
,W/FusedLocationProvider( 1238): location=null
,I/dalvikvm( 4388): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4388): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4388): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4388): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 4388): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4388): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4388): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4388): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4388): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4388): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4388): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4388): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4388): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4388): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4388): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4388): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4388): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5242000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5242000
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
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
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=23518152
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4388): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4388): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421992a0
D/dalvikvm( 4388): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421992a0
,D/dalvikvm( 4388): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421992a0, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/ConnectivityService( 1000): NetTransition Wakelock for ConnectedState released by timeout
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=994375649
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 4388): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4388): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4426): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4388): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4388): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 79ms
,I/Adreno-EGL( 4388): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4388): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4388): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4388): Local Branch: 
I/Adreno-EGL( 4388): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4388): Local Patches: NONE
I/Adreno-EGL( 4388): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4388): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4388): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4388): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4388): Local Branch: 
I/Adreno-EGL( 4388): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4388): Local Patches: NONE
I/Adreno-EGL( 4388): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4388): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4388): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4388): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4388): Local Branch: 
I/Adreno-EGL( 4388): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4388): Local Patches: NONE
I/Adreno-EGL( 4388): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4388): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4388): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4388): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4388): Local Branch: 
I/Adreno-EGL( 4388): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4388): Local Patches: NONE
I/Adreno-EGL( 4388): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1409): Classify the device as Phone.
,V/NativeCrypto( 1409): SSL shutdown failed: ssl=0x6a988560: I/O error during system call, Connection timed out
,I/CheckinTask( 1409): Sending checkin request (11753 bytes)
,D/dalvikvm( 1409): GC_CONCURRENT freed 1918K, 30% free 12069K/17224K, paused 5ms+5ms, total 46ms
,I/CheckinRequestBuilder( 1409): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1409): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1409): Classify the device as Phone.
,I/CheckinTask( 1409): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1409): Checking schedule, now: 1452517216218 next: 1453110286209
,I/CheckinService( 1409): active receiver: disabled
,D/CheckinService( 1409): Recording last checkin time for package unspecified as 1452517216246
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/CaptivePortalTracker( 1000): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1573): now: 362774 ,futureTime: 30001732
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1573): Polling alarm set to expire at: 30001732 Current Time: 362774
,W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1573): now: 362796 ,futureTime: 30001732
D/PollingManager( 1573): Polling alarm set to expire at: 30001732 Current Time: 362796
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1573): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1573): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1573): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/Tethering( 1000): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1000): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/openssl ( 4151): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4151): Crypto mode 0 already enabled
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1573): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4202): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4202): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1573): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
I/iu.Environment( 3439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 3439): num queued entries: 0
I/iu.UploadsManager( 3439): num updated entries: 0
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1573): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
I/iu.SyncManager( 3439): NEXT; no task
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
I/iu.Environment( 1409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.UploadsManager( 1409): num queued entries: 0
I/iu.UploadsManager( 1409): num updated entries: 0
D/dalvikvm( 3439): GC_CONCURRENT freed 647K, 5% free 16465K/17224K, paused 2ms+3ms, total 26ms
D/dalvikvm( 3439): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/iu.SyncManager( 1409): NEXT; no task
D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/dalvikvm-heap( 3439): Grow heap (frag case) to 19.848MB for 1821008-byte allocation
I/openssl ( 4151): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4151): Crypto mode 0 already enabled
D/MobileConnectivityChangeReceiver( 4202): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4202): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3439): GC_FOR_ALLOC freed 50K, 5% free 18196K/19004K, paused 11ms, total 12ms
,I/iu.Environment( 3439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1573): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1573): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1573): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1573): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1573): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1573): onServiceConnected()
,D/GetNotificationsWS( 1573): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1573): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1573): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1573): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1573): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1573): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1573): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1573): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1000): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1573
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1573): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1573): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1573): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1000): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1573
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1000): Activity reported stop, but no longer stopping: ActivityRecord{420ec960 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WifiStateMachine( 1000): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1000): processMsg: ConnectedState
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1000): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1000):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1000): handleMessage: X
,D/ConnectivityService( 1000): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager( 1000): Killing 3471:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1000): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1000):   Scheme: "smsto"
I/ActivityManager( 1000): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4479 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
,I/Launcher( 1326): Deferring update until onResume
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/Launcher( 1326): Deferring update until onResume
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
,I/GCoreNlp( 1238): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4479): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4479): MmsConfig.loadMmsSettings
I/Babel   ( 4479): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4479): MmsConfig.loadFromDatabase
,E/Babel   ( 4479): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4479): MmsConfig.loadFromResources
,E/Babel   ( 4479): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4479): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4479): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1000): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4517 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
D/dalvikvm( 1238): GC_EXPLICIT freed 811K, 36% free 11043K/17224K, paused 6ms+6ms, total 43ms
,I/ActivityManager( 1000): Killing 4314:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1000): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4535 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm( 1000): GC_EXPLICIT freed 1998K, 65% free 18180K/51000K, paused 5ms+12ms, total 103ms
,I/ActivityManager( 1000): Killing 4151:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2305): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1000): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4553 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 4182:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4517): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/dalvikvm( 4553): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4553): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4553): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2305): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
,I/dalvikvm( 4553): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4553): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4553): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4553): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4553): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4553): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4553): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4553): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4553): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4553): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4553): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4553): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4553): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4553): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4553): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1000): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4587 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4553): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4553): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4553): Skipping gmscore version check
,D/Finsky  ( 4553): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4553): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4553): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4553): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1000): Killing 4202:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1409): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1409): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1409): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4587): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fad308, skipping init
I/openssl ( 4587): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4587): Crypto mode 0 already enabled
,D/Finsky  ( 4553): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4553): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1000): Killing 4215:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1409): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1409): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452517225
,D/CaptivePortalTracker( 1000): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1000): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1000): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1000): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1000): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1000): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1000): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/PhenotypeConfigurator( 1238): Scheduling Phenotype for one-off execution 6776 seconds from now (1452517237244)
,D/GetConfigurationSnapshotOperation( 1238): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1238): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1238): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1238): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1238): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1238): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
,W/dalvikvm( 1238): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1238): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1238): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1000): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/ModemStatsDSDetect( 1314): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1238): GC_CONCURRENT freed 1413K, 33% free 11593K/17224K, paused 2ms+8ms, total 37ms
,D/dalvikvm( 1358): GC_EXPLICIT freed 1842K, 40% free 10354K/17224K, paused 2ms+5ms, total 30ms
,I/dalvikvm( 1238): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1238): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1238): VFY: replacing opcode 0x6e at 0x003d
,V/AlarmManager( 1000): sending alarm Alarm{42573d80 type 2 com.google.android.gms}
,V/AlarmManager( 1000): sending alarm Alarm{420c3868 type 2 com.google.android.gms}
,D/ConnectivityService( 1000): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1314): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1314): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{429254a0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{43923db8 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{4230aaa0 type 3 android}
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
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
,V/AlarmManager( 1000): sending alarm Alarm{429661a8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{42814348 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{4352f0f0 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{43530fd8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{428aab28 type 2 android}
,D/ConnectivityService( 1000): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1000): sending alarm Alarm{42963758 type 0 com.google.android.gms}
,D/ConnectivityService( 1000): Done.
,D/ConnectivityService( 1000): Setting timer for 720seconds
,I/EventLogService( 1409): Aggregate from 1452517213376 (log), 1452515631403 (data)
,V/AlarmManager( 1000): sending alarm Alarm{422d31e8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4393f320 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4241d1d8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{42918cc8 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{427bd1a0 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{4259f580 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{427eb268 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{43556b70 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{422d32c0 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1000): cleanup(): cleared. Last call was 876873 ms ago
,I/ActivityManager( 1000): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4664 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1000): Killing 4228:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1000): sending alarm Alarm{428228b8 type 2 com.google.android.gms}
,D/ConnectivityService( 1000): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1314): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1314): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1314): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{43589908 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4280b960 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4312f830 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{441b3ab8 type 3 android}
,V/AlarmManager( 1000): sending alarm Alarm{435899e0 type 2 android}
,D/ConnectivityService( 1000): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1000): Done.
,D/ConnectivityService( 1000): Setting timer for 720seconds
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1000): sending alarm Alarm{4295c488 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{427c6460 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{427e5cd8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{4280b1e8 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{441b7d20 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{42933dc0 type 3 android}
,I/ProcessStatsService( 1000): Prepared write state in 47ms
,I/ProcessStatsService( 1000): Prepared write state in 18ms
,I/ProcessStatsService( 1000): Pruning old procstats: /data/system/procstats/state-2016-01-10-15-10-52.bin
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
,V/AlarmManager( 1000): sending alarm Alarm{43e1ac80 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{43e9e500 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{43533508 type 3 android}
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
,V/AlarmManager( 1000): sending alarm Alarm{438fc2d0 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4746): 
D/AndroidRuntime( 4746): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4746): CheckJNI is OFF
D/dalvikvm( 4746): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4746): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4746): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4746): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4746): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4746): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4746): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4746): failed to load memtrack module: -2
D/AndroidRuntime( 4746): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1000): Force stopping com.test.thalitest appid=10537 user=-1: uninstall pkg
W/PackageSettings( 1000): Skipping PackageSetting{42269ab8 com.example.hello/10529} due to missing metadata
I/ActivityManager( 1000): Force stopping com.test.thalitest appid=10537 user=0: pkg removed
D/dalvikvm( 2270): GC_EXPLICIT freed 5502K, 44% free 9649K/17224K, paused 3ms+6ms, total 39ms
I/InputReader( 1000): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2305): GC_EXPLICIT freed 4334K, 42% free 10098K/17224K, paused 2ms+4ms, total 130ms
D/dalvikvm( 1326): GC_EXPLICIT freed 3340K, 33% free 11596K/17224K, paused 2ms+5ms, total 145ms
I/Launcher( 1326): Deferring update until onResume
D/dalvikvm( 1409): GC_EXPLICIT freed 1933K, 31% free 11991K/17224K, paused 26ms+14ms, total 164ms
W/SQLiteConnectionPool( 1409): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1000): GC_EXPLICIT freed 2281K, 65% free 18127K/51000K, paused 19ms+11ms, total 158ms
W/GeofencerStateMachine( 1238): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452518984
D/VoicemailCleanupService( 4517): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
I/Launcher( 1326): Deferring update until onResume
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2305): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1000): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4778 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452518985
D/BackupManagerService( 1000): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1000): removePackageParticipantsLocked: uid=10537 #1
I/InternalIcingCorporaPro( 2305): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
D/dalvikvm( 1000): GC_EXPLICIT freed 707K, 65% free 18059K/51000K, paused 9ms+16ms, total 180ms
D/AndroidRuntime( 4746): Shutting down VM
D/dalvikvm( 4746): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
W/ActiveOrDefaultContextProvider( 4778): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1000): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4801 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4778): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4553): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4553): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4553): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1409): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1409): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1409): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1409): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1409): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1409): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1409): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1358): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1358): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1000): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4827 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1409): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1409): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1409): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1409): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1409): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
E/SQLiteLog( 1409): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1409): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/gH_CompatibleDatabase( 1409): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
E/SQLiteLog( 1409): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Icing   ( 1409): doRemovePackageData com.test.thalitest
W/dalvikvm( 1409): threadid=53: thread exiting with uncaught exception (group=0x416d6d40)
E/GMPM-SVC( 1409): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1409): (3850) statement aborts at 25: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
E/SharedPreferencesImpl( 1409): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
D/gH_CompatibleDatabase( 1409): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/dalvikvm( 1409): threadid=47: thread exiting with uncaught exception (group=0x416d6d40)
I/Process ( 1409): Sending signal. PID: 1409 SIG: 9
V/AlarmManager( 1000): sending alarm Alarm{42548e08 type 3 android}
V/AlarmManager( 1000): sending alarm Alarm{4252f850 type 3 com.google.android.gms}
V/AlarmManager( 1000): sending alarm Alarm{42511a30 type 2 com.motorola.ccc.cce}
I/ActivityManager( 1000): Process com.google.android.gms (pid 1409) has died.
D/WifiService( 1000): Client connection lost with reason: 4
E/SQLiteDatabase( 4801): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4801): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4801): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4801): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4801): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4801): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4801): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4801): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4801): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4801): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4801): threadid=10: thread exiting with uncaught exception (group=0x416d6d40)
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 10999ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 10999ms
W/ActivityManager( 1000): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20999ms
E/AndroidRuntime( 4801): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4801): Process: com.android.keychain, PID: 4801
E/AndroidRuntime( 4801): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4801): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4801): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4801): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4801): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4801): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4801): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4801): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4801): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4801): Sending signal. PID: 4801 SIG: 9
E/DropBoxManagerService( 1000): Can't write: system_app_crash
E/DropBoxManagerService( 1000): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
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
D/Documents( 4827): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1000): Process com.android.keychain (pid 4801) has died.
W/ActivityManager( 1000): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 30979ms
D/Documents( 4827): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4827): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4827): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4827): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4827): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4827): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4827): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4827): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4827): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4827): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4827): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4827): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4827): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4827): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4827): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4827): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4827): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4827): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4827): Shutting down VM
W/dalvikvm( 4827): threadid=1: thread exiting with uncaught exception (group=0x416d6d40)
E/AndroidRuntime( 4827): FATAL EXCEPTION: main
E/AndroidRuntime( 4827): Process: com.android.documentsui, PID: 4827
E/AndroidRuntime( 4827): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4827): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4827): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4827): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4827): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4827): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4827): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4827): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4827): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4827): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4827): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4827): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4827): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4827): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4827): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4827): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4827): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4827): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4827): 	... 10 more
I/ActivityManager( 1000): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4853 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager( 1000): Killing 4388:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/DropBoxManagerService( 1000): Can't write: system_app_crash
E/DropBoxManagerService( 1000): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
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

```
