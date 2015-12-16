#### Test 506502783fcf234_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4048): 
D/AndroidRuntime( 4048): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4048): CheckJNI is OFF
D/dalvikvm( 4048): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4048): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4048): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4048): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4048): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4048): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4048): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4048): failed to load memtrack module: -2
D/AndroidRuntime( 4048): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4048
W/WindowManager(  989): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  989): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4078 uid=10484 gids={50484, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4048): Shutting down VM
D/dalvikvm( 4048): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4078): Binding Chromium to main looper Looper (main, tid 1) {428bb9c0}
I/LibraryLoader( 4078): Expected native library version number "",actual native library version number ""
I/chromium( 4078): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4078): Initializing chromium process, renderers=0
D/BluetoothManagerService(  989): Message: 20
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a6e128:true
I/Adreno-EGL( 4078): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4078): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4078): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4078): Local Branch: 
I/Adreno-EGL( 4078): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4078): Local Patches: NONE
I/Adreno-EGL( 4078): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4078): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4078): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4078): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4078): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4078): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4078): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4078): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4078): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4078): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4078): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4078): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4078): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4078): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4078): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4078): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4078): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4078): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4078): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4078): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4078): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4078): Enabling debug mode 0
,W/AwContents( 4078): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4078): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler(  989): Displayed com.test.thalitest/.MainActivity,cp,ca,373
I/ActivityManager(  989): Displayed com.test.thalitest/.MainActivity: +348ms (total +373ms)
W/IInputConnectionWrapper( 4078): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4078): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4078): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428bfe70
,D/dalvikvm( 4078): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428bfe70
D/jxcore_app_log( 4078): JniHelper::setJavaVM(0x41fd6f78), pthread_self() = 1614042992
,D/JX-Cordova( 4078): jxcore cordova android initializing
,D/dalvikvm( 4078): GC_CONCURRENT freed 2800K, 17% free 14353K/17224K, paused 1ms+2ms, total 53ms
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 132K, 17% free 14358K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 307K, 17% free 14421K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 16.254MB for 144892-byte allocation
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 268K, 17% free 14458K/17368K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 16.359MB for 217334-byte allocation
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 370K, 18% free 14532K/17584K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 16.535MB for 325996-byte allocation
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 572K, 19% free 14654K/17904K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 16.809MB for 488990-byte allocation
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 870K, 20% free 14830K/18384K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 17.214MB for 733480-byte allocation
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 1292K, 22% free 15088K/19104K, paused 29ms, total 29ms
,D/dalvikvm( 4078): GC_CONCURRENT freed 1676K, 20% free 15460K/19104K, paused 1ms+3ms, total 38ms
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 381K, 20% free 15418K/19104K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 18.663MB for 1650320-byte allocation
,D/dalvikvm( 4078): GC_CONCURRENT freed 1652K, 23% free 16013K/20716K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 1421K, 23% free 16072K/20716K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 20.089MB for 2475476-byte allocation
,D/dalvikvm( 4078): GC_CONCURRENT freed 1831K, 28% free 16794K/23136K, paused 5ms+4ms, total 51ms
,D/dalvikvm( 4078): GC_CONCURRENT freed 2393K, 27% free 16998K/23136K, paused 2ms+6ms, total 44ms
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 699K, 28% free 16773K/23136K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4078): Grow heap (frag case) to 21.955MB for 3713210-byte allocation
,D/dalvikvm( 4078): GC_CONCURRENT freed 165K, 24% free 20405K/26764K, paused 5ms+4ms, total 43ms
,D/dalvikvm( 4078): GC_FOR_ALLOC freed 3060K, 33% free 17997K/26764K, paused 27ms, total 27ms
,W/jxcore-log( 4078): Initializing JXcore engine
,W/jxcore-log( 4078): JXcore engine is ready
,D/dalvikvm( 4078): GC_CONCURRENT freed 325K, 23% free 20671K/26764K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/jxcore-log( 4078): Starting JXcore engine
,W/jxcore-log( 4078): Platform android
W/jxcore-log( 4078): 
,W/jxcore-log( 4078): Process ARCH arm
W/jxcore-log( 4078): 
,I/jxcore-log( 4078): JXcore Cordova bridge is ready!
I/jxcore-log( 4078): 
,W/jxcore-log( 4078): JXcore engine is started
,I/chromium( 4078): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4078): Toggling radios to true
I/jxcore-log( 4078): 
,D/BluetoothAdapter( 4078): enable(): BT is already enabled..!
D/WifiService(  989): setWifiEnabled: true pid=4078, uid=10484
D/WifiService(  989): New client listening to asynchronous messages
,E/WifiService(  989): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine(  989): handleMessage: E msg.what=131145
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
I/jxcore-log( 4078): Radios toggled
I/jxcore-log( 4078): 
D/BluetoothManagerService(  989): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4078): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4078): 
I/jxcore-log( 4078): Perf Test app loaded loaded
I/jxcore-log( 4078): 
,I/jxcore-log( 4078): check test folder
I/jxcore-log( 4078): 
,I/jxcore-log( 4078): found test : ./testFindPeers.js
I/jxcore-log( 4078): 
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
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
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine(  989): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  989): invokeExitMethods: ConnectedState
D/WifiStateMachine(  989): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  989): Stopping DHCP and clearing IP
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
D/WifiP2pService(  989): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  989): InitialState.processMessage what=4
,V/ConnectivityService(  989): WiFi NOT Tethered!
D/Tethering(  989): sendTetherStateChangedBroadcast 0, 0, 0
,I/jxcore-log( 4078): found test : ./testSendData.js
I/jxcore-log( 4078): 
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  447): NL - Read 60 bytes from update socket.
D/TCMD    (  447): NL - ignore NL message, type = 21
,D/TCMD    (  447): Listening for incoming client connection request
,D/WifiStateMachine(  989): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  989): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  989): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics(  989): connected time updated 340546
D/ConnectivityService(  989): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  989): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/ConnectivityService(  989): Attempting to switch to mobile
D/ConnectivityService(  989): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  989): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine(  989): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine(  989): DisconnectingState
,D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService(  989): resetConnections(wlan0, 3)
D/NetUtils(  989): android_net_utils_resetConnections in env=0x61189480 clazz=0x62d00001 iface=wlan0 mask=0x3
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131146
D/WifiStateMachine(  989): processMsg: DisconnectingState
D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=147460
D/WifiStateMachine(  989): processMsg: DisconnectingState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): Network connection lost
D/WifiStateMachine(  989): Stopping DHCP and clearing IP
V/NativeCrypto( 1364): Read error: ssl=0x6345e828: I/O error during system call, Connection timed out
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1364): SSL shutdown failed: ssl=0x6345e828: I/O error during system call, Broken pipe
,D/WifiP2pService(  989): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  989): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  989): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  989): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131101
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131216
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131216
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): handleMessage: X
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  989): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  989): Attempting to switch to mobile
D/ConnectivityService(  989): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService(  989): Attempting to switch to ETHERNET
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  989): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
,I/chromium( 4078): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/WifiStateMachine(  989): handleMessage: E msg.what=147461
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/TCMD    (  447): NL - Read 56 bytes from update socket.
D/MDMCTBK (  275): Event received = Trying to associate with
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  989): processMsg: DisconnectedState
,D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
,D/WifiStateMachine(  989): processMsg: SupplicantStartedState
,D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
,D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/WifiStateMachine(  989): handleMessage: X
,D/TCMD    (  447): NL - Read 312 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  447): NL - Read 192 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 80 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 80 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  989): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering(  989): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  989): handleMessage: E msg.what=131101
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
,D/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
,D/WifiStateMachine(  989): processMsg: DisconnectedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
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
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1192776880
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19,
D/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
,D/WifiStateMachine(  989): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=147459
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/WifiStateMachine(  989): Network connection established
,D/WifiStateMachine(  989): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  989): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  989): invokeExitMethods: DisconnectedState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine(  989): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  989): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
,D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@43a57568 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
,D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=196612
D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  989): processMsg: L2ConnectedState
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine(  989): Unexpected BatchedScanResults :OK
D/WifiP2pService(  989): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a61c90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a61c90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): handleMessage: X
,D/TCMD    (  447): NL - Read 56 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine(  989): handleMessage: E msg.what=147461
D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
,D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiP2pService(  989): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44a61b80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44a61b80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@44a61b80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  989): handleMessage: X
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
,D/Tethering(  989): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker(  989): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  989): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1299): Active network info is not available
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ActivityManager(  989): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4158 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1299): Active network info is not available
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1560): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/Tethering(  989): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker(  989): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1560): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1560): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/dalvikvm( 4158): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x428c3910, skipping init
I/openssl ( 4158): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4158): Crypto mode 0 already enabled
,I/ActivityManager(  989): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4189 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 3882:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,V/MmsConfig( 4189): mnc/mcc: 
V/MmsConfig( 4189): tag: bool value: enabledMMS - true
V/MmsConfig( 4189): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4189): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4189): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4189): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4189): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4189): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4189): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4189): tag: int value: recipientLimit - 20
V/MmsConfig( 4189): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4189): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4189): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4189): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4189): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4189): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4189): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4189): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4189): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/ActivityManager(  989): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4210 uid=10041 gids={50041, 3003}
,I/ActivityManager(  989): Killing 3461:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TCMD    (  447): NL - Read 60 bytes from update socket.
D/TCMD    (  447): NL - ignore NL message, type = 20
D/TCMD    (  447): Listening for incoming client connection request
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4210): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4210): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/WifiStateMachine(  989): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  989): handleMessage: E msg.what=131215
D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  989): handleMessage: X
,I/ActivityManager(  989): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4225 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 3925:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  989): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4254 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 3480:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiStateMachine(  989): handleMessage: E msg.what=196613
,D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
,V/WebViewChromiumFactoryProvider( 4254): Binding Chromium to main looper Looper (main, tid 1) {428b5838}
I/LibraryLoader( 4254): Expected native library version number "",actual native library version number ""
,I/chromium( 4254): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4254): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4254): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4254): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4254): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4254): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4254): Local Branch: 
I/Adreno-EGL( 4254): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4254): Local Patches: NONE
I/Adreno-EGL( 4254): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiP2pService(  989): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): DHCP successful
D/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  989): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine(  989): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  989): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine(  989): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  989): VerifyingLinkState enter
D/WifiStateMachine(  989): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=151572
D/WifiStateMachine(  989): processMsg: VerifyingLinkState
D/WifiStateMachine(  989): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine(  989): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=135190
D/WifiStateMachine(  989): processMsg: VerifyingLinkState
D/WifiStateMachine(  989): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  989): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  989): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine(  989): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  989): CaptivePortalCheckState enter
,D/WifiStateMachine(  989): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  989): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  989): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  989): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  989): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131092
D/WifiStateMachine(  989): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  989): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine(  989): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService(  989): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService(  989): WiFi NOT Tethered!
,E/ConnectivityService(  989): Unexpected mtu value: android.net.wifi.WifiStateTracker@429a10a8
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine(  989): transitionTo: destState=ConnectedState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  989): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine(  989): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131092
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  989): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService(  989): WiFi NOT Tethered!
,E/ConnectivityService(  989): Unexpected mtu value: android.net.wifi.WifiStateTracker@429a10a8
I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/dalvikvm(  989): GC_EXPLICIT freed 1685K, 65% free 18135K/50784K, paused 4ms+11ms, total 105ms
D/ConnectivityService(  989): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
I/jxcore-log( 4078): Connected to the server!
I/jxcore-log( 4078): 
,I/CheckinService( 1380): Checkin interval check for package: unspecified last checkin: 1450238186370 min interval config: 0 actual interval: 328702
,I/CheckinService( 1380): Checking schedule, now: 1450238515082 next: 1450238216349
,I/CheckinService( 1380): active receiver: enabled
,W/chromium( 4254): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/chromium( 4078): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/CheckinService( 1380): Preparing to send checkin request
,I/EventLogService( 1380): Accumulating logs since 1450238181269
,I/CheckinRequestBuilder( 1380): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1380): Failed to find provider info for com.google.android.wearable.settings
W/GAV2    ( 4254): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4254): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1364): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1364): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1364): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1364): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1364): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1364): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1364): VFY: replacing opcode 0x6e at 0x003d
,I/NSApplication( 4254): Starting up...
,I/ImageResourceManager( 3496): ImageResourceManager: uninitalized
,I/iu.Environment( 3496): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager(  989): Killing 3952:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1560): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1560): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1560): bindWebServices(): registering our AIDL callback...
I/SundryService( 1560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1560): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1560): onServiceConnected()
,D/GetNotificationsWS( 1560): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1560): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4158): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4158): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3496): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager(  989): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4324 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4324): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4324): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4324): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4324): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4324): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4324): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4324): install
,I/MultiDex( 4324): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4324): loading existing secondary dex files
,I/MultiDex( 4324): load found 3 secondary dex files
,I/MultiDex( 4324): install done
,D/dalvikvm( 4324): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4324): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4324): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4324): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4324): VFY: unable to resolve instance field 36
,D/dalvikvm( 4324): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4324): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4324): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4324): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4324): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4324): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4324): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428bbbb0
,D/dalvikvm( 4324): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428bbbb0
,D/dalvikvm( 4324): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428bbbb0, skipping init
D/dalvikvm( 4324): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428bbbb0
,D/dalvikvm( 4324): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428bbbb0
,V/JNIHelp ( 4324): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4324): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428bbbb0
,D/dalvikvm( 4324): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428bbbb0
D/dalvikvm( 4324): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428bbbb0
,D/dalvikvm( 4324): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428bbbb0
,I/ProviderInstaller( 4324): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  989): NetTransition Wakelock for ConnectedState released by timeout
,D/WearableService( 1217): callingUid 10022, callindPid: 1217
,E/MDM     ( 1217): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1364): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1364): Proximity feature is not enabled.
,D/LocationInitializer( 1380): Restart initialization of location
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4324): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4324): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4324): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4324): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4324): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4324): VFY: replacing opcode 0x6e at 0x000d
,W/GCoreFlp( 1217): No location to return for getLastLocation()
,W/FusedLocationProvider( 1217): location=null
,I/dalvikvm( 4324): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4324): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4324): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4324): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4324): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4324): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
,W/dalvikvm( 4324): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4324): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4324): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4324): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4324): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  288): Instantiating CDM.
,I/WVCdm   (  288): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  288): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  288): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  288): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb516e000
,E/DrmWidevineDash(  288): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb516e000
D/DrmWidevineDash(  288): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  288): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  288): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  288): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  288): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  288): CdmEngine::OpenSession
,D/DrmWidevineDash(  288): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  288): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  288): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  288): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  288): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  288): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  288): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  288): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  288): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  288): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  288): PrepareKeyRequest: nonce=146164051
,D/DrmWidevineDash(  288): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  288): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  288): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  288): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4078): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4078): 
,D/dalvikvm( 4324): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ac52b8
,D/dalvikvm( 4324): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ac52b8
,D/dalvikvm( 4324): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ac52b8, skipping init
,D/NativeLibraryUtils( 4324): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  288): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  288): CdmEngine::CloseSession
,D/DrmWidevineDash(  288): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  288): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4324): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4360): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4324): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4324): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4324): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4324): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4324): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4324): Local Branch: 
I/Adreno-EGL( 4324): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4324): Local Patches: NONE
I/Adreno-EGL( 4324): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4324): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4324): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4324): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4324): Local Branch: 
I/Adreno-EGL( 4324): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4324): Local Patches: NONE
I/Adreno-EGL( 4324): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4324): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4324): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4324): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4324): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4324): Local Branch: 
I/Adreno-EGL( 4324): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4324): Local Patches: NONE
I/Adreno-EGL( 4324): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4324): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4324): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4324): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4324): Local Branch: 
I/Adreno-EGL( 4324): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4324): Local Patches: NONE
I/Adreno-EGL( 4324): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  288): CdmEngine::OpenSession
,D/DrmWidevineDash(  288): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  288): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  288): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  288): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  288): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  288): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  288): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  288): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  288): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  288): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  288): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  288): PrepareKeyRequest: nonce=3458160842
,D/DrmWidevineDash(  288): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  288): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  288): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  288): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  288): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  288): CdmEngine::CloseSession
,D/DrmWidevineDash(  288): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  288): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1380): Classify the device as Phone.
,V/NativeCrypto( 1380): SSL shutdown failed: ssl=0x6b8e36e0: I/O error during system call, Connection timed out
,D/dalvikvm( 1380): GC_CONCURRENT freed 1823K, 31% free 12053K/17224K, paused 3ms+4ms, total 36ms
,I/CheckinTask( 1380): Sending checkin request (11757 bytes)
,D/Tethering(  989): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker(  989): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1560): now: 373905 ,futureTime: 56673140
,D/PollingManager( 1560): Polling alarm set to expire at: 56673140 Current Time: 373905
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1299): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1560): [debug] > CusSM.onRadioUp
D/PollingManager( 1560): now: 373928 ,futureTime: 56673140
D/PollingManager( 1560): Polling alarm set to expire at: 56673140 Current Time: 373928
D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/Tethering(  989): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  989): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1560): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
I/openssl ( 4158): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4158): Crypto mode 0 already enabled
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1560): GC_CONCURRENT freed 2030K, 38% free 10731K/17224K, paused 8ms+4ms, total 39ms
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/dalvikvm( 1560): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/OtaApp  ( 1560): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3496): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1560): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: server told to :continue
,I/CheckinService( 1380): Checkin interval check for package: unspecified last checkin: 1450238186370 min interval config: 0 actual interval: 331835
,D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DEBUG   ( 1560): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1560): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1560): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1560): onServiceConnected()
,D/GetNotificationsWS( 1560): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1560): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1560): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4158): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4158): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3496): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1380): Checkin interval check for package: unspecified last checkin: 1450238186370 min interval config: 0 actual interval: 331891
,D/DEBUG   ( 1560): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1560): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/dalvikvm( 3496): GC_CONCURRENT freed 646K, 5% free 16441K/17224K, paused 3ms+3ms, total 20ms
,D/GetNotificationsWS( 1560): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1560): onServiceConnected()
I/SundryService( 1560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1560): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1560): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/WaitableIntentService( 1560): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1560): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  989): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1560
,D/GetNotificationsWS( 1560): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/CheckinRequestBuilder( 1380): Checkin reason type: 8 attempt count: 1
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
E/ActivityThread( 1380): Failed to find provider info for com.google.android.wearable.settings
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1560): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  989): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1560
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4078): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager(  989): Activity reported stop, but no longer stopping: ActivityRecord{42a52dd8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler(  989): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,112
,I/CheckinRequestBuilder( 1380): Classify the device as Phone.
,I/CheckinTask( 1380): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1380): Checking schedule, now: 1450238518426 next: 1450831588424
,I/CheckinService( 1380): active receiver: disabled
,I/CheckinService( 1380): Checking schedule, now: 1450238518441 next: 1450831588424
,I/CheckinService( 1380): active receiver: disabled
,D/CheckinService( 1380): Recording last checkin time for package unspecified as 1450238518448
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1364): GC_CONCURRENT freed 1900K, 40% free 10435K/17224K, paused 2ms+6ms, total 32ms
,D/dalvikvm( 1217): GC_EXPLICIT freed 1252K, 35% free 11276K/17224K, paused 3ms+8ms, total 38ms
,D/WifiStateMachine(  989): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  989): handleMessage: E msg.what=131215
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
,D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype for one-off execution 4418 seconds from now (1450238519071)
,D/WifiStateMachine(  989): handleMessage: X
D/ConnectivityService(  989): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  989):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService(  989): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
,D/GetConfigurationSnapshotOperation( 1217): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1217): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1217): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  989): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1309): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1309): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/dalvikvm(  989): GC_EXPLICIT freed 1109K, 65% free 18062K/50784K, paused 4ms+9ms, total 93ms
,I/dalvikvm( 1217): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1217): GC_CONCURRENT freed 1736K, 34% free 11506K/17224K, paused 4ms+6ms, total 40ms
,V/AlarmManager(  989): sending alarm Alarm{430d56c0 type 3 android}
,I/GAV2    ( 4254): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  989): Killing 3514:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
,I/ActivityManager(  989): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4427 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/Launcher( 1324): Deferring update until onResume
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
,I/Launcher( 1324): Deferring update until onResume
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
,I/Babel   ( 4427): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4427): MmsConfig.loadMmsSettings
I/Babel   ( 4427): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4427): MmsConfig.loadFromDatabase
,E/Babel   ( 4427): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4427): MmsConfig.loadFromResources
,E/Babel   ( 4427): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4427): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1217): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  989): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4465 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager(  989): Killing 4031:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  989): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4484 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 4158:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2299): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  989): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4501 uid=10038 gids={50038, 3003, 1028, 1015}
,D/dalvikvm( 3496): GC_FOR_ALLOC freed 45K, 5% free 16408K/17224K, paused 13ms, total 14ms
,I/dalvikvm-heap( 3496): Grow heap (frag case) to 19.793MB for 1821008-byte allocation
I/ActivityManager(  989): Killing 4189:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3496): GC_FOR_ALLOC freed 1K, 5% free 18186K/19004K, paused 17ms, total 17ms
,I/ContactLocale( 4465): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4501): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4501): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4501): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2299): UpdateCorporaTask done [took 224 ms] updated apps [took 224 ms] 
,I/dalvikvm( 4501): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4501): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4501): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4501): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4501): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4501): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4501): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4501): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4501): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4501): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4501): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4501): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4501): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4501): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4501): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager(  989): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4535 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4501): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4501): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4501): Skipping gmscore version check
,D/Finsky  ( 4501): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4501): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4501): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4501): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager(  989): Killing 4210:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1380): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1380): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1380): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4535): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x428c20c0, skipping init
I/openssl ( 4535): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4535): Crypto mode 0 already enabled
,D/Finsky  ( 4501): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  989): Killing 4225:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4501): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1380): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1380): GC_CONCURRENT freed 1896K, 30% free 12145K/17224K, paused 5ms+6ms, total 48ms
,I/Icing   ( 1380): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450238527
,D/CaptivePortalTracker(  989): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  989): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  989): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  989): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  989): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  989): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  989): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  989): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{4315aa90 type 3 android}
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1364): disconnect managed GoogleApiClient
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
,V/AlarmManager(  989): sending alarm Alarm{432b1ba0 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
,V/AlarmManager(  989): sending alarm Alarm{4430a598 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44a8c9c0 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{44a7a168 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4318aef0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{431c4940 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43158d48 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  989): sending alarm Alarm{431572a8 type 0 com.google.android.gms}
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
,I/EventLogService( 1380): Aggregate from 1450238515102 (log), 1450236949613 (data)
,V/AlarmManager(  989): sending alarm Alarm{43b93630 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44a17ce8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43ac9b78 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43bfd1f0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43138000 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{446a1eb0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43b93708 type 1 com.android.deskclock}
,I/ActivityManager(  989): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4611 uid=10015 gids={50015, 1028}
,I/ActivityManager(  989): Killing 4254:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager(  989): sending alarm Alarm{44a9dfc8 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{4316c348 type 2 com.google.android.gms}
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/ConnectivityService(  989): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1309): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/PhenotypeConfigurator( 1217): Server returned 404
,V/AlarmManager(  989): sending alarm Alarm{44a9bf90 type 3 android}
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4078): teardown
I/jxcore-log( 4078): 
,E/jxcore  ( 4078): Error!: self.currentTest is undefined
E/jxcore  ( 4078): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:159:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 4078): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager(  989): sending alarm Alarm{44372e28 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{43ac4c30 type 3 android}
,I/jxcore-log( 4078): Connected to the server!
I/jxcore-log( 4078): 
,I/chromium( 4078): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
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
,V/AlarmManager(  989): sending alarm Alarm{44794f98 type 3 android}
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{43b92290 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{44a9c068 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{43293e40 type 3 android}
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = ,
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{443e5178 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{431d2990 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{445e3930 type 3 android}
,D/dalvikvm(  989): GC_CONCURRENT freed 2075K, 65% free 18185K/50784K, paused 4ms+8ms, total 106ms
,V/AlarmManager(  989): sending alarm Alarm{43c4f1d8 type 3 android}
,I/ProcessStatsService(  989): Prepared write state in 23ms
,I/ProcessStatsService(  989): Prepared write state in 20ms
,I/ProcessStatsService(  989): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-04-40.bin
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
,V/AlarmManager(  989): sending alarm Alarm{44a7cbe0 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{445a8c10 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{4459b730 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{443736d8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{44a9c140 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44a9c218 type 3 com.google.android.gms}
,V/AlarmManager(  989): sending alarm Alarm{44a9c268 type 1 com.android.deskclock}
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  989): sending alarm Alarm{4431bc90 type 3 android}
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
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4697): 
D/AndroidRuntime( 4697): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4697): CheckJNI is OFF
D/dalvikvm( 4697): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4697): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4697): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4697): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4697): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4697): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4697): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4697): failed to load memtrack module: -2
D/AndroidRuntime( 4697): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10484 user=-1: uninstall pkg
I/ActivityManager(  989): Killing 4078:com.test.thalitest/u0a484 (adj 9): stop com.test.thalitest
I/ActivityManager(  989):   Force finishing activity ActivityRecord{4328a818 u0 com.test.thalitest/.MainActivity t3}
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState(  989): WIN DEATH: Window{42aa9cf8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  989): Client connection lost with reason: 4
W/PackageSettings(  989): Skipping PackageSetting{42b7a5a8 com.example.hello/10480} due to missing metadata
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10484 user=0: pkg removed
D/dalvikvm( 2267): GC_EXPLICIT freed 5516K, 44% free 9650K/17224K, paused 2ms+5ms, total 47ms
D/dalvikvm( 2299): GC_EXPLICIT freed 3737K, 42% free 10074K/17224K, paused 2ms+4ms, total 100ms
D/dalvikvm( 1324): GC_EXPLICIT freed 3340K, 33% free 11595K/17224K, paused 2ms+5ms, total 84ms
D/dalvikvm(  989): GC_EXPLICIT freed 1077K, 65% free 17950K/50672K, paused 5ms+11ms, total 116ms
D/dalvikvm( 1380): GC_EXPLICIT freed 536K, 31% free 11916K/17224K, paused 5ms+10ms, total 135ms
I/Launcher( 1324): Deferring update until onResume
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
D/VoicemailCleanupService( 4465): Cleaning up data for package: com.test.thalitest
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Launcher( 1324): Deferring update until onResume
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2299): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450240316
I/ActivityManager(  989): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4729 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
D/BackupManagerService(  989): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  989): removePackageParticipantsLocked: uid=10484 #1
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450240316
D/dalvikvm(  989): GC_EXPLICIT freed 638K, 65% free 18038K/50672K, paused 4ms+23ms, total 229ms
I/InternalIcingCorporaPro( 2299): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
D/AndroidRuntime( 4697): Shutting down VM
D/dalvikvm( 4697): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4729): Missing scope.enter somewhere. Returning default context
I/ActivityManager(  989): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4752 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4729): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1380): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1380): Clearing selected account for com.test.thalitest
I/dalvikvm( 4501): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4501): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1380): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1380): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1380): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1380): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1380): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1380): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/NetworkScheduler.SchedulerReceiver( 1364): Invalid parameter app
D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/Icing   ( 1380): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
E/NetworkScheduler.SchedulerReceiver( 1364): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/SQLiteLog( 1380): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1380): threadid=54: thread exiting with uncaught exception (group=0x41fe8d40)
I/ActivityManager(  989): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4790 uid=10058 gids={50058}
W/FileUtils( 1380): Failed to chmod(/data/data/com.google.android.gms/databases/auto_complete_suggestions.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/AndroidRuntime( 1380): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1380): Process: com.google.android.gms, PID: 1380
E/AndroidRuntime( 1380): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1380): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1380): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 1380): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1380): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1380): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1380): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1380): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1380): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 1380): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1380): Failed to open Apps corpus file.
E/Icing   ( 1380): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1380): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
V/AlarmManager(  989): sending alarm Alarm{42ec98a8 type 2 com.motorola.ccc.cce}
D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 1380): (3850) statement aborts at 29: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
W/dalvikvm( 1380): threadid=50: thread exiting with uncaught exception (group=0x41fe8d40)
I/Process ( 1380): Sending signal. PID: 1380 SIG: 9
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
W/dalvikvm( 4752): threadid=10: thread exiting with uncaught exception (group=0x41fe8d40)
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
I/ActivityManager(  989): Process com.google.android.gms (pid 1380) has died.
D/WifiService(  989): Client connection lost with reason: 4
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager(  989): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
I/Process ( 4752): Sending signal. PID: 4752 SIG: 9
E/DropBoxManagerService(  989): Can't write: system_app_crash
E/DropBoxManagerService(  989): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  989): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  989): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  989): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  989): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  989): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  989): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  989): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  989): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  989): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  989): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  989): 	... 5 more
I/ActivityManager(  989): Process com.android.keychain (pid 4752) has died.
W/ActivityManager(  989): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20989ms
D/Documents( 4790): Loading roots for com.android.providers.downloads.documents
D/Documents( 4790): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4790): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4790): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4790): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4790): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4790): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4790): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4790): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4790): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4790): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4790): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4790): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4790): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4790): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4790): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4790): Shutting down VM
W/dalvikvm( 4790): threadid=1: thread exiting with uncaught exception (group=0x41fe8d40)
E/AndroidRuntime( 4790): FATAL EXCEPTION: main
E/AndroidRuntime( 4790): Process: com.android.documentsui, PID: 4790
E/AndroidRuntime( 4790): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4790): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4790): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4790): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4790): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4790): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4790): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4790): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4790): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4790): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4790): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4790): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4790): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4790): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4790): 	... 10 more
I/ActivityManager(  989): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4808 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}

```
