#### Test 539786637913587_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{420bee80 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4084): 
D/AndroidRuntime( 4084): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4084): CheckJNI is OFF
D/dalvikvm( 4084): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4084): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4084): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4084): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4084): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4084): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4084): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4084): failed to load memtrack module: -2
D/AndroidRuntime( 4084): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4084
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4100 uid=10492 gids={50492, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4084): Shutting down VM
D/dalvikvm( 4084): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4100): Binding Chromium to main looper Looper (main, tid 1) {41f97d68}
I/LibraryLoader( 4100): Expected native library version number "",actual native library version number ""
I/chromium( 4100): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4100): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41fe8158:true
I/Adreno-EGL( 4100): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4100): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4100): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4100): Local Branch: 
I/Adreno-EGL( 4100): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4100): Local Patches: NONE
I/Adreno-EGL( 4100): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4100): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4100): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4100): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4100): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4100): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4100): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4100): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4100): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4100): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4100): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4100): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4100): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4100): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4100): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4100): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4100): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4100): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4100): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4100): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4100): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4100): Enabling debug mode 0
,W/AwContents( 4100): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4100): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,374
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +348ms (total +374ms)
,D/JsMessageQueue( 4100): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4100): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f9c038
,D/dalvikvm( 4100): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f9c038
D/jxcore_app_log( 4100): JniHelper::setJavaVM(0x415e5fa8), pthread_self() = 1614409664
,D/JX-Cordova( 4100): jxcore cordova android initializing
,D/dalvikvm( 4100): GC_CONCURRENT freed 2790K, 17% free 14387K/17224K, paused 3ms+4ms, total 52ms
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 218K, 17% free 14366K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 188K, 17% free 14394K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 16.229MB for 146998-byte allocation
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 257K, 17% free 14442K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 16.346MB for 220492-byte allocation
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 373K, 18% free 14518K/17584K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 16.526MB for 330734-byte allocation
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 579K, 19% free 14642K/17908K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 16.804MB for 496096-byte allocation
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 879K, 20% free 14821K/18396K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 17.215MB for 744140-byte allocation
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 1301K, 22% free 15082K/19124K, paused 28ms, total 28ms
,D/dalvikvm( 4100): GC_CONCURRENT freed 1672K, 20% free 15457K/19124K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4100): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 404K, 20% free 15419K/19124K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 18.687MB for 1674304-byte allocation
,D/dalvikvm( 4100): GC_CONCURRENT freed 1751K, 23% free 15998K/20760K, paused 2ms+4ms, total 43ms
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 1351K, 23% free 16075K/20760K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 20.126MB for 2511452-byte allocation
,D/dalvikvm( 4100): GC_CONCURRENT freed 318K, 21% free 18399K/23216K, paused 5ms+4ms, total 46ms
,D/dalvikvm( 4100): GC_CONCURRENT freed 4346K, 27% free 17060K/23216K, paused 1ms+7ms, total 47ms
,D/dalvikvm( 4100): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/dalvikvm-heap( 4100): Grow heap (frag case) to 22.285MB for 3767174-byte allocation
,D/dalvikvm( 4100): GC_CONCURRENT freed 560K, 24% free 20562K/26896K, paused 4ms+5ms, total 69ms
,D/dalvikvm( 4100): GC_FOR_ALLOC freed 2841K, 34% free 17998K/26896K, paused 27ms, total 27ms
,W/jxcore-log( 4100): Initializing JXcore engine
,W/jxcore-log( 4100): JXcore engine is ready
,D/dalvikvm( 4100): GC_CONCURRENT freed 326K, 24% free 20660K/26896K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4100): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4100): Starting JXcore engine
,W/jxcore-log( 4100): Platform android
W/jxcore-log( 4100): 
,W/jxcore-log( 4100): Process ARCH arm
W/jxcore-log( 4100): 
,I/jxcore-log( 4100): JXcore Cordova bridge is ready!
I/jxcore-log( 4100): 
,W/jxcore-log( 4100): JXcore engine is started
,I/chromium( 4100): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4100): Toggling radios to true
I/jxcore-log( 4100): 
,D/BluetoothAdapter( 4100): enable(): BT is already enabled..!
D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=4100, uid=10492
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 4100): Radios toggled
I/jxcore-log( 4100): 
,I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273):  STA Disconnected !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
,D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1020): WiFi NOT Tethered!
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  458): NL - Read 60 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 21
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1020): connected time updated 388995
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1020): DisconnectingState
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x611d9d20 clazz=0x60f00001 iface=wlan0 mask=0x3
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1356): Read error: ssl=0x62d5f7c8: I/O error during system call, Connection timed out
V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x62d5f7c8: I/O error during system call, Broken pipe
,E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
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
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1242): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1242): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1242): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1242): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1242): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1242): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1164): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1164): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,I/wpa_supplicant( 1164): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1164): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  458): NL - Read 312 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 88 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 80 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 80 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 1164): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221096624
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@444535f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421f38c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421f38c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
,D/WifiP2pService( 1020): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 0c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 0c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 fc
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 fc
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiP2pService( 1020): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiP2pService( 1020): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4446b5c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4446b5c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4446b5c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): handleMessage: X
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4100): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4100): 
,I/jxcore-log( 4100): my name is : motorola-XT1039_PT9097
I/jxcore-log( 4100): 
,I/jxcore-log( 4100): attempting to connect to test coordinator
I/jxcore-log( 4100): 
,I/jxcore-log( 4100): check test folder
I/jxcore-log( 4100): 
,I/jxcore-log( 4100): found test : ./testFindPeers.js
I/jxcore-log( 4100): 
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1297): Active network info is not available
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/jxcore-log( 4100): found test : ./testReConnect.js
I/jxcore-log( 4100): 
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1297): Active network info is not available
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/jxcore-log( 4100): found test : ./testSendData.js
I/jxcore-log( 4100): 
,D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4195 uid=10030 gids={50030, 3003, 1028, 1015}
,I/jxcore-log( 4100): Test app app.js loaded
I/jxcore-log( 4100): 
,V/MmsConfig( 4195): mnc/mcc: 
,I/jxcore-log( 4100): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4100): 
V/MmsConfig( 4195): tag: bool value: enabledMMS - true
V/MmsConfig( 4195): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4195): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4195): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4195): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4195): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4195): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4195): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4195): tag: int value: recipientLimit - 20
V/MmsConfig( 4195): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4195): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4195): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4195): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4195): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4195): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4195): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4195): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4195): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/Choreographer( 4100): Skipped 206 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4100): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4222 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 3847:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  275): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 22ms
,D/dalvikvm( 1020): GC_EXPLICIT freed 1432K, 65% free 18052K/50664K, paused 17ms+15ms, total 129ms
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4222): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4222): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4236 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3914:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4249 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3930:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4249): Binding Chromium to main looper Looper (main, tid 1) {41f90c88}
,I/LibraryLoader( 4249): Expected native library version number "",actual native library version number ""
,I/chromium( 4249): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4249): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4249): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4249): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4249): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4249): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4249): Local Branch: 
I/Adreno-EGL( 4249): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4249): Local Patches: NONE
I/Adreno-EGL( 4249): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4249): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4249): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4249): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4249): Starting up...
,I/ImageResourceManager( 3972): ImageResourceManager: uninitalized
,I/iu.Environment( 3972): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3972): SYNC; picasa accounts
D/TCMD    (  458): NL - Read 60 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 20
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
I/ActivityManager( 1020): Killing 3946:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1404): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1404): num queued entries: 0
,I/iu.UploadsManager( 1404): num updated entries: 0
,I/iu.SyncManager( 1404): NEXT; no task
,I/iu.UploadsManager( 3972): num queued entries: 0
,I/iu.UploadsManager( 3972): num updated entries: 0
,I/iu.SyncManager( 3972): NEXT; no task
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3972): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,I/jxcore-log( 4100): DBG, CoordinatorConnector connect called
I/jxcore-log( 4100): 
,I/jxcore-log( 4100): Coordinator is now connected to the server!
I/jxcore-log( 4100): 
,I/chromium( 4100): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
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
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine( 1020): handleMessage: X
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1020): WiFi NOT Tethered!
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4206d388
D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1242): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
I/ModemStatsDSDetect( 1242): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1242): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
V/ConnectivityService( 1020): WiFi NOT Tethered!
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4206d388
,I/CheckinService( 1404): Checkin interval check for package: unspecified last checkin: 1450442750558 min interval config: 0 actual interval: 378721
D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1242): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1242): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1242): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1404): Checking schedule, now: 1450443129294 next: 1450442780501
,I/CheckinService( 1404): active receiver: enabled
,I/CheckinService( 1404): Preparing to send checkin request
,I/EventLogService( 1404): Accumulating logs since 1450442747152
,I/CheckinRequestBuilder( 1404): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1404): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4347 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4347): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4347): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4347): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4347): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4347): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4347): install
,I/MultiDex( 4347): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4347): loading existing secondary dex files
,I/MultiDex( 4347): load found 3 secondary dex files
,I/MultiDex( 4347): install done
,D/dalvikvm( 4347): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4347): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4347): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4347): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4347): VFY: unable to resolve instance field 36
,D/dalvikvm( 4347): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4347): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4347): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4347): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4347): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4347): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f96ca0
,D/dalvikvm( 4347): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f96ca0
,D/dalvikvm( 4347): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f96ca0, skipping init
,D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f96ca0
D/dalvikvm( 4347): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f96ca0
,V/JNIHelp ( 4347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f96ca0
,D/dalvikvm( 4347): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f96ca0
D/dalvikvm( 4347): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f96ca0
,D/dalvikvm( 4347): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f96ca0
,I/ProviderInstaller( 4347): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1356): Proximity feature is not enabled.
,D/LocationInitializer( 1404): Restart initialization of location
,D/WearableService( 1223): callingUid 10022, callindPid: 1223
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1223): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
,I/dalvikvm( 4347): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4347): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4347): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4347): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4347): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4347): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4347): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4347): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4347): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4347): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4347): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4347): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4347): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4347): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4347): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5233000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5233000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1119191969
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4347): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42185498
D/dalvikvm( 4347): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42185498
,D/dalvikvm( 4347): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42185498, skipping init
,D/NativeLibraryUtils( 4347): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,W/Settings( 4347): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4347): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4387): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4347): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4347): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
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
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1943603651
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1404): Classify the device as Phone.
,V/NativeCrypto( 1404): SSL shutdown failed: ssl=0x6c103578: I/O error during system call, Connection timed out
,I/CheckinTask( 1404): Sending checkin request (11624 bytes)
,I/CheckinRequestBuilder( 1404): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1404): Failed to find provider info for com.google.android.wearable.settings
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): now: 422063 ,futureTime: 24913797
,D/PollingManager( 1562): Polling alarm set to expire at: 24913797 Current Time: 422064
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/openssl ( 3992): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3992): Crypto mode 0 already enabled
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1356): GC_EXPLICIT freed 1395K, 41% free 10330K/17224K, paused 2ms+4ms, total 98ms
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): now: 422106 ,futureTime: 24913797
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1562): Polling alarm set to expire at: 24913797 Current Time: 422109
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 1562): GC_CONCURRENT freed 1961K, 38% free 10756K/17224K, paused 4ms+5ms, total 40ms
,D/dalvikvm( 1562): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1223): GC_CONCURRENT freed 1696K, 33% free 11588K/17224K, paused 4ms+16ms, total 106ms
,I/iu.Environment( 3972): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,I/CheckinService( 1404): Checkin interval check for package: unspecified last checkin: 1450442750558 min interval config: 0 actual interval: 381858
,I/iu.UploadsManager( 3972): num queued entries: 0
,I/iu.UploadsManager( 3972): num updated entries: 0
,I/iu.Environment( 1404): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3972): NEXT; no task
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 3972): GC_CONCURRENT freed 623K, 5% free 16458K/17224K, paused 2ms+3ms, total 30ms
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,I/iu.UploadsManager( 1404): num queued entries: 0
,I/iu.UploadsManager( 1404): num updated entries: 0
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,I/iu.SyncManager( 1404): NEXT; no task
I/openssl ( 3992): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3992): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,I/CheckinRequestBuilder( 1404): Classify the device as Phone.
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/dalvikvm( 3972): GC_FOR_ALLOC freed 35K, 5% free 16425K/17224K, paused 15ms, total 17ms
,I/dalvikvm-heap( 3972): Grow heap (frag case) to 19.809MB for 1821008-byte allocation
D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/iu.Environment( 3972): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinTask( 1404): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1404): Checkin interval check for package: unspecified last checkin: 1450442750558 min interval config: 0 actual interval: 381950
I/CheckinService( 1404): Checking schedule, now: 1450443132509 next: 1451036202504
,I/CheckinService( 1404): active receiver: disabled
,D/dalvikvm( 3972): GC_FOR_ALLOC freed 7K, 5% free 18200K/19004K, paused 19ms, total 19ms
,I/CheckinService( 1404): Checking schedule, now: 1450443132527 next: 1451036202504
,I/CheckinService( 1404): active receiver: disabled
,D/CheckinService( 1404): Recording last checkin time for package unspecified as 1450443132530
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
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
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SFPerfTracer(  274):      triggers: (rate: 2:34) (compose: 0:4) (post: 0:1) (render: 0:6) (0:113 frames) (1:555)
D/SFPerfTracer(  274):        layers: (0:13) (FocusedStackFrame: 1:10)* (StatusBar: 0:212)* (NavigationBar: 0:42)* (com.android.systemui.ImageWallpaper: 0:6)* (com.android.launcher/com.android.launcher2.Launcher: 0:10)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:4)* 
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4100): showStatusIcon on inactive InputConnection
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1020): Activity reported stop, but no longer stopping: ActivityRecord{4281fb40 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
I/LaunchCheckinHandler( 1020): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,111
,D/dalvikvm( 1020): GC_EXPLICIT freed 1133K, 65% free 17984K/50664K, paused 4ms+9ms, total 91ms
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/dalvikvm( 4100): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported,
W/dalvikvm( 4100): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4100): VFY: replacing opcode 0x6e at 0x0002,
,D/AndroidRuntime( 4100): Shutting down VM
,W/dalvikvm( 4100): threadid=1: thread exiting with uncaught exception (group=0x416c4d40),
,E/AndroidRuntime( 4100): FATAL EXCEPTION: main
E/AndroidRuntime( 4100): Process: com.test.thalitest, PID: 4100
E/AndroidRuntime( 4100): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4100): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4100): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4100): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4100): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4100): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4100): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4100): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4100): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4100): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4100): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4100): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4100): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4100): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4100): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4100): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4100): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4100): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4100): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 4100): Sending signal. PID: 4100 SIG: 9
,I/ActivityManager( 1020): Process com.test.thalitest (pid 4100) has died.
,I/WindowState( 1020): WIN DEATH: Window{4438f158 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1242): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1242): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1242): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1242): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service,
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4249): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1020): Killing 3891:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/Launcher( 1309): Deferring update until onResume
I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4442 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/Launcher( 1309): Deferring update until onResume
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
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4442): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4442): MmsConfig.loadMmsSettings
I/Babel   ( 4442): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4442): MmsConfig.loadFromDatabase
,E/Babel   ( 4442): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4442): MmsConfig.loadFromResources
,E/Babel   ( 4442): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4442): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4442): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4479 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3506:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4499 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3992:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2307): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4517 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4195:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4479): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4517): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4517): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4517): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4517): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4517): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4517): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4517): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2307): UpdateCorporaTask done [took 238 ms] updated apps [took 238 ms] 
,D/Finsky  ( 4517): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4517): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4517): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4517): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4517): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4517): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4517): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4517): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4517): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4517): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4517): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4552 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4517): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4517): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4517): Skipping gmscore version check
,D/Finsky  ( 4517): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4517): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4517): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4517): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1020): Killing 4222:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1404): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1404): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1404): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4552): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f9d1a8, skipping init
I/openssl ( 4552): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4552): Crypto mode 0 already enabled
,D/dalvikvm( 1404): GC_CONCURRENT freed 2190K, 31% free 12035K/17224K, paused 5ms+5ms, total 51ms
,D/dalvikvm( 1404): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/Finsky  ( 4517): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/dalvikvm( 1404): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Finsky  ( 4517): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1020): Killing 4236:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1404): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1404): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450443141
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1020): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1020): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1020): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1020): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1020): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{444bc2b0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [58:3f:54:73:64:c0]: 0, 0, 0
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1020): sending alarm Alarm{44585520 type 3 android}
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c528 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c1b0 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c528 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c36c rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [58:3f:54:73:64:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c1b0 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 0
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 0
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c8a0 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [e0:db:10:14:e2:c0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c36c rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c1b0 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c1b0 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c528 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c528 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1750): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c528 rs_disc_pending=2
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1020): sending alarm Alarm{4458b3c0 type 3 android}
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38ca5c rs_disc_pending=0
W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1,
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1750): l2cu_get_conn_role 0
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:85:54]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1750): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f38c6e4 rs_disc_pending=2
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1020): sending alarm Alarm{44592920 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{4459fbf0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445a2bc8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445aa148 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445afe28 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444bae10 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{444baa18 type 0 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{444ba620 type 1 com.android.deskclock}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4596 uid=10015 gids={50015, 1028}
,I/EventLogService( 1404): Aggregate from 1450443129312 (log), 1450441722398 (data)
,I/ActivityManager( 1020): Killing 4249:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445c6a88 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445cec78 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d5438 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d65c0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d7748 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d88b0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445d9a38 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445c6b60 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1242): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1242): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1242): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1020): sending alarm Alarm{445dd378 type 3 android}
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1750): l2cu_get_conn_role 1
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1020): sending alarm Alarm{445e1178 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445e29b0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445e3c48 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445e6930 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445eb620 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445ec8d8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445edb90 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445dd450 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{445dd528 type 1 com.android.deskclock}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,V/AlarmManager( 1020): sending alarm Alarm{445dd578 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445dd650 type 3 com.google.android.gms}
,I/ProcessStatsService( 1020): Prepared write state in 9ms
,I/ProcessStatsService( 1020): Prepared write state in 25ms
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-43-01.bin
,D/dalvikvm( 1020): GC_CONCURRENT freed 2047K, 65% free 18212K/50664K, paused 5ms+13ms, total 135ms
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{445eee48 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{445063e0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444e8e20 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444bc2b0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444b8868 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44494e98 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{444879e0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4687): 
D/AndroidRuntime( 4687): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4687): CheckJNI is OFF
D/dalvikvm( 4687): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4687): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4687): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4687): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4687): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4687): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4687): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4687): failed to load memtrack module: -2
D/AndroidRuntime( 4687): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10492 user=-1: uninstall pkg
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{4286efd8 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings( 1020): Skipping PackageSetting{42256ec0 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10492 user=0: pkg removed
D/dalvikvm( 2274): GC_EXPLICIT freed 5454K, 44% free 9650K/17224K, paused 4ms+6ms, total 48ms
D/dalvikvm( 2307): GC_EXPLICIT freed 3490K, 42% free 10076K/17224K, paused 2ms+4ms, total 54ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1309): GC_EXPLICIT freed 3236K, 33% free 11595K/17224K, paused 13ms+4ms, total 132ms
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1404): GC_EXPLICIT freed 1037K, 31% free 11936K/17224K, paused 11ms+4ms, total 81ms
W/SQLiteConnectionPool( 1404): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1020): GC_EXPLICIT freed 848K, 65% free 17966K/50556K, paused 4ms+10ms, total 135ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/Launcher( 1309): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
D/VoicemailCleanupService( 4479): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450444932
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2307): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/Launcher( 1309): Deferring update until onResume
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4719 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450444932
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10492 #1
I/InternalIcingCorporaPro( 2307): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
D/dalvikvm( 1020): GC_EXPLICIT freed 664K, 65% free 18035K/50556K, paused 6ms+12ms, total 195ms
D/AndroidRuntime( 4687): Shutting down VM
D/dalvikvm( 4687): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4719): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 4719): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4748 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
W/ContextImpl( 4748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 17ms
I/dalvikvm( 4517): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4517): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4517): VFY: replacing opcode 0x6e at 0x0013
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
D/ChimeraCfgMgr( 1404): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1404): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1404): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1404): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1404): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1404): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1404): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1356): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1356): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1404): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1404): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1404): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1404): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
V/AlarmManager( 1020): sending alarm Alarm{4254b430 type 2 com.motorola.ccc.cce}
W/FileUtils( 1404): Failed to chmod(/data/data/com.google.android.gms/databases/help_responses.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1404): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4781 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1404): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
E/SQLiteLog( 1404): (3850) statement aborts at 25: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1404): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/dalvikvm( 1404): threadid=50: thread exiting with uncaught exception (group=0x416c4d40)
E/AndroidRuntime( 1404): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1404): Process: com.google.android.gms, PID: 1404
E/AndroidRuntime( 1404): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1404): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1404): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1404): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1404): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1404): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1404): 	at com.google.android.gms.googlehelp.b.b.d(SourceFile:535)
E/AndroidRuntime( 1404): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/AndroidRuntime( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1404): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1404): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1404): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1404): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1404): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1404): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1404): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1404): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4748): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4748): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4748): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4748): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4748): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4748): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4748): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4748): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4748): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4748): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4748): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4748): threadid=11: thread exiting with uncaught exception (group=0x416c4d40)
I/Process ( 1404): Sending signal. PID: 1404 SIG: 9
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
E/AndroidRuntime( 4748): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4748): Process: com.android.keychain, PID: 4748
E/AndroidRuntime( 4748): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4748): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4748): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4748): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4748): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4748): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4748): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4748): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4748): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4748): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
I/Process ( 4748): Sending signal. PID: 4748 SIG: 9
I/ActivityManager( 1020): Process com.google.android.gms (pid 1404) has died.
D/WifiService( 1020): Client connection lost with reason: 4
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
I/ActivityManager( 1020): Process com.android.keychain (pid 4748) has died.
W/ActivityManager( 1020): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20999ms
D/Documents( 4781): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4781): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
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
E/SQLiteDatabase( 4781): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4781): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4781): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4781): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4781): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4781): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4781): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4781): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4781): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4781): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4781): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4781): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4781): Shutting down VM
W/dalvikvm( 4781): threadid=1: thread exiting with uncaught exception (group=0x416c4d40)
D/Documents( 4781): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4781): FATAL EXCEPTION: main
E/AndroidRuntime( 4781): Process: com.android.documentsui, PID: 4781
E/AndroidRuntime( 4781): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4781): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4781): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4781): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4781): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4781): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4781): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4781): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4781): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime( 4781): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4781): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4781): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4781): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4781): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4781): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4781): 	... 10 more
I/ActivityManager( 1020): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4799 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager( 1020): Killing 4347:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4781): Sending signal. PID: 4781 SIG: 9
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4807 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1020): Process com.android.documentsui (pid 4781) has died.
E/SQLiteLog( 2274): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2274): Error inserting state=event=am_kill pid=4347 process=com.google.android.gms.unstable reason=empty+%239 selectadj=15 timestamp=1450444932899 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2274): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2274): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2274): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2274): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2274): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2274): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2274): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2274): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2274): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2274): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2274): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2274): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2274): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2274): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2274): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2274): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
