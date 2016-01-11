#### Test 549702617e2936d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
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
--------- beginning of /dev/log/system
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4052
W/WindowManager( 1015): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4068 uid=10540 gids={50540, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4052): Shutting down VM
D/dalvikvm( 4052): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4068): Binding Chromium to main looper Looper (main, tid 1) {41f56c30}
I/LibraryLoader( 4068): Expected native library version number "",actual native library version number ""
I/chromium( 4068): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4068): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42339208:true
I/Adreno-EGL( 4068): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4068): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4068): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4068): Local Branch: 
I/Adreno-EGL( 4068): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4068): Local Patches: NONE
I/Adreno-EGL( 4068): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4068): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4068): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4068): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4068): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4068): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4068): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4068): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4068): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4068): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4068): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4068): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4068): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4068): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4068): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4068): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4068): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4068): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4068): Enabling debug mode 0
,W/AwContents( 4068): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4068): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1015): Displayed com.test.thalitest/.MainActivity,cp,ca,354
I/ActivityManager( 1015): Displayed com.test.thalitest/.MainActivity: +327ms (total +354ms)
,D/JsMessageQueue( 4068): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4068): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f5aff0
,D/dalvikvm( 4068): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f5aff0
,D/jxcore_app_log( 4068): JniHelper::setJavaVM(0x415a4fa8), pthread_self() = 1614193360
,D/JX-Cordova( 4068): jxcore cordova android initializing
,D/dalvikvm( 4068): GC_CONCURRENT freed 2792K, 17% free 14397K/17224K, paused 2ms+2ms, total 57ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 114K, 17% free 14395K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 125K, 17% free 14415K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.201MB for 95956-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 177K, 17% free 14450K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.281MB for 143930-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 251K, 17% free 14497K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.395MB for 215890-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 366K, 18% free 14571K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.571MB for 323830-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 565K, 19% free 14692K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.843MB for 485740-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 860K, 20% free 14867K/18472K, paused 27ms, total 27ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 1275K, 19% free 15123K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 17.843MB for 1092904-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 1736K, 21% free 15503K/19540K, paused 3ms+5ms, total 37ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 302K, 21% free 15443K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 18.676MB for 1639352-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 1693K, 25% free 16020K/21144K, paused 2ms+4ms, total 32ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 1289K, 24% free 16078K/21144K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 20.079MB for 2459024-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 1781K, 29% free 16795K/23548K, paused 4ms+4ms, total 41ms
,D/dalvikvm( 4068): GC_CONCURRENT freed 2364K, 28% free 17029K/23548K, paused 2ms+7ms, total 43ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 641K, 29% free 16897K/23548K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 22.051MB for 3688532-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 2688K, 34% free 18097K/27152K, paused 4ms+5ms, total 50ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 752K, 34% free 18016K/27152K, paused 28ms, total 28ms
,W/jxcore-log( 4068): Initializing JXcore engine
,W/jxcore-log( 4068): JXcore engine is ready
,D/dalvikvm( 4068): GC_CONCURRENT freed 363K, 24% free 20644K/27152K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 24ms
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
D/WifiService( 1015): New client listening to asynchronous messages
D/WifiService( 1015): setWifiEnabled: true pid=4068, uid=10540
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1015): handleMessage: E msg.what=131145
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
I/jxcore-log( 4068): Radios toggled
I/jxcore-log( 4068): 
I/jxcore-log( 4068): My device name is: motorola-XT1039
I/jxcore-log( 4068): 
,D/TCMD    (  454): NL - Read 1000 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
,D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
I/wpa_supplicant( 1147): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  271): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  271):  STA Disconnected !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0,
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1015): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/Tethering( 1015): InitialState.processMessage what=4
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1015): WiFi NOT Tethered!
,D/WifiStateMachine( 1015): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1015): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1015): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1147): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1147): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  454): NL - Read 60 bytes from update socket.
D/TCMD    (  454): NL - ignore NL message, type = 21
D/TCMD    (  454): Listening for incoming client connection request
D/WifiStateMachine( 1015): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1015): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1015): connected time updated 300293
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1077): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1015): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1077): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1077): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1077): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1015): resetConnections(wlan0, 3)
D/NetUtils( 1015): android_net_utils_resetConnections in env=0x61192620 clazz=0x61200001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1015): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1015): DisconnectingState
E/wpa_supplicant( 1147): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1147): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131146
D/WifiStateMachine( 1015): processMsg: DisconnectingState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147460
D/WifiStateMachine( 1015): processMsg: DisconnectingState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): Network connection lost
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1382): Read error: ssl=0x63097950: I/O error during system call, Connection timed out
,V/NativeCrypto( 1382): SSL shutdown failed: ssl=0x63097950: I/O error during system call, Broken pipe
,D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1147): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1147): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1077): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): transitionTo: destState=DisconnectedState
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1015): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=4
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1015): Attempting to switch to mobile
I/ModemStatsDSDetect( 1197): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1197): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1197): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1197): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1197): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1197): onReceive() - done, currentInetCondition=0
,D/TCMD    (  454): NL - Read 56 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
,D/TCMD    (  454): Listening for incoming client connection request
I/wpa_supplicant( 1147): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
E/wpa_supplicant( 1147): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  271): Event received = Trying to associate with
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,I/wpa_supplicant( 1147): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1147): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  454): NL - Read 312 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 88 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 1000 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
I/wpa_supplicant( 1147): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  454): NL - Read 80 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 80 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
,D/TCMD    (  454): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  271): Event received = Associated with c0:ff:d4
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
,D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1147): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1147): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  454): NL - Read 1000 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  271): Event received = WPA: Key negotiation com
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271):  STA Connected !!
E/MDMCTBK (  271): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  271): get_freq !!, resp=0
I/MDMCTBK (  271): get_freq !!, Strip data
I/MDMCTBK (  271): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  271): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  271): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193256112
I/MDMCTBK (  271): return from set_get_from_wpa_supplicant
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1015): handleMessage: X
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  271): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  271): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  271): , reply_len: 3, ret: 0
E/MDMCTBK (  271): MdmCutbackHndler, resp=OK
E/MDMCTBK (  271): 
,D/MDMCTBK (  271): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): Network connection established
,D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1077): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1015): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1015): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1015): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1015): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@441619f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=196612
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420c1700 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420c1700 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  454): NL - Read 56 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4481bfa0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4481bfa0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4481bfa0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  454): NL - Read 60 bytes from update socket.
D/TCMD    (  454): NL - ignore NL message, type = 20
,D/TCMD    (  454): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
,D/WifiStateMachine( 1015): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): DHCP successful
D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1015): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1015): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1015): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState enter
D/WifiStateMachine( 1015): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1077): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=151572
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1077): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=135190
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1015): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1015): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): CaptivePortalCheckState enter
,D/WifiStateMachine( 1015): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1077): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1015): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1015): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1077): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1015): WiFi NOT Tethered!
,E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@4202f450
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1077): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1015): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1015): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: ConnectedState
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,I/SBar.NetworkController( 1077): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1077): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1197): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1197): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1197): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1015): WiFi NOT Tethered!
E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@4202f450
,D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1197): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1197): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1197): onReceive() - done, currentInetCondition=0
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1015): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1077): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1015): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1077): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1077): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/Tethering( 1015): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1077): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1077): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1573): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1573): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1573): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1573): [debug] > CusSM.onRadioDown
E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
,I/openssl ( 3981): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3981): Crypto mode 0 already enabled
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4193 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,D/ConnectivityService( 1015): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 1015): GC_EXPLICIT freed 1998K, 65% free 18141K/50972K, paused 3ms+11ms, total 101ms
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,V/MmsConfig( 4193): mnc/mcc: 
V/MmsConfig( 4193): tag: bool value: enabledMMS - true
,V/MmsConfig( 4193): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4193): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4193): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4193): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4193): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4193): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4193): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4193): tag: int value: recipientLimit - 20
,V/MmsConfig( 4193): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4193): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4193): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4193): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4193): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4193): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4193): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4193): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4193): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1015): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4215 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1015): Killing 3859:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  273): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 23ms
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,D/MobileConnectivityChangeReceiver( 4215): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4215): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4215): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4215): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4229 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3899:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452525607777 min interval config: 0 actual interval: 289895
,I/CheckinService( 1419): Checking schedule, now: 1452525897682 next: 1452525637752
,I/CheckinService( 1419): active receiver: enabled
,I/CheckinService( 1419): Preparing to send checkin request
,I/EventLogService( 1419): Accumulating logs since 1452525604410
,I/CheckinRequestBuilder( 1419): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1419): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4243 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3921:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4243): Binding Chromium to main looper Looper (main, tid 1) {41f4fb98}
I/LibraryLoader( 4243): Expected native library version number "",actual native library version number ""
I/chromium( 4243): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4243): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4243): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4243): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4243): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4243): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4243): Local Branch: 
I/Adreno-EGL( 4243): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4243): Local Patches: NONE
I/Adreno-EGL( 4243): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1382): GC_EXPLICIT freed 1485K, 40% free 10340K/17224K, paused 2ms+5ms, total 43ms
,W/chromium( 4243): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4243): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4243): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1015): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4277 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4277): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4277): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4277): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4277): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4277): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4277): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4277): install
,I/MultiDex( 4277): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4277): loading existing secondary dex files
,I/MultiDex( 4277): load found 3 secondary dex files
,I/MultiDex( 4277): install done
,D/dalvikvm( 4277): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4277): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4277): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4277): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4277): VFY: unable to resolve instance field 36
,D/dalvikvm( 4277): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4277): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4277): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4277): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4277): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4277): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4277): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f55d40
,D/dalvikvm( 4277): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f55d40
,D/dalvikvm( 4277): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f55d40, skipping init
,D/dalvikvm( 4277): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f55d40
D/dalvikvm( 4277): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f55d40
,V/JNIHelp ( 4277): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4243): Starting up...
,D/dalvikvm( 4277): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f55d40
,D/dalvikvm( 4277): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f55d40
D/dalvikvm( 4277): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f55d40
,D/dalvikvm( 4277): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f55d40
,I/ImageResourceManager( 3961): ImageResourceManager: uninitalized
,I/iu.Environment( 3961): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1015): Killing 3936:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1573): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1573): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1573): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1573): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1573): onServiceConnected()
,D/GetNotificationsWS( 1573): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1573): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1573): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1573): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3981): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3981): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4215): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4215): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3961): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ProviderInstaller( 4277): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1244): callingUid 10022, callindPid: 1244
,E/MDM     ( 1244): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1382): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1382): Proximity feature is not enabled.
,D/LocationInitializer( 1419): Restart initialization of location
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4277): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4277): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4277): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4277): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4277): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4277): VFY: replacing opcode 0x6e at 0x000d
,W/GCoreFlp( 1244): No location to return for getLastLocation()
,W/FusedLocationProvider( 1244): location=null
,I/dalvikvm( 4277): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4277): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4277): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4277): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4277): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4277): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4277): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4277): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4277): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4277): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4277): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  275): Instantiating CDM.
,I/WVCdm   (  275): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  275): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  275): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  275): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5162000
,E/DrmWidevineDash(  275): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5162000
D/DrmWidevineDash(  275): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  275): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  275): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  275): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  275): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  275): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=4126223534
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4277): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4277): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42120408
,D/dalvikvm( 4277): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42120408
,D/dalvikvm( 4277): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42120408, skipping init
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
,D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  275): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=1599057098
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
,D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,W/Settings( 4277): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4277): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4316): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4277): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4277): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4277): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4277): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4277): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4277): Local Branch: 
I/Adreno-EGL( 4277): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4277): Local Patches: NONE
I/Adreno-EGL( 4277): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4277): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4277): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4277): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4277): Local Branch: 
I/Adreno-EGL( 4277): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4277): Local Patches: NONE
I/Adreno-EGL( 4277): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4277): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4277): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4277): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4277): Local Branch: 
I/Adreno-EGL( 4277): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4277): Local Patches: NONE
I/Adreno-EGL( 4277): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4277): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4277): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4277): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4277): Local Branch: 
I/Adreno-EGL( 4277): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4277): Local Patches: NONE
I/Adreno-EGL( 4277): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1077): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1077): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,D/PollingManager( 1573): now: 332167 ,futureTime: 21287790
,D/PollingManager( 1573): Polling alarm set to expire at: 21287790 Current Time: 332167
,E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1573): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1573): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,I/openssl ( 3981): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3981): Crypto mode 0 already enabled
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/Tethering( 1015): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1077): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1077): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1573): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
D/PollingManager( 1573): now: 332205 ,futureTime: 21287790
D/PollingManager( 1573): Polling alarm set to expire at: 21287790 Current Time: 332206
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,I/OtaApp  ( 1573): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,E/ActivityThread( 1573): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1573): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,D/OtaApp  ( 1573): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1573): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1573): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MobileConnectivityChangeReceiver( 4215): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4215): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1573): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1276): Column apn id key is 'apn_id'
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 604K, 5% free 16434K/17224K, paused 17ms, total 18ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 19.817MB for 1821008-byte allocation
,I/iu.Environment( 3961): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452525607777 min interval config: 0 actual interval: 291967
,D/DEBUG   ( 1573): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1573): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1573): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1573): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1573): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1573): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 30K, 5% free 18186K/19004K, paused 33ms, total 34ms
,D/GetNotificationsWS( 1573): onServiceConnected()
D/GetNotificationsWS( 1573): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1573): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 3981): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3981): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4215): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4215): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3961): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1419): Checkin interval check for package: unspecified last checkin: 1452525607777 min interval config: 0 actual interval: 292037
,D/DEBUG   ( 1573): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1573): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1573): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1573): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1573): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1573): onServiceConnected()
D/GetNotificationsWS( 1573): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1573): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1573): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1573): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1015): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1573
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1573): unbindWebServices(): un-registering our AIDL callback...
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
I/SFPerfTracer(  272):      triggers: (rate: 2:34) (compose: 0:4) (post: 0:1) (render: 0:5) (0:115 frames) (1:551)
,D/SFPerfTracer(  272):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:212)* (NavigationBar: 0:41)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:4)* 
D/OtaApp  ( 1573): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1573): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1015): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1573
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1573): [info] > Updatetime from metadata: 10
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1573): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1573): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1015): Activity reported stop, but no longer stopping: ActivityRecord{428f42e0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1015): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,120
,V/AlarmManager( 1015): sending alarm Alarm{42248720 type 3 android}
,I/CheckinRequestBuilder( 1419): Classify the device as Phone.
,I/CheckinTask( 1419): Sending checkin request (11805 bytes)
,I/CheckinRequestBuilder( 1419): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1419): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1015): GC_EXPLICIT freed 742K, 65% free 18004K/50972K, paused 3ms+8ms, total 91ms
,I/CheckinRequestBuilder( 1419): Classify the device as Phone.
,I/CheckinTask( 1419): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1419): Checking schedule, now: 1452525900836 next: 1453118970823
,I/CheckinService( 1419): active receiver: disabled
,I/CheckinService( 1419): Checking schedule, now: 1452525900857 next: 1453118970823
,I/CheckinService( 1419): active receiver: disabled
,D/CheckinService( 1419): Recording last checkin time for package unspecified as 1452525900863
,D/GCM     ( 1382): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine( 1015): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1015): handleMessage: X
,D/ConnectivityService( 1015): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1015):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1197): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1077): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1077): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1197): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1077): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1197): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1197): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1077): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4243): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1015): Killing 3881:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4068): Test app app.js loaded
I/jxcore-log( 4068): 
,I/Choreographer( 4068): Skipped 701 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 4068): showStatusIcon on inactive InputConnection
,I/chromium( 4068): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4068): --= Surplus to requirements =--
I/jxcore-log( 4068): 
,I/jxcore-log( 4068): ****TEST TOOK:  ms ****
I/jxcore-log( 4068): 
,I/jxcore-log( 4068): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4068): 
,D/AndroidRuntime( 4365): 
D/AndroidRuntime( 4365): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4365): CheckJNI is OFF
,D/dalvikvm( 4365): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4365): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4365): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4365): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4365): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4365): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4365): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4365): failed to load memtrack module: -2
,D/AndroidRuntime( 4365): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10540 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 4068:com.test.thalitest/u0a540 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{4277b0a0 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1015): WIN DEATH: Window{427c85f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1015): Client connection lost with reason: 4
,W/PackageSettings( 1015): Skipping PackageSetting{42217020 com.example.hello/10529} due to missing metadata
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10540 user=0: pkg removed
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1015): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4380 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
W/GeofencerStateMachine( 1244): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,D/dalvikvm( 2274): GC_EXPLICIT freed 5176K, 44% free 9647K/17224K, paused 2ms+6ms, total 67ms
,I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452525906
,I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
D/dalvikvm( 1419): GC_EXPLICIT freed 1721K, 31% free 12010K/17224K, paused 4ms+7ms, total 132ms
,D/dalvikvm( 2306): GC_EXPLICIT freed 2411K, 44% free 9771K/17224K, paused 2ms+4ms, total 145ms
,D/dalvikvm( 1015): GC_EXPLICIT freed 877K, 65% free 18022K/50972K, paused 5ms+12ms, total 133ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
D/dalvikvm( 1318): GC_EXPLICIT freed 3142K, 33% free 11593K/17224K, paused 6ms+7ms, total 139ms
I/Launcher( 1318): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452525906
,I/Launcher( 1318): Deferring update until onResume
,D/VoicemailCleanupService( 4380): Cleaning up data for package: com.test.thalitest
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager( 1015): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4402 uid=10033 gids={50033, 3003, 1028, 1015}
,V/BackupManagerService( 1015): removePackageParticipantsLocked: uid=10540 #1
,D/dalvikvm( 1015): GC_EXPLICIT freed 327K, 65% free 18087K/50972K, paused 13ms+14ms, total 166ms
,I/ActivityManager( 1015): Killing 3508:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2306): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4418 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3981:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4380): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/AndroidRuntime( 4365): Shutting down VM
,D/dalvikvm( 4365): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,I/InternalIcingCorporaPro( 2306): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
,W/ActiveOrDefaultContextProvider( 4418): Missing scope.enter somewhere. Returning default context
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4441 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/GAV2    ( 4418): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4441): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4462 uid=10038 gids={50038, 3003, 1028, 1015}
,E/SQLiteDatabase( 4441): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4441): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4441): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4441): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4441): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4441): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4441): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4441): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4441): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4441): threadid=10: thread exiting with uncaught exception (group=0x41683d40)
E/AndroidRuntime( 4441): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4441): Process: com.android.keychain, PID: 4441
E/AndroidRuntime( 4441): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4441): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4441): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4441): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4441): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4441): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4441): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4441): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4441): Sending signal. PID: 4441 SIG: 9
E/DropBoxManagerService( 1015): Can't write: system_app_crash
E/DropBoxManagerService( 1015): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1015): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1015): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1015): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1015): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1015): 	... 5 more

```
