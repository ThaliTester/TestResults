#### Test 549702610263d9b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1024): sending alarm Alarm{423f2a80 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4009): 
D/AndroidRuntime( 4009): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4009): CheckJNI is OFF
D/dalvikvm( 4009): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4009): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4009): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4009): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4009): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4009): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4009): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4009): failed to load memtrack module: -2
D/AndroidRuntime( 4009): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1024): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4009
W/WindowManager( 1024): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1024): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4025 uid=10516 gids={50516, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4009): Shutting down VM
D/dalvikvm( 4009): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4025): Binding Chromium to main looper Looper (main, tid 1) {41fec938}
I/LibraryLoader( 4025): Expected native library version number "",actual native library version number ""
I/chromium( 4025): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4025): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1024): Message: 20
D/BluetoothManagerService( 1024): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4219fa00:true
I/Adreno-EGL( 4025): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4025): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4025): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4025): Local Branch: 
I/Adreno-EGL( 4025): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4025): Local Patches: NONE
I/Adreno-EGL( 4025): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4025): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4025): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4025): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4025): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4025): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4025): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4025): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4025): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4025): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4025): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4025): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4025): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4025): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4025): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4025): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4025): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4025): Enabling debug mode 0
,W/AwContents( 4025): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4025): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1024): Displayed com.test.thalitest/.MainActivity,cp,ca,365
I/ActivityManager( 1024): Displayed com.test.thalitest/.MainActivity: +339ms (total +365ms)
,D/JsMessageQueue( 4025): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4025): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41ff10b8
,D/dalvikvm( 4025): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41ff10b8
,D/jxcore_app_log( 4025): JniHelper::setJavaVM(0x4163dfa8), pthread_self() = 1614844512
,D/JX-Cordova( 4025): jxcore cordova android initializing
,D/dalvikvm( 4025): GC_CONCURRENT freed 2763K, 17% free 14426K/17224K, paused 2ms+3ms, total 53ms
,D/dalvikvm( 4025): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4025): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 189K, 17% free 14449K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 135K, 17% free 14459K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 16.245MB for 95956-byte allocation
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 179K, 17% free 14494K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 16.324MB for 143930-byte allocation
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 253K, 17% free 14541K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 16.439MB for 215890-byte allocation
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 368K, 18% free 14615K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 16.614MB for 323830-byte allocation
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 568K, 19% free 14736K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 16.886MB for 485740-byte allocation
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 865K, 20% free 14911K/18472K, paused 26ms, total 26ms
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 1282K, 18% free 15167K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 17.886MB for 1092904-byte allocation
,D/dalvikvm( 4025): GC_CONCURRENT freed 1826K, 21% free 15573K/19540K, paused 1ms+7ms, total 46ms
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 239K, 21% free 15476K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 18.708MB for 1639352-byte allocation
,D/dalvikvm( 4025): GC_CONCURRENT freed 1751K, 24% free 16076K/21144K, paused 2ms+5ms, total 48ms
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 1248K, 24% free 16116K/21144K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 20.117MB for 2459024-byte allocation
,D/dalvikvm( 4025): GC_CONCURRENT freed 275K, 22% free 18428K/23548K, paused 5ms+3ms, total 48ms
,D/dalvikvm( 4025): GC_CONCURRENT freed 4354K, 28% free 17117K/23548K, paused 1ms+7ms, total 49ms
,D/dalvikvm( 4025): WAIT_FOR_CONCURRENT_GC blocked 45ms
,I/dalvikvm-heap( 4025): Grow heap (frag case) to 22.265MB for 3688532-byte allocation
,D/dalvikvm( 4025): GC_CONCURRENT freed 2828K, 33% free 18253K/27152K, paused 3ms+5ms, total 80ms
,D/dalvikvm( 4025): GC_FOR_ALLOC freed 913K, 34% free 18065K/27152K, paused 30ms, total 30ms
,W/jxcore-log( 4025): Initializing JXcore engine
,W/jxcore-log( 4025): JXcore engine is ready
,D/dalvikvm( 4025): GC_CONCURRENT freed 333K, 24% free 20753K/27152K, paused 1ms+2ms, total 30ms
D/dalvikvm( 4025): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4025): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4025): Starting JXcore engine
,W/jxcore-log( 4025): Platform android
W/jxcore-log( 4025): 
,W/jxcore-log( 4025): Process ARCH arm
W/jxcore-log( 4025): 
,I/jxcore-log( 4025): JXcore Cordova bridge is ready!
I/jxcore-log( 4025): 
,W/jxcore-log( 4025): JXcore engine is started
,I/chromium( 4025): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4025): Toggling radios to true
I/jxcore-log( 4025): 
,D/BluetoothAdapter( 4025): enable(): BT is already enabled..!
D/WifiService( 1024): New client listening to asynchronous messages
D/WifiService( 1024): setWifiEnabled: true pid=4025, uid=10516
,E/WifiService( 1024): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1024): handleMessage: E msg.what=131145
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
I/jxcore-log( 4025): Radios toggled
I/jxcore-log( 4025): 
,I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  401): NL - Read 1000 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
,D/TCMD    (  401): Listening for incoming client connection request
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
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  401): NL - Read 1000 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 68 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 68 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
,D/TCMD    (  401): Listening for incoming client connection request
,D/WifiStateMachine( 1024): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1024): invokeExitMethods: ConnectedState
,D/Tethering( 1024): InitialState.processMessage what=4
D/WifiStateMachine( 1024): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1024): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,V/ConnectivityService( 1024): WiFi NOT Tethered!
D/Tethering( 1024): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1024): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  401): NL - Read 60 bytes from update socket.
D/TCMD    (  401): NL - ignore NL message, type = 21
,D/TCMD    (  401): Listening for incoming client connection request
,D/WifiStateMachine( 1024): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1024): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1024): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1024): connected time updated 346117
D/ConnectivityService( 1024): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1024): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1024): Attempting to switch to mobile
,D/ConnectivityService( 1024): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1024): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1024): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1024): DisconnectingState
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131146
D/WifiStateMachine( 1024): processMsg: DisconnectingState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147460
D/WifiStateMachine( 1024): processMsg: DisconnectingState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): Network connection lost
,D/WifiStateMachine( 1024): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,D/ConnectivityService( 1024): resetConnections(wlan0, 3)
,D/NetUtils( 1024): android_net_utils_resetConnections in env=0x6122eeb0 clazz=0x60f00001 iface=wlan0 mask=0x3
D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 1367): Read error: ssl=0x633fda98: I/O error during system call, Connection timed out
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x633fda98: I/O error during system call, Broken pipe
,E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1024): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1024): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1024): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131101
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131216
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131216
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1024): Attempting to switch to mobile
D/ConnectivityService( 1024): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1024): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/TCMD    (  401): NL - Read 56 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
,D/TCMD    (  401): Listening for incoming client connection request
D/WifiP2pService( 1024): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4296b968 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4296b968 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4296b968 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): handleMessage: X
,D/PollingManager( 1574): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/CaptivePortalTracker( 1024): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1024): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1303): Active network info is not available
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1024): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4101 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1303): Active network info is not available
,E/ActivityThread( 1574): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1574): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker( 1024): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1024): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/PollingManager( 1574): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1574): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1574): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1574): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1574): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/dalvikvm( 4101): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ff4c30, skipping init
I/openssl ( 4101): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4101): Crypto mode 0 already enabled
I/ActivityManager( 1024): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4128 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 3782:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4128): mnc/mcc: 
V/MmsConfig( 4128): tag: bool value: enabledMMS - true
,V/MmsConfig( 4128): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4128): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4128): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 4128): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4128): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4128): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4128): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4128): tag: int value: recipientLimit - 20
V/MmsConfig( 4128): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4128): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4128): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4128): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4128): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4128): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4128): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4128): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4128): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1024): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4147 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1024): Killing 3882:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4147): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4147): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4147): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4147): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1024): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4160 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 3474:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4173 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 3915:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,V/WebViewChromiumFactoryProvider( 4173): Binding Chromium to main looper Looper (main, tid 1) {41ff1988}
,I/LibraryLoader( 4173): Expected native library version number "",actual native library version number ""
,I/chromium( 4173): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4173): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4173): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4173): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4173): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4173): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4173): Local Branch: 
I/Adreno-EGL( 4173): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4173): Local Patches: NONE
I/Adreno-EGL( 4173): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4173): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4173): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4173): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4173): Starting up...
,I/ImageResourceManager( 3506): ImageResourceManager: uninitalized
,I/iu.Environment( 3506): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3506): SYNC; picasa accounts
I/ActivityManager( 1024): Killing 3489:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/iu.Environment( 1411): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/DEBUG   ( 1574): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1574): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1574): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1574): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1574): onServiceConnected()
,D/GetNotificationsWS( 1574): onServiceConnected(): Registered for remote service callbacks...
,I/iu.UploadsManager( 1411): num queued entries: 0
I/SundryService( 1574): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1574): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1574): unbindWebServices(): un-registering our AIDL callback...
,I/iu.UploadsManager( 3506): num queued entries: 0
,I/iu.UploadsManager( 1411): num updated entries: 0
,I/iu.UploadsManager( 3506): num updated entries: 0
,D/MobileConnectivityChangeReceiver( 4147): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
I/iu.SyncManager( 1411): NEXT; no task
,D/MobileConnectivityChangeReceiver( 4147): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3506): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.SyncManager( 3506): NEXT; no task
,I/GAV2    ( 4173): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/jxcore-log( 4025): Test app app.js loaded
I/jxcore-log( 4025): 
,I/chromium( 4025): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1159): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  401): NL - Read 56 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
,D/TCMD    (  401): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  276): Event received = Trying to associate with,
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1159): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,I/wpa_supplicant( 1159): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1159): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  401): NL - Read 312 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 88 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 68 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 1000 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1159): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  401): NL - Read 80 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 80 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/TCMD    (  401): NL - Read 68 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
,D/TCMD    (  401): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1159): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  276): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  401): NL - Read 1000 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
,D/TCMD    (  401): Listening for incoming client connection request
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1203618992
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/Tethering( 1024): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): Network connection established
,D/WifiStateMachine( 1024): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1024): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1024): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1024): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1024): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1024): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-30ms what=147462 obj=android.net.wifi.StateChangeResult@4482ad00 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131101
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-23ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43eff2b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1024): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427eb4c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427eb4c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  401): NL - Read 56 bytes from update socket.
D/TCMD    (  401): NL - message type is RTM_NEWLINK
D/TCMD    (  401): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 fe
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 fe
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 b8
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 b8
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 10
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 10
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fc
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 fc
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1024): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
,D/WifiP2pService( 1024): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): handleMessage: X
,D/TCMD    (  401): NL - Read 60 bytes from update socket.
D/TCMD    (  401): NL - ignore NL message, type = 20
,D/TCMD    (  401): Listening for incoming client connection request
,D/WifiStateMachine( 1024): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
,D/WifiStateMachine( 1024): ObtainingIpState{ when=-4ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
,D/WifiStateMachine( 1024): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): DHCP successful
,D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1024): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1024): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1024): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState enter
,D/WifiStateMachine( 1024): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=151572
D/WifiStateMachine( 1024): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1024): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=135190
D/WifiStateMachine( 1024): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1024): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1024): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1024): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1024): CaptivePortalCheckState enter
,D/WifiStateMachine( 1024): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1024): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1024): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1024): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1024): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131092
,D/WifiStateMachine( 1024): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1024): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1024): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1024): WiFi NOT Tethered!
,E/ConnectivityService( 1024): Unexpected mtu value: android.net.wifi.WifiStateTracker@4213d140
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/WifiStateMachine( 1024): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1024): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131092
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): processMsg: DefaultState
,I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1024): handleMessage: X
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1024): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1024): WiFi NOT Tethered!
,E/ConnectivityService( 1024): Unexpected mtu value: android.net.wifi.WifiStateTracker@4213d140
,D/ConnectivityService( 1024): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/CheckinService( 1411): Checkin interval check for package: unspecified last checkin: 1452015094286 min interval config: 0 actual interval: 349077
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1411): Checking schedule, now: 1452015443379 next: 1452015124258
,I/CheckinService( 1411): active receiver: enabled
,I/CheckinService( 1411): Preparing to send checkin request
,I/EventLogService( 1411): Accumulating logs since 1452015089800
,I/CheckinRequestBuilder( 1411): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1411): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1367): GC_EXPLICIT freed 1652K, 40% free 10343K/17224K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 1024): GC_EXPLICIT freed 1728K, 65% free 18168K/51168K, paused 5ms+9ms, total 94ms
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1024): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4298 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4298): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4298): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4298): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4298): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4298): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4298): install
,I/MultiDex( 4298): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4298): loading existing secondary dex files
,I/MultiDex( 4298): load found 3 secondary dex files
,I/MultiDex( 4298): install done
,D/dalvikvm( 4298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4298): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4298): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4298): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4298): VFY: unable to resolve instance field 36
,D/dalvikvm( 4298): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4298): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4298): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4298): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4298): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe2f10
,D/dalvikvm( 4298): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe2f10
,D/dalvikvm( 4298): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe2f10, skipping init
D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe2f10
,D/dalvikvm( 4298): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe2f10
,V/JNIHelp ( 4298): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe2f10
,D/dalvikvm( 4298): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fe2f10
D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe2f10
,D/dalvikvm( 4298): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe2f10
,I/ProviderInstaller( 4298): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1242): callingUid 10022, callindPid: 1242
,D/LocationInitializer( 1411): Restart initialization of location
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1242): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1242): No location to return for getLastLocation()
,W/FusedLocationProvider( 1242): location=null
,I/dalvikvm( 4298): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4298): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4298): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4298): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4298): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4298): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4298): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4298): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4298): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4298): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4298): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4298): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4298): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4298): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb517d000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb517d000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=2805090519
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4298): Install completed successfully. count=14 extracted=0
,D/ConnectivityService( 1024): NetTransition Wakelock for ConnectedState released by timeout
D/dalvikvm( 4298): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42201f60
D/dalvikvm( 4298): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42201f60
D/dalvikvm( 4298): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42201f60, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=405219611
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4298): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4342): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4298): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4298): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 4298): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4298): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4298): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4298): Local Branch: 
I/Adreno-EGL( 4298): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4298): Local Patches: NONE
I/Adreno-EGL( 4298): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4298): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4298): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4298): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4298): Local Branch: 
I/Adreno-EGL( 4298): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4298): Local Patches: NONE
I/Adreno-EGL( 4298): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4298): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4298): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4298): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4298): Local Branch: 
I/Adreno-EGL( 4298): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4298): Local Patches: NONE
I/Adreno-EGL( 4298): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4298): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4298): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4298): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4298): Local Branch: 
I/Adreno-EGL( 4298): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4298): Local Patches: NONE
I/Adreno-EGL( 4298): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4298): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1411): Classify the device as Phone.
,V/NativeCrypto( 1411): SSL shutdown failed: ssl=0x6c8e01d8: I/O error during system call, Connection timed out
,D/dalvikvm( 1411): GC_CONCURRENT freed 1869K, 30% free 12082K/17224K, paused 5ms+9ms, total 66ms
,I/CheckinTask( 1411): Sending checkin request (11629 bytes)
,I/jxcore-log( 4025): TAP version 13
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # multiplex can send data
I/jxcore-log( 4025): 
,I/CheckinRequestBuilder( 1411): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1411): Failed to find provider info for com.google.android.wearable.settings
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1024): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/PollingManager( 1574): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/PollingManager( 1574): now: 393875 ,futureTime: 16518120
,D/PollingManager( 1574): Polling alarm set to expire at: 16518120 Current Time: 393876
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1024): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1303): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
I/openssl ( 4101): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4101): Crypto mode 0 already enabled
,E/ActivityThread( 1574): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1574): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1574): now: 393919 ,futureTime: 16518120
D/PollingManager( 1574): Polling alarm set to expire at: 16518120 Current Time: 393919
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1574): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1574): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1574): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1574): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1574): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1574): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1574): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/OtaApp  ( 1574): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1574): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1574): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1574): [debug] > CusSM.onRadioUp
,D/MobileConnectivityChangeReceiver( 4147): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/OtaApp  ( 1574): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4147): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1574): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1574): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1574): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1574): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.Environment( 3506): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/OtaApp  ( 1574): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.UploadsManager( 3506): num queued entries: 0
,I/iu.UploadsManager( 3506): num updated entries: 0
,I/iu.SyncManager( 3506): NEXT; no task
,I/CheckinService( 1411): Checkin interval check for package: unspecified last checkin: 1452015094286 min interval config: 0 actual interval: 352201
,I/iu.Environment( 1411): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/dalvikvm( 3506): GC_CONCURRENT freed 646K, 5% free 16465K/17224K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 3506): WAIT_FOR_CONCURRENT_GC blocked 22ms
I/iu.UploadsManager( 1411): num queued entries: 0
I/dalvikvm-heap( 3506): Grow heap (frag case) to 19.848MB for 1821008-byte allocation
I/iu.UploadsManager( 1411): num updated entries: 0
,I/iu.SyncManager( 1411): NEXT; no task
,I/openssl ( 4101): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4101): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4147): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4147): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinRequestBuilder( 1411): Classify the device as Phone.
,D/WifiStateMachine( 1024): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1024): handleMessage: E msg.what=131215
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1024): handleMessage: X
,D/dalvikvm( 3506): GC_FOR_ALLOC freed 50K, 5% free 18196K/19004K, paused 12ms, total 12ms
,D/ConnectivityService( 1024): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1024):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
I/iu.Environment( 3506): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/ConnectivityService( 1024): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
I/CheckinService( 1411): Checkin interval check for package: unspecified last checkin: 1452015094286 min interval config: 0 actual interval: 352282
,I/CheckinTask( 1411): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1411): Checking schedule, now: 1452015446578 next: 1452608516574
,I/CheckinService( 1411): active receiver: disabled
,I/CheckinService( 1411): Checking schedule, now: 1452015446593 next: 1452608516574
,I/CheckinService( 1411): active receiver: disabled
,D/DEBUG   ( 1574): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/CheckinService( 1411): Recording last checkin time for package unspecified as 1452015446598
,W/ContextImpl( 1574): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1574): bindWebServices(): registering our AIDL callback...
I/SundryService( 1574): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1574): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1574): onServiceConnected()
,D/GetNotificationsWS( 1574): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1574): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1574): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1574): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1574): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1574): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1574): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1574): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1574): onServiceConnected()
D/GetNotificationsWS( 1574): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1574): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1574): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1574): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1024): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1574
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1574): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1574): [info] > Updatetime from metadata: 10
,D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1574): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1574): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1574): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1574): [info] > Updatetime from metadata: 10
,D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1574): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1574): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1574): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1574): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1024): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1574
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/SFPerfTracer(  277):      triggers: (rate: 2:27) (compose: 0:4) (post: 0:1) (render: 0:5) (0:110 frames) (1:555)
D/SFPerfTracer(  277):        layers: (0:12) (FocusedStackFrame: 0:10)* (StatusBar: 0:212)* (NavigationBar: 0:38)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:26)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:5)* 
D/OtaApp  ( 1574): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1574): [info] > Updatetime from metadata: 10
D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1574): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1574): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1574): [info] > Updatetime from metadata: 10
D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1574): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1574): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1574): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1574): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4025): showStatusIcon on inactive InputConnection
D/OtaApp  ( 1574): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1024): Activity reported stop, but no longer stopping: ActivityRecord{428caee0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
I/LaunchCheckinHandler( 1024): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,120
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1242): GC_EXPLICIT freed 1220K, 35% free 11287K/17224K, paused 4ms+8ms, total 41ms
,I/PhenotypeConfigurator( 1242): Scheduling Phenotype for one-off execution 160 seconds from now (1452015447044)
,D/GetConfigurationSnapshotOperation( 1242): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1242): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1242): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1242): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1242): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1242): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1242): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1242): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1242): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1024): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1085): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1310): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1310): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/dalvikvm( 1242): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1242): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1242): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1242): GC_CONCURRENT freed 1726K, 34% free 11532K/17224K, paused 3ms+7ms, total 36ms
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/ActivityManager( 1024): Killing 3940:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4025): ok 1 String should be length:200
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/ActivityManager( 1024): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4420 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
,I/InputReader( 1024): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
I/Launcher( 1329): Deferring update until onResume
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
I/Launcher( 1329): Deferring update until onResume
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
,I/GCoreNlp( 1242): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4420): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4420): MmsConfig.loadMmsSettings
I/Babel   ( 4420): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4420): MmsConfig.loadFromDatabase
,E/Babel   ( 4420): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4420): MmsConfig.loadFromResources
,E/Babel   ( 4420): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4420): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1024): GC_EXPLICIT freed 1460K, 65% free 18177K/51168K, paused 3ms+9ms, total 89ms
,I/ActivityManager( 1024): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4457 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1024): Killing 3524:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4476 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 4101:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2335): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1024): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4494 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 4128:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4457): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4494): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4494): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4494): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2335): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
,I/dalvikvm( 4494): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4494): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4494): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4494): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4494): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4494): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4494): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4494): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4494): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4494): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4494): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4494): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4494): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4494): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4494): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1024): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4528 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4494): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4494): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4494): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4494): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4494): Skipping gmscore version check
,I/dalvikvm( 4494): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4494): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1024): Killing 4147:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1411): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1411): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1411): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4528): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ff33e8, skipping init
I/openssl ( 4528): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4528): Crypto mode 0 already enabled
,I/ActivityManager( 1024): Killing 4160:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4494): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4494): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/jxcore-log( 4025): # basic
I/jxcore-log( 4025): 
,I/Icing   ( 1411): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1411): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,D/dalvikvm( 1411): GC_CONCURRENT freed 2029K, 31% free 11995K/17224K, paused 4ms+5ms, total 44ms
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452015455
,D/CaptivePortalTracker( 1024): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1024): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1024): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1024): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1024): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1024): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1024): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1024): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 2 sane
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # another
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 3 sane
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 4 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 5 null
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 6 (unnamed assert)
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 7 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 8 should not throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 9 (unnamed assert)
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 10 (unnamed assert)
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 11 should not throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 12 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 13 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4025): 
,V/AlarmManager( 1024): sending alarm Alarm{42989ff0 type 3 android}
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 14 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # failed to get mobile documents path
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 15 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 16 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 17 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 18 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #init should register the networkChanged event
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 19 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should throw on null device name
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 20 should throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 21 should throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 22 should throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 23 should throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should throw on negative port
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 24 should throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should throw on too large port
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,V/AlarmManager( 1024): sending alarm Alarm{420f1e78 type 3 android}
,I/jxcore-log( 4025): ok 25 should throw
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 26 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 27 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 28 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 29 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 30 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 31 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 32 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 33 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 34 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 35 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 36 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 37 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 38 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 39 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 40 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 41 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 42 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,V/AlarmManager( 1024): sending alarm Alarm{42930ac8 type 3 android}
,I/jxcore-log( 4025): ok 43 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ok 44 should be equal
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # setup
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): # teardown
I/jxcore-log( 4025): 
,I/dalvikvm( 4025): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4025): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4025): Shutting down VM
,W/dalvikvm( 4025): threadid=1: thread exiting with uncaught exception (group=0x4171cd40)
E/AndroidRuntime( 4025): FATAL EXCEPTION: main
E/AndroidRuntime( 4025): Process: com.test.thalitest, PID: 4025
E/AndroidRuntime( 4025): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4025): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4025): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4025): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4025): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4025): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4025): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4025): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4025): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4025): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4025): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4025): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4025): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4025): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4025): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4025): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4025): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 4025): Sending signal. PID: 4025 SIG: 9
,I/ActivityManager( 1024): Process com.test.thalitest (pid 4025) has died.
,I/WindowState( 1024): WIN DEATH: Window{420f41c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1024): Client connection lost with reason: 4
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1,
,V/AlarmManager( 1024): sending alarm Alarm{42875f90 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{43d44bf0 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42648e70 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{421abe50 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428a5728 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{429a63d0 type 2 android}
,D/ConnectivityService( 1024): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1024): sending alarm Alarm{429b0628 type 1 com.android.deskclock}
,D/ConnectivityService( 1024): Done.
,I/ActivityManager( 1024): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4593 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1024): Setting timer for 720seconds
,I/ActivityManager( 1024): Killing 4173:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1024): sending alarm Alarm{42250218 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4232d660 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428b3ee0 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{429b0678 type 2 android}
,V/AlarmManager( 1024): sending alarm Alarm{433e33d8 type 0 com.google.android.gms}
,I/EventLogService( 1411): Aggregate from 1452015443401 (log), 1452014101083 (data)
,V/AlarmManager( 1024): sending alarm Alarm{421fc518 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428ee868 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4333ab90 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{4239c940 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42247078 type 2 com.google.android.gms}
,I/GoogleURLConnFactory( 1242): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1242): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/dalvikvm( 1367): GC_EXPLICIT freed 930K, 40% free 10337K/17224K, paused 2ms+4ms, total 45ms
,D/ConnectivityService( 1024): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/PhenotypeConfigurator( 1242): Server returned 404
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{444d89f8 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4353f260 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{43327ae8 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4281e190 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{43dfd018 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{428a9928 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428d7668 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4292e7e0 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{444e3a80 type 2 android}
,D/ConnectivityService( 1024): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1024): sending alarm Alarm{444e3b58 type 1 com.android.deskclock}
,D/ConnectivityService( 1024): Done.
,D/ConnectivityService( 1024): Setting timer for 720seconds
,V/AlarmManager( 1024): sending alarm Alarm{42855230 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42c96148 type 3 android}
,I/ProcessStatsService( 1024): Prepared write state in 45ms
,I/ProcessStatsService( 1024): Prepared write state in 20ms
,I/ProcessStatsService( 1024): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-55-32.bin
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{4483c1c8 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{432e8360 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{43da5618 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428287e0 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4421dce0 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4660): 
D/AndroidRuntime( 4660): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4660): CheckJNI is OFF
D/dalvikvm( 4660): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4660): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4660): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4660): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4660): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4660): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4660): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4660): failed to load memtrack module: -2
D/AndroidRuntime( 4660): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1024): Force stopping com.test.thalitest appid=10516 user=-1: uninstall pkg
I/ActivityManager( 1024):   Force finishing activity ActivityRecord{41fe0988 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings( 1024): Skipping PackageSetting{422c8aa0 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1024): Force stopping com.test.thalitest appid=10516 user=0: pkg removed
D/dalvikvm( 2299): GC_EXPLICIT freed 5342K, 44% free 9649K/17224K, paused 2ms+5ms, total 40ms
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
I/InputReader( 1024): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
D/dalvikvm( 2335): GC_EXPLICIT freed 3021K, 43% free 9824K/17224K, paused 2ms+3ms, total 115ms
D/dalvikvm( 1329): GC_EXPLICIT freed 3340K, 33% free 11596K/17224K, paused 2ms+4ms, total 132ms
I/Launcher( 1329): Deferring update until onResume
D/dalvikvm( 1411): GC_EXPLICIT freed 234K, 31% free 11901K/17224K, paused 4ms+6ms, total 158ms
W/SQLiteConnectionPool( 1411): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1024): GC_EXPLICIT freed 1986K, 65% free 18170K/51168K, paused 5ms+10ms, total 149ms
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452017231
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
W/GeofencerStateMachine( 1242): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 4457): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
I/Launcher( 1329): Deferring update until onResume
I/InternalIcingCorporaPro( 2335): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1024): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4691 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452017232
D/BackupManagerService( 1024): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1024): removePackageParticipantsLocked: uid=10516 #1
I/InternalIcingCorporaPro( 2335): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
D/dalvikvm( 1024): GC_EXPLICIT freed 749K, 65% free 18053K/51168K, paused 5ms+14ms, total 183ms
D/AndroidRuntime( 4660): Shutting down VM
D/dalvikvm( 4660): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 4691): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1024): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4713 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4691): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4494): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4494): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4494): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1411): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1411): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1411): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1411): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1411): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1411): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1411): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1367): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1367): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1411): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1411): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1411): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1411): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 1024): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4744 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1411): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1411): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1411): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Icing   ( 1411): doRemovePackageData com.test.thalitest
V/AlarmManager( 1024): sending alarm Alarm{42680368 type 3 android}
V/AlarmManager( 1024): sending alarm Alarm{42661178 type 3 com.google.android.gms}
V/AlarmManager( 1024): sending alarm Alarm{426610b0 type 2 com.motorola.ccc.cce}
D/gH_CompatibleDatabase( 1411): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1411): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1411): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1411): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1411): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1411): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1024): Killing 4298:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/SQLiteLog( 2299): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2299): Error inserting state=event=am_kill pid=4298 process=com.google.android.gms.unstable reason=empty+%239 selectadj=15 timestamp=1452017232755 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2299): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2299): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2299): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2299): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2299): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Documents( 4744): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4744): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4744): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4744): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4744): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4744): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4744): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4744): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4744): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4744): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4744): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4744): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4744): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4744): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4744): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4744): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4744): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4744): Shutting down VM
W/dalvikvm( 4744): threadid=1: thread exiting with uncaught exception (group=0x4171cd40)
I/ActivityManager( 1024): Killing 4420:com.google.android.talk/u0a70 (adj 15): empty #9
E/AndroidRuntime( 4744): FATAL EXCEPTION: main
E/AndroidRuntime( 4744): Process: com.android.documentsui, PID: 4744
E/AndroidRuntime( 4744): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4744): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4744): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4744): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4744): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4744): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4744): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4744): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4744): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4744): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4744): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4744): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4744): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4744): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4744): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4744): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4744): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4744): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4744): 	... 10 more
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 4744): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1024): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4766 uid=10020 gids={50020, 1028, 1015, 1023}
E/SQLiteLog( 2299): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2299): Error inserting state=event=am_kill pid=4420 process=com.google.android.talk reason=empty+%239 selectadj=15 timestamp=1452017232794 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2299): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2299): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2299): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2299): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2299): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4744): Sending signal. PID: 4744 SIG: 9
I/ActivityManager( 1024): Killing 4593:com.android.deskclock/u0a15 (adj 15): empty #9
E/DropBoxManagerService( 1024): Can't write: system_app_crash
E/DropBoxManagerService( 1024): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1024): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1024): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1024): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1024): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1024): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1024): 	... 5 more
D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 23ms
W/ContextImpl( 1286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1024): Process com.android.documentsui (pid 4744) has died.
D/CCE     ( 1574): Registering with Alarm Manager to restart CCE
E/SQLiteLog( 2299): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms

```
