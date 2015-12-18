#### Test 50650278d76d9c3_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1021): sending alarm Alarm{43d57fa0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4052): 
D/AndroidRuntime( 4052): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4052): CheckJNI is OFF
D/dalvikvm( 4052): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4052): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4052): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4052): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4052): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4052): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4052): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4052): failed to load memtrack module: -2
D/AndroidRuntime( 4052): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4052
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4068 uid=10495 gids={50495, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4052): Shutting down VM
D/dalvikvm( 4052): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4068): Binding Chromium to main looper Looper (main, tid 1) {41f35db0}
I/LibraryLoader( 4068): Expected native library version number "",actual native library version number ""
I/chromium( 4068): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4068): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43dac7d0:true
,D/dalvikvm( 1021): GC_EXPLICIT freed 22750K, 65% free 18043K/50732K, paused 4ms+10ms, total 144ms
,I/Adreno-EGL( 4068): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4068): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4068): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4068): Local Branch: 
I/Adreno-EGL( 4068): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4068): Local Patches: NONE
I/Adreno-EGL( 4068): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4068): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4068): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4068): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4068): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4068): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4068): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4068): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4068): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4068): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4068): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4068): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4068): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4068): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4068): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4068): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4068): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4068): Enabling debug mode 0
,W/AwContents( 4068): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4068): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,521
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +493ms (total +522ms)
,D/JsMessageQueue( 4068): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4068): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f3a170
,D/dalvikvm( 4068): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f3a170
D/jxcore_app_log( 4068): JniHelper::setJavaVM(0x41585fa8), pthread_self() = 1614013232
,D/JX-Cordova( 4068): jxcore cordova android initializing
,D/dalvikvm( 4068): GC_CONCURRENT freed 2811K, 17% free 14378K/17224K, paused 2ms+2ms, total 55ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 227K, 17% free 14361K/17224K, paused 24ms, total 25ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 189K, 17% free 14387K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.221MB for 144892-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 255K, 17% free 14435K/17368K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.336MB for 217334-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 371K, 18% free 14510K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.513MB for 325996-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 572K, 19% free 14631K/17904K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.787MB for 488990-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 873K, 20% free 14808K/18384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 17.193MB for 733480-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 1293K, 22% free 15065K/19104K, paused 26ms, total 26ms
,D/dalvikvm( 4068): GC_CONCURRENT freed 1676K, 20% free 15437K/19104K, paused 2ms+3ms, total 41ms
D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 382K, 20% free 15396K/19104K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 18.641MB for 1650320-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 1612K, 23% free 15960K/20716K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 1460K, 23% free 16054K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 20.071MB for 2475476-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 194K, 21% free 18467K/23136K, paused 5ms+4ms, total 39ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 4458K, 27% free 17018K/23136K, paused 35ms, total 36ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 22.193MB for 3713210-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 2849K, 33% free 18109K/26764K, paused 5ms+7ms, total 58ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 620K, 33% free 17958K/26764K, paused 27ms, total 28ms
,W/jxcore-log( 4068): Initializing JXcore engine
,W/jxcore-log( 4068): JXcore engine is ready
,D/dalvikvm( 4068): GC_CONCURRENT freed 314K, 23% free 20608K/26764K, paused 1ms+2ms, total 34ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 4068): Starting JXcore engine
,W/jxcore-log( 4068): Platform android
W/jxcore-log( 4068): 
,W/jxcore-log( 4068): Process ARCH arm
W/jxcore-log( 4068): 
,I/jxcore-log( 4068): JXcore Cordova bridge is ready!
I/jxcore-log( 4068): 
,W/jxcore-log( 4068): JXcore engine is started
,I/chromium( 4068): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4068): Toggling radios to true
I/jxcore-log( 4068): 
,D/BluetoothAdapter( 4068): enable(): BT is already enabled..!
D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=4068, uid=10495
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4068): Radios toggled
I/jxcore-log( 4068): 
D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4068): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4068): 
I/jxcore-log( 4068): Perf Test app loaded loaded
I/jxcore-log( 4068): 
,I/jxcore-log( 4068): check test folder
I/jxcore-log( 4068): 
,I/jxcore-log( 4068): found test : ./testFindPeers.js
I/jxcore-log( 4068): 
,D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  278): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  278):  STA Disconnected !!
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): get_property_value, Enter
I/MDMCTBK (  278): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  278): get_property_value, Exit
I/MDMCTBK (  278): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  278): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  278): set_property_value, Enter
,I/MDMCTBK (  278): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  278): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  278): set_property_value, Exit
I/MDMCTBK (  278): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  278): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  278): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  278): set_property_value, Enter
I/MDMCTBK (  278): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  278): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  278): set_property_value, Exit
,E/MDMCTBK (  278): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
,D/Tethering( 1021): InitialState.processMessage what=4
,D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,V/ConnectivityService( 1021): WiFi NOT Tethered!
D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  276): Clearing all IP addresses on wlan0
D/TCMD    (  438): NL - Read 60 bytes from update socket.
D/TCMD    (  438): NL - ignore NL message, type = 21
D/TCMD    (  438): Listening for incoming client connection request
D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1021): connected time updated 294947
I/jxcore-log( 4068): found test : ./testSendData.js
I/jxcore-log( 4068): 
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1021): Attempting to switch to ETHERNET
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x61186828 clazz=0x61e00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1021): DisconnectingState
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection lost
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1362): Read error: ssl=0x63076850: I/O error during system call, Connection timed out
,V/NativeCrypto( 1362): SSL shutdown failed: ssl=0x63076850: I/O error during system call, Broken pipe
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  276): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1021): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
,I/chromium( 4068): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  278): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  278): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  438): NL - Read 56 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request,
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  278): Event received = Trying to associate with
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
,D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  438): NL - Read 312 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 88 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  278): Event received = Associated with c0:ff:d4
D/TCMD    (  438): NL - Read 80 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 80 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request,
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X,
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  278): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  278): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  278):  STA Connected !!
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
E/MDMCTBK (  278): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  278): get_freq !!, resp=0
I/MDMCTBK (  278): get_freq !!, Strip data
I/MDMCTBK (  278): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): get_property_value, Enter
I/MDMCTBK (  278): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  278): get_property_value, Exit
I/MDMCTBK (  278): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  278): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  278): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  278): set_property_value, Enter
I/MDMCTBK (  278): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  278): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  278): set_property_value, Exit
,I/MDMCTBK (  278): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  278): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  278): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
,I/MDMCTBK (  278): get_property_value, Enter
I/MDMCTBK (  278): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  278): get_property_value, Exit
I/MDMCTBK (  278): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1219720368
,I/MDMCTBK (  278): return from set_get_from_wpa_supplicant
I/MDMCTBK (  278): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  278): set_property_value, Enter
I/MDMCTBK (  278): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  278): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  278): set_property_value, Exit
E/MDMCTBK (  278): MdmCutbackHndler,Airplane Mode Enabled !! =1,
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE ,
,D/MDMCTBK (  278): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  278): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  278): , reply_len: 3, ret: 0
E/MDMCTBK (  278): MdmCutbackHndler, resp=OK
E/MDMCTBK (  278): 
,D/MDMCTBK (  278): wifi_set_tx_pwr: Exit
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection established
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1021): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-38ms what=147462 obj=android.net.wifi.StateChangeResult@425b19a8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-44ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42288ba8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-13ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41ff4470 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41ff4470 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
,D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  278): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
,D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 0 c2
,D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 1 c0,
D/TCMD    (  438): NL - Read 56 bytes from update socket.
,D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
,D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 9e
,D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 7 64
,D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 10
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-ADDED 8 10
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  278): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  278): Event received = WPS-AP-AVAILABLE-AUTH ,
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  278): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@420d7fb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@420d7fb0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@420d7fb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): handleMessage: X
,D/TCMD    (  438): NL - Read 60 bytes from update socket.
D/TCMD    (  438): NL - ignore NL message, type = 20
,D/TCMD    (  438): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-9ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,I/jxcore-log( 4068): Connected to the server!
I/jxcore-log( 4068): 
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,I/chromium( 4068): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): DHCP successful
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1021): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1021): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1021): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState enter
,D/WifiStateMachine( 1021): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1021): WiFi NOT Tethered!
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@4202df18
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
V/ConnectivityService( 1021): WiFi NOT Tethered!
E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@4202df18
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/Tethering( 1021): MasterInitialState.processMessage what=3
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1565): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1565): Registering with Alarm Manager to restart CCE
D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1565): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1565): [debug] > CusSM.onRadioDown
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/openssl ( 3956): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3956): Crypto mode 0 already enabled
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4220 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,V/MmsConfig( 4220): mnc/mcc: 
V/MmsConfig( 4220): tag: bool value: enabledMMS - true
V/MmsConfig( 4220): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4220): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4220): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4220): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4220): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4220): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4220): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4220): tag: int value: recipientLimit - 20
V/MmsConfig( 4220): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4220): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4220): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4220): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4220): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4220): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4220): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4220): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4220): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4242 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 3832:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4242): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4242): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4242): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4242): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4256 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3855:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1450463608424 min interval config: 0 actual interval: 283276
,I/CheckinService( 1381): Checking schedule, now: 1450463891705 next: 1450463638389
,I/CheckinService( 1381): active receiver: enabled
,I/CheckinService( 1381): Preparing to send checkin request
,I/EventLogService( 1381): Accumulating logs since 1450463605081
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4270 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3878:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  280): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 23ms
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,V/WebViewChromiumFactoryProvider( 4270): Binding Chromium to main looper Looper (main, tid 1) {41f39c08}
,I/LibraryLoader( 4270): Expected native library version number "",actual native library version number ""
,I/chromium( 4270): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4270): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4270): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4270): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4270): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4270): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4270): Local Branch: 
I/Adreno-EGL( 4270): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4270): Local Patches: NONE
I/Adreno-EGL( 4270): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4270): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4298 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4298): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4298): VFY: replacing opcode 0x60 at 0x000b
,W/GAV2    ( 4270): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  265): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  265): Returning OperationFailed - no handler for errno 30
I/dalvikvm( 4298): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4298): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x00cd
W/ContextImpl( 4270): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/MultiDex( 4298): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4298): install
I/MultiDex( 4298): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 4298): loading existing secondary dex files
I/MultiDex( 4298): load found 3 secondary dex files
I/MultiDex( 4298): install done
,D/dalvikvm( 4298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4298): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4298): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4298): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4298): VFY: unable to resolve instance field 36
,D/dalvikvm( 4298): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4298): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4298): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4298): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4298): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4298): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f345f0
,D/dalvikvm( 4298): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f345f0
,D/dalvikvm( 4298): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f345f0, skipping init
,D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f345f0
D/dalvikvm( 4298): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f345f0
,V/JNIHelp ( 4298): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f345f0
,D/dalvikvm( 4298): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f345f0
D/dalvikvm( 4298): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f345f0
,D/dalvikvm( 4298): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f345f0
,I/NSApplication( 4270): Starting up...
,I/ProviderInstaller( 4298): Installed default security provider GmsCore_OpenSSL
,I/ImageResourceManager( 3938): ImageResourceManager: uninitalized
,I/iu.Environment( 3938): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1021): Killing 3893:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4298): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4298): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4298): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4298): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x000d
,I/openssl ( 3956): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3956): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4242): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4242): onReceive CONNECTIVITY_CHANGE networkType=1
,I/dalvikvm( 4298): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4298): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4298): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4298): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4298): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4298): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4298): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4298): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4298): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4298): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/iu.Environment( 3938): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  283): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  283): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  283): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5108000
,E/DrmWidevineDash(  283): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5108000
,D/DEBUG   ( 1565): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/DrmWidevineDash(  283): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_APIVersion...
,W/ContextImpl( 1565): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1565): bindWebServices(): registering our AIDL callback...
D/DrmWidevineDash(  283): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  283): calling OEMCrypto_IsKeyboxValid...
,I/SundryService( 1565): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1565): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1565): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
D/GetNotificationsWS( 1565): onServiceConnected()
D/GetNotificationsWS( 1565): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1565): unbindWebServices(): un-registering our AIDL callback...
,D/DrmWidevineDash(  283): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  283): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  283): CdmEngine::OpenSession
,D/DrmWidevineDash(  283): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  283): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  283): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  283): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  283): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  283): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_GetDeviceID...
,D/LocationInitializer( 1381): Restart initialization of location
,D/WearableService( 1224): callingUid 10022, callindPid: 1224
D/DrmWidevineDash(  283): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_GenerateNonce. SID = 1
D/AuthorizationBluetoothService( 1362): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1362): Proximity feature is not enabled.
D/DrmWidevineDash(  283): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  283): PrepareKeyRequest: nonce=1466604630
,D/DrmWidevineDash(  283): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  283): calling OEMCrypto_GenerateRSASignature. SID = 1
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1224): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
,D/NativeLibraryUtils( 4298): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4298): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42151f28
D/dalvikvm( 4298): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42151f28
,D/dalvikvm( 4298): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42151f28, skipping init
,D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  283): CdmEngine::CloseSession
,D/DrmWidevineDash(  283): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  283): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4298): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4335): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4298): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4298): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
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
,I/dalvikvm( 4068): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4068): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4068): Shutting down VM
,W/dalvikvm( 4068): threadid=1: thread exiting with uncaught exception (group=0x41664d40)
E/AndroidRuntime( 4068): FATAL EXCEPTION: main
E/AndroidRuntime( 4068): Process: com.test.thalitest, PID: 4068
E/AndroidRuntime( 4068): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4068): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4068): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4068): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4068): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4068): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4068): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4068): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4068): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4068): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4068): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4068): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4068): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4068): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4068): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4068): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4068): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4068): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4068): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager( 1021):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager( 1021): Killing 3909:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4068): Sending signal. PID: 4068 SIG: 9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1021): Process com.test.thalitest (pid 4068) has died.
,I/WindowState( 1021): WIN DEATH: Window{41f73600 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1021): Client connection lost with reason: 4
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/SFPerfTracer(  279):      triggers: (rate: 2:30) (compose: 0:4) (post: 0:1) (render: 0:5) (0:127 frames) (1:551)
,D/SFPerfTracer(  279):        layers: (0:12) (FocusedStackFrame: 1:10)* (StatusBar: 0:208)* (NavigationBar: 0:41)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:4)* 
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 4068 uid 10495
,W/Binder  ( 1205): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1205): java.lang.NullPointerException
W/Binder  ( 1205): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1205): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1205): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1205): 	at dalvik.system.NativeStart.run(Native Method)
,I/WVCdm   (  283): CdmEngine::OpenSession
,D/DrmWidevineDash(  283): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  283): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  283): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  283): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  283): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  283): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  283): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  283): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  283): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  283): PrepareKeyRequest: nonce=3192913145
,D/DrmWidevineDash(  283): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  283): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  283): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  283): CdmEngine::CloseSession
,D/DrmWidevineDash(  283): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  283): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/CheckinTask( 1381): Sending checkin request (11757 bytes)
,D/WifiStateMachine( 1021): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1021): processMsg: ConnectedState
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1021): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1021):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/WifiStateMachine( 1021): handleMessage: X
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1565): now: 326136 ,futureTime: 4055891
,D/PollingManager( 1565): Polling alarm set to expire at: 4055891 Current Time: 326137
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1565): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1565): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/PollingManager( 1565): now: 326172 ,futureTime: 4055891
,D/PollingManager( 1565): Polling alarm set to expire at: 4055891 Current Time: 326173
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1565): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1565): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1021): MasterInitialState.processMessage what=3
I/openssl ( 3956): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3956): Crypto mode 0 already enabled
D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/OtaApp  ( 1565): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/MobileConnectivityChangeReceiver( 4242): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4242): onReceive CONNECTIVITY_CHANGE networkType=1
,I/OtaApp  ( 1565): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,I/iu.Environment( 3938): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1450463608424 min interval config: 0 actual interval: 286075
,D/DEBUG   ( 1565): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1565): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1565): bindWebServices(): registering our AIDL callback...
I/SundryService( 1565): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1565): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1565): onServiceConnected()
,D/GetNotificationsWS( 1565): onServiceConnected(): Registered for remote service callbacks...
,D/dalvikvm( 3938): GC_FOR_ALLOC freed 607K, 5% free 16434K/17224K, paused 30ms, total 34ms
,D/WaitableIntentService( 1565): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1565): unbindWebServices(): un-registering our AIDL callback...
,I/dalvikvm-heap( 3938): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/MobileConnectivityChangeReceiver( 4242): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4242): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 1021): GC_EXPLICIT freed 1738K, 65% free 17977K/50732K, paused 5ms+10ms, total 103ms
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/dalvikvm( 3938): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 16ms, total 16ms
,I/iu.Environment( 3938): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1450463608424 min interval config: 0 actual interval: 286172
,D/DEBUG   ( 1565): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1565): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1565): bindWebServices(): registering our AIDL callback...
I/SundryService( 1565): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1565): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1565): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1565): onServiceConnected()
,D/GetNotificationsWS( 1565): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1565): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1565): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1565
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1565): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1565): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1565): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1565
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinTask( 1381): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1381): Checking schedule, now: 1450463894699 next: 1451056964693
,I/CheckinService( 1381): active receiver: disabled
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1021): Activity reported stop, but no longer stopping: ActivityRecord{428c7d68 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinService( 1381): Checking schedule, now: 1450463894716 next: 1451056964693
,I/CheckinService( 1381): active receiver: disabled
,D/CheckinService( 1381): Recording last checkin time for package unspecified as 1450463894722
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1281): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/GAV2    ( 4270): Thread[GAThread,5,main]: No campaign data found.
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4401 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4401): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4401): MmsConfig.loadMmsSettings
I/Babel   ( 4401): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4401): MmsConfig.loadFromDatabase
,E/Babel   ( 4401): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4401): MmsConfig.loadFromResources
,E/Babel   ( 4401): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4401): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4401): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4439 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1021): Killing 3466:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4457 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3956:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2298): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1021): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4475 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4220:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4475): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4475): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4439): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4475): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1381): GC_CONCURRENT freed 1877K, 31% free 12031K/17224K, paused 5ms+5ms, total 39ms
,I/InternalIcingCorporaPro( 2298): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,I/dalvikvm( 4475): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4475): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4475): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4475): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4475): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4475): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4475): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4475): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4475): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4475): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4475): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4475): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4475): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4475): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4475): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4511 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4475): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4475): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4475): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4475): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4475): Skipping gmscore version check
I/dalvikvm( 4475): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4475): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1021): Killing 4242:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1381): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1381): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4511): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f3b3c0, skipping init
I/openssl ( 4511): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4511): Crypto mode 0 already enabled
,D/Finsky  ( 4475): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4475): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1021): Killing 4256:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1381): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1381): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450463903
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1021): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1021): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1021): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1021): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1021): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{42250128 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{42007110 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{43e0b2f8 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1,
,D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1,
D/MDMCTBK (  278): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  278): Event received = CTRL-EVENT-BSS-REMOVED 1,
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{427cb4a0 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{440d7d18 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{4274bae8 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{43db10b8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4224c980 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1021): cleanup(): cleared. Last call was 398544 ms ago
,I/ActivityManager( 1021): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4554 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1021): Killing 4270:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{439adbe8 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{427e7500 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{42871f28 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4224c570 type 2 android}
,V/AlarmManager( 1021): sending alarm Alarm{4223c7d8 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{4222f1f0 type 0 com.google.android.gms}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,I/EventLogService( 1381): Aggregate from 1450463891730 (log), 1450462501078 (data)
,D/dalvikvm( 1362): GC_EXPLICIT freed 957K, 40% free 10341K/17224K, paused 2ms+5ms, total 36ms
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{44765a08 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{43762e30 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{43514430 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{44765330 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427650a8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440ca110 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1021): sending alarm Alarm{427ac248 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{430390f0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4281deb8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440dbde0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4277ae50 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1021): GC_CONCURRENT freed 1992K, 65% free 18108K/50732K, paused 11ms+9ms, total 98ms
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{436fe258 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44107d08 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427ac320 type 1 com.android.deskclock}
,V/AlarmManager( 1021): sending alarm Alarm{44106150 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440c7308 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440b7a20 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427ac3f8 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{427ac4d0 type 3 android}
,I/ProcessStatsService( 1021): Prepared write state in 36ms
,V/AlarmManager( 1021): sending alarm Alarm{42ff5020 type 3 com.google.android.gms}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,I/ProcessStatsService( 1021): Pruning old procstats: /data/system/procstats/state-2015-12-18-06-43-57.bin
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1224): GC_CONCURRENT freed 1824K, 34% free 11510K/17224K, paused 2ms+7ms, total 34ms
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{43c140d0 type 3 android}
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  278): NetlinkHandler, power_supply subsys
I/MDMCTBK (  278): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  278): checkDefaultInst, current pid is = 278
I/MDMCTBK (  278): checkDefaultInst, pid match
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  278): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  278): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{41f845d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{421d1868 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42101618 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42784408 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1021): sending alarm Alarm{43d6ca20 type 2 com.google.android.gms}
V/AlarmManager( 1021): sending alarm Alarm{420b8700 type 2 com.motorola.ccc.cce}
D/CCE     ( 1565): Registering with Alarm Manager to restart CCE
D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/AndroidRuntime( 4615): 
D/AndroidRuntime( 4615): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4615): CheckJNI is OFF
D/dalvikvm( 4615): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4615): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4615): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4615): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4615): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4615): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4615): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4615): failed to load memtrack module: -2
D/AndroidRuntime( 4615): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10495 user=-1: uninstall pkg
I/dalvikvm( 1021): Total arena pages for JIT: 15
W/PackageSettings( 1021): Skipping PackageSetting{421f9ba8 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10495 user=0: pkg removed
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450465698
I/ActivityManager( 1021): Killing 4298:com.google.android.gms.unstable/u0a22 (adj 15): empty for 1800s
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
D/dalvikvm( 2265): GC_EXPLICIT freed 5446K, 44% free 9651K/17224K, paused 2ms+7ms, total 99ms
D/VoicemailCleanupService( 4439): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
D/dalvikvm( 2298): GC_EXPLICIT freed 2674K, 44% free 9777K/17224K, paused 2ms+3ms, total 135ms
D/dalvikvm( 1297): GC_EXPLICIT freed 3234K, 33% free 11608K/17224K, paused 2ms+5ms, total 138ms
I/Launcher( 1297): Deferring update until onResume
D/dalvikvm( 1381): GC_EXPLICIT freed 1225K, 31% free 11938K/17224K, paused 4ms+12ms, total 178ms
W/SQLiteConnectionPool( 1381): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10495 #1
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/Launcher( 1297): Deferring update until onResume
I/InternalIcingCorporaPro( 2298): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450465699
I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4647 uid=10059 gids={50059, 3003, 1028, 1015}
D/dalvikvm( 1021): GC_EXPLICIT freed 1687K, 65% free 18042K/50732K, paused 6ms+12ms, total 117ms
D/dalvikvm( 1021): WAIT_FOR_CONCURRENT_GC blocked 104ms
I/InternalIcingCorporaPro( 2298): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
D/dalvikvm( 1021): GC_EXPLICIT freed 240K, 65% free 17928K/50732K, paused 4ms+10ms, total 112ms
D/AndroidRuntime( 4615): Shutting down VM
D/dalvikvm( 4615): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
W/ActiveOrDefaultContextProvider( 4647): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4672 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4647): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4672): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/ChimeraCfgMgr( 1381): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1381): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1381): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1381): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1381): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1381): Removing dialog suppression flag for package com.test.thalitest
I/dalvikvm( 4475): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4475): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x0013
D/gH_CompatibleDatabase( 1381): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1381): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/NetworkScheduler.SchedulerReceiver( 1362): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1362): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_MetricsDatabase( 1381): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1381): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Icing   ( 1381): doRemovePackageData com.test.thalitest
I/ActivityManager( 1021): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4712 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1381): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1381): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1381): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/dalvikvm( 3938): GC_FOR_ALLOC freed 26K, 4% free 20546K/21204K, paused 55ms, total 73ms
E/SharedPreferencesImpl( 1381): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
W/FileUtils( 1381): Failed to chmod(/data/data/com.google.android.gms/databases/auto_complete_suggestions.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1381): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1381): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 1381): (3850) statement aborts at 29: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1381): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
W/dalvikvm( 1381): threadid=52: thread exiting with uncaught exception (group=0x41664d40)
E/AndroidRuntime( 1381): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1381): Process: com.google.android.gms, PID: 1381
E/AndroidRuntime( 1381): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1381): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 1381): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1381): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1381): Sending signal. PID: 1381 SIG: 9
E/SQLiteDatabase( 4672): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4672): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4672): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4672): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4672): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4672): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4672): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4672): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4672): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4672): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4672): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1021): Can't write: system_app_crash
E/DropBoxManagerService( 1021): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1021): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1021): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1021): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1021): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1021): 	... 5 more
W/dalvikvm( 4672): threadid=11: thread exiting with uncaught exception (group=0x41664d40)
E/AndroidRuntime( 4672): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4672): Process: com.android.keychain, PID: 4672
E/AndroidRuntime( 4672): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4672): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4672): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4672): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4672): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4672): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4672): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4672): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4672): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4672): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4672): Sending signal. PID: 4672 SIG: 9
E/DropBoxManagerService( 1021): Can't write: system_app_crash
E/DropBoxManagerService( 1021): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1021): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1021): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1021): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1021): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1021): 	... 5 more
D/Documents( 4712): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1021): Process com.android.keychain (pid 4672) has died.
W/ActivityManager( 1021): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager( 1021): Process com.google.android.gms (pid 1381) has died.
D/WifiService( 1021): Client connection lost with reason: 4
E/SQLiteDatabase( 4712): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4712): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4712): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4712): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4712): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4712): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4712): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4712): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4712): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4712): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4712): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4712): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4712): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4712): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4712): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4712): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4712): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4712): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4712): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4712): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4712): Shutting down VM
W/dalvikvm( 4712): threadid=1: thread exiting with uncaught exception (group=0x41664d40)
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
E/AndroidRuntime( 4712): FATAL EXCEPTION: main
E/AndroidRuntime( 4712): Process: com.android.documentsui, PID: 4712
E/AndroidRuntime( 4712): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4712): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4712): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4712): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4712): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4712): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4712): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4712): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4712): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4712): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4712): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4712): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4712): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4712): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4712): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4712): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4712): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4712): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4712): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4712): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4712): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4712): 	... 10 more
D/Documents( 4712): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1021): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4732 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
D/dalvikvm(  280): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms

```
