#### Test 558877588826def_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4277): 
D/AndroidRuntime( 4277): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4277): CheckJNI is OFF
D/dalvikvm( 4277): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4277): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4277): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4277): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4277): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4277): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4277): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4277): failed to load memtrack module: -2
D/AndroidRuntime( 4277): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4277
W/WindowManager( 1015): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4293 uid=10105 gids={50105, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4277): Shutting down VM
D/dalvikvm( 4277): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4293): Binding Chromium to main looper Looper (main, tid 1) {41f6fa70}
I/LibraryLoader( 4293): Expected native library version number "",actual native library version number ""
I/chromium( 4293): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4293): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a90d28:true
I/Adreno-EGL( 4293): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4293): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4293): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4293): Local Branch: 
I/Adreno-EGL( 4293): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4293): Local Patches: NONE
I/Adreno-EGL( 4293): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4293): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4293): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4293): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4293): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4293): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4293): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4293): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4293): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4293): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4293): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4293): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4293): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4293): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4293): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4293): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4293): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4293): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4293): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4293): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4293): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4293): Enabling debug mode 0
,W/AwContents( 4293): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1210): onFinishInput()
,W/IInputConnectionWrapper( 4293): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1015): Displayed com.test.thalitest/.MainActivity,cp,ca,416
I/ActivityManager( 1015): Displayed com.test.thalitest/.MainActivity: +388ms (total +416ms)
,D/JsMessageQueue( 4293): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4293): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f73f20
,D/dalvikvm( 4293): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f73f20
D/jxcore_app_log( 4293): JniHelper::setJavaVM(0x415bcfa8), pthread_self() = 1614306320
,D/JX-Cordova( 4293): jxcore cordova android initializing
,D/dalvikvm( 4293): GC_CONCURRENT freed 2796K, 17% free 14392K/17224K, paused 2ms+1ms, total 57ms
,D/dalvikvm( 4293): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 112K, 17% free 14389K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 124K, 17% free 14410K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 16.197MB for 95956-byte allocation
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 178K, 17% free 14444K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 16.276MB for 143930-byte allocation
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 251K, 18% free 14492K/17464K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 16.390MB for 215890-byte allocation
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 366K, 18% free 14566K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 16.566MB for 323830-byte allocation
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 564K, 19% free 14686K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 16.838MB for 485740-byte allocation
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 860K, 20% free 14862K/18472K, paused 27ms, total 27ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 1276K, 19% free 15117K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 17.837MB for 1092904-byte allocation
,D/dalvikvm( 4293): GC_CONCURRENT freed 1778K, 21% free 15504K/19540K, paused 2ms+3ms, total 41ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 270K, 22% free 15432K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 18.666MB for 1639352-byte allocation
,D/dalvikvm( 4293): GC_CONCURRENT freed 1651K, 25% free 16011K/21144K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 1329K, 24% free 16078K/21144K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 20.080MB for 2459024-byte allocation
,D/dalvikvm( 4293): GC_CONCURRENT freed 1835K, 29% free 16841K/23548K, paused 4ms+5ms, total 47ms
,D/dalvikvm( 4293): GC_CONCURRENT freed 2429K, 28% free 17025K/23548K, paused 2ms+6ms, total 41ms
,D/dalvikvm( 4293): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 506K, 29% free 16913K/23548K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4293): Grow heap (frag case) to 22.067MB for 3688532-byte allocation
,D/dalvikvm( 4293): GC_CONCURRENT freed 2617K, 33% free 18201K/27152K, paused 5ms+5ms, total 60ms
,D/dalvikvm( 4293): GC_FOR_ALLOC freed 822K, 34% free 18018K/27152K, paused 28ms, total 30ms
,W/jxcore-log( 4293): Initializing JXcore engine
,W/jxcore-log( 4293): JXcore engine is ready
,D/dalvikvm( 4293): GC_CONCURRENT freed 333K, 24% free 20672K/27152K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4293): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4293): Starting JXcore engine
,W/jxcore-log( 4293): Platform android
W/jxcore-log( 4293): 
,W/jxcore-log( 4293): Process ARCH arm
W/jxcore-log( 4293): 
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4293): JXcore Cordova bridge is ready!
I/jxcore-log( 4293): 
,W/jxcore-log( 4293): JXcore engine is started
,I/chromium( 4293): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4293): Toggling radios to true
I/jxcore-log( 4293): 
,D/BluetoothAdapter( 4293): enable(): BT is already enabled..!
D/WifiService( 1015): New client listening to asynchronous messages
D/WifiService( 1015): setWifiEnabled: true pid=4293, uid=10105
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1015): handleMessage: E msg.what=131145
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
I/jxcore-log( 4293): Radios toggled
I/jxcore-log( 4293): 
I/jxcore-log( 4293): My device name is: motorola-XT1039
I/jxcore-log( 4293): 
,I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  271): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  271):  STA Disconnected !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
,D/Tethering( 1015): InitialState.processMessage what=4
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
,I/MDMCTBK (  271): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
,D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
I/MDMCTBK (  271): send SAR ctrl over QMI
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,V/ConnectivityService( 1015): WiFi NOT Tethered!
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiStateMachine( 1015): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1015): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1015): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  539): NL - Read 60 bytes from update socket.
D/TCMD    (  539): NL - ignore NL message, type = 21
,D/TCMD    (  539): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1015): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1015): connected time updated 293588
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1015): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1015): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1091): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1091): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1091): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1015): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1015): DisconnectingState
,D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1015): resetConnections(wlan0, 3)
D/NetUtils( 1015): android_net_utils_resetConnections in env=0x6160c5c0 clazz=0x62700001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131146
D/WifiStateMachine( 1015): processMsg: DisconnectingState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147460
D/WifiStateMachine( 1015): processMsg: DisconnectingState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): Network connection lost
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1356): Read error: ssl=0x63193568: I/O error during system call, Connection timed out
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x63193568: I/O error during system call, Broken pipe
D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/dalvikvm( 1015): Jit: resizing JitTable from 8192 to 16384
I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
D/WifiStateMachine( 1015): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1015): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: DisconnectedState
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
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
,D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1015): Attempting to switch to ETHERNET
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1163): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  271): Event received = Trying to associate with
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/TCMD    (  539): NL - Read 56 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
,D/TCMD    (  539): Listening for incoming client connection request
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1163): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  539): NL - Read 312 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 88 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
I/wpa_supplicant( 1163): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1163): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
,D/TCMD    (  539): Listening for incoming client connection request
I/wpa_supplicant( 1163): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  271): Event received = Associated with c0:ff:d4
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  539): NL - Read 80 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 80 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1163): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  271): Event received = WPA: Key negotiation com
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  271):  STA Connected !!
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
E/MDMCTBK (  271): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  271): get_freq !!, resp=0
I/MDMCTBK (  271): get_freq !!, Strip data
I/MDMCTBK (  271): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  271): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  271): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1210807472
I/MDMCTBK (  271): return from set_get_from_wpa_supplicant
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
,I/MDMCTBK (  271): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
I/MDMCTBK (  271): send SAR ctrl over QMI
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): wifi_set_tx_pwr: SETTXPOWER = 19
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147459
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
E/MDMCTBK (  271): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  271): , reply_len: 3, ret: 0
E/MDMCTBK (  271): MdmCutbackHndler, resp=OK
E/MDMCTBK (  271): 
D/MDMCTBK (  271): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1015): Network connection established
,D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1015): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1015): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1015): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1015): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@43b2df18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-20ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43b30310 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1015): processMsg: ObtainingIpState
,D/WifiStateMachine( 1015): ObtainingIpState{ when=-10ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427cbe18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427cbe18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): handleMessage: X
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1015): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiP2pService( 1015): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43aa2bb8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43aa2bb8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43aa2bb8 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  539): NL - Read 56 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
,D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  539): NL - Read 60 bytes from update socket.
D/TCMD    (  539): NL - ignore NL message, type = 20
,D/TCMD    (  539): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
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
,I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=151572
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1091): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=135190
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1015): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1015): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): CaptivePortalCheckState enter
,D/WifiStateMachine( 1015): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1015): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1015): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1015): WiFi NOT Tethered!
I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@42039330
I/SBar.NetworkController( 1091): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1015): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1091): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1091): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1015): WiFi NOT Tethered!
E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@42039330
,D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,D/CaptivePortalTracker( 1015): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1015): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/Tethering( 1015): MasterInitialState.processMessage what=3
D/PollingManager( 1610): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
I/ActivityManager( 1015): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4406 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/dalvikvm(  273): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 29ms
,I/SBar.NetworkController( 1091): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,E/ActivityThread( 1610): Failed to find provider info for com.motorola.blur.setupprovider
,D/PollingManager( 1610): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1610): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1610): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1610): Registering with Alarm Manager to restart CCE
D/dalvikvm(  273): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/OtaApp  ( 1610): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1610): [debug] > CusSM.onRadioDown
D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1015): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/dalvikvm( 4406): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f779c0, skipping init
I/openssl ( 4406): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4406): Crypto mode 0 already enabled
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4438 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3945:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1015): GC_EXPLICIT freed 23653K, 65% free 18378K/51288K, paused 4ms+11ms, total 148ms
,V/MmsConfig( 4438): mnc/mcc: 
,V/MmsConfig( 4438): tag: bool value: enabledMMS - true
V/MmsConfig( 4438): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4438): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4438): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4438): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4438): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4438): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4438): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4438): tag: int value: recipientLimit - 20
V/MmsConfig( 4438): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4438): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4438): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4438): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4438): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4438): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4438): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4438): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4438): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1015): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4459 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1015): Killing 4091:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4459): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4459): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4459): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4472 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 4127:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1740): Checkin interval check for package: unspecified last checkin: 1452688603094 min interval config: 0 actual interval: 278348
,I/CheckinService( 1740): Checking schedule, now: 1452688881455 next: 1452688633069
,I/CheckinService( 1740): active receiver: enabled
,I/CheckinService( 1740): Preparing to send checkin request
,I/EventLogService( 1740): Accumulating logs since 1452688597310
D/ConnectivityService( 1015): NetTransition Wakelock for ConnectedState released by timeout
,I/CheckinRequestBuilder( 1740): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1740): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4472): Binding Chromium to main looper Looper (main, tid 1) {41f688e8}
,I/LibraryLoader( 4472): Expected native library version number "",actual native library version number ""
,I/chromium( 4472): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4472): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4472): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4472): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4472): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4472): Local Branch: 
I/Adreno-EGL( 4472): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4472): Local Patches: NONE
I/Adreno-EGL( 4472): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1356): GC_EXPLICIT freed 1557K, 40% free 10359K/17224K, paused 2ms+4ms, total 38ms
,W/chromium( 4472): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4472): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  260): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4472): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1015): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4512 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4512): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4512): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4512): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4512): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4512): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4512): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4512): install
,I/MultiDex( 4512): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4512): loading existing secondary dex files
,I/MultiDex( 4512): load found 3 secondary dex files
,I/MultiDex( 4512): install done
,D/dalvikvm( 4512): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4512): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4512): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4512): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4512): VFY: unable to resolve instance field 36
,D/dalvikvm( 4512): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4512): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4512): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4512): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4512): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4512): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4512): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f6ec78
,D/dalvikvm( 4512): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f6ec78
,D/dalvikvm( 4512): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f6ec78, skipping init
,D/dalvikvm( 4512): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f6ec78
D/dalvikvm( 4512): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f6ec78
,V/JNIHelp ( 4512): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4472): Starting up...
,I/ActivityManager( 1015): Killing 3874:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4533 uid=10056 gids={50056, 3003, 1028, 1015}
,D/dalvikvm( 4512): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f6ec78
,D/dalvikvm( 4512): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f6ec78
D/dalvikvm( 4512): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f6ec78
,D/dalvikvm( 4512): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f6ec78
,D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4533): VFY: unable to resolve instance field 68
D/dalvikvm( 4533): VFY: replacing opcode 0x54 at 0x000c
,D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4533): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4533): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4533): VFY: unable to resolve instance field 68
,D/dalvikvm( 4533): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/openssl ( 4406): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4406): Crypto mode 0 already enabled
I/dalvikvm( 4533): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4533): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4533): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4533): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/MobileConnectivityChangeReceiver( 4459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4459): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager( 1015): Killing 4166:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1610): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1610): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1610): bindWebServices(): registering our AIDL callback...
I/SundryService( 1610): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1610): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1610): onServiceConnected()
D/GetNotificationsWS( 1610): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1610): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1610): unbindWebServices(): un-registering our AIDL callback...
,I/ProviderInstaller( 4512): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1237): callingUid 10022, callindPid: 1237
,E/MDM     ( 1237): [132] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1356): Proximity feature is not enabled.
,D/LocationInitializer( 1740): Restart initialization of location
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1237): No location to return for getLastLocation()
,W/FusedLocationProvider( 1237): location=null
,I/dalvikvm( 4512): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4512): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4512): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4512): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4512): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4512): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4512): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4512): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4512): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4512): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4512): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4512): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4512): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4512): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4512): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4512): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4512): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5229000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5229000
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=3867764103
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4512): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4512): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bfe40
D/dalvikvm( 4512): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bfe40
,D/dalvikvm( 4512): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421bfe40, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4512): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4563): DexOpt: load 5ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4512): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4512): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 91ms
,I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4512): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4512): Local Patches: NONE
I/Adreno-EGL( 4512): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4512): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4512): Local Patches: NONE
I/Adreno-EGL( 4512): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4512): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4512): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4512): Local Patches: NONE
I/Adreno-EGL( 4512): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4512): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4512): Local Patches: NONE
I/Adreno-EGL( 4512): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1610): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1610): now: 327216 ,futureTime: 70324522
,D/PollingManager( 1610): Polling alarm set to expire at: 70324522 Current Time: 327217
,E/ActivityThread( 1610): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1610): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1610): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1610): [debug] > CusSM.onRadioUp
,D/PollingManager( 1610): now: 327250 ,futureTime: 70324522
,D/PollingManager( 1610): Polling alarm set to expire at: 70324522 Current Time: 327250
,E/ActivityThread( 1610): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1610): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1610): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,I/openssl ( 4406): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4406): Crypto mode 0 already enabled
D/OtaApp  ( 1610): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1610): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
D/Checkin ( 1610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1610): [debug] > CusSM.runStateMachine: server told to :continue
,D/MobileConnectivityChangeReceiver( 4459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4459): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1740): Checkin interval check for package: unspecified last checkin: 1452688603094 min interval config: 0 actual interval: 280548
,D/OtaApp  ( 1610): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1610): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1610): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1610): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1610): [debug] > CusSM.runStateMachine: server told to :continue
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DEBUG   ( 1610): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/ContextImpl( 1610): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/GetNotificationsWS( 1610): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1610): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1610): onServiceConnected()
D/GetNotificationsWS( 1610): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1610): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/WaitableIntentService( 1610): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1610): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4406): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4406): Crypto mode 0 already enabled
D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1635102141
D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/MobileConnectivityChangeReceiver( 4459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4459): onReceive CONNECTIVITY_CHANGE networkType=1
I/CheckinService( 1740): Checkin interval check for package: unspecified last checkin: 1452688603094 min interval config: 0 actual interval: 280638
D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/DEBUG   ( 1610): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1610): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1610): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1610): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1610): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1610): onServiceConnected()
,D/GetNotificationsWS( 1610): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1610): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1610): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/GetNotificationsWS( 1610): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1610): [debug] > Received start id 2: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1610): [debug] > handle intent : null
,D/OtaApp  ( 1610): [debug] > supress duplicated intent, nextPompt: 1452775005443 and mNotificationInStatusBar: true
,D/OtaApp  ( 1610): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/OtaApp  ( 1610): [debug] > Received start id 3: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1610): [debug] > handle intent : null
,D/OtaApp  ( 1610): [debug] > supress duplicated intent, nextPompt: 1452775005443 and mNotificationInStatusBar: true
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1740): Classify the device as Phone.
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
,I/CheckinTask( 1740): Sending checkin request (11903 bytes)
,V/AlarmManager( 1015): sending alarm Alarm{4282b420 type 2 com.google.android.gms}
,I/CheckinRequestBuilder( 1740): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1740): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1015): GC_EXPLICIT freed 806K, 65% free 18234K/51288K, paused 3ms+9ms, total 98ms
,I/CheckinRequestBuilder( 1740): Classify the device as Phone.
,I/CheckinTask( 1740): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1740): Checking schedule, now: 1452688886502 next: 1452730940490
,I/CheckinService( 1740): active receiver: disabled
,I/CheckinService( 1740): Checking schedule, now: 1452688886522 next: 1452730940490
,I/CheckinService( 1740): active receiver: disabled
,D/CheckinService( 1740): Recording last checkin time for package unspecified as 1452688886526
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 4472): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1015): Killing 4198:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4293): Test app app.js loaded
I/jxcore-log( 4293): 
,I/Choreographer( 4293): Skipped 709 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4293): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/Launcher( 1328): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
I/Launcher( 1328): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/ActivityManager( 1015): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4649 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/GCoreNlp( 1237): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/InternalIcingCorporaPro( 2340): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1740): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1015): Killing 4406:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/PackageBroadcastService( 1740): Null package name or gms related package.  Ignoreing.
,D/dalvikvm( 1740): GC_CONCURRENT freed 2000K, 31% free 12044K/17224K, paused 5ms+5ms, total 67ms
D/dalvikvm( 1740): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 1740): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Icing   ( 1740): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2340): UpdateCorporaTask done [took 322 ms] updated apps [took 322 ms] 
,I/jxcore-log( 4293): --= Surplus to requirements =--
I/jxcore-log( 4293): 
,I/jxcore-log( 4293): ****TEST TOOK:  ms ****
I/jxcore-log( 4293): 
,I/jxcore-log( 4293): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4293): 
,D/AndroidRuntime( 4686): 
D/AndroidRuntime( 4686): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4686): CheckJNI is OFF
,D/dalvikvm( 4686): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4686): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4686): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4686): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4686): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4686): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1091): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1312): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1312): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=100
,E/memtrack( 4686): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4686): failed to load memtrack module: -2
,I/Icing   ( 1740): Indexing 08D2302403BBE76D1189E62A66162DB0256D4E65 from com.google.android.gms
,I/Icing   ( 1740): Indexing done 08D2302403BBE76D1189E62A66162DB0256D4E65
,D/AndroidRuntime( 4686): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10105 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 4293:com.test.thalitest/u0a105 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{444c23b8 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState( 1015): WIN DEATH: Window{444ca368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1015): Client connection lost with reason: 4
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10105 user=0: pkg removed
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1210): resetDictionaries() : en_GB
,W/GeofencerStateMachine( 1237): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1210): run()
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
D/dalvikvm( 1328): GC_EXPLICIT freed 3532K, 33% free 11601K/17224K, paused 2ms+5ms, total 63ms
,I/Launcher( 1328): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,D/dalvikvm( 2305): GC_EXPLICIT freed 5205K, 44% free 9650K/17224K, paused 2ms+6ms, total 61ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,D/VoicemailCleanupService( 1188): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1210): createOrResetDecoder
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,D/dalvikvm( 2340): GC_EXPLICIT freed 3451K, 42% free 10029K/17224K, paused 2ms+23ms, total 138ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,D/dalvikvm( 1015): GC_EXPLICIT freed 1672K, 65% free 18360K/51288K, paused 4ms+14ms, total 168ms
,D/dalvikvm( 1015): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
I/Launcher( 1328): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
I/ConfigService( 1237): onCreate
,I/InternalIcingCorporaPro( 2340): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4719 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): run()
,W/ContextImpl( 4719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/dalvikvm( 1237): GC_CONCURRENT freed 1680K, 35% free 11349K/17224K, paused 3ms+8ms, total 46ms
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1015): removePackageParticipantsLocked: uid=10105 #1
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42284678)
,D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PackageBroadcastService( 1740): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1740): Clearing selected account for com.test.thalitest
,I/dalvikvm( 3781): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3781): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3781): VFY: replacing opcode 0x6e at 0x0013
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42216490)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42219688)
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42281488)
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4227e298)
,I/LocationSettingsChecker( 1740): Removing dialog suppression flag for package com.test.thalitest
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 4293 uid 10105
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
,I/Keyboard.Facilitator( 1210): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1210): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1210): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1210): run()
I/StatsUtilsManager( 1210): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1210): shouldRecordStats() = Too Soon
,D/ChimeraCfgMgr( 1740): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1740): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1356): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1356): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1740): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1740): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1740): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1740): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1740): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/ChimeraCfgMgr( 1740): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1740): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1740): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4747 uid=10059 gids={50059, 1028, 3003, 1015}
D/gH_CompatibleDatabase( 1740): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1740): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1740): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1740): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1740): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1740): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,I/ActivityManager( 1015): Killing 4438:com.android.mms/u0a30 (adj 15): empty #9
,D/gH_CompatibleDatabase( 1740): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1740): doRemovePackageData com.test.thalitest
,I/InternalIcingCorporaPro( 2340): UpdateCorporaTask done [took 242 ms] updated apps [took 241 ms] 
,D/dalvikvm( 1015): GC_EXPLICIT freed 576K, 65% free 18333K/51288K, paused 4ms+17ms, total 315ms
,D/CaptivePortalTracker( 1015): Checking http://216.58.209.46/generate_204
,D/AndroidRuntime( 4686): Shutting down VM
,D/dalvikvm( 4686): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/dalvikvm( 4747): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
,W/dalvikvm( 4747): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4747): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4747): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4747):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4747):   adb logcat -s GAv4
,W/GAv4    ( 4747): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4747): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4747): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4747): VFY: replacing opcode 0x6e at 0x001b
,W/GAv4    ( 4747): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4747): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4747): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
I/dalvikvm( 4747): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4747): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 4747): VFY: replacing opcode 0x71 at 0x0075
,I/ActivityManager( 1015): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=4779 uid=10095 gids={50095, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 4459:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4747): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/Quickoffice( 4779): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 4779): Loading recent documents list
,D/Quickoffice( 4779): The number of lines present in  /proc/mount 24
,D/Quickoffice( 4779): Parsing the storagedefinition.xml.
,D/Quickoffice( 4779): # of Storagedefinitions - 35
D/Quickoffice( 4779): The # of storage definitions available - 35
,D/Quickoffice( 4779): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 4779): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,size=428100k,nr_inodes=107025,mode=755 0 0
,D/Quickoffice( 4779): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 4779): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
,D/Quickoffice( 4779): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 4779): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 4779): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/dalvikvm( 4747): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4747): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4747): VFY: replacing opcode 0x62 at 0x000a
,D/Quickoffice( 4779): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 4779): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,size=428100k,nr_inodes=107025,mode=750,gid=1000 0 0
D/Quickoffice( 4779): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/dalvikvm( 4747): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4747): VFY: unable to resolve instance field 36
,D/dalvikvm( 4747): VFY: replacing opcode 0x54 at 0x005f
,D/Quickoffice( 4779): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,size=428100k,nr_inodes=107025,mode=755,gid=1000 0 0
D/Quickoffice( 4779): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,size=428100k,nr_inodes=107025,mode=755,gid=1000 0 0
,D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/dalvikvm( 4747): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4747): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4747): VFY: replacing opcode 0x62 at 0x0047
,D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data f2fs rw,seclabel,nosuid,nodev,noatime,nodiratime,background_gc=on,discard,user_xattr,inline_xattr,acl,errors=recover,active_logs=6 0 0
,D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nodiratime,data=ordered 0 0
D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,defcontext=u:object_r:persist_file:s0,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/dalvikvm( 4747): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4747): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware ext4 ro,defcontext=u:object_r:modem_file:s0,seclabel,nosuid,nodev,relatime,data=ordered 0 0
,D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/pds /pds ext3 rw,defcontext=u:object_r:pds_file:s0,seclabel,nosuid,noexec,relatime,barrier=1,data=writeback 0 0
D/dalvikvm( 4747): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4227f770
,D/Quickoffice( 4779): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/fsg /fsg ext4 ro,defcontext=u:object_r:modem_file:s0,seclabel,nosuid,nodev,relatime 0 0
,D/Quickoffice( 4779): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 4779): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/dalvikvm( 4747): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4227f770
D/dalvikvm( 4747): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4227f770, skipping init
,D/Quickoffice( 4779): Build properties are not configured for this storage definition.
D/Quickoffice( 4779): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 4779): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,size=428100k,nr_inodes=107025,mode=751,gid=1028 0 0
,D/Quickoffice( 4779): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 4779): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/dalvikvm( 4747): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4227f770
D/Quickoffice( 4779): Build properties are not configured for this storage definition.
,D/dalvikvm( 4747): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4227f770
,V/JNIHelp ( 4747): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Quickoffice( 4779): The # of mounts identified -  1
,D/com.google.android.apps.docs.quickoffice.X( 4779): Checking validity of 0 items
I/ActivityManager( 1015): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4800 uid=10058 gids={50058}
I/ActivityManager( 1015): Killing 4472:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ActivityManager( 1015): No permission grants found for com.quickoffice.android
,D/ContentResolverUtil( 4779): There are 0 persisted uri permissions.
,D/com.google.android.apps.docs.quickoffice.X( 4779): 0 items were valid
,E/SQLiteLog( 2305): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2305): Error inserting state=event=am_kill pid=4472 process=com.google.android.apps.magazines reason=empty+%239 selectadj=15 timestamp=1452688894083 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2305): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2305): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2305): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2305): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2305): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2305): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2305): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2305): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2305): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2305): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2305): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2305): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2305): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2305): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2305): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2305): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 4747): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4227f770
D/dalvikvm( 4747): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4227f770
D/dalvikvm( 4747): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4227f770
,D/dalvikvm( 4747): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4227f770
,D/Documents( 4800): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4800): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4800): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4800): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4800): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4800): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4800): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4800): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4800): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4800): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4800): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4800): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4800): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4800): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4800): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4800): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4800): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 4800): Shutting down VM
W/dalvikvm( 4800): threadid=1: thread exiting with uncaught exception (group=0x4169bd40)
E/AndroidRuntime( 4800): FATAL EXCEPTION: main
E/AndroidRuntime( 4800): Process: com.android.documentsui, PID: 4800
E/AndroidRuntime( 4800): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4800): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4800): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4800): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4800): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4800): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4800): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4800): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4800): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4800): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4800): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4800): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4800): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4800): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4800): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4800): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4800): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4800): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4800): 	... 10 more
I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4818 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
W/Quickoffice( 4779): Could not load clipboard.
I/ActivityManager( 1015): Killing 4533:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1278): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1015): Killing 4512:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
E/DropBoxManagerService( 1015): Can't write: system_app_crash
E/DropBoxManagerService( 1015): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
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
