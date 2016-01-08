#### Test 55467363832a26e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1017): sending alarm Alarm{43dd4a18 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4057): 
D/AndroidRuntime( 4057): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4057): CheckJNI is OFF
D/dalvikvm( 4057): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4057): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4057): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4057): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4057): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4057): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4057): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4057): failed to load memtrack module: -2
D/AndroidRuntime( 4057): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4057
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4073 uid=10527 gids={50527, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4057): Shutting down VM
D/dalvikvm( 4057): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4073): Binding Chromium to main looper Looper (main, tid 1) {41f4bd30}
I/LibraryLoader( 4073): Expected native library version number "",actual native library version number ""
I/chromium( 4073): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4073): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d87ca0:true
I/Adreno-EGL( 4073): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4073): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4073): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4073): Local Branch: 
I/Adreno-EGL( 4073): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4073): Local Patches: NONE
I/Adreno-EGL( 4073): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4073): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4073): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4073): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4073): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4073): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4073): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4073): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4073): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4073): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4073): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4073): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4073): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4073): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4073): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4073): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4073): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4073): Enabling debug mode 0
,W/AwContents( 4073): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4073): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,378
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +354ms (total +378ms)
W/IInputConnectionWrapper( 4073): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4073): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4073): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f50000
,D/dalvikvm( 4073): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f50000
,D/jxcore_app_log( 4073): JniHelper::setJavaVM(0x4159bfa8), pthread_self() = 1614941384
,D/JX-Cordova( 4073): jxcore cordova android initializing
,D/dalvikvm( 4073): GC_CONCURRENT freed 2781K, 17% free 14382K/17224K, paused 3ms+2ms, total 71ms
,D/dalvikvm( 4073): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 164K, 17% free 14401K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 119K, 17% free 14429K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 16.215MB for 96598-byte allocation
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 194K, 17% free 14450K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 16.282MB for 144892-byte allocation
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 255K, 17% free 14498K/17464K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 16.397MB for 217334-byte allocation
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 371K, 18% free 14572K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 16.574MB for 325996-byte allocation
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 572K, 19% free 14694K/18000K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 16.848MB for 488990-byte allocation
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 872K, 20% free 14871K/18480K, paused 27ms, total 27ms
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 1290K, 19% free 15128K/18480K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 17.855MB for 1100216-byte allocation
,D/dalvikvm( 4073): GC_CONCURRENT freed 1696K, 21% free 15508K/19556K, paused 1ms+4ms, total 38ms
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 366K, 21% free 15456K/19556K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 18.700MB for 1650320-byte allocation
,D/dalvikvm( 4073): GC_CONCURRENT freed 1789K, 25% free 16048K/21168K, paused 1ms+5ms, total 47ms
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 1263K, 25% free 16086K/21168K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 20.102MB for 2475476-byte allocation
,D/dalvikvm( 4073): GC_CONCURRENT freed 221K, 22% free 18427K/23588K, paused 5ms+4ms, total 45ms
,D/dalvikvm( 4073): GC_CONCURRENT freed 4436K, 28% free 17100K/23588K, paused 2ms+7ms, total 52ms
,D/dalvikvm( 4073): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/dalvikvm-heap( 4073): Grow heap (frag case) to 22.272MB for 3713210-byte allocation
,D/dalvikvm( 4073): GC_CONCURRENT freed 279K, 24% free 20731K/27216K, paused 5ms+9ms, total 69ms
,D/dalvikvm( 4073): GC_FOR_ALLOC freed 3307K, 34% free 18045K/27216K, paused 29ms, total 29ms
,W/jxcore-log( 4073): Initializing JXcore engine
,W/jxcore-log( 4073): JXcore engine is ready
,D/dalvikvm( 4073): GC_CONCURRENT freed 373K, 25% free 20667K/27216K, paused 1ms+2ms, total 32ms
,D/dalvikvm( 4073): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 4073): Starting JXcore engine
,W/jxcore-log( 4073): Platform android
W/jxcore-log( 4073): 
,W/jxcore-log( 4073): Process ARCH arm
W/jxcore-log( 4073): 
,I/jxcore-log( 4073): JXcore Cordova bridge is ready!
I/jxcore-log( 4073): 
,W/jxcore-log( 4073): JXcore engine is started
,I/chromium( 4073): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4073): Toggling radios to true
I/jxcore-log( 4073): 
,D/BluetoothAdapter( 4073): enable(): BT is already enabled..!
D/WifiService( 1017): New client listening to asynchronous messages
D/WifiService( 1017): setWifiEnabled: true pid=4073, uid=10527
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1017): handleMessage: E msg.what=131145
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
I/jxcore-log( 4073): Radios toggled
I/jxcore-log( 4073): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4073): Received device characteristics:
I/jxcore-log( 4073): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4073): Bluetooth name: XT1039
I/jxcore-log( 4073): Device name: motorola-XT1039
I/jxcore-log( 4073): 
I/jxcore-log( 4073): Perf Test app loaded loaded
I/jxcore-log( 4073): 
,I/jxcore-log( 4073): check test folder
I/jxcore-log( 4073): 
,I/jxcore-log( 4073): found test : ./testFindPeers.js
I/jxcore-log( 4073): 
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  428): NL - Read 1000 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
,D/TCMD    (  428): Listening for incoming client connection request
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
D/TCMD    (  428): NL - Read 1000 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 68 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 68 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1017): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1017): InitialState.processMessage what=4
,V/ConnectivityService( 1017): WiFi NOT Tethered!
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/jxcore-log( 4073): found test : ./testSendData.js
I/jxcore-log( 4073): 
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  428): NL - Read 60 bytes from update socket.
D/TCMD    (  428): NL - ignore NL message, type = 21
,D/TCMD    (  428): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1017): connected time updated 291839
,D/WifiStateMachine( 1017): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1017): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1017): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1017): resetConnections(wlan0, 3)
D/NetUtils( 1017): android_net_utils_resetConnections in env=0x61190550 clazz=0x61e00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1017): DisconnectingState
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131146
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147460
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection lost
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1358): Read error: ssl=0x63290628: I/O error during system call, Connection timed out
,V/NativeCrypto( 1358): SSL shutdown failed: ssl=0x63290628: I/O error during system call, Broken pipe
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
,D/WifiStateMachine( 1017): handleMessage: X
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1206): INET_CONDITION=0 ,activeNet=null
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1206): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=0
,I/chromium( 4073): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TCMD    (  428): NL - Read 56 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
,D/TCMD    (  428): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1168): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1168): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  428): NL - Read 312 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 192 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 68 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 1000 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  428): NL - Read 80 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 80 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/TCMD    (  428): NL - Read 68 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
,D/TCMD    (  428): Listening for incoming client connection request,
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  428): NL - Read 1000 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
,D/TCMD    (  428): Listening for incoming client connection request
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1192162480
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147459
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection established
,D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1017): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1017): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@443e1a78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=196612
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427514e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427514e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  428): NL - Read 56 bytes from update socket.
D/TCMD    (  428): NL - message type is RTM_NEWLINK
D/TCMD    (  428): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 10
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 10
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiP2pService( 1017): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4319d5c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@4319d5c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@4319d5c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: X
,D/TCMD    (  428): NL - Read 60 bytes from update socket.
D/TCMD    (  428): NL - ignore NL message, type = 20
,D/TCMD    (  428): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): DHCP successful
D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1017): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1017): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1017): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState enter
D/WifiStateMachine( 1017): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=151572
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1017): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=135190
,D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1017): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1017): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1017): CaptivePortalCheckState enter
,D/WifiStateMachine( 1017): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1017): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1017): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1017): WiFi NOT Tethered!
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@42024e30
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1017): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1206): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1017): WiFi NOT Tethered!
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@42024e30
D/WifiStateMachine( 1017): handleMessage: X
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1206): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=0
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1017): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager( 1017): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4208 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1568): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/dalvikvm( 4208): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f53aa0, skipping init
I/openssl ( 4208): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4208): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4230 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3729:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4230): mnc/mcc: 
V/MmsConfig( 4230): tag: bool value: enabledMMS - true
,V/MmsConfig( 4230): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4230): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4230): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4230): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4230): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4230): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4230): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4230): tag: int value: recipientLimit - 20
V/MmsConfig( 4230): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4230): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4230): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4230): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4230): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4230): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4230): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4230): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4230): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4249 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 3902:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4249): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4249): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4249): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4249): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4262 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3428:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452271950801 min interval config: 0 actual interval: 279816
,I/CheckinService( 1419): Checking schedule, now: 1452272230632 next: 1452271980752
,I/CheckinService( 1419): active receiver: enabled
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/CheckinService( 1419): Preparing to send checkin request
,I/EventLogService( 1419): Accumulating logs since 1452271946926
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/CheckinRequestBuilder( 1419): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1419): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4278 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3931:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4278): Binding Chromium to main looper Looper (main, tid 1) {41f45d40}
,I/LibraryLoader( 4278): Expected native library version number "",actual native library version number ""
,I/chromium( 4278): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4278): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4278): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4278): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4278): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4278): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4278): Local Branch: 
I/Adreno-EGL( 4278): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4278): Local Patches: NONE
I/Adreno-EGL( 4278): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4278): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4278): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  262): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1017): GC_EXPLICIT freed 23406K, 65% free 18156K/50880K, paused 5ms+11ms, total 168ms
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1017): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4312 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4312): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4312): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4312): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4312): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4312): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4312): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4312): install
,I/MultiDex( 4312): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4312): loading existing secondary dex files
,I/MultiDex( 4312): load found 3 secondary dex files
,I/NSApplication( 4278): Starting up...
,I/MultiDex( 4312): install done
,I/ImageResourceManager( 3459): ImageResourceManager: uninitalized
,I/iu.Environment( 3459): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1017): Killing 3444:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1017): NetTransition Wakelock for ConnectedState released by timeout
D/dalvikvm( 4312): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4312): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4312): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4312): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4312): VFY: unable to resolve instance field 36
,D/dalvikvm( 4312): VFY: replacing opcode 0x54 at 0x005f
I/openssl ( 4208): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4208): Crypto mode 0 already enabled
D/dalvikvm( 4312): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4312): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4312): VFY: replacing opcode 0x62 at 0x0047
I/jxcore-log( 4073): Connected to the server!
I/jxcore-log( 4073): 
D/dalvikvm( 4312): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4312): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/WifiStateMachine( 1017): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/ConnectivityService( 1017): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1017):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,D/MobileConnectivityChangeReceiver( 4249): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
D/dalvikvm( 4312): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f4bd58
D/dalvikvm( 4312): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f4bd58
D/dalvikvm( 4312): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f4bd58, skipping init
I/chromium( 4073): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
D/MobileConnectivityChangeReceiver( 4249): onReceive CONNECTIVITY_CHANGE networkType=1
D/dalvikvm( 4312): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f4bd58
D/dalvikvm( 4312): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f4bd58
V/JNIHelp ( 4312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/iu.Environment( 3459): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): onServiceConnected()
D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 3459): GC_CONCURRENT freed 628K, 5% free 16441K/17224K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 4312): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f4bd58
,D/dalvikvm( 4312): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f4bd58
D/dalvikvm( 4312): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f4bd58
,D/dalvikvm( 4312): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f4bd58
,I/jxcore-log( 4073): --- start :testFindPeers.js---
I/jxcore-log( 4073): 
,I/jxcore-log( 4073): testFindPeers created [object Object]
I/jxcore-log( 4073): 
,I/jxcore-log( 4073): serverPort is 8876
I/jxcore-log( 4073): 
I/dalvikvm( 4073): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4073): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4073): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4073): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4073): start: Peer ID: F4:F1:E1:5C:3B:E2, peer name: XT1039
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4073): bind: Binding a new listener
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4073): initialize: My bluetooth address is F4:F1:E1:5C:3B:E2
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4073): verifyIdentityString: Identity string created: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"XT1039"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4073): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4073): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1750): SOCK FLAG = 0 ***********************
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4073): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4073): start: OK
I/io.jxcore.node.ConnectionHelper( 4073): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4073): start: Peer ID: F4:F1:E1:5C:3B:E2, peer name: XT1039
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4073): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4073): bind: Binding a new listener
,W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4073): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
W/dalvikvm( 4073): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 4073): VFY: replacing opcode 0x22 at 0x0013
,W/dalvikvm( 4073): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
I/dalvikvm( 4073): Could not find method android.bluetooth.le.ScanResult.getScanRecord, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.checkScanResult
W/dalvikvm( 4073): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
,D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0002
E/dalvikvm( 4073): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 4073): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 4073): VFY: replacing opcode 0x22 at 0x002d
W/dalvikvm( 4073): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4073): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4073): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.start
W/dalvikvm( 4073): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
,D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0016
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4073): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.stop, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stop
W/dalvikvm( 4073): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
D/dalvikvm( 4073): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
D/dalvikvm( 4073): DexOpt: unable to opt direct call 0x0709 at 0x15 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
W/dalvikvm( 4073): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
W/dalvikvm( 4073): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/dalvikvm( 4073): DexOpt: unable to opt direct call 0x072a at 0x25 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
D/dalvikvm( 4073): DexOpt: unable to opt direct call 0x0048 at 0x2f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
D/dalvikvm( 4073): DexOpt: unable to opt direct call 0x005c at 0x5f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/AndroidRuntime( 4073): Shutting down VM
,W/dalvikvm( 4073): threadid=1: thread exiting with uncaught exception (group=0x4167ad40)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at android.os.Looper.loop(Looper.java:136)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): 	at dalvik.system.NativeStart.main(Native Method)
,I/ProviderInstaller( 4312): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1249): callingUid 10022, callindPid: 1249
,D/LocationInitializer( 1419): Restart initialization of location
D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,E/MDM     ( 1249): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1249): No location to return for getLastLocation()
,W/FusedLocationProvider( 1249): location=null
,I/dalvikvm( 4312): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4312): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4312): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4312): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4312): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4312): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4312): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4312): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4312): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4312): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4312): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 4312): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4312): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4312): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4312): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4312): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4312): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51d4000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51d4000
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1052372322
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4312): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4312): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42195700
D/dalvikvm( 4312): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42195700
,D/dalvikvm( 4312): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42195700, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4312): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4350): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4312): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4312): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 77ms
,I/Adreno-EGL( 4312): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4312): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4312): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4312): Local Branch: 
I/Adreno-EGL( 4312): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4312): Local Patches: NONE
I/Adreno-EGL( 4312): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4312): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4312): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4312): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4312): Local Branch: 
I/Adreno-EGL( 4312): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4312): Local Patches: NONE
I/Adreno-EGL( 4312): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1287526963
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4312): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4312): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4312): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4312): Local Branch: 
I/Adreno-EGL( 4312): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4312): Local Patches: NONE
I/Adreno-EGL( 4312): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4312): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4312): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4312): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4312): Local Branch: 
I/Adreno-EGL( 4312): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4312): Local Patches: NONE
I/Adreno-EGL( 4312): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4312): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1419): Classify the device as Phone.
,I/CheckinTask( 1419): Sending checkin request (11749 bytes)
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/PollingManager( 1568): now: 323104 ,futureTime: 17863810
,D/PollingManager( 1568): Polling alarm set to expire at: 17863810 Current Time: 323105
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1568): now: 323116 ,futureTime: 17863810
D/PollingManager( 1568): Polling alarm set to expire at: 17863810 Current Time: 323116
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/openssl ( 4208): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4208): Crypto mode 0 already enabled
E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4249): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4249): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
D/dalvikvm( 3459): GC_FOR_ALLOC freed 38K, 5% free 16405K/17224K, paused 13ms, total 13ms
I/dalvikvm-heap( 3459): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
I/iu.Environment( 3459): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452271950801 min interval config: 0 actual interval: 282465
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
D/dalvikvm( 3459): GC_FOR_ALLOC freed 4K, 5% free 18183K/19004K, paused 13ms, total 13ms
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4208): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4208): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4249): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4249): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3459): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452271950801 min interval config: 0 actual interval: 282511
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): onServiceConnected()
D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1568): onServiceConnected()
,D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1017): Activity reported stop, but no longer stopping: ActivityRecord{42098b20 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1017): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,123
,I/CheckinRequestBuilder( 1419): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1419): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1419): Classify the device as Phone.
,I/CheckinTask( 1419): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1419): Checking schedule, now: 1452272234133 next: 1452865304125
,I/CheckinService( 1419): active receiver: disabled
,I/CheckinService( 1419): Checking schedule, now: 1452272234149 next: 1452865304125
,I/CheckinService( 1419): active receiver: disabled
,D/CheckinService( 1419): Recording last checkin time for package unspecified as 1452272234154
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1206): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1206): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4278): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1017): Killing 3960:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4407 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
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
I/Launcher( 1316): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/Launcher( 1316): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/GCoreNlp( 1249): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4407): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4407): MmsConfig.loadMmsSettings
I/Babel   ( 4407): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4407): MmsConfig.loadFromDatabase
,E/Babel   ( 4407): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4407): MmsConfig.loadFromResources
,E/Babel   ( 4407): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4407): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4407): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1017): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4445 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1017): Killing 3478:com.android.vending/u0a38 (adj 15): empty #9
I/ActivityManager( 1017): Killing 4208:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4465 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ContactLocale( 4445): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 1017): GC_EXPLICIT freed 1517K, 65% free 18092K/50880K, paused 4ms+10ms, total 93ms
,I/InternalIcingCorporaPro( 2294): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4482 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4230:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4482): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4482): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4482): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4482): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4482): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4482): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4482): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2294): UpdateCorporaTask done [took 210 ms] updated apps [took 210 ms] 
,D/Finsky  ( 4482): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4482): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4482): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4482): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4482): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4482): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4482): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4482): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4482): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4482): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4482): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4516 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4482): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4482): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4482): Skipping gmscore version check
,D/Finsky  ( 4482): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4482): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4482): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4482): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1017): Killing 4249:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1419): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1419): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1419): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4516): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f52268, skipping init
I/openssl ( 4516): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4516): Crypto mode 0 already enabled
,D/Finsky  ( 4482): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4482): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1017): Killing 4262:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1419): GC_CONCURRENT freed 1954K, 31% free 12050K/17224K, paused 4ms+4ms, total 45ms
,I/Icing   ( 1419): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1419): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452272242
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1017): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1017): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1017): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1017): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1017): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1017): sending alarm Alarm{4237aeb0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4231be50 type 3 android}
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
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 1750): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1750): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1750): Entering PendingCommandState State
,D/BluetoothManagerService( 1017): Message: 20
,D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427de100:true
,I/ActivityManager( 1017): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=4560 uid=10011 gids={50011, 3003, 3002, 3001}
,D/BluetoothManagerService( 1017): Message: 20
,D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42417a68:true
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1017): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4573 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1017): Killing 4278:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 1750): Ftp Service onStartCommand
V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/ActivityManager( 1017): Killing 4312:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/bt-btif ( 1750): services_to_search = 3fffffff
,E/bt-btif ( 1750): ****************search UUID = 1200***********
,W/bt-sdp  ( 1750): process_service_search_attr_rsp
,E/bt-btif ( 1750): services_to_search = 3ffffffe
,E/bt-btif ( 1750): ****************search UUID = 0100***********
,W/bt-btif ( 1750): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1750): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1750): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Incoming connection initialized (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Waiting for incoming connections...,
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4073): Entering thread (ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): onBytesRead: Read 63 bytes successfully (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): onBytesWritten: 65 bytes successfully written (thread ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): removeThreadFromList: Removing thread with ID 341
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Handshake thread disposed (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
,W/bt-sdp  ( 1750): process_service_search_attr_rsp
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4073): Exiting thread (ID: 341)
,E/bt-btif ( 1750): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1750): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 1750): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1750): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1750): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1750): StableState(): Entering Off State
,D/BluetoothMetrics( 1750): btclass5a020c
,D/Checkin ( 1750): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1750): send none, EAGAIN or EWOULDBLOCK, errno:11
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f34136c rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 1750): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1750): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1750): Entering PendingCommandState State
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f3411b0 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 1750): services_to_search = 3fffffff
,E/bt-btif ( 1750): ****************search UUID = 1200***********
,W/bt-sdp  ( 1750): process_service_search_attr_rsp
,E/bt-btif ( 1750): services_to_search = 3ffffffe
,E/bt-btif ( 1750): ****************search UUID = 0100***********
,W/bt-btif ( 1750): new conn_srvc id:26, app_id:255
W/bt-btif ( 1750): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1750): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Incoming connection initialized (thread ID: 342)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4073): Entering thread (ID: 342)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f34136c rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f34136c rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): onBytesRead: Read 66 bytes successfully (thread ID: 342)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Got valid identity from [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): onBytesWritten: 65 bytes successfully written (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): removeThreadFromList: Removing thread with ID 342
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Handshake thread disposed (thread ID: 342)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4073): Exiting thread (ID: 342)
,W/bt-sdp  ( 1750): process_service_search_attr_rsp
,E/bt-btif ( 1750): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1750): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 1750): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1750): Failed to remove device: E0:DB:10:14:E2:C0
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1750): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 1750): StableState(): Entering Off State
,D/BluetoothMetrics( 1750): btclass5a020c
,D/Checkin ( 1750): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f341528 rs_disc_pending=0
,W/bt-btif ( 1750): info:x10
,D/        ( 1750): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1750): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f34136c rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f341528 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f341528 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 1750): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
I/BluetoothBondStateMachine( 1750): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1750): Entering PendingCommandState State
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1750): send none, EAGAIN or EWOULDBLOCK, errno:11
,E/bt-btif ( 1750): services_to_search = 3fffffff
,E/bt-btif ( 1750): ****************search UUID = 1200***********
,W/bt-sdp  ( 1750): process_service_search_attr_rsp
,E/bt-btif ( 1750): services_to_search = 3ffffffe
,E/bt-btif ( 1750): ****************search UUID = 0100***********
,W/bt-btif ( 1750): new conn_srvc id:26, app_id:255
W/bt-btif ( 1750): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1750): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Incoming connection initialized (thread ID: 343)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4073): Entering thread (ID: 343)
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
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f341528 rs_disc_pending=1
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): onBytesRead: Read 66 bytes successfully (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Got valid identity from [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): onBytesWritten: 65 bytes successfully written (thread ID: 343)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): removeThreadFromList: Removing thread with ID 343
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4073): Handshake thread disposed (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4073): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4073): Exiting thread (ID: 343)
,W/bt-sdp  ( 1750): process_service_search_attr_rsp
,E/bt-btif ( 1750): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1750): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1750): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1750): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
D/BluetoothAdapterProperties( 1750): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1750): Failed to remove device: 34:FC:EF:11:AE:67
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1750): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1750): StableState(): Entering Off State
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothMetrics( 1750): btclass5a020c
,D/Checkin ( 1750): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1750): send none, EAGAIN or EWOULDBLOCK, errno:11
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,D/btif_config_util( 1750): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 1
,W/bt-btif ( 1750): proc dm_pm_timer expires
,V/AlarmManager( 1017): sending alarm Alarm{421015b8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42354960 type 1 com.android.deskclock}
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4622 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 4407:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 2
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f341528 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1750): tBTM_SEC_DEV:0x5f3411b0 rs_disc_pending=0
,W/bt-btif ( 1750): bta_dm_check_av:0
,W/bt-btif ( 1750): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 1
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 2
,W/bt-btif ( 1750): proc dm_pm_timer expires
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
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 1
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 1
,W/bt-btif ( 1750): proc dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 0
,W/bt-btif ( 1750): proc dm_pm_timer expires
,V/AlarmManager( 1017): sending alarm Alarm{42157908 type 3 android}
,W/bt-btif ( 1750): dm_pm_timer expires
,W/bt-btif ( 1750): dm_pm_timer expires 1
,W/bt-btif ( 1750): proc dm_pm_timer expires
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
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1750): invalid rfc slot id: 7
,D/BluetoothPbapService( 1750): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1750): invalid rfc slot id: 6
,D/BluetoothPbapService( 1750): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,E/bt-btm  ( 1750): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1750): invalid rfc slot id: 5
,D/BluetoothPbapService( 1750): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4560): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1750): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1750): Ftp Service onStartCommand
,V/BluetoothFtpService( 1750): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,D/BluetoothAdapterService(1106609864)( 1750): Get Bonded Devices being called
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{443c4b40 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4227cba0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{447333c8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{43e794e8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{422bf428 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
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
,V/AlarmManager( 1017): sending alarm Alarm{44081c80 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{432893c0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{42103d58 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{43d391f8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4202ad58 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{43e80db8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{435bccc0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42430c60 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1206): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1017): sending alarm Alarm{43c45c28 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e03878 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{420df2b8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43c45d50 type 1 com.android.deskclock}
,V/AlarmManager( 1017): sending alarm Alarm{43b02718 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{438ce8d0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43c45e10 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1017): sending alarm Alarm{43d41128 type 0 com.google.android.gms}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/EventLogService( 1419): Aggregate from 1452272230658 (log), 1452271501259 (data)
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
,V/AlarmManager( 1017): sending alarm Alarm{42097730 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{428bc908 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{439d7970 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{440c2340 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4280fbf0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42127cd8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42127d88 type 3 com.google.android.gms}
,I/ProcessStatsService( 1017): Prepared write state in 17ms
,I/ProcessStatsService( 1017): Prepared write state in 12ms
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1017): Pruning old procstats: /data/system/procstats/state-2016-01-08-02-18-48.bin
,V/AlarmManager( 1017): sending alarm Alarm{428115a0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4218c0c8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4327fe78 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{438e11e0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4205d290 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1017): sending alarm Alarm{42127dd8 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1017): sending alarm Alarm{42127eb0 type 2 com.google.android.gms}
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1206): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/AndroidRuntime( 4696): 
D/AndroidRuntime( 4696): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4696): CheckJNI is OFF
D/dalvikvm( 4696): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4696): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4696): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4696): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4696): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4696): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4696): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4696): failed to load memtrack module: -2
D/AndroidRuntime( 4696): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10527 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 4073:com.test.thalitest/u0a527 (adj 9): stop com.test.thalitest
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{44396ad8 u0 com.test.thalitest/.MainActivity t3}
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1017): WIN DEATH: Window{443a1a90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1017): Client connection lost with reason: 4
E/bt-btif ( 1750): bta_jv_rfcomm_stop_server
W/PackageSettings( 1017): Skipping PackageSetting{4220d0e8 com.example.hello/10523} due to missing metadata
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10527 user=0: pkg removed
D/dalvikvm( 1017): GC_CONCURRENT freed 2085K, 65% free 18175K/50880K, paused 5ms+9ms, total 90ms
D/dalvikvm( 2258): GC_EXPLICIT freed 5462K, 44% free 9668K/17224K, paused 2ms+5ms, total 41ms
D/dalvikvm( 1419): GC_EXPLICIT freed 888K, 31% free 11943K/17224K, paused 4ms+6ms, total 121ms
W/SQLiteConnectionPool( 1419): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/VoicemailCleanupService( 4445): Cleaning up data for package: com.test.thalitest
W/GeofencerStateMachine( 1249): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
D/dalvikvm( 2294): GC_EXPLICIT freed 2944K, 44% free 9784K/17224K, paused 2ms+24ms, total 123ms
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
D/dalvikvm( 1316): GC_EXPLICIT freed 3341K, 33% free 11598K/17224K, paused 2ms+6ms, total 85ms
I/Launcher( 1316): Deferring update until onResume
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452274037
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/InternalIcingCorporaPro( 2294): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/ActivityManager( 1017): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4728 uid=10059 gids={50059, 3003, 1028, 1015}
I/Launcher( 1316): Deferring update until onResume
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 21ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 3ms+3ms, total 20ms
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10527 #1
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452274037
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
I/InternalIcingCorporaPro( 2294): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
D/dalvikvm( 1017): GC_EXPLICIT freed 899K, 65% free 18062K/50880K, paused 7ms+15ms, total 253ms
D/AndroidRuntime( 4696): Shutting down VM
D/dalvikvm( 4696): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
W/ActiveOrDefaultContextProvider( 4728): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4751 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1017): Killing 3459:com.google.android.apps.plus/u0a90 (adj 15): empty #9
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/GAV2    ( 4728): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4772 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
E/SQLiteDatabase( 4751): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4751): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4751): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4751): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4751): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4751): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4751): threadid=10: thread exiting with uncaught exception (group=0x4167ad40)
E/AndroidRuntime( 4751): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4751): Process: com.android.keychain, PID: 4751
E/AndroidRuntime( 4751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4751): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4751): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4751): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4751): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4751): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4751): Sending signal. PID: 4751 SIG: 9
E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1017): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1017): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1017): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1017): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1017): 	... 5 more
I/ActivityManager( 1017): Process com.android.keychain (pid 4751) has died.
W/ActivityManager( 1017): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
E/SQLiteDatabase( 4772): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4772): 	at cwo.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4772): 	at cwp.a(PG:262)
E/SQLiteDatabase( 4772): 	at eec.run(PG:155)
E/SQLiteDatabase( 4772): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4772): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4772): 	at cwo.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4772): 	at cwp.a(PG:262)
E/SQLiteDatabase( 4772): 	at eec.run(PG:155)
E/SQLiteDatabase( 4772): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 4772): threadid=10: thread exiting with uncaught exception (group=0x4167ad40)

```
