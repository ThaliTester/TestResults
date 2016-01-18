#### Test 56151093f6e24ff_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4254): 
D/AndroidRuntime( 4254): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4254): CheckJNI is OFF
D/dalvikvm( 4254): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4254): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4254): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4254): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4254): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4254): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4254): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4254): failed to load memtrack module: -2
D/AndroidRuntime( 4254): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4254
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4270 uid=10121 gids={50121, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4254): Shutting down VM
D/dalvikvm( 4254): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+2ms, total 24ms
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 23ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+8ms, total 24ms
V/WebViewChromiumFactoryProvider( 4270): Binding Chromium to main looper Looper (main, tid 1) {424a8bb0}
I/LibraryLoader( 4270): Expected native library version number "",actual native library version number ""
I/chromium( 4270): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4270): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44665638:true
I/Adreno-EGL( 4270): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4270): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4270): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4270): Local Branch: 
I/Adreno-EGL( 4270): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4270): Local Patches: NONE
I/Adreno-EGL( 4270): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4270): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4270): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4270): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4270): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4270): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4270): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4270): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4270): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4270): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4270): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4270): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4270): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4270): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4270): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4270): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4270): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4270): Enabling debug mode 0
,W/AwContents( 4270): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1223): onFinishInput()
,W/AwContents( 4270): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,486
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +456ms (total +486ms)
W/IInputConnectionWrapper( 4270): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4270): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4270): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424ad060
,D/dalvikvm( 4270): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424ad060
D/jxcore_app_log( 4270): JniHelper::setJavaVM(0x41bc1f78), pthread_self() = 1614809016
D/JX-Cordova( 4270): jxcore cordova android initializing
,D/dalvikvm( 4270): GC_CONCURRENT freed 2700K, 16% free 14489K/17224K, paused 2ms+3ms, total 38ms
D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/dalvikvm( 4270): GC_FOR_ALLOC freed 423K, 14% free 14912K/17224K, paused 28ms, total 28ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.656MB for 63974-byte allocation
D/dalvikvm( 4270): GC_FOR_ALLOC freed 129K, 14% free 14928K/17288K, paused 28ms, total 28ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.703MB for 95956-byte allocation
D/dalvikvm( 4270): GC_FOR_ALLOC freed 191K, 15% free 14950K/17384K, paused 27ms, total 27ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.769MB for 143930-byte allocation
D/dalvikvm( 4270): GC_FOR_ALLOC freed 251K, 15% free 14997K/17528K, paused 27ms, total 27ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.884MB for 215890-byte allocation
D/dalvikvm( 4270): GC_FOR_ALLOC freed 366K, 16% free 15071K/17740K, paused 27ms, total 27ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 17.059MB for 323830-byte allocation
D/dalvikvm( 4270): GC_FOR_ALLOC freed 565K, 16% free 15192K/18060K, paused 27ms, total 28ms
D/dalvikvm( 4270): GC_FOR_ALLOC freed 858K, 15% free 15367K/18060K, paused 28ms, total 29ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 17.734MB for 728606-byte allocation
D/dalvikvm( 4270): GC_FOR_ALLOC freed 1274K, 17% free 15623K/18772K, paused 29ms, total 29ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 18.332MB for 1092904-byte allocation
D/dalvikvm( 4270): GC_CONCURRENT freed 1879K, 20% free 16022K/19840K, paused 1ms+4ms, total 34ms
D/dalvikvm( 4270): GC_FOR_ALLOC freed 147K, 20% free 15952K/19840K, paused 27ms, total 27ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 19.173MB for 1639352-byte allocation
D/dalvikvm( 4270): GC_CONCURRENT freed 1867K, 23% free 16538K/21444K, paused 1ms+4ms, total 39ms
D/dalvikvm( 4270): GC_FOR_ALLOC freed 1045K, 23% free 16518K/21444K, paused 29ms, total 29ms
I/dalvikvm-heap( 4270): Grow heap (frag case) to 20.508MB for 2459024-byte allocation
D/dalvikvm( 4270): GC_CONCURRENT freed 1971K, 28% free 17337K/23848K, paused 5ms+4ms, total 49ms
,D/dalvikvm( 4270): GC_CONCURRENT freed 2515K, 27% free 17544K/23848K, paused 1ms+6ms, total 41ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 22.682MB for 3688532-byte allocation
,D/dalvikvm( 4270): GC_CONCURRENT freed 341K, 24% free 21100K/27452K, paused 4ms+6ms, total 64ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 4403K, 33% free 18652K/27452K, paused 34ms, total 34ms
,W/jxcore-log( 4270): Initializing JXcore engine
,W/jxcore-log( 4270): JXcore engine is ready
,D/dalvikvm( 4270): GC_CONCURRENT freed 397K, 22% free 21472K/27452K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4270): Starting JXcore engine
,W/jxcore-log( 4270): Platform android
W/jxcore-log( 4270): 
,W/jxcore-log( 4270): Process ARCH arm
W/jxcore-log( 4270): 
,I/jxcore-log( 4270): JXcore Cordova bridge is ready!
I/jxcore-log( 4270): 
,W/jxcore-log( 4270): JXcore engine is started
,I/chromium( 4270): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4270): Toggling radios to true
I/jxcore-log( 4270): 
,D/BluetoothAdapter( 4270): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4270, uid=10121
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4270): Radios toggled
I/jxcore-log( 4270): 
I/jxcore-log( 4270): My device name is: motorola-XT1039
I/jxcore-log( 4270): 
,I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276):  STA Disconnected !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
D/TCMD    (  500): NL - Read 1000 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  276): send SAR ctrl over QMI
D/TCMD    (  500): NL - Read 1000 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 68 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 68 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/Tethering( 1019): InitialState.processMessage what=4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  500): NL - Read 60 bytes from update socket.
D/TCMD    (  500): NL - ignore NL message, type = 21
,D/TCMD    (  500): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 300421
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1019): DisconnectingState
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6161c7d8 clazz=0x63400001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1342): Read error: ssl=0x635c0858: I/O error during system call, Connection timed out
,V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x635c0858: I/O error during system call, Broken pipe
,E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1211): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1211): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1211): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1211): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1211): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1211): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  500): NL - Read 56 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@44ec6440 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@44ec6440 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@44ec6440 target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4348 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1576): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1295): Active network info is not available
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,E/ActivityThread( 1576): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1576): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1576): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1576): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1576): Registering with Alarm Manager to restart CCE
W/XTWiFiOS( 1295): Active network info is not available
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/OtaApp  ( 1576): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1576): [debug] > CusSM.onRadioDown
,D/dalvikvm( 4348): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x424a5f90, skipping init
I/openssl ( 4348): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4348): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4375 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3923:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4375): mnc/mcc: 
,V/MmsConfig( 4375): tag: bool value: enabledMMS - true
V/MmsConfig( 4375): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4375): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4375): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 4375): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4375): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4375): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4375): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4375): tag: int value: recipientLimit - 20
,V/MmsConfig( 4375): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4375): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4375): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4375): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4375): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4375): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4375): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4375): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4375): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4395 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 4095:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4395): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4395): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4395): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4395): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4408 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4124:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4408): Binding Chromium to main looper Looper (main, tid 1) {424a1808}
,I/LibraryLoader( 4408): Expected native library version number "",actual native library version number ""
,I/chromium( 4408): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4408): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4408): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4408): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4408): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4408): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4408): Local Branch: 
I/Adreno-EGL( 4408): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4408): Local Patches: NONE
I/Adreno-EGL( 4408): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4408): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4408): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4408): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4408): Starting up...
,I/ActivityManager( 1019): Killing 3812:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1706): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1706): num queued entries: 0
,I/iu.UploadsManager( 1706): num updated entries: 0
,I/iu.SyncManager( 1706): NEXT; no task
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4450 uid=10056 gids={50056, 3003, 1028, 1015}
,D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4450): VFY: unable to resolve instance field 68
D/dalvikvm( 4450): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4450): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4450): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4450): VFY: unable to resolve instance field 68
,D/dalvikvm( 4450): VFY: replacing opcode 0x54 at 0x0011
,I/ActivityManager( 1019): Killing 4162:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4450): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4450): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4450): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4450): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4395): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4395): onReceive CONNECTIVITY_CHANGE networkType=1
,D/DEBUG   ( 1576): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1576): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/dalvikvm( 1019): GC_EXPLICIT freed 24788K, 66% free 18749K/53680K, paused 4ms+11ms, total 149ms
,D/GetNotificationsWS( 1576): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1576): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1576): onServiceConnected()
D/GetNotificationsWS( 1576): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1576): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1576): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1576): unbindWebServices(): un-registering our AIDL callback...
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test app app.js loaded
I/jxcore-log( 4270): 
,I/dalvikvm( 4270): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4270): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4270): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4270): BLE advertisement is supported
I/jxcore-log( 4270): 
,I/Choreographer( 4270): Skipped 351 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4270): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
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
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{445dd9c0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/GAV2    ( 4408): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 fc
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 fc
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  500): NL - Read 56 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{445c93f0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  500): NL - Read 56 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): DefaultState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{445dc310 type 3 android}
,I/wpa_supplicant( 1167): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  500): NL - Read 56 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  276): Event received = Trying to associate with,
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE ,
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,E/wpa_supplicant( 1167): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1167): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1167): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  500): NL - Read 312 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 192 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 68 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 1000 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1167): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  500): NL - Read 80 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 80 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
D/TCMD    (  500): NL - Read 68 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1167): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  500): NL - Read 1000 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
,D/TCMD    (  500): Listening for incoming client connection request
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  276): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  276): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1217867000
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1,
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-56ms what=147462 obj=android.net.wifi.StateChangeResult@438ad780 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-44ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@427cf308 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427c55c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427c55c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  500): NL - Read 56 bytes from update socket.
D/TCMD    (  500): NL - message type is RTM_NEWLINK
D/TCMD    (  500): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  500): NL - Read 60 bytes from update socket.
D/TCMD    (  500): NL - ignore NL message, type = 20
,D/TCMD    (  500): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-5ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/jxcore-log( 4270): --= Surplus to requirements =--
I/jxcore-log( 4270): 
I/jxcore-log( 4270): ****TEST TOOK:  ms ****
I/jxcore-log( 4270): 
I/jxcore-log( 4270): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4270): 
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42572690
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=zz_moto_stat_sys_wifi_inout_wide in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1211): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1211): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1211): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42572690
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=zz_moto_stat_sys_wifi_inout_wide in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1211): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1211): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1211): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1706): Checkin interval check for package: unspecified last checkin: 1453125154033 min interval config: 0 actual interval: 333899
,I/CheckinService( 1706): Checking schedule, now: 1453125487942 next: 1453125184013
,I/CheckinService( 1706): active receiver: enabled
,I/CheckinService( 1706): Preparing to send checkin request
,I/EventLogService( 1706): Accumulating logs since 1453125150167
,I/CheckinRequestBuilder( 1706): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1706): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1342): GC_EXPLICIT freed 1488K, 40% free 10360K/17224K, paused 2ms+4ms, total 31ms
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4567 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4567): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4567): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4567): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4567): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4567): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4567): install
,I/MultiDex( 4567): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4567): loading existing secondary dex files
,I/MultiDex( 4567): load found 3 secondary dex files
,I/MultiDex( 4567): install done
,D/dalvikvm( 4567): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4567): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4567): VFY: replacing opcode 0x62 at 0x000a
,D/AndroidRuntime( 4557): 
D/AndroidRuntime( 4557): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/dalvikvm( 4567): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4567): VFY: unable to resolve instance field 36
,D/dalvikvm( 4567): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4567): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4567): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4567): VFY: replacing opcode 0x62 at 0x0047
,D/AndroidRuntime( 4557): CheckJNI is OFF
D/dalvikvm( 4567): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4567): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4567): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424a8c28
D/dalvikvm( 4567): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424a8c28
,D/dalvikvm( 4567): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424a8c28, skipping init
,D/dalvikvm( 4567): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x424a8c28
D/dalvikvm( 4567): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x424a8c28
,V/JNIHelp ( 4567): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4557): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4557): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4557): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4557): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4557): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4567): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424a8c28
,D/dalvikvm( 4567): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x424a8c28
D/dalvikvm( 4567): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x424a8c28
,D/dalvikvm( 4567): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x424a8c28
,D/dalvikvm( 4557): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,I/ProviderInstaller( 4567): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1237): callingUid 10022, callindPid: 1237
,E/MDM     ( 1237): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1706): Restart initialization of location
D/AuthorizationBluetoothService( 1342): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1237): No location to return for getLastLocation()
,W/FusedLocationProvider( 1237): location=null
,I/dalvikvm( 4567): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4567): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4567): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4567): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4567): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4567): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4567): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4567): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4567): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 4567): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
E/memtrack( 4557): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4557): failed to load memtrack module: -2
W/dalvikvm( 4567): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4567): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4567): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4567): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4567): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/AndroidRuntime( 4557): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10121 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 4270:com.test.thalitest/u0a121 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{436ed3e8 u0 com.test.thalitest/.MainActivity t3}
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb511d000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb511d000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
I/WindowState( 1019): WIN DEATH: Window{439ada10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/dalvikvm( 1019): Total arena pages for JIT: 15
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3515671112
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10121 user=0: pkg removed
,D/NativeLibraryUtils( 4567): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 1706): GC_EXPLICIT freed 739K, 31% free 11963K/17224K, paused 4ms+5ms, total 44ms
,W/SQLiteConnectionPool( 1706): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Keyboard.Facilitator( 1223): resetDictionaries() : en_GB
,W/GeofencerStateMachine( 1237): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1223): run()
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Decoder ( 1223): createOrResetDecoder
,D/VoicemailCleanupService( 1187): Cleaning up data for package: com.test.thalitest
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/dalvikvm( 2238): GC_EXPLICIT freed 6167K, 44% free 9767K/17224K, paused 4ms+6ms, total 47ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,D/dalvikvm( 2298): GC_EXPLICIT freed 4930K, 42% free 10144K/17224K, paused 2ms+5ms, total 122ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 1492K, 66% free 18643K/53680K, paused 5ms+11ms, total 148ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/ConfigService( 1237): onCreate
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 4567): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42711660
D/dalvikvm( 4567): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42711660
D/dalvikvm( 4567): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42711660, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/WVCdm   (  280): CdmEngine::CloseSession
D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 1309): GC_EXPLICIT freed 3253K, 33% free 11598K/17224K, paused 3ms+4ms, total 243ms
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/OtaApp  ( 1576): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1576): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4615 uid=10033 gids={50033, 3003, 1028, 1015}
D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1223): run()
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10121 #1
,D/OtaApp  ( 1576): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1576): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1576): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 4270 uid 10121
I/Keyboard.Facilitator.MainLanguageModelLoader( 1223): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1223): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1223): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1223): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1223): run()
I/StatsUtilsManager( 1223): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1223): shouldRecordStats() = Too Soon
W/Binder  ( 1223): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1223): java.lang.NullPointerException
W/Binder  ( 1223): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1223): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1223): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1223): 	at dalvik.system.NativeStart.run(Native Method)
I/Keyboard.Facilitator( 1223): onFinishInput()
,I/InternalIcingCorporaPro( 2298): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4632 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Launcher( 1309): Deferring update until onResume
,I/ActivityManager( 1019): Killing 4193:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 4632): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1706): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1706): Clearing selected account for com.test.thalitest
I/dalvikvm( 3831): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3831): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3831): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1706): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1706): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1706): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1706): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1706): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1342): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1342): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1706): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1706): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1706): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1706): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/dalvikvm( 4567): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
D/gH_CompatibleDatabase( 1706): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1706): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1706): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1706): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1706): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1706): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1706): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1706): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4655 uid=10059 gids={50059, 1028, 3003, 1015}
D/gH_CompatibleDatabase( 1706): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/InternalIcingCorporaPro( 2298): UpdateCorporaTask done [took 176 ms] updated apps [took 176 ms] 
,I/Icing   ( 1706): doRemovePackageData com.test.thalitest
I/ActivityManager( 1019): Killing 4348:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1019): GC_EXPLICIT freed 705K, 66% free 18685K/53680K, paused 5ms+15ms, total 350ms
,D/dalvikvm( 4661): DexOpt: load 5ms, verify+opt 7ms, 128132 bytes
,D/dalvikvm( 4567): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4567): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 102ms
,I/Adreno-EGL( 4567): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4567): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4567): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4567): Local Branch: 
I/Adreno-EGL( 4567): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4567): Local Patches: NONE
I/Adreno-EGL( 4567): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/AndroidRuntime( 4557): Shutting down VM
,D/dalvikvm( 4557): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,I/Adreno-EGL( 4567): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4567): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4567): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4567): Local Branch: 
I/Adreno-EGL( 4567): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4567): Local Patches: NONE
I/Adreno-EGL( 4567): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4655): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
,W/dalvikvm( 4655): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4655): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4655): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4655):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4655):   adb logcat -s GAv4
,W/GAv4    ( 4655): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4655): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4655): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4655): VFY: replacing opcode 0x6e at 0x001b
,W/GAv4    ( 4655): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4655): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4655): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
,I/dalvikvm( 4655): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4655): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 4655): VFY: replacing opcode 0x71 at 0x0075
,I/ActivityManager( 1019): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=4693 uid=10095 gids={50095, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4375:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/SQLiteLog( 2238): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2238): Error inserting state=event=am_kill pid=4375 process=com.android.mms reason=empty+%239 selectadj=15 timestamp=1453125489646 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2238): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2238): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2238): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2238): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2238): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2238): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2238): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2238): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2238): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2238): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2238): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2238): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2238): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2238): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2238): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2238): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 4655): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4655): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,D/dalvikvm( 4655): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4655): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4655): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4655): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4655): VFY: unable to resolve instance field 36
,D/dalvikvm( 4655): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4655): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4655): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4655): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4655): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4655): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4655): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428039a8
D/dalvikvm( 4655): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428039a8
,D/dalvikvm( 4655): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428039a8, skipping init
,D/dalvikvm( 4655): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428039a8
D/dalvikvm( 4655): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428039a8
,V/JNIHelp ( 4655): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/SQLiteDatabase( 4693): Failed to open database '/data/data/com.quickoffice.android/databases/keyvaluedb.db'.
E/SQLiteDatabase( 4693): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4693): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4693): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4693): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4693): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/SQLiteDatabase( 4693): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4693): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4693): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4693): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4693): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4693): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4693): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4693): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4693): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4693): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4693): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4693): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4693): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4693): Shutting down VM
,W/dalvikvm( 4693): threadid=1: thread exiting with uncaught exception (group=0x41bd3d40)
E/AndroidRuntime( 4693): FATAL EXCEPTION: main
E/AndroidRuntime( 4693): Process: com.quickoffice.android, PID: 4693
E/AndroidRuntime( 4693): java.lang.RuntimeException: Unable to get provider com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 4693): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4693): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4693): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4693): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4693): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4693): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4693): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4693): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4693): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4693): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/AndroidRuntime( 4693): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 4693): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 4693): 	... 12 more
I/Process ( 4693): Sending signal. PID: 4693 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 5 more
I/ActivityManager( 1019): Process com.quickoffice.android (pid 4693) has died.

```
