#### Test 550731521dbc378_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = ,
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4035): 
D/AndroidRuntime( 4035): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4035): CheckJNI is OFF
D/dalvikvm( 4035): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4035): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4035): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4035): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4035): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4035): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4035): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4035): failed to load memtrack module: -2
D/AndroidRuntime( 4035): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4035
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4051 uid=10513 gids={50513, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4035): Shutting down VM
D/dalvikvm( 4035): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4051): Binding Chromium to main looper Looper (main, tid 1) {41fe5490}
I/LibraryLoader( 4051): Expected native library version number "",actual native library version number ""
I/chromium( 4051): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4051): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43df9f20:true
I/Adreno-EGL( 4051): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4051): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4051): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4051): Local Branch: 
I/Adreno-EGL( 4051): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4051): Local Patches: NONE
I/Adreno-EGL( 4051): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4051): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4051): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4051): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4051): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4051): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4051): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4051): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4051): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4051): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4051): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4051): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4051): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4051): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4051): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4051): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4051): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4051): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4051): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4051): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4051): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4051): Enabling debug mode 0
,W/AwContents( 4051): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1016): Displayed com.test.thalitest/.MainActivity,cp,ca,473
I/ActivityManager( 1016): Displayed com.test.thalitest/.MainActivity: +445ms (total +473ms)
W/AwContents( 4051): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4051): showStatusIcon on inactive InputConnection
,D/dalvikvm( 1567): GC_CONCURRENT freed 1932K, 38% free 10685K/17224K, paused 4ms+5ms, total 36ms
,D/JsMessageQueue( 4051): Set native->JS mode to OnlineEventsBridgeMode
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4051): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fea140
,D/dalvikvm( 4051): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fea140
D/jxcore_app_log( 4051): JniHelper::setJavaVM(0x41637fa8), pthread_self() = 1614829280
,D/JX-Cordova( 4051): jxcore cordova android initializing
,D/dalvikvm( 4051): GC_CONCURRENT freed 2744K, 17% free 14425K/17224K, paused 2ms+2ms, total 47ms
,D/dalvikvm( 4051): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 163K, 17% free 14445K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 131K, 17% free 14459K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 16.245MB for 96598-byte allocation
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 179K, 17% free 14494K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 16.325MB for 144892-byte allocation
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 253K, 17% free 14542K/17464K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 16.441MB for 217334-byte allocation
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 369K, 18% free 14616K/17680K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 16.617MB for 325996-byte allocation
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 568K, 19% free 14738K/18000K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 16.891MB for 488990-byte allocation
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 867K, 20% free 14915K/18480K, paused 27ms, total 27ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 1287K, 18% free 15172K/18480K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 17.898MB for 1100216-byte allocation
,D/dalvikvm( 4051): GC_CONCURRENT freed 1807K, 21% free 15564K/19556K, paused 3ms+5ms, total 45ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 258K, 21% free 15484K/19556K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 18.727MB for 1650320-byte allocation
,D/dalvikvm( 4051): GC_CONCURRENT freed 1672K, 25% free 16072K/21168K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 1330K, 24% free 16140K/21168K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 20.155MB for 2475476-byte allocation
,D/dalvikvm( 4051): GC_CONCURRENT freed 306K, 22% free 18450K/23588K, paused 5ms+3ms, total 50ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 4319K, 28% free 17131K/23588K, paused 36ms, total 36ms
,I/dalvikvm-heap( 4051): Grow heap (frag case) to 22.303MB for 3713210-byte allocation
,D/dalvikvm( 4051): GC_CONCURRENT freed 2918K, 34% free 18205K/27216K, paused 4ms+5ms, total 63ms
,D/dalvikvm( 4051): GC_FOR_ALLOC freed 759K, 34% free 18084K/27216K, paused 29ms, total 29ms
,W/jxcore-log( 4051): Initializing JXcore engine
,W/jxcore-log( 4051): JXcore engine is ready
,D/dalvikvm( 4051): GC_CONCURRENT freed 364K, 24% free 20739K/27216K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 4051): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4051): Starting JXcore engine
,W/jxcore-log( 4051): Platform android
W/jxcore-log( 4051): 
,W/jxcore-log( 4051): Process ARCH arm
W/jxcore-log( 4051): 
,I/jxcore-log( 4051): JXcore Cordova bridge is ready!
I/jxcore-log( 4051): 
,W/jxcore-log( 4051): JXcore engine is started
,I/chromium( 4051): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4051): Toggling radios to true
I/jxcore-log( 4051): 
,D/BluetoothAdapter( 4051): enable(): BT is already enabled..!
D/WifiService( 1016): New client listening to asynchronous messages
D/WifiService( 1016): setWifiEnabled: true pid=4051, uid=10513
,E/WifiService( 1016): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1016): handleMessage: E msg.what=131145
D/WifiStateMachine( 1016): processMsg: ConnectedState
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
I/jxcore-log( 4051): Radios toggled
I/jxcore-log( 4051): 
D/BluetoothManagerService( 1016): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1016): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4051): Received device characteristics:
I/jxcore-log( 4051): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4051): Bluetooth name: XT1039
I/jxcore-log( 4051): Device name: motorola-XT1039
I/jxcore-log( 4051): 
I/jxcore-log( 4051): Perf Test app loaded loaded
I/jxcore-log( 4051): 
,I/jxcore-log( 4051): check test folder
I/jxcore-log( 4051): 
,I/jxcore-log( 4051): found test : ./testFindPeers.js
I/jxcore-log( 4051): 
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 68 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 68 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1016): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/Tethering( 1016): InitialState.processMessage what=4
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiStateMachine( 1016): invokeExitMethods: ConnectedState
,V/ConnectivityService( 1016): WiFi NOT Tethered!
D/WifiStateMachine( 1016): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1016): Stopping DHCP and clearing IP
D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1016): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  387): NL - Read 60 bytes from update socket.
D/TCMD    (  387): NL - ignore NL message, type = 21
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiStateMachine( 1016): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,I/jxcore-log( 4051): found test : ./testSendData.js
I/jxcore-log( 4051): 
,D/WifiStateMachine( 1016): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1016): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1016): connected time updated 184280
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1016): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1016): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1016): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1016): DisconnectingState
,D/Checkin ( 1016): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService( 1016): Attempting to switch to mobile
D/ConnectivityService( 1016): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1016): Attempting to switch to ETHERNET
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131146
D/WifiStateMachine( 1016): processMsg: DisconnectingState
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147460
D/WifiStateMachine( 1016): processMsg: DisconnectingState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): Network connection lost
,D/WifiStateMachine( 1016): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1016): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1016): resetConnections(wlan0, 3)
D/NetUtils( 1016): android_net_utils_resetConnections in env=0x6173b668 clazz=0x62c00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1379): Read error: ssl=0x6117cb00: I/O error during system call, Connection timed out
,D/WifiStateMachine( 1016): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1016): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1016): invokeExitMethods: DisconnectingState
,D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1016): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131101
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131216
,D/Checkin ( 1016): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): processMsg: DefaultState
,D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131216
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): processMsg: DefaultState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
,V/NativeCrypto( 1379): SSL shutdown failed: ssl=0x6117cb00: I/O error during system call, Broken pipe
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1016): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1296): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1016): Attempting to switch to mobile
D/ConnectivityService( 1016): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1016): Attempting to switch to ETHERNET
I/Choreographer( 4051): Skipped 117 frames!  The application may be doing too much work on its main thread.
I/chromium( 4051): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1296): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1154): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1154): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1016): handleMessage: E msg.what=147461
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
,D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
,I/wpa_supplicant( 1154): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1154): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  387): NL - Read 312 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 88 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 68 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1154): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  387): NL - Read 80 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 80 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 68 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1154): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213371568
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
,E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/Tethering( 1016): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147459
D/WifiStateMachine( 1016): processMsg: DisconnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
,D/WifiStateMachine( 1016): Network connection established
,D/WifiStateMachine( 1016): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1016): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1016): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1016): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1016): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1016): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147462
D/WifiStateMachine( 1016): processMsg: ObtainingIpState
D/WifiStateMachine( 1016): ObtainingIpState{ when=-44ms what=147462 obj=android.net.wifi.StateChangeResult@4324a558 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=131101
D/WifiStateMachine( 1016): processMsg: ObtainingIpState
,D/WifiStateMachine( 1016): ObtainingIpState{ when=-30ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4320b6b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
D/WifiStateMachine( 1016): ObtainingIpState{ when=-19ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1016): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1016): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4250cee0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4250cee0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 3
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 3
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 8
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 8
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 8c
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 8c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 8e,
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 8e,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE ,
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1016): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
,D/WifiStateMachine( 1016): ObtainingIpState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiP2pService( 1016): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiP2pService( 1016): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43579a18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43579a18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43579a18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): handleMessage: X
,D/TCMD    (  387): NL - Read 60 bytes from update socket.
D/TCMD    (  387): NL - ignore NL message, type = 20
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiStateMachine( 1016): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1016): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
,D/WifiStateMachine( 1016): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): processMsg: DefaultState
,D/WifiStateMachine( 1016): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1016): processMsg: ObtainingIpState
,D/WifiStateMachine( 1016): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,D/WifiStateMachine( 1016): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1016): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1016): DHCP successful
D/WifiStateMachine( 1016): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1016): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1016): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1016): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1016): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1016): VerifyingLinkState enter
D/WifiStateMachine( 1016): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=151572
D/WifiStateMachine( 1016): processMsg: VerifyingLinkState
D/WifiStateMachine( 1016): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1016): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1016): handleMessage: X
,D/WifiStateMachine( 1016): handleMessage: E msg.what=135190
D/WifiStateMachine( 1016): processMsg: VerifyingLinkState
D/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1016): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1016): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1016): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1016): CaptivePortalCheckState enter
,D/WifiStateMachine( 1016): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1016): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1016): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1016): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1016): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131092
D/WifiStateMachine( 1016): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1016): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1016): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1016): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1016): WiFi NOT Tethered!
,E/ConnectivityService( 1016): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ce850
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1016): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1296): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1016): transitionTo: destState=ConnectedState
D/ConnectivityService( 1016): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1016): WiFi NOT Tethered!
,D/WifiStateMachine( 1016): handleMessage: new destination call exit/enter
,E/ConnectivityService( 1016): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ce850
I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1016): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1016): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1016): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1016): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1016): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1016): handleMessage: X
D/WifiStateMachine( 1016): handleMessage: E msg.what=131092
D/WifiStateMachine( 1016): processMsg: ConnectedState
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
D/WifiStateMachine( 1016): processMsg: DefaultState
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1016): handleMessage: X
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1016): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1296): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=0
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1016): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,D/PollingManager( 1567): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1016): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1016): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4196 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1016): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,E/ActivityThread( 1567): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1567): Registering with Alarm Manager to restart CCE
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
D/PollingManager( 1567): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1567): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1567): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,D/dalvikvm( 4196): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fedbe0, skipping init
I/openssl ( 4196): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4196): Crypto mode 0 already enabled
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4233 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 3727:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4233): mnc/mcc: 
V/MmsConfig( 4233): tag: bool value: enabledMMS - true
V/MmsConfig( 4233): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4233): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4233): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4233): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4233): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4233): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4233): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4233): tag: int value: recipientLimit - 20
V/MmsConfig( 4233): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4233): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4233): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4233): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4233): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4233): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4233): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4233): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4233): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1016): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4252 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1016): Killing 3879:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4252): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4252): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4252): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4252): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4265 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 3415:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1398): Checkin interval check for package: unspecified last checkin: 1451989057845 min interval config: 0 actual interval: 172114
,I/CheckinService( 1398): Checking schedule, now: 1451989229968 next: 1451989087822
,I/CheckinService( 1398): active receiver: enabled
,I/CheckinService( 1398): Preparing to send checkin request
,I/EventLogService( 1398): Accumulating logs since 1451989053252
,I/CheckinRequestBuilder( 1398): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1398): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4284 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 3926:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1016): NetTransition Wakelock for ConnectedState released by timeout
,V/WebViewChromiumFactoryProvider( 4284): Binding Chromium to main looper Looper (main, tid 1) {41feab20}
,I/LibraryLoader( 4284): Expected native library version number "",actual native library version number ""
,I/chromium( 4284): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4284): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4284): BLUETOOTH permission is missing!
,D/dalvikvm( 1016): GC_EXPLICIT freed 23961K, 65% free 18135K/51044K, paused 5ms+11ms, total 169ms
,I/Adreno-EGL( 4284): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4284): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4284): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4284): Local Branch: 
I/Adreno-EGL( 4284): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4284): Local Patches: NONE
I/Adreno-EGL( 4284): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4284): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4284): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4284): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1016): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4318 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,W/dalvikvm( 4318): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4318): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/dalvikvm( 4318): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4318): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4318): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4318): install
,I/MultiDex( 4318): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4318): loading existing secondary dex files
,I/MultiDex( 4318): load found 3 secondary dex files
,I/MultiDex( 4318): install done
,D/dalvikvm( 4318): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4318): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4318): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4318): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4318): VFY: unable to resolve instance field 36
,D/dalvikvm( 4318): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4318): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4318): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4318): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4318): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4318): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff06f0
,D/dalvikvm( 4318): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff06f0
,D/dalvikvm( 4318): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff06f0, skipping init
D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41ff06f0
,D/dalvikvm( 4318): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41ff06f0
,V/JNIHelp ( 4318): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4284): Starting up...
,D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41ff06f0
,D/dalvikvm( 4318): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41ff06f0
D/dalvikvm( 4318): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41ff06f0
D/dalvikvm( 4318): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41ff06f0
,I/ImageResourceManager( 3448): ImageResourceManager: uninitalized
,I/iu.Environment( 3448): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1016): Killing 3431:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1567): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1567): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1567): bindWebServices(): registering our AIDL callback...
I/SundryService( 1567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1567): onServiceConnected()
D/GetNotificationsWS( 1567): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1567): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 4196): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4196): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4252): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4252): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3448): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ProviderInstaller( 4318): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1210): callingUid 10022, callindPid: 1210
,E/MDM     ( 1210): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1398): Restart initialization of location
D/AuthorizationBluetoothService( 1379): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1379): Proximity feature is not enabled.
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1210): No location to return for getLastLocation()
,W/FusedLocationProvider( 1210): location=null
,I/dalvikvm( 4318): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4318): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4318): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4318): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4318): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4318): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4318): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4318): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4318): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4318): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4318): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4318): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4318): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4318): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5390000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5390000
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=2655885859
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4318): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4318): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421f9830
D/dalvikvm( 4318): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421f9830
,D/dalvikvm( 4318): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421f9830, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 4318): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4051): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4051): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4051): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4051): Shutting down VM
,W/dalvikvm( 4051): threadid=1: thread exiting with uncaught exception (group=0x41716d40)
E/AndroidRuntime( 4051): FATAL EXCEPTION: main
E/AndroidRuntime( 4051): Process: com.test.thalitest, PID: 4051
E/AndroidRuntime( 4051): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4051): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4051): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4051): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4051): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4051): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4051): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4051): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4051): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4051): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4051): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4051): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4051): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4051): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4051): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4051): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager( 1016):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager( 1016): Killing 3944:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4051): Sending signal. PID: 4051 SIG: 9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1016): Process com.test.thalitest (pid 4051) has died.
,D/WifiService( 1016): Client connection lost with reason: 4
,I/WindowState( 1016): WIN DEATH: Window{444569e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/OtaApp  ( 1567): [info] > Updatetime from metadata: 10
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1567): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1567): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1016): Got RemoteException sending setActive(false) notification to pid 4051 uid 10513
W/Binder  ( 1196): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1196): java.lang.NullPointerException
W/Binder  ( 1196): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1196): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1196): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1196): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 4318): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4369): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4318): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4318): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 73ms
,I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1783670210
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1016): MasterInitialState.processMessage what=3
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1016): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1567): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,D/PollingManager( 1567): now: 216407 ,futureTime: 42555010
,D/PollingManager( 1567): Polling alarm set to expire at: 42555010 Current Time: 216408
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1016): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1567): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1567): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1567): [debug] > CusSM.onRadioUp
D/PollingManager( 1567): now: 216445 ,futureTime: 42555010
D/PollingManager( 1567): Polling alarm set to expire at: 42555010 Current Time: 216445
D/OtaApp  ( 1567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1567): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
E/ActivityThread( 1567): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
D/OtaApp  ( 1567): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1567): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
D/OtaApp  ( 1567): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4196): Crypto mode not selected, openssl will run on its regular mode.
I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
D/OtaApp  ( 1567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1567): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
I/openssl ( 4196): Crypto mode 0 already enabled
D/OtaApp  ( 1567): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1567): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/MobileConnectivityChangeReceiver( 4252): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4252): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3448): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/CheckinService( 1398): Checkin interval check for package: unspecified last checkin: 1451989057845 min interval config: 0 actual interval: 174448
I/Adreno-EGL( 4318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4318): Local Branch: 
I/Adreno-EGL( 4318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4318): Local Patches: NONE
I/Adreno-EGL( 4318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
D/DEBUG   ( 1567): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/dalvikvm( 3448): GC_CONCURRENT freed 633K, 5% free 16441K/17224K, paused 4ms+4ms, total 28ms
W/ContextImpl( 1567): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1567): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1567): onServiceConnected()
,D/GetNotificationsWS( 1567): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1567): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4196): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4196): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4252): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4252): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3448): GC_FOR_ALLOC freed 39K, 5% free 16405K/17224K, paused 11ms, total 12ms
,I/CheckinRequestBuilder( 1398): Classify the device as Phone.
,I/dalvikvm-heap( 3448): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
,I/iu.Environment( 3448): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1398): Checkin interval check for package: unspecified last checkin: 1451989057845 min interval config: 0 actual interval: 174524
,D/dalvikvm( 3448): GC_FOR_ALLOC freed 4K, 5% free 18183K/19004K, paused 13ms, total 13ms
,D/DEBUG   ( 1567): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1567): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1567): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1567): onServiceConnected()
D/GetNotificationsWS( 1567): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1567): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1016): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1567
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1567): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1567): [info] > Updatetime from metadata: 10
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1567): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1567): [info] > Updatetime from metadata: 10
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1567): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1567): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1016): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1567
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1567): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1567): [info] > Updatetime from metadata: 10
D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1567): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1567): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1567): [info] > Updatetime from metadata: 10
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1567): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1567): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1567): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1016): Activity reported stop, but no longer stopping: ActivityRecord{420b5e28 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/dalvikvm( 1398): GC_CONCURRENT freed 1800K, 30% free 12115K/17224K, paused 6ms+6ms, total 44ms
,I/CheckinTask( 1398): Sending checkin request (11629 bytes)
,D/WifiStateMachine( 1016): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1016): handleMessage: E msg.what=131215
D/WifiStateMachine( 1016): processMsg: ConnectedState
D/WifiStateMachine( 1016): processMsg: L2ConnectedState
D/WifiStateMachine( 1016): processMsg: ConnectModeState
D/WifiStateMachine( 1016): processMsg: DriverStartedState
D/WifiStateMachine( 1016): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1016): processMsg: DefaultState
,D/WifiStateMachine( 1016): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1016): handleMessage: X
,D/ConnectivityService( 1016): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1016):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1016): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1016): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1398): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1398): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1379): GC_EXPLICIT freed 1444K, 40% free 10354K/17224K, paused 2ms+4ms, total 37ms
,I/CheckinRequestBuilder( 1398): Classify the device as Phone.
,I/CheckinTask( 1398): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1398): Checking schedule, now: 1451989233273 next: 1452582303266
,I/CheckinService( 1398): active receiver: disabled
,I/CheckinService( 1398): Checking schedule, now: 1451989233293 next: 1452582303266
,I/CheckinService( 1398): active receiver: disabled
,D/CheckinService( 1398): Recording last checkin time for package unspecified as 1451989233298
,D/GCM     ( 1379): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1016): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1296): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1296): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4284): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4427 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
,I/Launcher( 1308): Deferring update until onResume
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/Launcher( 1308): Deferring update until onResume
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
,I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
,I/Babel   ( 4427): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4427): MmsConfig.loadMmsSettings
I/Babel   ( 4427): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4427): MmsConfig.loadFromDatabase
,E/Babel   ( 4427): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4427): MmsConfig.loadFromResources
,E/Babel   ( 4427): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4427): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1210): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 4427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1016): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4463 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1016): Killing 3466:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1016): GC_EXPLICIT freed 1532K, 65% free 18130K/51044K, paused 5ms+12ms, total 102ms
I/ActivityManager( 1016): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4482 uid=10033 gids={50033, 3003, 1028, 1015}
I/ActivityManager( 1016): Killing 4196:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2310): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4502 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1016): Killing 4233:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4463): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4502): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4502): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4502): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2310): UpdateCorporaTask done [took 200 ms] updated apps [took 200 ms] 
,I/dalvikvm( 4502): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4502): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4502): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4502): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4502): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4502): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4502): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4502): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4502): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4502): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4502): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x013c
,I/ActivityManager( 1016): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4536 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/dalvikvm( 4502): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4502): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4502): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4502): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4502): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4502): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4502): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4502): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4502): Skipping gmscore version check
I/dalvikvm( 4502): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4502): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1016): Killing 4252:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1398): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1398): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1398): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4536): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fec278, skipping init
I/openssl ( 4536): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4536): Crypto mode 0 already enabled
,D/Finsky  ( 4502): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4502): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1016): Killing 4265:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1398): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1398): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451989242
,D/CaptivePortalTracker( 1016): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1016): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1016): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker( 1016): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1016): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1016): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1016): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1016): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1016): sending alarm Alarm{42209450 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{4216d4b8 type 3 android}
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
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{42315ee8 type 3 android}
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
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
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
,V/AlarmManager( 1016): sending alarm Alarm{4280f4e0 type 3 android}
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
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{42986f18 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{425c7348 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{43d2f540 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{428a4138 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{42899dd0 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{428c6410 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{421dc898 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1016): cleanup(): cleared. Last call was 560297 ms ago
,I/ActivityManager( 1016): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4580 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1016): Killing 4284:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1016): sending alarm Alarm{421af2e0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{421ca1d0 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{4219f858 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{43e184f8 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{428416a8 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{421c0420 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{423b4f88 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,D/ConnectivityService( 1016): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1296): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1016): sending alarm Alarm{43f559d8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43dd9f58 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{444f3680 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43de59d8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{444cee58 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43df2fa0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42823a38 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{43dd1890 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{44456438 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4285dab0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{420f3df8 type 0 com.google.android.gms}
,V/AlarmManager( 1016): sending alarm Alarm{44473ad0 type 1 com.android.deskclock}
,I/EventLogService( 1398): Aggregate from 1451989229989 (log), 1451988672248 (data)
,D/dalvikvm( 1398): GC_CONCURRENT freed 2086K, 31% free 11958K/17224K, paused 8ms+4ms, total 49ms
,V/AlarmManager( 1016): sending alarm Alarm{4286d2e0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428e4770 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43f57dc0 type 3 android}
,I/ProcessStatsService( 1016): Prepared write state in 16ms
,I/ProcessStatsService( 1016): Prepared write state in 13ms
,I/ProcessStatsService( 1016): Prepared write state in 21ms
,I/ProcessStatsService( 1016): Pruning old procstats: /data/system/procstats/state-2016-01-04-17-02-32.bin
,V/AlarmManager( 1016): sending alarm Alarm{4321f308 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4321f3c8 type 3 com.google.android.gms}
,V/AlarmManager( 1016): sending alarm Alarm{4321f418 type 2 android}
,V/AlarmManager( 1016): sending alarm Alarm{4321f468 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1379): SSL shutdown failed: ssl=0x630d3040: I/O error during system call, Connection timed out
,V/NativeCrypto( 1379): SSL shutdown failed: ssl=0x639456b8: I/O error during system call, Connection timed out
,I/GoogleURLConnFactory( 1210): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1210): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1210): Server returned 404
,V/AlarmManager( 1016): sending alarm Alarm{42190a28 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4211de40 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4666): 
D/AndroidRuntime( 4666): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4666): CheckJNI is OFF
D/dalvikvm( 4666): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4666): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4666): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4666): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4666): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4666): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4666): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4666): failed to load memtrack module: -2
D/AndroidRuntime( 4666): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10513 user=-1: uninstall pkg
I/dalvikvm( 1016): Total arena pages for JIT: 15
W/PackageSettings( 1016): Skipping PackageSetting{422a94d8 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10513 user=0: pkg removed
D/dalvikvm( 2278): GC_EXPLICIT freed 5369K, 44% free 9649K/17224K, paused 3ms+6ms, total 41ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
W/GeofencerStateMachine( 1210): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1308): GC_EXPLICIT freed 3335K, 33% free 11596K/17224K, paused 2ms+10ms, total 110ms
I/Launcher( 1308): Deferring update until onResume
D/dalvikvm( 2310): GC_EXPLICIT freed 4929K, 42% free 10139K/17224K, paused 9ms+6ms, total 110ms
D/dalvikvm( 1398): GC_EXPLICIT freed 196K, 31% free 11918K/17224K, paused 3ms+17ms, total 118ms
D/dalvikvm( 1016): GC_EXPLICIT freed 2179K, 65% free 18135K/51044K, paused 8ms+11ms, total 130ms
D/dalvikvm( 1016): WAIT_FOR_CONCURRENT_GC blocked 79ms
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
D/VoicemailCleanupService( 4463): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/Launcher( 1308): Deferring update until onResume
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2310): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4699 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451991031
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1016): removePackageParticipantsLocked: uid=10513 #1
D/dalvikvm( 1016): GC_EXPLICIT freed 596K, 65% free 18060K/51044K, paused 4ms+17ms, total 174ms
I/InternalIcingCorporaPro( 2310): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451991031
D/AndroidRuntime( 4666): Shutting down VM
D/dalvikvm( 4666): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4699): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4720 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4699): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4720): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4502): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4502): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4502): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1398): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1398): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1398): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1398): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1398): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1398): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1398): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1379): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1379): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1016): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4747 uid=10058 gids={50058}
V/AlarmManager( 1016): sending alarm Alarm{424df018 type 2 com.motorola.ccc.cce}
E/SQLiteLog( 1398): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/FileUtils( 1398): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1398): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1398): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1398): (3850) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1398): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1398): threadid=51: thread exiting with uncaught exception (group=0x41716d40)
E/AndroidRuntime( 1398): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1398): Process: com.google.android.gms, PID: 1398
E/AndroidRuntime( 1398): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1398): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1398): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1398): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1398): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1398): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1398): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1398): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1398): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1398): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1398): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/GMPM-SVC( 1398): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SharedPreferencesImpl( 1398): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SQLiteDatabase( 4720): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4720): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4720): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4720): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4720): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4720): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4720): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4720): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4720): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4720): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4720): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4720): threadid=10: thread exiting with uncaught exception (group=0x41716d40)
E/SQLiteLog( 1398): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1398): threadid=54: thread exiting with uncaught exception (group=0x41716d40)
I/Icing   ( 1398): doRemovePackageData com.test.thalitest
I/Process ( 1398): Sending signal. PID: 1398 SIG: 9
E/DropBoxManagerService( 1016): Can't write: system_app_crash
E/DropBoxManagerService( 1016): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1016): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1016): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1016): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1016): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1016): 	... 5 more
E/AndroidRuntime( 4720): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4720): Process: com.android.keychain, PID: 4720
E/AndroidRuntime( 4720): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4720): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4720): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4720): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4720): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4720): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4720): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4720): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4720): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4720): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4720): Sending signal. PID: 4720 SIG: 9
E/DropBoxManagerService( 1016): Can't write: system_app_crash
E/DropBoxManagerService( 1016): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1016): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1016): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1016): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1016): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1016): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1016): 	... 5 more
I/ActivityManager( 1016): Process com.android.keychain (pid 4720) has died.
W/ActivityManager( 1016): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager( 1016): Process com.google.android.gms (pid 1398) has died.
D/WifiService( 1016): Client connection lost with reason: 4
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 11000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 21000ms
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 31000ms
D/Documents( 4747): Loading roots for com.android.providers.downloads.documents
D/Documents( 4747): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4747): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4747): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4747): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4747): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4747): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4747): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4747): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4747): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4747): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4747): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4747): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4747): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4747): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4747): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4747): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4747): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4747): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4747): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4747): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4747): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4747): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4747): Shutting down VM
W/dalvikvm( 4747): threadid=1: thread exiting with uncaught exception (group=0x41716d40)
E/AndroidRuntime( 4747): FATAL EXCEPTION: main
E/AndroidRuntime( 4747): Process: com.android.documentsui, PID: 4747
E/AndroidRuntime( 4747): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4747): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4747): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4747): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4747): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4747): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4747): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4747): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4747): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4747): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4747): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4747): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4747): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4747): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4747): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4747): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4747): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4747): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4747): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4747): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4747): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4747): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4747): 	... 10 more
I/ActivityManager( 1016): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4774 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1016): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4786 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager( 1016): Killing 4318:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 

```
