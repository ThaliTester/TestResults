#### Test 5198634075bb434_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3998): 
D/AndroidRuntime( 3998): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3998): CheckJNI is OFF
D/dalvikvm( 3998): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3998): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3998): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3998): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3998): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3998): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3998): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3998): failed to load memtrack module: -2
D/AndroidRuntime( 3998): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3998
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4014 uid=10423 gids={50423, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3998): Shutting down VM
D/dalvikvm( 3998): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4014): Binding Chromium to main looper Looper (main, tid 1) {41fddfc0}
I/LibraryLoader( 4014): Expected native library version number "",actual native library version number ""
I/chromium( 4014): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4014): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428b5f68:true
I/Adreno-EGL( 4014): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4014): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4014): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4014): Local Branch: 
I/Adreno-EGL( 4014): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4014): Local Patches: NONE
I/Adreno-EGL( 4014): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4014): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4014): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4014): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4014): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4014): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4014): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4014): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4014): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4014): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4014): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4014): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4014): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4014): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4014): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4014): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4014): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4014): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4014): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4014): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4014): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4014): Enabling debug mode 0
,W/AwContents( 4014): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4014): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,415
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +389ms (total +415ms)
W/IInputConnectionWrapper( 4014): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4014): Set native->JS mode to OnlineEventsBridgeMode
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4014): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe3288
,D/dalvikvm( 4014): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe3288
,D/jxcore_app_log( 4014): JniHelper::setJavaVM(0x41639f78), pthread_self() = 1614197608
,D/JX-Cordova( 4014): jxcore cordova android initializing
I/dalvikvm( 4014): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4014): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4014): VFY: replacing opcode 0x6e at 0x0045
,V/AlarmManager( 1019): sending alarm Alarm{423f3848 type 3 android}
,D/dalvikvm( 4014): GC_CONCURRENT freed 2804K, 17% free 14380K/17224K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 233K, 17% free 14369K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 195K, 17% free 14394K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 16.229MB for 146998-byte allocation
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 260K, 17% free 14442K/17368K, paused 25ms, total 26ms
I/dalvikvm-heap( 4014): Grow heap (frag case) to 16.346MB for 220492-byte allocation
,W/PluginManager( 4014): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 377K, 18% free 14517K/17584K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 16.525MB for 330734-byte allocation
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 580K, 19% free 14641K/17908K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 16.803MB for 496096-byte allocation
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 884K, 20% free 14820K/18396K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 17.215MB for 744140-byte allocation
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 1311K, 22% free 15081K/19124K, paused 28ms, total 28ms
,D/dalvikvm( 4014): GC_CONCURRENT freed 1673K, 20% free 15456K/19124K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 4014): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 4014): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 416K, 20% free 15419K/19124K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 18.687MB for 1674304-byte allocation
,D/dalvikvm( 4014): GC_CONCURRENT freed 1726K, 23% free 16086K/20760K, paused 1ms+4ms, total 54ms
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 1400K, 23% free 16079K/20760K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 20.129MB for 2511452-byte allocation
,D/dalvikvm( 4014): GC_CONCURRENT freed 1939K, 28% free 16872K/23216K, paused 3ms+5ms, total 59ms
,D/dalvikvm( 4014): GC_CONCURRENT freed 2469K, 27% free 17027K/23216K, paused 2ms+6ms, total 45ms
,D/dalvikvm( 4014): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4014): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 539K, 28% free 16824K/23216K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4014): Grow heap (frag case) to 22.055MB for 3767174-byte allocation
,D/dalvikvm( 4014): GC_CONCURRENT freed 2614K, 33% free 18052K/26896K, paused 4ms+3ms, total 44ms
,D/dalvikvm( 4014): GC_FOR_ALLOC freed 524K, 34% free 18017K/26896K, paused 27ms, total 27ms
,W/jxcore-log( 4014): Initializing JXcore engine
,W/jxcore-log( 4014): JXcore engine is ready
,D/dalvikvm( 4014): GC_CONCURRENT freed 350K, 24% free 20656K/26896K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4014): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4014): Starting JXcore engine
,W/jxcore-log( 4014): Platform android
W/jxcore-log( 4014): 
,W/jxcore-log( 4014): Process ARCH arm
W/jxcore-log( 4014): 
,I/jxcore-log( 4014): JXcore Cordova bridge is ready!
I/jxcore-log( 4014): 
,W/jxcore-log( 4014): JXcore engine is started
,I/chromium( 4014): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4014): Toggling radios to true
I/jxcore-log( 4014): 
,D/BluetoothAdapter( 4014): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4014, uid=10423
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4014): Radios toggled
I/jxcore-log( 4014): 
,D/TCMD    (  443): NL - Read 1000 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
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
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1,
D/Tethering( 1019): InitialState.processMessage what=4
D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  443): NL - Read 60 bytes from update socket.
D/TCMD    (  443): NL - ignore NL message, type = 21
,D/TCMD    (  443): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 184849
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1019): DisconnectingState
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
,D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x5fdec0d8 clazz=0x61a00001 iface=wlan0 mask=0x3
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  270): Clearing all IP addresses on wlan0
V/NativeCrypto( 1352): Read error: ssl=0x6335a030: I/O error during system call, Connection timed out
V/NativeCrypto( 1352): SSL shutdown failed: ssl=0x6335a030: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/TCMD    (  443): NL - Read 56 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  443): NL - Read 312 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 192 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 1000 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
,D/TCMD    (  443): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/TCMD    (  443): NL - Read 80 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 80 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/TCMD    (  443): NL - Read 68 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  443): NL - Read 1000 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
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
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193813168
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-28ms what=147462 obj=android.net.wifi.StateChangeResult@44119e80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420ae648 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420ae648 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
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
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 fc
D/TCMD    (  443): NL - Read 56 bytes from update socket.
D/TCMD    (  443): NL - message type is RTM_NEWLINK
D/TCMD    (  443): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43ec1d40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43ec1d40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43ec1d40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  443): NL - Read 60 bytes from update socket.
D/TCMD    (  443): NL - ignore NL message, type = 20
,D/TCMD    (  443): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
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
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState enter
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
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@420d8ca8
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@420d8ca8
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4131 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/Tethering( 1019): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1549): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/CCE     ( 1549): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4014): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4014): 
I/jxcore-log( 4014): my name is : motorola-XT1039_PT4359
I/jxcore-log( 4014): 
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1549): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,I/jxcore-log( 4014): attempting to connect to test coordinator
I/jxcore-log( 4014): 
,D/dalvikvm( 4131): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe6d28, skipping init
I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4131): Crypto mode 0 already enabled
I/jxcore-log( 4014): check test folder
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): found test : ./testFindPeers.js
I/jxcore-log( 4014): 
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4152 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3722:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4014): found test : ./testReConnect.js
I/jxcore-log( 4014): 
,V/MmsConfig( 4152): mnc/mcc: 
V/MmsConfig( 4152): tag: bool value: enabledMMS - true
V/MmsConfig( 4152): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4152): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4152): tag: int value: maxImageWidth - 2592
I/jxcore-log( 4014): found test : ./testSendData.js
I/jxcore-log( 4014): 
V/MmsConfig( 4152): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4152): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4152): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4152): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4152): tag: int value: recipientLimit - 20
V/MmsConfig( 4152): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4152): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4152): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4152): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4152): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4152): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4152): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4152): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4152): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4170 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3849:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4014): Test app app.js loaded
I/jxcore-log( 4014): 
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4170): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4170): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/chromium( 4014): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4183 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3437:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1416): Checkin interval check for package: unspecified last checkin: 1449063075171 min interval config: 0 actual interval: 171626
,I/CheckinService( 1416): Checking schedule, now: 1449063246808 next: 1449063105132
,I/CheckinService( 1416): active receiver: enabled
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
I/CheckinService( 1416): Preparing to send checkin request
,I/EventLogService( 1416): Accumulating logs since 1449063070309
,I/CheckinRequestBuilder( 1416): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1416): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4197 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3891:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4197): Binding Chromium to main looper Looper (main, tid 1) {41fe0b88}
,I/LibraryLoader( 4197): Expected native library version number "",actual native library version number ""
,I/chromium( 4197): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4197): Initializing chromium process, renderers=0
,D/dalvikvm( 1019): GC_EXPLICIT freed 1660K, 65% free 18020K/50612K, paused 4ms+10ms, total 96ms
,E/AudioManagerAndroid( 4197): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4197): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4197): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4197): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4197): Local Branch: 
I/Adreno-EGL( 4197): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4197): Local Patches: NONE
I/Adreno-EGL( 4197): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4223 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
W/chromium( 4197): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4197): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 4223): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 4223): VFY: replacing opcode 0x60 at 0x000b
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/dalvikvm( 4223): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4223): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 4223): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 4223): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4223): install
I/MultiDex( 4223): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 4223): loading existing secondary dex files
,I/MultiDex( 4223): load found 3 secondary dex files
,I/MultiDex( 4223): install done
,D/dalvikvm( 4223): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4223): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4223): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4223): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4223): VFY: unable to resolve instance field 46
,D/dalvikvm( 4223): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4223): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4223): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4223): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4223): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4223): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4223): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe9838
,D/dalvikvm( 4223): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe9838
,D/dalvikvm( 4223): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe9838, skipping init
,D/dalvikvm( 4223): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fe9838
D/dalvikvm( 4223): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fe9838
,V/JNIHelp ( 4223): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4223): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe9838
,D/dalvikvm( 4223): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41fe9838
D/dalvikvm( 4223): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fe9838
,D/dalvikvm( 4223): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe9838
,I/NSApplication( 4197): Starting up...
,I/ImageResourceManager( 3473): ImageResourceManager: uninitalized
,I/iu.Environment( 3473): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 3456:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ProviderInstaller( 4223): Installed default security provider GmsCore_OpenSSL
,I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4131): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
,I/dalvikvm( 4223): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 4223): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4223): VFY: replacing opcode 0x6e at 0x000d
,I/iu.Environment( 3473): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4223): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4223): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4223): VFY: replacing opcode 0x6e at 0x0220
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/dalvikvm( 4223): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4223): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4223): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4223): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 4223): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4223): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4223): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4223): VFY: replacing opcode 0x6e at 0x0036
,D/dalvikvm( 3473): GC_CONCURRENT freed 629K, 5% free 16441K/17224K, paused 3ms+2ms, total 25ms
I/dalvikvm( 4223): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4223): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 4223): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1549): onServiceConnected()
,D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/WearableService( 1236): callingUid 10022, callindPid: 1236
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb536f000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb536f000
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,E/MDM     ( 1236): [81] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
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
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/LocationInitializer( 1416): Restart initialization of location
D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/GCM     ( 1352): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1352): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1352): Proximity feature is not enabled.
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1787593715
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1416): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1236): No location to return for getLastLocation()
,W/FusedLocationProvider( 1352): location=null
,D/dalvikvm( 4223): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bbf58
D/dalvikvm( 4223): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bbf58
,D/dalvikvm( 4223): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bbf58, skipping init
,D/NativeLibraryUtils( 4223): Install completed successfully. count=13 extracted=0
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
D/WVCdm   (  279): PrepareKeyRequest: nonce=3464292206
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4223): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4279): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4223): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4223): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 4223): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4223): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4223): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4223): Local Branch: 
I/Adreno-EGL( 4223): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4223): Local Patches: NONE
I/Adreno-EGL( 4223): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4223): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4223): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4223): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4223): Local Branch: 
I/Adreno-EGL( 4223): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4223): Local Patches: NONE
I/Adreno-EGL( 4223): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4223): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4223): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4223): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4223): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4223): Local Branch: 
I/Adreno-EGL( 4223): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4223): Local Patches: NONE
I/Adreno-EGL( 4223): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4223): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4223): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4223): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4223): Local Branch: 
I/Adreno-EGL( 4223): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4223): Local Patches: NONE
I/Adreno-EGL( 4223): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1416): Classify the device as Phone.
,I/CheckinTask( 1416): Sending checkin request (11736 bytes)
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service,
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,D/PollingManager( 1549): now: 216182 ,futureTime: 73076190
,D/PollingManager( 1549): Polling alarm set to expire at: 73076190 Current Time: 216183
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1549): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/PollingManager( 1549): now: 216213 ,futureTime: 73076190
,D/PollingManager( 1549): Polling alarm set to expire at: 73076190 Current Time: 216214
,I/OtaApp  ( 1549): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4131): Crypto mode 0 already enabled
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1549): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,I/iu.Environment( 3473): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1549): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/CheckinService( 1416): Checkin interval check for package: unspecified last checkin: 1449063075171 min interval config: 0 actual interval: 174224
,D/dalvikvm( 1549): GC_CONCURRENT freed 1984K, 38% free 10757K/17224K, paused 3ms+3ms, total 34ms
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3473): GC_FOR_ALLOC freed 43K, 5% free 16405K/17224K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3473): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1549): onServiceConnected()
D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4131): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3473): GC_FOR_ALLOC freed 2K, 5% free 18184K/19004K, paused 10ms, total 10ms
,I/iu.Environment( 3473): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1416): Checkin interval check for package: unspecified last checkin: 1449063075171 min interval config: 0 actual interval: 174299
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1549): onServiceConnected()
,D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1549): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1549): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1549
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1549): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1549
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4014): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429f3f88 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,121
,I/SFPerfTracer(  274):      triggers: (rate: 1:33) (compose: 0:4) (post: 0:1) (render: 0:5) (0:107 frames) (1:552)
,D/SFPerfTracer(  274):        layers: (0:13) (FocusedStackFrame: 0:10)* (StatusBar: 0:212)* (NavigationBar: 0:42)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:26)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 1:2)* 
,I/CheckinRequestBuilder( 1416): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1416): Failed to find provider info for com.google.android.wearable.settings
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1416): Classify the device as Phone.
,I/CheckinTask( 1416): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1416): Checking schedule, now: 1449063250001 next: 1449656319998
,I/CheckinService( 1416): active receiver: disabled
,I/CheckinService( 1416): Checking schedule, now: 1449063250018 next: 1449656319998
,I/CheckinService( 1416): active receiver: disabled
,D/CheckinService( 1416): Recording last checkin time for package unspecified as 1449063250025
,D/GCM     ( 1352): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GetConfigurationSnapshotOperation( 1352): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1352): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1352): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,D/dalvikvm( 1352): GC_CONCURRENT freed 1842K, 38% free 10757K/17224K, paused 3ms+5ms, total 33ms
,D/GetCommittedConfigurationOperation( 1352): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1208): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1208): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/Uploader( 1352):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1352): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1352): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1352): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 4014): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4014): 
,I/GAV2    ( 4197): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1019): Killing 3919:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4339 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+7ms, total 34ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 10ms+2ms, total 26ms
,I/Launcher( 1308): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/Launcher( 1308): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1236): DISABLE
,I/GCoreNlp( 1236): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4339): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4339): MmsConfig.loadMmsSettings
,I/Babel   ( 4339): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4339): MmsConfig.loadFromDatabase
,E/Babel   ( 4339): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4339): MmsConfig.loadFromResources
,E/Babel   ( 4339): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4339): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4339): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1019): GC_EXPLICIT freed 1710K, 65% free 18002K/50612K, paused 4ms+10ms, total 89ms
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4378 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3493:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4401 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4131:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2347): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1416): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4419 uid=10038 gids={50038, 3003, 1028, 1015}
,I/PackageBroadcastService( 1416): Null package name or gms related package.  Ignoreing.
,I/ActivityManager( 1019): Killing 4152:com.android.mms/u0a30 (adj 15): empty #9
,I/Icing   ( 1416): updateResources: need to parse f{com.google.android.gms}
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4419): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4419): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4378): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4419): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4419): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4419): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4419): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4419): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4419): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4419): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4419): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x0032
,I/InternalIcingCorporaPro( 2347): UpdateCorporaTask done [took 271 ms] updated apps [took 271 ms] 
,W/Settings( 4419): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4419): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4419): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4419): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4419): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4419): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4419): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4419): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4459 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4419): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4419): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4419): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4419): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4419): Skipping gmscore version check
I/dalvikvm( 4419): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4419): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1019): Killing 4170:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4459): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe5310, skipping init
I/openssl ( 4459): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4459): Crypto mode 0 already enabled
,D/Finsky  ( 4419): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4419): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1019): Killing 4183:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{43cc2810 type 3 android}
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{420c9f08 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42620cb8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{428305d8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4231e448 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42530078 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{421029d0 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{428171e8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{424a9a18 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{429c75d8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4289efd8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4416d0c0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{4416d198 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4498 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 4197:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{428b2848 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{428b3888 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{43ebaea0 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4416d1e8 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{4416d2c0 type 0 com.google.android.gms}
,I/EventLogService( 1416): Aggregate from 1449063246825 (log), 1449062101052 (data)
,D/dalvikvm( 1416): GC_CONCURRENT freed 1896K, 32% free 11732K/17224K, paused 5ms+6ms, total 53ms
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42887b08 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{428b0d40 type 2 com.google.android.gms}
,D/UdcCache:FPQuery( 1416): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1208): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{43e62440 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42842de0 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42103070 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42873628 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4291b408 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{44102fb0 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open '',
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4291c7b8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42933300 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4293fd18 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{43a1a1d8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{42936308 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43e62518 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{4218c740 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{44111b88 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 48ms
,I/ProcessStatsService( 1019): Prepared write state in 16ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-55-41.bin
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{4290afa0 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{43cc7258 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,V/AlarmManager( 1019): sending alarm Alarm{428469b8 type 3 android}
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,I/jxcore-log( 4014): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4014): 
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4613): 
D/AndroidRuntime( 4613): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4613): CheckJNI is OFF
D/dalvikvm( 4613): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4613): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4613): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4613): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4613): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4613): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4613): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4613): failed to load memtrack module: -2
D/AndroidRuntime( 4613): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10423 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 4014:com.test.thalitest/u0a423 (adj 9): stop com.test.thalitest
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1019): WIN DEATH: Window{420914b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1019): Client connection lost with reason: 4
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{4209ec98 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings( 1019): Skipping PackageSetting{422a24f0 com.example.hello/10416} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10423 user=0: pkg removed
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm( 2308): GC_EXPLICIT freed 5471K, 44% free 9653K/17224K, paused 1ms+5ms, total 69ms
D/dalvikvm( 1308): GC_EXPLICIT freed 3336K, 33% free 11596K/17224K, paused 2ms+4ms, total 106ms
I/Launcher( 1308): Deferring update until onResume
D/dalvikvm( 2347): GC_EXPLICIT freed 4343K, 42% free 10100K/17224K, paused 2ms+18ms, total 144ms
D/dalvikvm( 1019): GC_EXPLICIT freed 1999K, 65% free 18063K/50612K, paused 4ms+12ms, total 137ms
I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1236): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/VoicemailCleanupService( 4378): Cleaning up data for package: com.test.thalitest
I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449065050
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1308): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
V/AlarmManager( 1019): sending alarm Alarm{4218c790 type 3 android}
V/AlarmManager( 1019): sending alarm Alarm{4218c868 type 3 com.google.android.gms}
V/AlarmManager( 1019): sending alarm Alarm{4218c8b8 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1019): sending alarm Alarm{4218c908 type 2 com.google.android.gms}
I/InternalIcingCorporaPro( 2347): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4643 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449065050
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10423 #1
D/dalvikvm( 1019): GC_EXPLICIT freed 736K, 65% free 18004K/50612K, paused 5ms+15ms, total 158ms
I/InternalIcingCorporaPro( 2347): UpdateCorporaTask done [took 106 ms] updated apps [took 106 ms] 
D/AndroidRuntime( 4613): Shutting down VM
D/dalvikvm( 4613): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4643): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 4643): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4666 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1416): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1416): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1416): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1416): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1416): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1416): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1416): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1352): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1352): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/SQLiteLog( 1416): (3850) statement aborts at 26: [DELETE FROM events WHERE app_id=?] disk I/O error
I/dalvikvm( 4419): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4419): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4419): VFY: replacing opcode 0x6e at 0x0013
I/PeopleContactsSync( 1416): CP2 sync disabled
E/SQLiteDatabase( 1416): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1416): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1416): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1416): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1416): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1416): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1416): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1416): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1416): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1416): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/GMPM-SVC( 1416): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
E/SQLiteOpenHelper( 1416): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1416): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1416): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1416): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1416): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1416): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1416): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1416): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1416): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1416): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1416): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
I/Icing   ( 1416): doRemovePackageData com.test.thalitest
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4702 uid=10058 gids={50058}
W/SQLiteOpenHelper( 1416): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1416): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1416): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1416): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1416): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1416): threadid=44: thread exiting with uncaught exception (group=0x41710d40)
W/FileUtils( 1416): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/GAv4-SVC( 1416): Error creating clientId file: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/gaClientId: open failed: EROFS (Read-only file system)
E/SharedPreferencesImpl( 1416): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1416): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 4666): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4666): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4666): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4666): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4666): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4666): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4666): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4666): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4666): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4666): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4666): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4666): threadid=10: thread exiting with uncaught exception (group=0x41710d40)
E/GAv4-SVC( 1416): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1416): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1416): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1416): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AndroidRuntime( 4666): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4666): Process: com.android.keychain, PID: 4666
E/AndroidRuntime( 4666): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4666): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4666): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4666): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4666): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4666): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4666): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4666): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4666): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4666): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4666): Sending signal. PID: 4666 SIG: 9
E/SQLiteLog( 1416): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1416): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
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
E/SharedPreferencesImpl( 1416): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AndroidRuntime( 1416): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1416): Process: com.google.android.gms, PID: 1416
E/AndroidRuntime( 1416): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1416): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1416): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1416): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1416): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1416): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1416): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1416): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1416): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1019): Process com.android.keychain (pid 4666) has died.
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
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
W/ActivityManager( 1019): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/Process ( 1416): Sending signal. PID: 1416 SIG: 9
D/Documents( 4702): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4702): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4702): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4702): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4702): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4702): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4702): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4702): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4702): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4702): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4702): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4702): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4702): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4702): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4702): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4702): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4702): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4702): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager( 1019): Killing 4223:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/SQLiteLog( 2308): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
I/ActivityManager( 1019): Process com.google.android.gms (pid 1416) has died.
D/WifiService( 1019): Client connection lost with reason: 4
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
E/SQLiteDatabase( 2308): Error inserting state=event=am_kill pid=4223 process=com.google.android.gms.unstable reason=empty+%239 selectadj=15 timestamp=1449065050962 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2308): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2308): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2308): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2308): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2308): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2308): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2308): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2308): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2308): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2308): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2308): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2308): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2308): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2308): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2308): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
D/AndroidRuntime( 4702): Shutting down VM
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/dalvikvm( 4702): threadid=1: thread exiting with uncaught exception (group=0x41710d40)
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.analytics.AnalyticsService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
D/Documents( 4702): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4702): FATAL EXCEPTION: main
E/AndroidRuntime( 4702): Process: com.android.documentsui, PID: 4702
E/AndroidRuntime( 4702): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4702): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4702): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4702): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4702): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4702): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4702): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4702): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4702): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4702): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4702): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4702): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4702): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4702): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4702): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4702): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4702): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4702): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4702): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4702): 	... 10 more

```
