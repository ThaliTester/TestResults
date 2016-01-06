#### Test 552541413820a6d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager(  989): sending alarm Alarm{43e65db8 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3912): 
D/AndroidRuntime( 3912): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3912): CheckJNI is OFF
D/dalvikvm( 3912): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3912): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3912): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3912): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3912): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3912): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3912): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3912): failed to load memtrack module: -2
D/AndroidRuntime( 3912): Calling main entry com.android.commands.am.Am
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3912
W/WindowManager(  989): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  989): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3928 uid=10518 gids={50518, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3912): Shutting down VM
D/dalvikvm( 3912): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3928): Binding Chromium to main looper Looper (main, tid 1) {41fdafc8}
I/LibraryLoader( 3928): Expected native library version number "",actual native library version number ""
I/chromium( 3928): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3928): Initializing chromium process, renderers=0
D/BluetoothManagerService(  989): Message: 20
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43aa7770:true
I/Adreno-EGL( 3928): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3928): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3928): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3928): Local Branch: 
I/Adreno-EGL( 3928): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3928): Local Patches: NONE
I/Adreno-EGL( 3928): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3928): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3928): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3928): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3928): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3928): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3928): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3928): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3928): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3928): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3928): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3928): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3928): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3928): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3928): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3928): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3928): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3928): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3928): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3928): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3928): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3928): Enabling debug mode 0
,W/AwContents( 3928): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler(  989): Displayed com.test.thalitest/.MainActivity,cp,ca,395
I/ActivityManager(  989): Displayed com.test.thalitest/.MainActivity: +370ms (total +395ms)
W/AwContents( 3928): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3928): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3928): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3928): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdf478
,D/dalvikvm( 3928): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdf478
D/jxcore_app_log( 3928): JniHelper::setJavaVM(0x41631fa8), pthread_self() = 1614812720
,D/JX-Cordova( 3928): jxcore cordova android initializing
,D/dalvikvm( 3928): GC_CONCURRENT freed 2733K, 17% free 14455K/17224K, paused 2ms+2ms, total 47ms
,D/dalvikvm( 3928): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 159K, 17% free 14444K/17224K, paused 24ms, total 25ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 130K, 17% free 14459K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 16.245MB for 96598-byte allocation
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 178K, 17% free 14493K/17320K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 16.325MB for 144892-byte allocation
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 253K, 17% free 14541K/17464K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 16.440MB for 217334-byte allocation
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 369K, 18% free 14616K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 16.617MB for 325996-byte allocation
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 568K, 19% free 14737K/18000K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 16.891MB for 488990-byte allocation
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 866K, 20% free 14914K/18480K, paused 26ms, total 27ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 1286K, 18% free 15171K/18480K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 17.898MB for 1100216-byte allocation
,D/dalvikvm( 3928): GC_CONCURRENT freed 1752K, 21% free 15556K/19556K, paused 1ms+4ms, total 32ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 302K, 21% free 15491K/19556K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 18.735MB for 1650320-byte allocation
,D/dalvikvm( 3928): GC_CONCURRENT freed 1705K, 25% free 16074K/21168K, paused 1ms+3ms, total 31ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 1306K, 24% free 16138K/21168K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 20.153MB for 2475476-byte allocation
,D/dalvikvm( 3928): GC_CONCURRENT freed 1866K, 29% free 16886K/23588K, paused 4ms+9ms, total 53ms
,D/dalvikvm( 3928): GC_CONCURRENT freed 2427K, 28% free 17087K/23588K, paused 2ms+6ms, total 42ms
,D/dalvikvm( 3928): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 547K, 29% free 16921K/23588K, paused 32ms, total 32ms
,I/dalvikvm-heap( 3928): Grow heap (frag case) to 22.098MB for 3713210-byte allocation
,D/dalvikvm( 3928): GC_CONCURRENT freed 2693K, 34% free 18175K/27216K, paused 4ms+3ms, total 49ms
,D/dalvikvm( 3928): GC_FOR_ALLOC freed 762K, 34% free 18092K/27216K, paused 27ms, total 29ms
,W/jxcore-log( 3928): Initializing JXcore engine
,W/jxcore-log( 3928): JXcore engine is ready
,D/dalvikvm( 3928): GC_CONCURRENT freed 372K, 24% free 20738K/27216K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 3928): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 3928): Starting JXcore engine
,W/jxcore-log( 3928): Platform android
W/jxcore-log( 3928): 
,W/jxcore-log( 3928): Process ARCH arm
W/jxcore-log( 3928): 
,I/jxcore-log( 3928): JXcore Cordova bridge is ready!
I/jxcore-log( 3928): 
,W/jxcore-log( 3928): JXcore engine is started
,I/chromium( 3928): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3928): Toggling radios to true
I/jxcore-log( 3928): 
,D/BluetoothAdapter( 3928): enable(): BT is already enabled..!
D/WifiService(  989): New client listening to asynchronous messages
D/WifiService(  989): setWifiEnabled: true pid=3928, uid=10518
,E/WifiService(  989): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine(  989): handleMessage: E msg.what=131145
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
I/jxcore-log( 3928): Radios toggled
I/jxcore-log( 3928): 
D/BluetoothManagerService(  989): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3928): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3928): 
I/jxcore-log( 3928): Perf Test app loaded loaded
I/jxcore-log( 3928): 
I/jxcore-log( 3928): check test folder
I/jxcore-log( 3928): 
I/jxcore-log( 3928): found test : ./testFindPeers.js
I/jxcore-log( 3928): 
,I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  426): NL - Read 1000 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED 
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
D/TCMD    (  426): NL - Read 1000 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 68 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 68 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine(  989): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/Tethering(  989): InitialState.processMessage what=4
,V/ConnectivityService(  989): WiFi NOT Tethered!
D/Tethering(  989): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 3928): found test : ./testSendData.js
I/jxcore-log( 3928): 
,D/WifiStateMachine(  989): invokeExitMethods: ConnectedState
D/WifiStateMachine(  989): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  989): Stopping DHCP and clearing IP
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  989): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  426): NL - Read 60 bytes from update socket.
D/TCMD    (  426): NL - ignore NL message, type = 21
,D/TCMD    (  426): Listening for incoming client connection request
,D/WifiStateMachine(  989): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  989): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  989): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics(  989): connected time updated 390628
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  989): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  989): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService(  989): Attempting to switch to mobile
D/ConnectivityService(  989): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  989): Attempting to switch to ETHERNET
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine(  989): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  989): DisconnectingState
D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131146
D/WifiStateMachine(  989): processMsg: DisconnectingState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147460
D/WifiStateMachine(  989): processMsg: DisconnectingState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): Network connection lost
D/WifiStateMachine(  989): Stopping DHCP and clearing IP
D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  989): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  989): resetConnections(wlan0, 3)
D/NetUtils(  989): android_net_utils_resetConnections in env=0x6121ef10 clazz=0x61a00001 iface=wlan0 mask=0x3
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1365): Read error: ssl=0x63124d40: I/O error during system call, Connection timed out
,V/NativeCrypto( 1365): SSL shutdown failed: ssl=0x63124d40: I/O error during system call, Broken pipe
,D/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  989): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  989): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine(  989): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  989): processMsg: ConnectModeState
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
,I/ModemStatsDSDetect( 1294): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService(  989): Attempting to switch to mobile
D/ConnectivityService(  989): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  989): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1294): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1294): onReceive() - done, currentInetCondition=0
I/Choreographer( 3928): Skipped 113 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3928): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  989): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1294): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1294): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1294): onReceive() - done, currentInetCondition=0
,D/TCMD    (  426): NL - Read 56 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
,I/wpa_supplicant( 1157): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine(  989): handleMessage: E msg.what=147461
D/WifiStateMachine(  989): processMsg: DisconnectedState
E/wpa_supplicant( 1157): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
,D/WifiStateMachine(  989): processMsg: SupplicantStartedState
,D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
,D/WifiStateMachine(  989): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/WifiStateMachine(  989): handleMessage: X
,I/wpa_supplicant( 1157): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1157): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  426): NL - Read 312 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 88 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 68 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 1000 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK,
D/TCMD    (  426): Listening for incoming client connection request
,I/wpa_supplicant( 1157): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  426): NL - Read 80 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 80 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
D/TCMD    (  426): NL - Read 68 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
,D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
,D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  989): processMsg: ConnectModeState
,D/WifiStateMachine(  989): handleMessage: X
,D/Tethering(  989): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering(  989): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine(  989): handleMessage: E msg.what=131101
D/WifiStateMachine(  989): processMsg: DisconnectedState
,D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1157): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  426): NL - Read 1000 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
,D/TCMD    (  426): Listening for incoming client connection request
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
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1199834288
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
,D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147459
,D/WifiStateMachine(  989): processMsg: DisconnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): Network connection established
,D/WifiStateMachine(  989): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  989): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  989): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  989): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine(  989): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  989): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
,D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@432a9ff8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=196612
D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  989): processMsg: L2ConnectedState
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine(  989): Unexpected BatchedScanResults :OK
D/WifiP2pService(  989): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4247d068 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4247d068 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  426): NL - Read 56 bytes from update socket.
D/TCMD    (  426): NL - message type is RTM_NEWLINK
D/TCMD    (  426): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 fc
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 fc
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService(  989): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@431e7a10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@431e7a10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@431e7a10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): handleMessage: E msg.what=147461
D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): handleMessage: X
,D/TCMD    (  426): NL - Read 60 bytes from update socket.
D/TCMD    (  426): NL - ignore NL message, type = 20
,D/TCMD    (  426): Listening for incoming client connection request
,D/WifiStateMachine(  989): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  989): handleMessage: E msg.what=131215
D/WifiStateMachine(  989): processMsg: ObtainingIpState
D/WifiStateMachine(  989): ObtainingIpState{ when=-5ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=196613
,D/WifiStateMachine(  989): processMsg: ObtainingIpState
,D/WifiStateMachine(  989): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  989): processMsg: L2ConnectedState
,D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  989): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
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
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=151572
D/WifiStateMachine(  989): processMsg: VerifyingLinkState
D/WifiStateMachine(  989): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine(  989): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=135190
,D/WifiStateMachine(  989): processMsg: VerifyingLinkState
,D/WifiStateMachine(  989): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  989): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  989): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine(  989): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  989): CaptivePortalCheckState enter
,D/WifiStateMachine(  989): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService(  989): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  989): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  989): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  989): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131092
D/WifiStateMachine(  989): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  989): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  989): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService(  989): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService(  989): WiFi NOT Tethered!
,E/ConnectivityService(  989): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ca0a8
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1294): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1294): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1294): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine(  989): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  989): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine(  989): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  989): handleMessage: X
,D/WifiStateMachine(  989): handleMessage: E msg.what=131092
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
,I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService(  989): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
V/ConnectivityService(  989): WiFi NOT Tethered!
E/ConnectivityService(  989): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ca0a8
,D/ConnectivityService(  989): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1294): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1294): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1294): onReceive() - done, currentInetCondition=0
,D/Tethering(  989): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  989): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1080): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,D/ConnectivityService(  989): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,D/Tethering(  989): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker(  989): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1557): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1557): [debug] > CusSM.onRadioDown
E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
,I/openssl ( 3830): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3830): Crypto mode 0 already enabled
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,I/ActivityManager(  989): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4065 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,D/dalvikvm(  989): GC_EXPLICIT freed 23561K, 65% free 18121K/51100K, paused 3ms+10ms, total 138ms
,V/MmsConfig( 4065): mnc/mcc: 
,V/MmsConfig( 4065): tag: bool value: enabledMMS - true
V/MmsConfig( 4065): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4065): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4065): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4065): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4065): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4065): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4065): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4065): tag: int value: recipientLimit - 20
V/MmsConfig( 4065): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4065): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4065): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4065): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4065): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4065): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4065): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4065): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4065): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager(  989): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4092 uid=10041 gids={50041, 3003}
,I/ActivityManager(  989): Killing 3721:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4092): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4092): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4092): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4092): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  989): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4110 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 3756:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1452109850101 min interval config: 0 actual interval: 380282
,I/CheckinService( 1408): Checking schedule, now: 1452110230392 next: 1452109880071
,I/CheckinService( 1408): active receiver: enabled
,I/CheckinService( 1408): Preparing to send checkin request
,I/EventLogService( 1408): Accumulating logs since 1452109846631
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  989): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  989): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4124 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 3364:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4124): Binding Chromium to main looper Looper (main, tid 1) {41fdef08}
,I/LibraryLoader( 4124): Expected native library version number "",actual native library version number ""
,I/chromium( 4124): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4124): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4124): BLUETOOTH permission is missing!
,W/dalvikvm( 1365): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/Adreno-EGL( 4124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4124): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4124): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4124): Local Branch: 
I/Adreno-EGL( 4124): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4124): Local Patches: NONE
I/Adreno-EGL( 4124): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,E/dalvikvm( 1365): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1365): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1365): VFY: replacing opcode 0x1f at 0x0011
,I/dalvikvm( 1365): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1365): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1365): VFY: replacing opcode 0x6e at 0x003d
,W/chromium( 4124): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4124): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4124): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4124): Starting up...
,I/ImageResourceManager( 3809): ImageResourceManager: uninitalized
,I/iu.Environment( 3809): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager(  989): Killing 3782:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1557): onServiceConnected()
D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 3830): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3830): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4092): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4092): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3809): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/jxcore-log( 3928): Connected to the server!
I/jxcore-log( 3928): 
,I/chromium( 3928): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  989): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4180 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4180): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4180): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4180): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4180): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4180): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4180): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4180): install
,I/MultiDex( 4180): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4180): loading existing secondary dex files
,I/MultiDex( 4180): load found 3 secondary dex files
,I/MultiDex( 4180): install done
,D/dalvikvm( 4180): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4180): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4180): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4180): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4180): VFY: unable to resolve instance field 36
,D/dalvikvm( 4180): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4180): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4180): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4180): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4180): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4180): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4180): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe5ae0
D/dalvikvm( 4180): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe5ae0
,D/dalvikvm( 4180): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe5ae0, skipping init
D/dalvikvm( 4180): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe5ae0
D/dalvikvm( 4180): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe5ae0
,V/JNIHelp ( 4180): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4180): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe5ae0
D/dalvikvm( 4180): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fe5ae0
D/dalvikvm( 4180): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe5ae0
,D/dalvikvm( 4180): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe5ae0
,I/ProviderInstaller( 4180): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1220): callingUid 10022, callindPid: 1220
,E/MDM     ( 1220): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 5167 seconds from now (1452110231326)
D/AuthorizationBluetoothService( 1365): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1365): Proximity feature is not enabled.
,D/LocationInitializer( 1408): Restart initialization of location
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
,I/dalvikvm( 4180): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4180): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4180): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4180): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4180): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4180): VFY: replacing opcode 0x6e at 0x000d
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/dalvikvm( 4180): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4180): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4180): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4180): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4180): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4180): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4180): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4180): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4180): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4180): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4180): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 1220): GC_CONCURRENT freed 1635K, 34% free 11370K/17224K, paused 6ms+7ms, total 60ms
,D/dalvikvm( 1220): GC_EXPLICIT freed 331K, 36% free 11048K/17224K, paused 10ms+4ms, total 57ms
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb539e000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb539e000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3163625113
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4180): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4180): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42212df8
,D/dalvikvm( 4180): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42212df8
,D/dalvikvm( 4180): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42212df8, skipping init
,I/dalvikvm( 3928): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 3928): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3928): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 3928): Shutting down VM
,W/dalvikvm( 3928): threadid=1: thread exiting with uncaught exception (group=0x41710d40)
E/AndroidRuntime( 3928): FATAL EXCEPTION: main
E/AndroidRuntime( 3928): Process: com.test.thalitest, PID: 3928
E/AndroidRuntime( 3928): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3928): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 3928): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 3928): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 3928): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 3928): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 3928): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 3928): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3928): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3928): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3928): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3928): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3928): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 3928): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 3928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 3928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 3928): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  989):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  989): Killing 3349:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 3928): Sending signal. PID: 3928 SIG: 9
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WindowState(  989): WIN DEATH: Window{4448f470 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  989): Client connection lost with reason: 4
,I/SFPerfTracer(  277):      triggers: (rate: 1:29) (compose: 0:4) (post: 0:1) (render: 0:5) (0:108 frames) (1:559)
,D/SFPerfTracer(  277):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:196)* (NavigationBar: 0:33)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:32)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:8)* (ElectronBeam: 0:26)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:5)* 
,I/ActivityManager(  989): Process com.test.thalitest (pid 3928) has died.
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService(  989): Got RemoteException sending setActive(false) notification to pid 3928 uid 10518
,W/Binder  ( 1205): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1205): java.lang.NullPointerException
W/Binder  ( 1205): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1205): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1205): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1205): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 4180): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4224): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4180): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4180): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 97ms
,I/Adreno-EGL( 4180): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4180): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4180): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4180): Local Branch: 
I/Adreno-EGL( 4180): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4180): Local Patches: NONE
I/Adreno-EGL( 4180): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4180): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4180): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4180): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4180): Local Branch: 
I/Adreno-EGL( 4180): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4180): Local Patches: NONE
I/Adreno-EGL( 4180): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4180): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3266389001
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/Tethering(  989): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  989): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1557): now: 421380 ,futureTime: 8160958
,D/PollingManager( 1557): Polling alarm set to expire at: 8160958 Current Time: 421380
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
I/openssl ( 3830): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3830): Crypto mode 0 already enabled
I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1557): now: 421410 ,futureTime: 8160958
D/PollingManager( 1557): Polling alarm set to expire at: 8160958 Current Time: 421410
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1270): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/Tethering(  989): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  989): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/MobileConnectivityChangeReceiver( 4092): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4092): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3809): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/TelephonyProvider( 1250): Column apn id key is 'apn_id'
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1452109850101 min interval config: 0 actual interval: 382531
,D/dalvikvm( 3809): GC_FOR_ALLOC freed 621K, 5% free 16433K/17224K, paused 18ms, total 20ms
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/dalvikvm-heap( 3809): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
,D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3830): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3830): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4092): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4092): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 1557): GC_CONCURRENT freed 2015K, 38% free 10715K/17224K, paused 4ms+3ms, total 37ms
,D/dalvikvm( 3809): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 11ms, total 11ms
,I/iu.Environment( 3809): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1452109850101 min interval config: 0 actual interval: 382628
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
,D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  989): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/dalvikvm(  989): GC_EXPLICIT freed 871K, 65% free 18075K/51100K, paused 4ms+13ms, total 125ms
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  989): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager(  989): Activity reported stop, but no longer stopping: ActivityRecord{428e30b8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/Adreno-EGL( 4180): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4180): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4180): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4180): Local Branch: 
I/Adreno-EGL( 4180): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4180): Local Patches: NONE
I/Adreno-EGL( 4180): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4180): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4180): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4180): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4180): Local Branch: 
I/Adreno-EGL( 4180): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4180): Local Patches: NONE
I/Adreno-EGL( 4180): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,V/NativeCrypto( 1408): SSL shutdown failed: ssl=0x6c3bb5f0: I/O error during system call, Connection timed out
,I/CheckinTask( 1408): Sending checkin request (11803 bytes)
,D/dalvikvm( 1220): GC_CONCURRENT freed 1451K, 33% free 11627K/17224K, paused 2ms+9ms, total 49ms
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,I/CheckinTask( 1408): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1408): Checking schedule, now: 1452110234905 next: 1452703304898
,I/CheckinService( 1408): active receiver: disabled
,I/CheckinService( 1408): Checking schedule, now: 1452110234924 next: 1452703304898
,I/CheckinService( 1408): active receiver: disabled
,D/CheckinService( 1408): Recording last checkin time for package unspecified as 1452110234929
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1365): GC_CONCURRENT freed 1941K, 40% free 10386K/17224K, paused 3ms+4ms, total 37ms
,D/WifiStateMachine(  989): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  989): handleMessage: E msg.what=131215
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
,D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
,D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  989): handleMessage: X
D/ConnectivityService(  989): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  989):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  989): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4124): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  989): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1294): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1080): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1294): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1294): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1294): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
,I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
,I/ActivityManager(  989): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4283 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
,I/Launcher( 1306): Deferring update until onResume
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
,I/Launcher( 1306): Deferring update until onResume
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
,I/Babel   ( 4283): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4283): MmsConfig.loadMmsSettings
I/Babel   ( 4283): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4283): MmsConfig.loadFromDatabase
,E/Babel   ( 4283): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4283): MmsConfig.loadFromResources
W/Settings( 4283): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4283): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4283): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/ActivityManager(  989): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4320 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  989): Killing 3399:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  989): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4341 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 3830:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2291): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  989): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4359 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager(  989): Killing 4065:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4320): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4359): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4359): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4359): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2291): UpdateCorporaTask done [took 203 ms] updated apps [took 202 ms] 
,I/dalvikvm( 4359): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4359): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4359): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4359): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4359): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4359): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4359): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4359): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4359): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4359): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4359): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4359): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4359): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4359): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4359): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager(  989): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4393 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,I/dalvikvm( 4359): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4359): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/Ads     ( 4359): Skipping gmscore version check
,D/Finsky  ( 4359): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4359): [1] Libraries$2.run: Finished loading 1 libraries.
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/dalvikvm( 4359): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4359): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4359): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager(  989): Killing 4092:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1408): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1408): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4393): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41febff0, skipping init
I/openssl ( 4393): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4393): Crypto mode 0 already enabled
,D/Finsky  ( 4359): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4359): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  989): Killing 4110:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1408): GC_CONCURRENT freed 1944K, 31% free 12043K/17224K, paused 3ms+4ms, total 39ms
,I/Icing   ( 1408): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1408): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452110242
,D/CaptivePortalTracker(  989): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  989): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  989): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  989): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  989): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  989): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  989): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  989): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager(  989): sending alarm Alarm{425f8888 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43192280 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43b750c8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{425f5600 type 0 com.google.android.gms}
,V/AlarmManager(  989): sending alarm Alarm{425ef400 type 1 com.android.deskclock}
,I/LaunchCheckinHandler(  989): cleanup(): cleared. Last call was 159927 ms ago
,I/ActivityManager(  989): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4435 uid=10015 gids={50015, 1028}
,I/EventLogService( 1408): Aggregate from 1452110230418 (log), 1452108390129 (data)
,I/ActivityManager(  989): Killing 4124:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 9
,V/AlarmManager(  989): sending alarm Alarm{43d7d298 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43f0a788 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{433e7028 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43d7d370 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
,V/AlarmManager(  989): sending alarm Alarm{43efc6e0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43f1efe0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43b19200 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44454858 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4286e5f8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{429aeea0 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{42a2e700 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{43350660 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{4315b038 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{43d7d448 type 2 com.google.android.gms}
,D/ConnectivityService(  989): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1294): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1294): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1294): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,V/AlarmManager(  989): sending alarm Alarm{444520f8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{441eb1a8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{428960f8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{444521d0 type 1 com.android.deskclock}
,V/AlarmManager(  989): sending alarm Alarm{444522a8 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
,V/AlarmManager(  989): sending alarm Alarm{43a99838 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a953e8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43aa24d0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44162808 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4280c418 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4281f7f8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4281f888 type 3 com.google.android.gms}
,I/ProcessStatsService(  989): Prepared write state in 20ms
,I/ProcessStatsService(  989): Prepared write state in 11ms
,D/dalvikvm(  989): GC_CONCURRENT freed 2090K, 65% free 18225K/51100K, paused 4ms+11ms, total 144ms
,D/dalvikvm(  989): GC_EXPLICIT freed 309K, 65% free 17972K/51100K, paused 4ms+8ms, total 88ms
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{429efb68 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{43e96718 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{43d35170 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{429fd3a8 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{429e5870 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{42909ce0 type 3 android}
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
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{428dbe60 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4530): 
D/AndroidRuntime( 4530): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4530): CheckJNI is OFF
D/dalvikvm( 4530): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4530): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4530): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4530): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4530): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4530): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4530): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4530): failed to load memtrack module: -2
D/AndroidRuntime( 4530): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10518 user=-1: uninstall pkg
W/PackageSettings(  989): Skipping PackageSetting{422a2be0 com.example.hello/10509} due to missing metadata
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10518 user=0: pkg removed
D/dalvikvm( 2258): GC_EXPLICIT freed 5335K, 44% free 9649K/17224K, paused 2ms+5ms, total 39ms
I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1306): GC_EXPLICIT freed 2892K, 33% free 11592K/17224K, paused 2ms+4ms, total 116ms
I/Launcher( 1306): Deferring update until onResume
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
D/dalvikvm(  989): GC_EXPLICIT freed 674K, 65% free 18019K/51080K, paused 5ms+26ms, total 123ms
D/dalvikvm( 1408): GC_EXPLICIT freed 835K, 31% free 11916K/17224K, paused 4ms+5ms, total 144ms
D/dalvikvm(  989): WAIT_FOR_CONCURRENT_GC blocked 9ms
W/SQLiteConnectionPool( 1408): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2291): GC_EXPLICIT freed 4071K, 42% free 10092K/17224K, paused 2ms+6ms, total 88ms
D/dalvikvm(  989): GC_EXPLICIT freed 92K, 65% free 17975K/51080K, paused 14ms+9ms, total 100ms
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
D/VoicemailCleanupService( 4320): Cleaning up data for package: com.test.thalitest
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452112032
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
I/Launcher( 1306): Deferring update until onResume
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/InternalIcingCorporaPro( 2291): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/ActivityManager(  989): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4568 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager(  989):   Scheme: "mms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
D/BackupManagerService(  989): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  989): removePackageParticipantsLocked: uid=10518 #1
D/AndroidRuntime( 4530): Shutting down VM
D/dalvikvm( 4530): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 4ms
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452112032
I/InternalIcingCorporaPro( 2291): UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
W/ActiveOrDefaultContextProvider( 4568): Missing scope.enter somewhere. Returning default context
E/SQLiteDatabase( 4568): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4568): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4568): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4568): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4568): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4568): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4568): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4568): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 4568): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 4568): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 4568): threadid=11: thread exiting with uncaught exception (group=0x41710d40)
E/AndroidRuntime( 4568): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4568): Process: com.google.android.apps.docs, PID: 4568
E/AndroidRuntime( 4568): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4568): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4568): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4568): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4568): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4568): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 4568): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 4568): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 4568): 	at WT.run(AbstractDatabaseInstance.java:411)
I/Process ( 4568): Sending signal. PID: 4568 SIG: 9
E/DropBoxManagerService(  989): Can't write: system_app_crash
E/DropBoxManagerService(  989): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  989): Process com.google.android.apps.docs (pid 4568) has died.

```
