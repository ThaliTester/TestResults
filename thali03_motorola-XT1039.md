#### Test 549702619369e5e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{427f0ae8 type 3 android}
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
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4052
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4068 uid=10533 gids={50533, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4052): Shutting down VM
D/dalvikvm( 4052): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4068): Binding Chromium to main looper Looper (main, tid 1) {41fa9d30}
I/LibraryLoader( 4068): Expected native library version number "",actual native library version number ""
I/chromium( 4068): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4068): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42588818:true
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
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,359
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +335ms (total +360ms)
W/AwContents( 4068): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4068): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4068): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4068): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fae000
,D/dalvikvm( 4068): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fae000
D/jxcore_app_log( 4068): JniHelper::setJavaVM(0x415f8fa8), pthread_self() = 1614536120
D/JX-Cordova( 4068): jxcore cordova android initializing
,D/dalvikvm( 4068): GC_CONCURRENT freed 2783K, 17% free 14382K/17224K, paused 3ms+2ms, total 63ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 165K, 17% free 14401K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 132K, 17% free 14416K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.202MB for 95956-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 180K, 17% free 14450K/17320K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.281MB for 143930-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 253K, 17% free 14497K/17464K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.396MB for 215890-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 369K, 18% free 14571K/17676K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.571MB for 323830-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 569K, 19% free 14692K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 16.843MB for 485740-byte allocation
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 865K, 20% free 14868K/18472K, paused 26ms, total 27ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 1282K, 19% free 15123K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 17.843MB for 1092904-byte allocation
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4068): GC_CONCURRENT freed 1777K, 21% free 15539K/19540K, paused 3ms+6ms, total 60ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 278K, 21% free 15442K/19540K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 18.675MB for 1639352-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 1734K, 25% free 16036K/21144K, paused 3ms+7ms, total 47ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 1272K, 24% free 16076K/21144K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 20.078MB for 2459024-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 457K, 22% free 18417K/23548K, paused 5ms+7ms, total 79ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 4208K, 28% free 17056K/23548K, paused 35ms, total 35ms
,I/dalvikvm-heap( 4068): Grow heap (frag case) to 22.207MB for 3688532-byte allocation
,D/dalvikvm( 4068): GC_CONCURRENT freed 331K, 25% free 20554K/27152K, paused 4ms+7ms, total 51ms
,D/dalvikvm( 4068): GC_FOR_ALLOC freed 3235K, 34% free 18064K/27152K, paused 29ms, total 29ms
,W/jxcore-log( 4068): Initializing JXcore engine
,W/jxcore-log( 4068): JXcore engine is ready
,D/dalvikvm( 4068): GC_CONCURRENT freed 414K, 24% free 20671K/27152K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 28ms
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
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4068, uid=10533
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4068): Radios toggled
I/jxcore-log( 4068): 
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 21
,D/TCMD    (  481): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 300884
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1019): DisconnectingState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x611fd1b8 clazz=0x63500001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1350): Read error: ssl=0x62f089f8: I/O error during system call, Connection timed out
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
V/NativeCrypto( 1350): SSL shutdown failed: ssl=0x62f089f8: I/O error during system call, Broken pipe
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1240): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1240): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1240): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1240): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1240): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1240): onReceive() - done, currentInetCondition=0
,D/TCMD    (  481): NL - Read 56 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  481): NL - Read 312 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  481): NL - Read 88 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
,D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
,D/TCMD    (  481): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274):  STA Connected !!
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1216133560
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
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-32ms what=147462 obj=android.net.wifi.StateChangeResult@444439d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-30ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43e99080 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42798a68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42798a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  481): NL - Read 56 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
,D/TCMD    (  481): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@435f3528 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@435f3528 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@435f3528 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 20
,D/TCMD    (  481): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/Tethering( 1019): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1296): Active network info is not available
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4183 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1296): Active network info is not available
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
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
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/dalvikvm( 4183): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fb1aa0, skipping init
I/openssl ( 4183): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4183): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4210 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3866:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4210): mnc/mcc: 
V/MmsConfig( 4210): tag: bool value: enabledMMS - true
,V/MmsConfig( 4210): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4210): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4210): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4210): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4210): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4210): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4210): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4210): tag: int value: recipientLimit - 20
V/MmsConfig( 4210): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4210): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4210): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4210): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4210): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4210): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4210): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4210): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4210): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4229 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3639:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@420b2eb0
D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 21ms
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/ModemStatsDSDetect( 1240): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1240): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1240): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@420b2eb0
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1240): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1240): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1240): onReceive() - done, currentInetCondition=0
,D/MobileConnectivityChangeReceiver( 4229): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4229): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4229): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4229): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4246 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3909:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1452291981302 min interval config: 0 actual interval: 287449
I/CheckinService( 1396): Checking schedule, now: 1452292268755 next: 1452292011268
,I/CheckinService( 1396): active receiver: enabled
,I/CheckinService( 1396): Preparing to send checkin request
,I/EventLogService( 1396): Accumulating logs since 1452291976161
,I/CheckinRequestBuilder( 1396): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1396): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4260 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3933:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4260): Binding Chromium to main looper Looper (main, tid 1) {41fa3d40}
,I/LibraryLoader( 4260): Expected native library version number "",actual native library version number ""
,I/chromium( 4260): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4260): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4260): BLUETOOTH permission is missing!
,D/dalvikvm( 1019): GC_EXPLICIT freed 1706K, 65% free 18132K/51008K, paused 4ms+10ms, total 97ms
,I/Adreno-EGL( 4260): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4260): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4260): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4260): Local Branch: 
I/Adreno-EGL( 4260): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4260): Local Patches: NONE
I/Adreno-EGL( 4260): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4260): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4290 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4260): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/GAV2    ( 4260): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 4290): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4290): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4290): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4290): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4290): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4290): install
,I/MultiDex( 4290): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4290): loading existing secondary dex files
,I/MultiDex( 4290): load found 3 secondary dex files
,I/MultiDex( 4290): install done
,D/dalvikvm( 4290): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4290): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4290): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4290): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4290): VFY: unable to resolve instance field 36
,D/dalvikvm( 4290): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4290): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4290): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4290): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4290): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4290): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa9d50
D/dalvikvm( 4290): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa9d50
,D/dalvikvm( 4290): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa9d50, skipping init
,D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fa9d50
,D/dalvikvm( 4290): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fa9d50
,V/JNIHelp ( 4290): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fa9d50
,D/dalvikvm( 4290): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fa9d50
D/dalvikvm( 4290): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fa9d50
,D/dalvikvm( 4290): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fa9d50
,I/NSApplication( 4260): Starting up...
,I/ImageResourceManager( 3672): ImageResourceManager: uninitalized
,I/iu.Environment( 3672): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 3950:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4183): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4183): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4229): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4229): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3672): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ProviderInstaller( 4290): Installed default security provider GmsCore_OpenSSL
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,D/LocationInitializer( 1396): Restart initialization of location
,D/WearableService( 1224): callingUid 10022, callindPid: 1224
,D/AuthorizationBluetoothService( 1350): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1350): Proximity feature is not enabled.
I/dalvikvm( 4290): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4290): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4290): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4290): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x000d
,V/GLSActivity( 1350): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1224): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
I/dalvikvm( 4290): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4290): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4290): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4290): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4290): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 4290): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4290): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4290): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4290): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4290): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4290): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb518d000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb518d000
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
D/WVCdm   (  279): PrepareKeyRequest: nonce=3055169073
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/NativeLibraryUtils( 4290): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4290): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421ac230
,D/dalvikvm( 4290): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421ac230
,D/dalvikvm( 4290): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421ac230, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
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
D/WVCdm   (  279): PrepareKeyRequest: nonce=1622016473
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Settings( 4290): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4290): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4336): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4290): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4290): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 67ms
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4290): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4290): Local Patches: NONE
I/Adreno-EGL( 4290): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1396): Classify the device as Phone.
,I/CheckinTask( 1396): Sending checkin request (11755 bytes)
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/CheckinRequestBuilder( 1396): Checkin reason type: 8 attempt count: 1
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1562): now: 332495 ,futureTime: 84235641
,D/PollingManager( 1562): Polling alarm set to expire at: 84235641 Current Time: 332499
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/PollingManager( 1562): now: 332536 ,futureTime: 84235641
D/PollingManager( 1562): Polling alarm set to expire at: 84235641 Current Time: 332536
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/openssl ( 4183): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4183): Crypto mode 0 already enabled
E/ActivityThread( 1396): Failed to find provider info for com.google.android.wearable.settings
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1263): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4229): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4229): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/iu.Environment( 3672): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1452291981302 min interval config: 0 actual interval: 290529
,D/dalvikvm( 3672): GC_FOR_ALLOC freed 595K, 5% free 16436K/17224K, paused 18ms, total 20ms
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/dalvikvm-heap( 3672): Grow heap (frag case) to 19.820MB for 1821008-byte allocation
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
I/openssl ( 4183): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4183): Crypto mode 0 already enabled
D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4229): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4229): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3672): GC_FOR_ALLOC freed 33K, 5% free 18184K/19004K, paused 13ms, total 14ms
,I/iu.Environment( 3672): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1452291981302 min interval config: 0 actual interval: 290613
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,I/CheckinRequestBuilder( 1396): Classify the device as Phone.
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/CheckinTask( 1396): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/CheckinService( 1396): Checking schedule, now: 1452292272005 next: 1452885341974
I/CheckinService( 1396): active receiver: disabled
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinService( 1396): Checking schedule, now: 1452292272041 next: 1452885341974
,I/CheckinService( 1396): active receiver: disabled
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,D/CheckinService( 1396): Recording last checkin time for package unspecified as 1452292272047
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,108
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{427e8ba0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/GCM     ( 1350): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1224): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1224): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/dalvikvm( 1224): GC_EXPLICIT freed 1082K, 35% free 11213K/17224K, paused 3ms+7ms, total 45ms
,I/dalvikvm( 1224): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1224): VFY: replacing opcode 0x6e at 0x003d
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 4783 seconds from now (1452292272619)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1350): GC_EXPLICIT freed 1542K, 40% free 10363K/17224K, paused 2ms+5ms, total 36ms
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1240): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1240): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1240): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1240): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1224): GC_CONCURRENT freed 1497K, 33% free 11672K/17224K, paused 4ms+8ms, total 41ms
,W/PhenotypeConfigurator( 1224): Server returned 404
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4260): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 1019): GC_EXPLICIT freed 960K, 65% free 18063K/51008K, paused 4ms+10ms, total 97ms
,I/ActivityManager( 1019): Killing 3445:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4068): Test app app.js loaded
I/jxcore-log( 4068): 
,W/IInputConnectionWrapper( 4068): showStatusIcon on inactive InputConnection
,I/chromium( 4068): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4068): --= Surplus to requirements =--
I/jxcore-log( 4068): 
,I/jxcore-log( 4068): ****TEST TOOK:  ms ****
I/jxcore-log( 4068): 
,I/jxcore-log( 4068): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4068): 
,D/AndroidRuntime( 4409): 
D/AndroidRuntime( 4409): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4409): CheckJNI is OFF
,D/dalvikvm( 4409): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4409): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4409): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4409): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4409): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4409): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4409): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4409): failed to load memtrack module: -2
,D/AndroidRuntime( 4409): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10533 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 4068:com.test.thalitest/u0a533 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{422cf990 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1019): WIN DEATH: Window{42072c88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/PackageSettings( 1019): Skipping PackageSetting{4226a208 com.example.hello/10529} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10533 user=0: pkg removed
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4421 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452292278
,D/dalvikvm( 2268): GC_EXPLICIT freed 5233K, 44% free 9651K/17224K, paused 11ms+22ms, total 88ms
,D/dalvikvm( 1308): GC_EXPLICIT freed 3236K, 33% free 11595K/17224K, paused 2ms+4ms, total 109ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1308): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/dalvikvm( 1396): GC_EXPLICIT freed 1119K, 31% free 11957K/17224K, paused 6ms+8ms, total 153ms
,W/SQLiteConnectionPool( 1396): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/dalvikvm( 2302): GC_EXPLICIT freed 4074K, 42% free 10092K/17224K, paused 32ms+23ms, total 199ms
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10533 #1
I/Launcher( 1308): Deferring update until onResume
,I/LatinIME:LogUtils( 1204): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452292278
,D/dalvikvm( 1019): GC_EXPLICIT freed 1100K, 65% free 18142K/51008K, paused 7ms+12ms, total 149ms
,D/VoicemailCleanupService( 4421): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4447 uid=10033 gids={50033, 3003, 1028, 1015}
,D/AndroidRuntime( 4409): Shutting down VM
,D/dalvikvm( 4409): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/InternalIcingCorporaPro( 2302): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4463 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4036:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4183:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1275): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2302): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
,I/ContactLocale( 4421): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ActiveOrDefaultContextProvider( 4463): Missing scope.enter somewhere. Returning default context
,E/SQLiteDatabase( 4463): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4463): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4463): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 4463): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 4463): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 4463): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4463): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 4463): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 4463): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4463): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 4463): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4463): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 4463): 	at an,droid.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4463): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4463): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4463): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4463): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4463): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4463): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4463): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4463): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4463): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4463): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4463): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4463): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4463): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 4463): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 4463): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4463): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 4463): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 4463): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4463): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4463): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 4463): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 4463): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4463): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4463): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4463): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 4463): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4463): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4463): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4463): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4463): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4463): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4463): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4463): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4463): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4463): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4463): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4463): Opened ClientFlag.db in read-only mode

```
