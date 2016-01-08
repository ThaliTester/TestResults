#### Test 549702613245198_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4023): 
D/AndroidRuntime( 4023): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4023): CheckJNI is OFF
D/dalvikvm( 4023): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4023): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4023): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4023): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4023): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4023): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4023): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4023): failed to load memtrack module: -2
D/AndroidRuntime( 4023): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1000): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4023
W/WindowManager( 1000): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1000): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4039 uid=10532 gids={50532, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4023): Shutting down VM
D/dalvikvm( 4023): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4039): Binding Chromium to main looper Looper (main, tid 1) {41fa9bf8}
I/LibraryLoader( 4039): Expected native library version number "",actual native library version number ""
I/chromium( 4039): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4039): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1000): Message: 20
D/BluetoothManagerService( 1000): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@433a54b8:true
I/Adreno-EGL( 4039): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4039): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4039): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4039): Local Branch: 
I/Adreno-EGL( 4039): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4039): Local Patches: NONE
I/Adreno-EGL( 4039): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4039): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4039): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4039): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4039): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4039): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4039): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4039): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4039): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4039): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4039): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4039): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4039): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4039): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4039): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4039): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4039): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4039): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4039): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4039): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4039): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4039): Enabling debug mode 0
,W/AwContents( 4039): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1000): Displayed com.test.thalitest/.MainActivity,cp,ca,383
I/ActivityManager( 1000): Displayed com.test.thalitest/.MainActivity: +355ms (total +383ms)
W/AwContents( 4039): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4039): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4039): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4039): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fae470
,D/dalvikvm( 4039): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fae470
,D/jxcore_app_log( 4039): JniHelper::setJavaVM(0x41607f78), pthread_self() = 1614026304
,D/JX-Cordova( 4039): jxcore cordova android initializing
,D/dalvikvm( 4039): GC_CONCURRENT freed 2712K, 17% free 14410K/17224K, paused 3ms+3ms, total 46ms
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 275K, 17% free 14431K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 16.216MB for 95956-byte allocation
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 193K, 17% free 14450K/17320K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 16.281MB for 143930-byte allocation
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 252K, 17% free 14497K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 16.396MB for 215890-byte allocation
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 366K, 18% free 14571K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 16.571MB for 323830-byte allocation
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 564K, 19% free 14692K/17996K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 16.843MB for 485740-byte allocation
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 860K, 20% free 14868K/18472K, paused 26ms, total 27ms
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 1275K, 19% free 15124K/18472K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 17.844MB for 1092904-byte allocation
,D/dalvikvm( 4039): GC_CONCURRENT freed 1751K, 21% free 15504K/19540K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 289K, 21% free 15441K/19540K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 18.675MB for 1639352-byte allocation
,D/dalvikvm( 4039): GC_CONCURRENT freed 1681K, 25% free 16022K/21144K, paused 1ms+4ms, total 31ms
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 1302K, 24% free 16079K/21144K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 20.080MB for 2459024-byte allocation
,D/dalvikvm( 4039): GC_CONCURRENT freed 1820K, 29% free 16792K/23548K, paused 4ms+7ms, total 44ms
,D/dalvikvm( 4039): GC_CONCURRENT freed 2356K, 28% free 17032K/23548K, paused 3ms+6ms, total 43ms
,D/dalvikvm( 4039): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 709K, 29% free 16802K/23548K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4039): Grow heap (frag case) to 21.958MB for 3688532-byte allocation
,D/dalvikvm( 4039): GC_CONCURRENT freed 2637K, 34% free 17974K/27152K, paused 5ms+3ms, total 38ms
,D/dalvikvm( 4039): GC_FOR_ALLOC freed 698K, 34% free 18023K/27152K, paused 26ms, total 26ms
,W/jxcore-log( 4039): Initializing JXcore engine
,W/jxcore-log( 4039): JXcore engine is ready
,D/dalvikvm( 4039): GC_CONCURRENT freed 369K, 24% free 20644K/27152K, paused 1ms+2ms, total 28ms
,D/dalvikvm( 4039): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4039): Starting JXcore engine
,W/jxcore-log( 4039): Platform android
W/jxcore-log( 4039): 
,W/jxcore-log( 4039): Process ARCH arm
W/jxcore-log( 4039): 
,I/jxcore-log( 4039): JXcore Cordova bridge is ready!
I/jxcore-log( 4039): 
,W/jxcore-log( 4039): JXcore engine is started
,I/chromium( 4039): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4039): Toggling radios to true
I/jxcore-log( 4039): 
,D/BluetoothAdapter( 4039): enable(): BT is already enabled..!
D/WifiService( 1000): New client listening to asynchronous messages
D/WifiService( 1000): setWifiEnabled: true pid=4039, uid=10532
,E/WifiService( 1000): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1000): handleMessage: E msg.what=131145
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
I/jxcore-log( 4039): Radios toggled
I/jxcore-log( 4039): 
,I/wpa_supplicant( 1170): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  475): NL - Read 1000 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 1000 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1000): transitionTo: destState=DisconnectingState
,D/Tethering( 1000): InitialState.processMessage what=4
,V/ConnectivityService( 1000): WiFi NOT Tethered!
D/Tethering( 1000): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1000): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1000): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1000): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1000): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1000): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/TCMD    (  475): NL - Read 60 bytes from update socket.
D/TCMD    (  475): NL - ignore NL message, type = 21
,D/TCMD    (  475): Listening for incoming client connection request
,D/WifiStateMachine( 1000): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1000): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1000): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1000): connected time updated 274208
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1000): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1000): Attempting to switch to mobile
D/ConnectivityService( 1000): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1000): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1000): resetConnections(wlan0, 3)
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1000): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1000): DisconnectingState
D/NetUtils( 1000): android_net_utils_resetConnections in env=0x5feb2290 clazz=0x5ff00001 iface=wlan0 mask=0x3
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131146
D/WifiStateMachine( 1000): processMsg: DisconnectingState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147460
D/WifiStateMachine( 1000): processMsg: DisconnectingState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): Network connection lost
D/WifiStateMachine( 1000): Stopping DHCP and clearing IP
D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 2105): Read error: ssl=0x61159ee0: I/O error during system call, Connection timed out
D/WifiP2pService( 1000): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1170): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1000): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
V/NativeCrypto( 2105): SSL shutdown failed: ssl=0x61159ee0: I/O error during system call, Broken pipe
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1000): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1000): invokeEnterMethods: DisconnectedState
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
D/WifiStateMachine( 1000): handleMessage: X
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1000): Attempting to switch to mobile
D/ConnectivityService( 1000): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1000): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1000): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 1170): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1170): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): processMsg: DriverStartedState
,D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
,I/wpa_supplicant( 1170): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  475): NL - Read 312 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
I/wpa_supplicant( 1170): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  475): NL - Read 88 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 1000 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
I/wpa_supplicant( 1170): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  475): NL - Read 80 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 80 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1000): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1170): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1170): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  475): NL - Read 1000 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
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
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202543864
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1000): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147459
D/WifiStateMachine( 1000): processMsg: DisconnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): Network connection established
D/WifiStateMachine( 1000): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1000): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1000): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1000): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1000): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
,D/WifiStateMachine( 1000): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@4361b870 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=196612
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,D/WifiStateMachine( 1000): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1000): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1000): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420e9eb8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420e9eb8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): handleMessage: X
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c2
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 c2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 0c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 8 0c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
,D/WifiStateMachine( 1000): handleMessage: E msg.what=147461
D/WifiP2pService( 1000): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiP2pService( 1000): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1000): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): handleMessage: X
,D/TCMD    (  475): NL - Read 60 bytes from update socket.
D/TCMD    (  475): NL - ignore NL message, type = 20
,D/TCMD    (  475): Listening for incoming client connection request
,D/WifiStateMachine( 1000): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1000): handleMessage: E msg.what=131215
D/WifiStateMachine( 1000): processMsg: ObtainingIpState
D/WifiStateMachine( 1000): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1000): processMsg: ObtainingIpState
,D/WifiStateMachine( 1000): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
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
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=151572
D/WifiStateMachine( 1000): processMsg: VerifyingLinkState
D/WifiStateMachine( 1000): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): handleMessage: X
,D/WifiStateMachine( 1000): handleMessage: E msg.what=135190
D/WifiStateMachine( 1000): processMsg: VerifyingLinkState
D/WifiStateMachine( 1000): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1000): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1000): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1000): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1000): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1000): CaptivePortalCheckState enter
,D/WifiStateMachine( 1000): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1000): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1000): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1000): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1000): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): handleMessage: X
D/WifiStateMachine( 1000): handleMessage: E msg.what=131092
D/WifiStateMachine( 1000): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1000): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1000): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1000): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1000): WiFi NOT Tethered!
,E/ConnectivityService( 1000): Unexpected mtu value: android.net.wifi.WifiStateTracker@42093ea0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1000): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1000): WiFi NOT Tethered!
,E/ConnectivityService( 1000): Unexpected mtu value: android.net.wifi.WifiStateTracker@42093ea0
D/Checkin ( 1000): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1000): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1000): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1000): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1000): invokeExitMethods: CaptivePortalCheckState
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
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
D/WifiStateMachine( 1000): handleMessage: X
,D/ConnectivityService( 1000): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1000): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1000): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1000): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4160 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1566): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1566): [debug] > CusSM.onRadioDown
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1566): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/Tethering( 1000): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1000): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,I/ActivityManager( 1000): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4187 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4160): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fb1f18, skipping init
I/openssl ( 4160): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4160): Crypto mode 0 already enabled
,I/ActivityManager( 1000): Killing 2906:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4187): mnc/mcc: 
V/MmsConfig( 4187): tag: bool value: enabledMMS - true
,V/MmsConfig( 4187): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4187): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4187): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4187): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4187): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4187): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4187): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4187): tag: int value: recipientLimit - 20
V/MmsConfig( 4187): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4187): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4187): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4187): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4187): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4187): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4187): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4187): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4187): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1000): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4210 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1000): Killing 3862:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4210): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4210): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1000): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4224 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 3660:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452283621204 min interval config: 0 actual interval: 270454
,I/CheckinService( 1419): Checking schedule, now: 1452283891665 next: 1452283651186
,I/CheckinService( 1419): active receiver: enabled
,I/CheckinService( 1419): Preparing to send checkin request
,I/EventLogService( 1419): Accumulating logs since 1452283617790
,I/CheckinRequestBuilder( 1419): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1419): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1000): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4238 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1000): Killing 3906:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1000): NetTransition Wakelock for ConnectedState released by timeout
,V/WebViewChromiumFactoryProvider( 4238): Binding Chromium to main looper Looper (main, tid 1) {41faec78}
,I/LibraryLoader( 4238): Expected native library version number "",actual native library version number ""
,I/chromium( 4238): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4238): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4238): BLUETOOTH permission is missing!
,D/dalvikvm( 1000): GC_EXPLICIT freed 23321K, 65% free 18084K/50880K, paused 4ms+10ms, total 143ms
,I/Adreno-EGL( 4238): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4238): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4238): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4238): Local Branch: 
I/Adreno-EGL( 4238): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4238): Local Patches: NONE
I/Adreno-EGL( 4238): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 2105): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2105): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4238): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1000): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4266 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/GAV2    ( 4238): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  265): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  265): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4238): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4266): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4266): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4266): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4266): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4266): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4266): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4266): install
,I/MultiDex( 4266): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4266): loading existing secondary dex files
,I/MultiDex( 4266): load found 3 secondary dex files
,I/MultiDex( 4266): install done
,D/dalvikvm( 4266): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4266): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4266): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4266): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4266): VFY: unable to resolve instance field 36
,D/dalvikvm( 4266): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4266): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4266): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4266): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4266): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4266): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4266): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb4a28
D/dalvikvm( 4266): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb4a28
,D/dalvikvm( 4266): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb4a28, skipping init
D/dalvikvm( 4266): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fb4a28
,D/dalvikvm( 4266): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fb4a28
,V/JNIHelp ( 4266): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4266): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb4a28
,D/dalvikvm( 4266): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fb4a28
D/dalvikvm( 4266): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fb4a28
,D/dalvikvm( 4266): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fb4a28
,I/NSApplication( 4238): Starting up...
,I/iu.Environment( 3221): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1000): Killing 3679:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1566): onServiceConnected()
D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4160): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4160): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3221): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ProviderInstaller( 4266): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1252): callingUid 10022, callindPid: 1252
D/AuthorizationBluetoothService( 2105): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2105): Proximity feature is not enabled.
,D/LocationInitializer( 1419): Restart initialization of location
,E/MDM     ( 1252): [72] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 2105): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1252): No location to return for getLastLocation()
,W/FusedLocationProvider( 1252): location=null
,I/dalvikvm( 4266): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4266): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4266): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4266): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4266): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4266): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4266): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4266): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4266): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4266): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4266): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4266): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4266): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4266): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4266): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4266): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4266): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53c1000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53c1000
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
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
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=2747006541
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4266): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4266): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bfdc0
D/dalvikvm( 4266): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bfdc0
,D/dalvikvm( 4266): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bfdc0, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4266): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4306): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4266): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4266): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 74ms
,I/Adreno-EGL( 4266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4266): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4266): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4266): Local Branch: 
I/Adreno-EGL( 4266): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4266): Local Patches: NONE
I/Adreno-EGL( 4266): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4266): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4266): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4266): Local Branch: 
I/Adreno-EGL( 4266): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4266): Local Patches: NONE
I/Adreno-EGL( 4266): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4266): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4266): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4266): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4266): Local Branch: 
I/Adreno-EGL( 4266): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4266): Local Patches: NONE
I/Adreno-EGL( 4266): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4266): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4266): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4266): Local Branch: 
I/Adreno-EGL( 4266): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4266): Local Patches: NONE
I/Adreno-EGL( 4266): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  281): PrepareKeyRequest: nonce=2585930825
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1000): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1000): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1566): now: 320958 ,futureTime: 6202222
,D/PollingManager( 1566): Polling alarm set to expire at: 6202222 Current Time: 320958
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1566): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/PollingManager( 1566): now: 320966 ,futureTime: 6202222
D/PollingManager( 1566): Polling alarm set to expire at: 6202222 Current Time: 320967
D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1566): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1566): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/OtaApp  ( 1566): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/Tethering( 1000): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1000): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
I/openssl ( 4160): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4160): Crypto mode 0 already enabled
D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/dalvikvm( 1566): GC_CONCURRENT freed 2165K, 39% free 10647K/17224K, paused 3ms+2ms, total 33ms
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3221): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/TelephonyProvider( 1278): Column apn id key is 'apn_id'
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452283621204 min interval config: 0 actual interval: 272756
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1566): onServiceConnected()
,D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 4160): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4160): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4210): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4210): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3221): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452283621204 min interval config: 0 actual interval: 272817
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1566): onServiceConnected()
,D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1566): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1566): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1000): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1566
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
,I/CheckinRequestBuilder( 1419): Classify the device as Phone.
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1566): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1000): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1566
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
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
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1000): Activity reported stop, but no longer stopping: ActivityRecord{41fdc630 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1000): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,149
I/SFPerfTracer(  278):      triggers: (rate: 3:30) (compose: 0:4) (post: 0:1) (render: 0:5) (3:114 frames) (4:550)
,D/SFPerfTracer(  278):        layers: (0:13) (FocusedStackFrame: 0:11)* (StatusBar: 0:202)* (NavigationBar: 0:34)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:26)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 4:4)* 
,I/CheckinTask( 1419): Sending checkin request (11633 bytes)
,I/CheckinRequestBuilder( 1419): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1419): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1419): Classify the device as Phone.
,I/CheckinTask( 1419): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1419): Checking schedule, now: 1452283894980 next: 1452876964970
,I/CheckinService( 1419): active receiver: disabled
,I/CheckinService( 1419): Checking schedule, now: 1452283894996 next: 1452876964970
,I/CheckinService( 1419): active receiver: disabled
,D/CheckinService( 1419): Recording last checkin time for package unspecified as 1452283895008
,D/GCM     ( 2105): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 2105): GC_EXPLICIT freed 1514K, 41% free 10294K/17224K, paused 2ms+4ms, total 37ms
,D/ConnectivityService( 1000): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1000): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1000): handleMessage: E msg.what=131215
D/WifiStateMachine( 1000): processMsg: ConnectedState
D/WifiStateMachine( 1000): processMsg: L2ConnectedState
D/WifiStateMachine( 1000): processMsg: ConnectModeState
D/WifiStateMachine( 1000): processMsg: DriverStartedState
D/WifiStateMachine( 1000): processMsg: SupplicantStartedState
D/WifiStateMachine( 1000): processMsg: DefaultState
,D/WifiStateMachine( 1000): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1000): handleMessage: X
,D/ConnectivityService( 1000): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1000):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1000): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1000): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4238): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1000): Killing 3934:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4039): Test app app.js loaded
I/jxcore-log( 4039): 
,I/Choreographer( 4039): Skipped 700 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 4039): showStatusIcon on inactive InputConnection
,I/chromium( 4039): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4039): --= Surplus to requirements =--
I/jxcore-log( 4039): 
,I/jxcore-log( 4039): ****TEST TOOK:  ms ****
I/jxcore-log( 4039): 
,I/jxcore-log( 4039): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4039): 
,D/AndroidRuntime( 4360): 
D/AndroidRuntime( 4360): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4360): CheckJNI is OFF
,D/dalvikvm( 4360): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4360): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4360): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4360): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4360): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4360): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4360): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4360): failed to load memtrack module: -2
,D/AndroidRuntime( 4360): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1000): Force stopping com.test.thalitest appid=10532 user=-1: uninstall pkg
,I/ActivityManager( 1000): Killing 4039:com.test.thalitest/u0a532 (adj 9): stop com.test.thalitest
I/ActivityManager( 1000):   Force finishing activity ActivityRecord{44486188 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1000): WIN DEATH: Window{445c3290 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1000): Client connection lost with reason: 4
,W/PackageSettings( 1000): Skipping PackageSetting{422723b8 com.example.hello/10529} due to missing metadata
,I/ActivityManager( 1000): Force stopping com.test.thalitest appid=10532 user=0: pkg removed
,D/dalvikvm( 2256): GC_EXPLICIT freed 6106K, 44% free 9755K/17224K, paused 2ms+6ms, total 43ms
,I/InputReader( 1000): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/ActivityManager( 1000): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4380 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,W/GeofencerStateMachine( 1252): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452283901
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
D/dalvikvm( 1419): GC_EXPLICIT freed 1380K, 31% free 11972K/17224K, paused 31ms+7ms, total 177ms
D/dalvikvm( 1000): GC_EXPLICIT freed 1354K, 65% free 18109K/50880K, paused 5ms+12ms, total 137ms
D/dalvikvm( 1000): WAIT_FOR_CONCURRENT_GC blocked 46ms
D/dalvikvm( 2293): GC_EXPLICIT freed 3008K, 43% free 9822K/17224K, paused 2ms+7ms, total 175ms
,D/dalvikvm( 1320): GC_EXPLICIT freed 2898K, 33% free 11593K/17224K, paused 2ms+14ms, total 167ms
,I/Launcher( 1320): Deferring update until onResume
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
,I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452283901
,I/Launcher( 1320): Deferring update until onResume
,D/VoicemailCleanupService( 4380): Cleaning up data for package: com.test.thalitest
D/BackupManagerService( 1000): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1000): removePackageParticipantsLocked: uid=10532 #1
,I/ActivityManager( 1000): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4405 uid=10033 gids={50033, 3003, 1028, 1015}
D/dalvikvm( 1000): GC_EXPLICIT freed 406K, 65% free 18104K/50880K, paused 13ms+27ms, total 176ms
,I/ActivityManager( 1000): Killing 3575:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2293): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1000): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4420 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ContactLocale( 4380): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager( 1000): Killing 4160:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 4360): Shutting down VM
D/dalvikvm( 4360): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/InputReader( 1000): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/Launcher( 1320): Deferring update until onResume
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
I/Launcher( 1320): Deferring update until onResume
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2293): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "sms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "smsto"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mms"
,I/PackageManager( 1000): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1000):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1000):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1000):   Scheme: "mmsto"
,I/GCoreNlp( 1252): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ActiveOrDefaultContextProvider( 4420): Missing scope.enter somewhere. Returning default context
,E/SQLiteDatabase( 4420): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4420): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4420): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 4420): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 4420): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 4420): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4420): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 4420): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 4420): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4420): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 4420): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4420): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 4420): 	at an,droid.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4420): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4420): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4420): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4420): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4420): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4420): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4420): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4420): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4420): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4420): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4420): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 4420): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 4420): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4420): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 4420): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 4420): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4420): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4420): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 4420): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 4420): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4420): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4420): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4420): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 4420): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4420): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4420): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4420): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4420): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4420): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4420): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4420): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4420): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4420): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4420): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4420): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4420): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4420): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 4420): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 4420): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 4420): threadid=11: thread exiting with uncaught exception (group=0x416ded40)
E/AndroidRuntime( 4420): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4420): Process: com.google.android.apps.docs, PID: 4420
E/AndroidRuntime( 4420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4420): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4420): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4420): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 4420): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 4420): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 4420): 	at WT.run(AbstractDatabaseInstance.java:411)
,I/Process ( 4420): Sending signal. PID: 4420 SIG: 9
E/DropBoxManagerService( 1000): Can't write: system_app_crash
E/DropBoxManagerService( 1000): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1000): Process com.google.android.apps.docs (pid 4420) has died.
,E/MP-Decision( 1515): Error(-22) changing core 2 status to offline

```
