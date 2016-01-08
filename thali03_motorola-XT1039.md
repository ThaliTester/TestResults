#### Test 5546736337bcedb_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4100): 
D/AndroidRuntime( 4100): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4100): CheckJNI is OFF
D/dalvikvm( 4100): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4100): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4100): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4100): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4100): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4100): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4100): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4100): failed to load memtrack module: -2
D/AndroidRuntime( 4100): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4100
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4116 uid=10524 gids={50524, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4100): Shutting down VM
D/dalvikvm( 4100): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 5ms
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4116): Binding Chromium to main looper Looper (main, tid 1) {41f18610}
I/LibraryLoader( 4116): Expected native library version number "",actual native library version number ""
I/chromium( 4116): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4116): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431d5cb8:true
I/Adreno-EGL( 4116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4116): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4116): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4116): Local Branch: 
I/Adreno-EGL( 4116): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4116): Local Patches: NONE
I/Adreno-EGL( 4116): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4116): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4116): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4116): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4116): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4116): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4116): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4116): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4116): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4116): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4116): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4116): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4116): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4116): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4116): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4116): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4116): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4116): Enabling debug mode 0
,W/AwContents( 4116): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,379
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +329ms (total +379ms)
W/AwContents( 4116): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4116): showStatusIcon on inactive InputConnection
,I/SFPerfTracer(  277):      triggers: (rate: 1:28) (compose: 0:4) (post: 0:1) (render: 0:5) (0:99 frames) (1:544)
,D/SFPerfTracer(  277):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:216)* (NavigationBar: 0:38)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:26)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:4)* 
,D/JsMessageQueue( 4116): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4116): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f1d238
,D/dalvikvm( 4116): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f1d238
,D/jxcore_app_log( 4116): JniHelper::setJavaVM(0x4156afa8), pthread_self() = 1613972616
,D/JX-Cordova( 4116): jxcore cordova android initializing
,D/dalvikvm( 4116): GC_CONCURRENT freed 2797K, 17% free 14392K/17224K, paused 2ms+2ms, total 55ms
,D/dalvikvm( 4116): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4116): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 139K, 17% free 14401K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 132K, 17% free 14416K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 16.203MB for 96598-byte allocation
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 180K, 17% free 14451K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 16.283MB for 144892-byte allocation
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 255K, 17% free 14499K/17464K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 16.398MB for 217334-byte allocation
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 371K, 18% free 14573K/17680K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 16.575MB for 325996-byte allocation
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 572K, 19% free 14695K/18000K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 16.849MB for 488990-byte allocation
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 872K, 20% free 14871K/18480K, paused 26ms, total 27ms
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 1291K, 19% free 15128K/18480K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 17.855MB for 1100216-byte allocation
,D/dalvikvm( 4116): GC_CONCURRENT freed 1812K, 21% free 15522K/19556K, paused 3ms+4ms, total 55ms
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 235K, 21% free 15469K/19556K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 18.712MB for 1650320-byte allocation
,D/dalvikvm( 4116): GC_CONCURRENT freed 1712K, 25% free 16036K/21168K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 1341K, 24% free 16096K/21168K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 20.112MB for 2475476-byte allocation
,D/dalvikvm( 4116): GC_CONCURRENT freed 263K, 22% free 18401K/23588K, paused 4ms+3ms, total 51ms
,D/dalvikvm( 4116): GC_CONCURRENT freed 4404K, 28% free 17099K/23588K, paused 1ms+8ms, total 48ms
,D/dalvikvm( 4116): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 22.271MB for 3713210-byte allocation
,D/dalvikvm( 4116): GC_CONCURRENT freed 2703K, 33% free 18302K/27216K, paused 1ms+7ms, total 56ms
,D/dalvikvm( 4116): GC_FOR_ALLOC freed 886K, 34% free 18043K/27216K, paused 28ms, total 28ms
,W/jxcore-log( 4116): Initializing JXcore engine
,W/jxcore-log( 4116): JXcore engine is ready
,D/dalvikvm( 4116): GC_CONCURRENT freed 370K, 25% free 20669K/27216K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4116): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4116): Starting JXcore engine
,W/jxcore-log( 4116): Platform android
W/jxcore-log( 4116): 
,W/jxcore-log( 4116): Process ARCH arm
W/jxcore-log( 4116): 
,I/jxcore-log( 4116): JXcore Cordova bridge is ready!
I/jxcore-log( 4116): 
,W/jxcore-log( 4116): JXcore engine is started
,I/chromium( 4116): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4116): Toggling radios to true
I/jxcore-log( 4116): 
,D/BluetoothAdapter( 4116): enable(): BT is already enabled..!
D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=4116, uid=10524
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4116): Radios toggled
I/jxcore-log( 4116): 
D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4116): Received device characteristics:
I/jxcore-log( 4116): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4116): Bluetooth name: XT1039
I/jxcore-log( 4116): Device name: motorola-XT1039
I/jxcore-log( 4116): 
I/jxcore-log( 4116): Perf Test app loaded loaded
I/jxcore-log( 4116): 
,I/jxcore-log( 4116): check test folder
I/jxcore-log( 4116): 
,I/jxcore-log( 4116): found test : ./testFindPeers.js
I/jxcore-log( 4116): 
,D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
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
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1021): InitialState.processMessage what=4
,V/ConnectivityService( 1021): WiFi NOT Tethered!
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1021): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiP2pService( 1021): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4116): found test : ./testSendData.js
I/jxcore-log( 4116): 
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  456): NL - Read 60 bytes from update socket.
D/TCMD    (  456): NL - ignore NL message, type = 21
,D/TCMD    (  456): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 302429
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1021): DisconnectingState
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection lost
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x61566e00 clazz=0x61000001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1365): Read error: ssl=0x62c86a48: I/O error during system call, Connection timed out
,V/NativeCrypto( 1365): SSL shutdown failed: ssl=0x62c86a48: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1021): invokeExitMethods: DisconnectingState
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,I/chromium( 4116): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  456): NL - Read 56 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  456): NL - Read 312 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 192 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  456): NL - Read 80 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 80 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request,
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
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
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193241264
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection established
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1021): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@43c5e148 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-45ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43775788 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-11ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420e4ae0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420e4ae0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  456): NL - Read 56 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 9
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 9
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 fc
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 fc
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fe
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 fe
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 10
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 10
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43718bb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43718bb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43718bb0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): handleMessage: X
,D/TCMD    (  456): NL - Read 60 bytes from update socket.
D/TCMD    (  456): NL - ignore NL message, type = 20
,D/TCMD    (  456): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): DHCP successful
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1021): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1021): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1021): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState enter
D/WifiStateMachine( 1021): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1021): WiFi NOT Tethered!
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff4300
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1021): WiFi NOT Tethered!
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff4300
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1021): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4272 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1565): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1565): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1565): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1565): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/dalvikvm( 4272): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f20cd8, skipping init
I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4272): Crypto mode 0 already enabled
I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4310 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3796:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1217): GC_CONCURRENT freed 1651K, 33% free 11631K/17224K, paused 3ms+13ms, total 50ms
,V/MmsConfig( 4310): mnc/mcc: 
,V/MmsConfig( 4310): tag: bool value: enabledMMS - true
V/MmsConfig( 4310): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4310): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4310): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4310): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4310): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4310): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4310): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4310): tag: int value: recipientLimit - 20
V/MmsConfig( 4310): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4310): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4310): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4310): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4310): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4310): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4310): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4310): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4310): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4329 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 3932:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4329): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4329): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4329): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4329): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4344 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3452:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1397): Checkin interval check for package: unspecified last checkin: 1452264505986 min interval config: 0 actual interval: 291690
,I/CheckinService( 1397): Checking schedule, now: 1452264797684 next: 1452264535964
,I/CheckinService( 1397): active receiver: enabled
,I/CheckinService( 1397): Preparing to send checkin request
,I/EventLogService( 1397): Accumulating logs since 1452264502206
,I/CheckinRequestBuilder( 1397): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1397): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4358 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3991:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 1021): GC_EXPLICIT freed 23809K, 65% free 18120K/50836K, paused 5ms+10ms, total 144ms
,V/WebViewChromiumFactoryProvider( 4358): Binding Chromium to main looper Looper (main, tid 1) {41f1dd88}
,I/LibraryLoader( 4358): Expected native library version number "",actual native library version number ""
,I/chromium( 4358): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4358): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4358): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4358): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4358): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4358): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4358): Local Branch: 
I/Adreno-EGL( 4358): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4358): Local Patches: NONE
I/Adreno-EGL( 4358): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4383 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 22ms
,W/chromium( 4358): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 5ms+2ms, total 21ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,W/dalvikvm( 4383): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4383): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4383): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4383): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4383): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4383): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4383): install
,I/MultiDex( 4383): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/GAV2    ( 4358): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
I/MultiDex( 4383): loading existing secondary dex files
W/ContextImpl( 4358): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/MultiDex( 4383): load found 3 secondary dex files
I/MultiDex( 4383): install done
,I/jxcore-log( 4116): Connected to the server!
I/jxcore-log( 4116): 
,D/dalvikvm( 4383): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4383): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4383): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4383): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4383): VFY: unable to resolve instance field 36
,D/dalvikvm( 4383): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4383): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4383): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4383): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4383): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4383): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4383): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f23a08
D/dalvikvm( 4383): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f23a08
,D/dalvikvm( 4383): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f23a08, skipping init
,D/dalvikvm( 4383): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f23a08
D/dalvikvm( 4383): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f23a08
,V/JNIHelp ( 4383): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/chromium( 4116): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 4383): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f23a08
,D/dalvikvm( 4383): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f23a08
D/dalvikvm( 4383): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f23a08
,D/dalvikvm( 4383): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f23a08
,I/ProviderInstaller( 4383): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 4358): Starting up...
,I/dalvikvm( 4383): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4383): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4383): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4383): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4383): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4383): VFY: replacing opcode 0x6e at 0x000d
,I/ImageResourceManager( 3485): ImageResourceManager: uninitalized
,I/iu.Environment( 3485): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1021): Killing 3469:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1565): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1565): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1565): bindWebServices(): registering our AIDL callback...
,I/dalvikvm( 4383): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4383): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4383): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4383): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4383): VFY: replacing opcode 0x22 at 0x0000
I/SundryService( 1565): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1565): ServiceHandler.handleMessage: mWaitCount=0
I/dalvikvm( 4383): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4383): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4383): VFY: replacing opcode 0x6e at 0x0036
,D/EmailService.MarketingOptInSetter( 1565): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1565): onServiceConnected()
D/GetNotificationsWS( 1565): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1565): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4272): Crypto mode 0 already enabled
I/dalvikvm( 4383): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4383): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/dalvikvm( 4383): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/MobileConnectivityChangeReceiver( 4329): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4329): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3485): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5131000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5131000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/AuthorizationBluetoothService( 1365): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1365): Proximity feature is not enabled.
,D/WearableService( 1217): callingUid 10022, callindPid: 1217
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/LocationInitializer( 1397): Restart initialization of location
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=201779917
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/MDM     ( 1217): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1217): No location to return for getLastLocation()
,W/FusedLocationProvider( 1217): location=null
,D/NativeLibraryUtils( 4383): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4383): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42138b48
,D/dalvikvm( 4383): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42138b48
,D/dalvikvm( 4383): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42138b48, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4383): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4431): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4383): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4383): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,D/WifiStateMachine( 1021): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,I/Adreno-EGL( 4383): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4383): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4383): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4383): Local Branch: 
I/Adreno-EGL( 4383): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4383): Local Patches: NONE
I/Adreno-EGL( 4383): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
D/ConnectivityService( 1021): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1021):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 4383): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4383): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4383): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4383): Local Branch: 
I/Adreno-EGL( 4383): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4383): Local Patches: NONE
I/Adreno-EGL( 4383): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4116): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4116): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4116): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4116): BLE is supported
I/jxcore-log( 4116): 
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2984555355
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4383): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4383): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4383): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4383): Local Branch: 
I/Adreno-EGL( 4383): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4383): Local Patches: NONE
I/Adreno-EGL( 4383): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4383): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4383): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4383): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4383): Local Branch: 
I/Adreno-EGL( 4383): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4383): Local Patches: NONE
I/Adreno-EGL( 4383): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1565): now: 334800 ,futureTime: 25308990
,D/PollingManager( 1565): Polling alarm set to expire at: 25308990 Current Time: 334800
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1565): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1565): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1565): [debug] > CusSM.onRadioUp
D/PollingManager( 1565): now: 334811 ,futureTime: 25308990
D/PollingManager( 1565): Polling alarm set to expire at: 25308990 Current Time: 334811
D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/Tethering( 1021): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1565): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,E/ActivityThread( 1565): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
D/OtaApp  ( 1565): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4272): Crypto mode 0 already enabled
D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4329): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4329): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1565): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1565): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1565): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.Environment( 3485): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1565): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3485): GC_CONCURRENT freed 626K, 5% free 16444K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm( 3485): WAIT_FOR_CONCURRENT_GC blocked 5ms
,I/CheckinService( 1397): Checkin interval check for package: unspecified last checkin: 1452264505986 min interval config: 0 actual interval: 293998
,I/dalvikvm-heap( 3485): Grow heap (frag case) to 19.828MB for 1821008-byte allocation
,D/DEBUG   ( 1565): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1565): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1565): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1565): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1565): onServiceConnected()
D/GetNotificationsWS( 1565): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1565): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1565): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1565): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4272): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4272): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4329): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4329): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3485): GC_FOR_ALLOC freed 41K, 5% free 18184K/19004K, paused 12ms, total 12ms
,I/iu.Environment( 3485): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1397): Checkin interval check for package: unspecified last checkin: 1452264505986 min interval config: 0 actual interval: 294069
,W/Settings( 4383): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1397): Classify the device as Phone.
,D/DEBUG   ( 1565): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1565): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1565): bindWebServices(): registering our AIDL callback...
I/SundryService( 1565): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1565): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1565): onServiceConnected()
,D/GetNotificationsWS( 1565): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1565): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1565): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1565): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1565
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1565): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1565): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1565): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1565
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
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
,W/IInputConnectionWrapper( 4116): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1021): Activity reported stop, but no longer stopping: ActivityRecord{41fd2108 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1021): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,128
,I/CheckinTask( 1397): Sending checkin request (11754 bytes)
,I/CheckinRequestBuilder( 1397): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1397): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1365): GC_EXPLICIT freed 1223K, 41% free 10329K/17224K, paused 2ms+5ms, total 43ms
,I/CheckinRequestBuilder( 1397): Classify the device as Phone.
,I/CheckinTask( 1397): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1397): Checking schedule, now: 1452264801088 next: 1452857871085
,I/CheckinService( 1397): active receiver: disabled
,I/CheckinService( 1397): Checking schedule, now: 1452264801103 next: 1452857871085
,I/CheckinService( 1397): active receiver: disabled
,D/CheckinService( 1397): Recording last checkin time for package unspecified as 1452264801107
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1295): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1295): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4358): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1021): Killing 4018:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4492 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/Launcher( 1307): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/Launcher( 1307): Deferring update until onResume
,I/GCoreNlp( 1217): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4492): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4492): MmsConfig.loadMmsSettings
,I/Babel   ( 4492): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4492): MmsConfig.loadFromDatabase
,E/Babel   ( 4492): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4492): MmsConfig.loadFromResources
,E/Babel   ( 4492): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4492): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4492): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1021): GC_EXPLICIT freed 1463K, 65% free 18092K/50836K, paused 5ms+9ms, total 94ms
,I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4529 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1021): Killing 3503:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4548 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4272:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2339): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1021): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4566 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4310:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4529): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4566): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4566): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4566): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2339): UpdateCorporaTask done [took 196 ms] updated apps [took 196 ms] 
,I/dalvikvm( 4566): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4566): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4566): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4566): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4566): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4566): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4566): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4566): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4566): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4566): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4566): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4566): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4566): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x037f
,I/dalvikvm( 4566): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4566): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4602 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4566): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4566): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4566): Skipping gmscore version check
,D/Finsky  ( 4566): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4566): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4566): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4566): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1021): Killing 4329:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1397): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1397): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1397): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4602): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f1f260, skipping init
I/openssl ( 4602): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4602): Crypto mode 0 already enabled
,D/Finsky  ( 4566): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4566): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1021): Killing 4344:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1397): GC_CONCURRENT freed 2147K, 30% free 12091K/17224K, paused 4ms+9ms, total 58ms
,I/Icing   ( 1397): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Icing   ( 1397): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,D/CaptivePortalTracker( 1021): Checking http://216.58.209.46/generate_204
,I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452264809
,D/CaptivePortalTracker( 1021): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1021): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1021): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1021): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
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
,V/AlarmManager( 1021): sending alarm Alarm{437554e8 type 2 android}
,V/AlarmManager( 1021): sending alarm Alarm{437555c0 type 3 android}
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
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = ,
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
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{424af908 type 3 android}
,I/jxcore-log( 4116): --- start :testFindPeers.js---
I/jxcore-log( 4116): 
,I/jxcore-log( 4116): testFindPeers created [object Object]
I/jxcore-log( 4116): 
,I/jxcore-log( 4116): serverPort is 8876
I/jxcore-log( 4116): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4116): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4116): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4116): start: Peer ID: F4:F1:E1:5C:3B:E2, peer name: XT1039
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4116): bind: Binding a new listener
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4116): initialize: My bluetooth address is F4:F1:E1:5C:3B:E2
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4116): verifyIdentityString: Identity string created: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"XT1039"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4116): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4116): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1797): SOCK FLAG = 0 ***********************
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4116): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4116): start: OK
I/io.jxcore.node.ConnectionHelper( 4116): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4116): start: Peer ID: F4:F1:E1:5C:3B:E2, peer name: XT1039
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4116): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4116): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4116): Waiting for incoming connections...
,W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4116): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
W/dalvikvm( 4116): VFY: unable to resolve new-instance 425 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 4116): VFY: replacing opcode 0x22 at 0x0013
W/dalvikvm( 4116): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,I/dalvikvm( 4116): Could not find method android.bluetooth.le.ScanResult.getScanRecord, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.checkScanResult
W/dalvikvm( 4116): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0002
E/dalvikvm( 4116): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 4116): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 4116): VFY: replacing opcode 0x22 at 0x002d
W/dalvikvm( 4116): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4116): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4116): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.start
W/dalvikvm( 4116): VFY: unable to resolve virtual method 1804: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
,D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0016
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4116): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.stop, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stop
W/dalvikvm( 4116): VFY: unable to resolve virtual method 1805: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
D/dalvikvm( 4116): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
D/dalvikvm( 4116): DexOpt: unable to opt direct call 0x0705 at 0x15 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
,W/dalvikvm( 4116): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
W/dalvikvm( 4116): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
D/dalvikvm( 4116): DexOpt: unable to opt direct call 0x0726 at 0x25 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
,D/dalvikvm( 4116): DexOpt: unable to opt direct call 0x0048 at 0x2f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
D/dalvikvm( 4116): DexOpt: unable to opt direct call 0x005c at 0x5f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AndroidRuntime( 4116): Shutting down VM
,W/dalvikvm( 4116): threadid=1: thread exiting with uncaught exception (group=0x41649d40)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at android.os.Looper.loop(Looper.java:136)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4116): 	at dalvik.system.NativeStart.main(Native Method)
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
,V/AlarmManager( 1021): sending alarm Alarm{4205f3e8 type 3 android}
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
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 9
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
,V/AlarmManager( 1021): sending alarm Alarm{42876b78 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{4272e180 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{422a3f88 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4371fb30 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43755698 type 0 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{43755770 type 1 com.android.deskclock}
,I/ActivityManager( 1021): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4661 uid=10015 gids={50015, 1028}
,I/EventLogService( 1397): Aggregate from 1452264797701 (log), 1452263107290 (data)
,I/ActivityManager( 1021): Killing 4358:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1021): sending alarm Alarm{434d0fa0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{434d1008 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,V/AlarmManager( 1021): sending alarm Alarm{420f97b0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4375c7e0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43c5a938 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427af7a8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43c54110 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{438464d0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{41f55ec8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43535968 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1295): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
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
,V/AlarmManager( 1021): sending alarm Alarm{43d33208 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43742938 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{42034360 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43c84dc0 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{4371d928 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{424a9398 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{42ede2b8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{41fcd880 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{41fcd958 type 1 com.android.deskclock}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
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
,V/AlarmManager( 1021): sending alarm Alarm{43542e68 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{427925d0 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{4371bb28 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43295c68 type 3 android}
,I/ProcessStatsService( 1021): Prepared write state in 21ms
,I/ProcessStatsService( 1021): Prepared write state in 17ms
,I/ProcessStatsService( 1021): Prepared write state in 19ms
,I/ProcessStatsService( 1021): Pruning old procstats: /data/system/procstats/state-2016-01-07-17-18-33.bin
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
,V/AlarmManager( 1021): sending alarm Alarm{425134e8 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{428ff798 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{43c8f830 type 3 android}
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
,V/AlarmManager( 1021): sending alarm Alarm{42fa02e8 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4715): 
D/AndroidRuntime( 4715): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4715): CheckJNI is OFF
D/dalvikvm( 4715): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4715): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4715): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4715): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4715): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4715): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4715): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4715): failed to load memtrack module: -2
D/AndroidRuntime( 4715): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10524 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 4116:com.test.thalitest/u0a524 (adj 9): stop com.test.thalitest
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1021):   Force finishing activity ActivityRecord{43543328 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1021): WIN DEATH: Window{434c83f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1021): Client connection lost with reason: 4
E/bt-btif ( 1797): bta_jv_rfcomm_stop_server
W/InputDispatcher( 1021): channel '434c83f0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1021): channel '434c83f0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher( 1021): Attempted to unregister already unregistered input channel '434c83f0 com.test.thalitest/com.test.thalitest.MainActivity (server)'
W/PackageSettings( 1021): Skipping PackageSetting{421db790 com.example.hello/10523} due to missing metadata
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10524 user=0: pkg removed
D/dalvikvm( 2307): GC_EXPLICIT freed 5459K, 44% free 9649K/17224K, paused 8ms+5ms, total 53ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1021): GC_EXPLICIT freed 1946K, 65% free 18133K/50836K, paused 6ms+18ms, total 124ms
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2339): GC_EXPLICIT freed 3021K, 43% free 9824K/17224K, paused 2ms+7ms, total 143ms
D/VoicemailCleanupService( 4529): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
D/dalvikvm( 1397): GC_EXPLICIT freed 1011K, 31% free 11918K/17224K, paused 3ms+19ms, total 116ms
D/dalvikvm( 1307): GC_EXPLICIT freed 3336K, 33% free 11598K/17224K, paused 39ms+5ms, total 143ms
I/Launcher( 1307): Deferring update until onResume
D/dalvikvm( 1021): GC_EXPLICIT freed 283K, 65% free 17950K/50836K, paused 6ms+10ms, total 105ms
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452266599
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2339): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4759 uid=10059 gids={50059, 3003, 1028, 1015}
I/Launcher( 1307): Deferring update until onResume
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10524 #1
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452266599
D/AndroidRuntime( 4715): Shutting down VM
D/dalvikvm( 4715): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/InternalIcingCorporaPro( 2339): UpdateCorporaTask done [took 144 ms] updated apps [took 144 ms] 
W/ActiveOrDefaultContextProvider( 4759): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4790 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1021): Killing 4383:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/SQLiteLog( 2307): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2307): Error inserting state=event=am_kill pid=4383 process=com.google.android.gms.unstable reason=empty+%239 selectadj=15 timestamp=1452266599767 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2307): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2307): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2307): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2307): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2307): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2307): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2307): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2307): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2307): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2307): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2307): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2307): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2307): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2307): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2307): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2307): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4759): (3850) statement aborts at 59: [DELETE FROM CachedSearch101 WHERE timestamp<?] disk I/O error
E/AbstractDatabaseInstance( 4759): Failed to delete from CachedSearch101
E/AbstractDatabaseInstance( 4759): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4759): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4759): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AbstractDatabaseInstance( 4759): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4759): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4759): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AbstractDatabaseInstance( 4759): 	at WQ.b(AbstractDatabaseInstance.java:292)
E/AbstractDatabaseInstance( 4759): 	at XC.a(DatabaseModelLoader.java:317)
E/AbstractDatabaseInstance( 4759): 	at Yg.a(ObsoleteDataCleanerImpl.java:122)
E/AbstractDatabaseInstance( 4759): 	at fh.run(DocsApplication.java:264)
W/dalvikvm( 4759): threadid=11: thread exiting with uncaught exception (group=0x41649d40)
E/AndroidRuntime( 4759): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4759): Process: com.google.android.apps.docs, PID: 4759
E/AndroidRuntime( 4759): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 4759): 	at WQ.b(AbstractDatabaseInstance.java:292)
E/AndroidRuntime( 4759): 	at XC.a(DatabaseModelLoader.java:317)
E/AndroidRuntime( 4759): 	at Yg.a(ObsoleteDataCleanerImpl.java:122)
E/AndroidRuntime( 4759): 	at fh.run(DocsApplication.java:264)
W/GAV2    ( 4759): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/DropBoxManagerService( 1021): Can't write: system_app_crash
E/DropBoxManagerService( 1021): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 4759): Sending signal. PID: 4759 SIG: 9
W/ContextImpl( 4790): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4566): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4566): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1397): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1397): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1397): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1397): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1397): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/LocationSettingsChecker( 1397): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1365): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/ChimeraModuleLdr( 1397): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 1365): Shutting down VM
W/dalvikvm( 1365): threadid=1: thread exiting with uncaught exception (group=0x41649d40)
E/SQLiteLog( 1397): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1397): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1397): disk I/O error (code 3850)
E/DriveAsyncService( 1397): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1397): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1397): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1397): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1397): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1397): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1397): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1397): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1397): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1397): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1397): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1397): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1397): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1397): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1397): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1397): 	at java.lang.Thread.run(Thread.java:841)

```
