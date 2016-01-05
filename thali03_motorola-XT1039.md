#### Test 54968200254eab2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4439): 
D/AndroidRuntime( 4439): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4439): CheckJNI is OFF
D/dalvikvm( 4439): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4439): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4439): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4439): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4439): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4439): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4439): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4439): failed to load memtrack module: -2
D/AndroidRuntime( 4439): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4439
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4455 uid=10511 gids={50511, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4439): Shutting down VM
D/dalvikvm( 4439): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 23ms
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
V/WebViewChromiumFactoryProvider( 4455): Binding Chromium to main looper Looper (main, tid 1) {4203fad0}
I/LibraryLoader( 4455): Expected native library version number "",actual native library version number ""
I/chromium( 4455): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4455): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4215a8f0:true
I/Adreno-EGL( 4455): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4455): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4455): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4455): Local Branch: 
I/Adreno-EGL( 4455): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4455): Local Patches: NONE
I/Adreno-EGL( 4455): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4455): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4455): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4455): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4455): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4455): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4455): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4455): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4455): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4455): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4455): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4455): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4455): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4455): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4455): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4455): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4455): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4455): Enabling debug mode 0
,W/AwContents( 4455): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4455): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,487
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +455ms (total +487ms)
,D/JsMessageQueue( 4455): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4455): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42043f80
,D/dalvikvm( 4455): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42043f80
,D/jxcore_app_log( 4455): JniHelper::setJavaVM(0x41758f78), pthread_self() = 1614193872
,D/JX-Cordova( 4455): jxcore cordova android initializing
,D/dalvikvm( 4455): GC_CONCURRENT freed 2750K, 17% free 14439K/17224K, paused 2ms+2ms, total 52ms
,D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 179K, 17% free 14445K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 16.201MB for 64402-byte allocation
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 132K, 17% free 14459K/17288K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 16.245MB for 96598-byte allocation
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 179K, 17% free 14494K/17384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 16.325MB for 144892-byte allocation
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 253K, 18% free 14542K/17528K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 16.440MB for 217334-byte allocation
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 369K, 18% free 14616K/17744K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 16.617MB for 325996-byte allocation
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 568K, 19% free 14738K/18064K, paused 26ms, total 26ms
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 866K, 18% free 14915K/18064K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 17.297MB for 733480-byte allocation
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 1287K, 20% free 15171K/18784K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 17.897MB for 1100216-byte allocation
,D/dalvikvm( 4455): GC_CONCURRENT freed 1758K, 22% free 15554K/19860K, paused 1ms+4ms, total 32ms
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 264K, 22% free 15524K/19860K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 18.767MB for 1650320-byte allocation
,D/dalvikvm( 4455): GC_CONCURRENT freed 1739K, 26% free 16074K/21472K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 4455): GC_FOR_ALLOC freed 1305K, 25% free 16137K/21472K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 20.152MB for 2475476-byte allocation
,D/dalvikvm( 4455): GC_CONCURRENT freed 211K, 23% free 18433K/23892K, paused 4ms+3ms, total 34ms
,D/dalvikvm( 4455): GC_CONCURRENT freed 4396K, 29% free 17143K/23892K, paused 1ms+8ms, total 45ms
,D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 22.315MB for 3713210-byte allocation
,D/dalvikvm( 4455): GC_CONCURRENT freed 449K, 26% free 20459K/27520K, paused 5ms+5ms, total 52ms
,W/jxcore-log( 4455): Initializing JXcore engine
,W/jxcore-log( 4455): JXcore engine is ready
,D/dalvikvm( 4455): GC_CONCURRENT freed 3418K, 25% free 20844K/27520K, paused 1ms+4ms, total 39ms
,D/dalvikvm( 4455): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 4455): Starting JXcore engine
,W/jxcore-log( 4455): Platform android
W/jxcore-log( 4455): 
,W/jxcore-log( 4455): Process ARCH arm
W/jxcore-log( 4455): 
,I/jxcore-log( 4455): JXcore Cordova bridge is ready!
I/jxcore-log( 4455): 
,W/jxcore-log( 4455): JXcore engine is started
,I/chromium( 4455): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4455): Toggling radios to true
I/jxcore-log( 4455): 
,D/BluetoothAdapter( 4455): enable(): BT is already enabled..!
D/WifiService( 1017): New client listening to asynchronous messages
D/WifiService( 1017): setWifiEnabled: true pid=4455, uid=10511
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1017): handleMessage: E msg.what=131145
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
I/jxcore-log( 4455): Radios toggled
I/jxcore-log( 4455): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4455): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4455): 
I/jxcore-log( 4455): Perf Test app loaded loaded
I/jxcore-log( 4455): 
,I/jxcore-log( 4455): check test folder
I/jxcore-log( 4455): 
,I/jxcore-log( 4455): found test : ./testFindPeers.js
I/jxcore-log( 4455): 
,I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
D/TCMD    (  427): NL - Read 1000 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  427): NL - Read 1000 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
D/TCMD    (  427): NL - Read 68 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
D/TCMD    (  427): NL - Read 68 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1017): InitialState.processMessage what=4
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1017): WiFi NOT Tethered!
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1017): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/jxcore-log( 4455): found test : ./testSendData.js
I/jxcore-log( 4455): 
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  427): NL - Read 60 bytes from update socket.
D/TCMD    (  427): NL - ignore NL message, type = 21
,D/TCMD    (  427): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1017): connected time updated 335471
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1017): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1017): DisconnectingState
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
,E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1017): handleMessage: X
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131146
D/WifiStateMachine( 1017): processMsg: DisconnectingState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/MDMCTBK (  271): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/ConnectivityService( 1017): resetConnections(wlan0, 3)
D/WifiStateMachine( 1017): handleMessage: X
D/NetUtils( 1017): android_net_utils_resetConnections in env=0x61197638 clazz=0x62100001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1017): handleMessage: E msg.what=147460
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection lost
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1365): Read error: ssl=0x633734d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1365): SSL shutdown failed: ssl=0x633734d0: I/O error during system call, Broken pipe
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
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
D/WifiStateMachine( 1017): handleMessage: X
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1235): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1017): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1235): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1235): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1235): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1235): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1235): onReceive() - done, currentInetCondition=0
,I/Choreographer( 4455): Skipped 118 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4455): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/TCMD    (  427): NL - Read 56 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiP2pService( 1017): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43f1a238 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@43f1a238 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@43f1a238 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: X
,D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1296): Active network info is not available
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1017): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4534 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1296): Active network info is not available
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1560): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1560): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/OtaApp  ( 1560): [debug] > CusSM.onRadioDown
,D/dalvikvm( 4534): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4203d098, skipping init
I/openssl ( 4534): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4534): Crypto mode 0 already enabled
I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4566 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4282:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4566): mnc/mcc: 
,V/MmsConfig( 4566): tag: bool value: enabledMMS - true
V/MmsConfig( 4566): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4566): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4566): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4566): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4566): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4566): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4566): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4566): tag: int value: recipientLimit - 20
V/MmsConfig( 4566): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4566): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4566): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4566): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4566): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4566): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4566): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4566): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4566): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4586 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 4257:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4586): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4586): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4586): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4586): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4599 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3967:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4612 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4336:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4612): Binding Chromium to main looper Looper (main, tid 1) {420392b8}
,I/LibraryLoader( 4612): Expected native library version number "",actual native library version number ""
,I/chromium( 4612): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4612): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4612): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4612): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4612): Local Patches: NONE
I/Adreno-EGL( 4612): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4612): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4612): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  259): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  259): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4612): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4612): Starting up...
,I/ImageResourceManager( 4003): ImageResourceManager: uninitalized
,I/iu.Environment( 4003): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 4003): SYNC; picasa accounts
,I/ActivityManager( 1017): Killing 3987:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1404): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4003): num queued entries: 0
,I/iu.UploadsManager( 4003): num updated entries: 0
D/DEBUG   ( 1560): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.UploadsManager( 1404): num queued entries: 0
,I/iu.UploadsManager( 1404): num updated entries: 0
,I/iu.SyncManager( 4003): NEXT; no task
I/iu.SyncManager( 1404): NEXT; no task
,W/ContextImpl( 1560): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1560): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1560): onServiceConnected()
,D/GetNotificationsWS( 1560): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1560): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1560): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4586): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4586): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4003): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/dalvikvm( 4455): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4455): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4455): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4455): Shutting down VM
,W/dalvikvm( 4455): threadid=1: thread exiting with uncaught exception (group=0x4176ad40)
E/AndroidRuntime( 4455): FATAL EXCEPTION: main
E/AndroidRuntime( 4455): Process: com.test.thalitest, PID: 4455
E/AndroidRuntime( 4455): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4455): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4455): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4455): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4455): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4455): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4455): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4455): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4455): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4455): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4455): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4455): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4455): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4455): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4455): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4455): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4455): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4455): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4455): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1017):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1017): Killing 4361:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4455): Sending signal. PID: 4455 SIG: 9
,I/ActivityManager( 1017): Process com.test.thalitest (pid 4455) has died.
,I/WindowState( 1017): WIN DEATH: Window{42107dd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1017): Client connection lost with reason: 4
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 4455 uid 10511
W/Binder  ( 1198): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1198): java.lang.NullPointerException
W/Binder  ( 1198): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1198): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1198): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1198): 	at dalvik.system.NativeStart.run(Native Method)
,I/GAV2    ( 4612): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1017): sending alarm Alarm{4336fd00 type 3 android}
,I/wpa_supplicant( 1169): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  271): Event received = Trying to associate with
D/TCMD    (  427): NL - Read 56 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request,
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState,
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState,
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1169): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  427): NL - Read 312 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request
D/TCMD    (  427): NL - Read 88 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  427): NL - Read 68 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request
D/TCMD    (  427): NL - Read 1000 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  271): Event received = Associated with c0:ff:d4
D/TCMD    (  427): NL - Read 80 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
D/TCMD    (  427): NL - Read 80 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
D/TCMD    (  427): NL - Read 68 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  271): Event received = WPA: Key negotiation com
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  271):  STA Connected !!
D/TCMD    (  427): NL - Read 1000 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
,D/TCMD    (  427): Listening for incoming client connection request
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
I/MDMCTBK (  271): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193305264
I/MDMCTBK (  271): return from set_get_from_wpa_supplicant
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1,
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/MDMCTBK (  271): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  271): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  271): , reply_len: 3, ret: 0
E/MDMCTBK (  271): MdmCutbackHndler, resp=OK
E/MDMCTBK (  271): 
,D/MDMCTBK (  271): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection established
,D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1017): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1017): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1017): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-44ms what=147462 obj=android.net.wifi.StateChangeResult@43f76c48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-31ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@433e2d70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=196612
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428354d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428354d0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/TCMD    (  427): NL - Read 56 bytes from update socket.
D/TCMD    (  427): NL - message type is RTM_NEWLINK
D/TCMD    (  427): Listening for incoming client connection request
,D/WifiStateMachine( 1017): handleMessage: X
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
,D/TCMD    (  427): NL - Read 60 bytes from update socket.
D/TCMD    (  427): NL - ignore NL message, type = 20
,D/TCMD    (  427): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-5ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
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
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=151572
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=135190
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1017): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1017): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState enter
,D/WifiStateMachine( 1017): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1017): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1017): WiFi NOT Tethered!
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@42192fe8
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1235): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1235): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1235): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1017): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,V/ConnectivityService( 1017): WiFi NOT Tethered!
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@42192fe8
,I/CheckinService( 1404): Checkin interval check for package: unspecified last checkin: 1451954357092 min interval config: 0 actual interval: 287836
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1235): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1235): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1235): onReceive() - done, currentInetCondition=0
,D/dalvikvm( 1017): GC_EXPLICIT freed 1777K, 65% free 18196K/51204K, paused 5ms+10ms, total 105ms
I/CheckinService( 1404): Checking schedule, now: 1451954645043 next: 1451954387069
,I/CheckinService( 1404): active receiver: enabled
,I/CheckinService( 1404): Preparing to send checkin request
,I/EventLogService( 1404): Accumulating logs since 1451954353836
,I/CheckinRequestBuilder( 1404): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1404): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1017): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4736 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4736): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4736): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4736): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4736): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4736): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4736): install
,I/MultiDex( 4736): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4736): loading existing secondary dex files
,I/MultiDex( 4736): load found 3 secondary dex files
,I/MultiDex( 4736): install done
,D/dalvikvm( 1365): GC_EXPLICIT freed 1140K, 40% free 10373K/17224K, paused 2ms+5ms, total 33ms
,D/dalvikvm( 4736): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4736): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4736): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4736): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4736): VFY: unable to resolve instance field 36
,D/dalvikvm( 4736): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4736): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4736): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4736): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4736): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4736): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4736): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4203fb50
D/dalvikvm( 4736): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4203fb50
,D/dalvikvm( 4736): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4203fb50, skipping init
D/dalvikvm( 4736): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4203fb50
,D/dalvikvm( 4736): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4203fb50
,V/JNIHelp ( 4736): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4736): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4203fb50
,D/dalvikvm( 4736): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4203fb50
D/dalvikvm( 4736): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4203fb50
,D/dalvikvm( 4736): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4203fb50
,I/ProviderInstaller( 4736): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 1365): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1365): Proximity feature is not enabled.
,D/WearableService( 1223): callingUid 10022, callindPid: 1223
,D/LocationInitializer( 1404): Restart initialization of location
,E/MDM     ( 1223): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
,I/dalvikvm( 4736): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4736): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4736): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4736): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4736): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4736): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4736): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4736): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4736): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4736): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4736): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4736): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52e6000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52e6000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=248673407
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4736): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4736): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42251e60
D/dalvikvm( 4736): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42251e60
,D/dalvikvm( 4736): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42251e60, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1017): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4736): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4767): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4736): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4736): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4736): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4736): Local Patches: NONE
I/Adreno-EGL( 4736): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4736): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4736): Local Patches: NONE
I/Adreno-EGL( 4736): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4736): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4736): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4736): Local Patches: NONE
I/Adreno-EGL( 4736): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4736): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4736): Local Patches: NONE
I/Adreno-EGL( 4736): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1399995700
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1404): Classify the device as Phone.
,D/dalvikvm( 1404): GC_CONCURRENT freed 1914K, 30% free 12131K/17224K, paused 3ms+6ms, total 43ms
,V/NativeCrypto( 1404): SSL shutdown failed: ssl=0x6c06cfd8: I/O error during system call, Connection timed out
,I/CheckinTask( 1404): Sending checkin request (11683 bytes)
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
,D/PollingManager( 1560): now: 383321 ,futureTime: 77306073
,D/PollingManager( 1560): Polling alarm set to expire at: 77306073 Current Time: 383321
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/PollingManager( 1560): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1560): [debug] > CusSM.onRadioUp
,D/PollingManager( 1560): now: 383379 ,futureTime: 77306073
D/PollingManager( 1560): Polling alarm set to expire at: 77306073 Current Time: 383379
D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
E/ActivityThread( 1560): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1560): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/openssl ( 4534): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4534): Crypto mode 0 already enabled
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1560): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4586): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4586): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
D/OtaApp  ( 1560): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 4003): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4003): num queued entries: 0
I/iu.UploadsManager( 4003): num updated entries: 0
I/iu.SyncManager( 4003): NEXT; no task
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1560): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1404): Checkin interval check for package: unspecified last checkin: 1451954357092 min interval config: 0 actual interval: 290964
D/TelephonyProvider( 1266): Column apn id key is 'apn_id'
I/CheckinRequestBuilder( 1404): Checkin reason type: 8 attempt count: 1
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1560): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
E/ActivityThread( 1404): Failed to find provider info for com.google.android.wearable.settings
D/dalvikvm( 4003): GC_CONCURRENT freed 631K, 5% free 16464K/17224K, paused 4ms+2ms, total 34ms
D/dalvikvm( 4003): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/OtaApp  ( 1560): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/dalvikvm-heap( 4003): Grow heap (frag case) to 19.847MB for 1821008-byte allocation
I/iu.Environment( 1404): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1404): num queued entries: 0
I/iu.UploadsManager( 1404): num updated entries: 0
D/DEBUG   ( 1560): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/iu.SyncManager( 1404): NEXT; no task
W/ContextImpl( 1560): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1560): bindWebServices(): registering our AIDL callback...
I/SundryService( 1560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1560): onServiceConnected()
D/GetNotificationsWS( 1560): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1560): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1560): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4534): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4534): Crypto mode 0 already enabled
D/MobileConnectivityChangeReceiver( 4586): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4586): onReceive CONNECTIVITY_CHANGE networkType=1
D/dalvikvm( 4003): GC_FOR_ALLOC freed 48K, 5% free 18197K/19004K, paused 12ms, total 12ms
I/iu.Environment( 4003): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/CheckinService( 1404): Checkin interval check for package: unspecified last checkin: 1451954357092 min interval config: 0 actual interval: 291050
,D/DEBUG   ( 1560): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1560): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1560): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1560): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1560): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1560): onServiceConnected()
D/GetNotificationsWS( 1560): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1560): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1560): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1560): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1560
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1560): unbindWebServices(): un-registering our AIDL callback...
,I/CheckinRequestBuilder( 1404): Classify the device as Phone.
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinTask( 1404): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1404): Checking schedule, now: 1451954648207 next: 1452547718204
,I/CheckinService( 1404): active receiver: disabled
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1560): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1560): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1560
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1404): Checking schedule, now: 1451954648238 next: 1452547718204
,I/CheckinService( 1404): active receiver: disabled
,D/CheckinService( 1404): Recording last checkin time for package unspecified as 1451954648245
,I/OtaApp  ( 1560): [info] > Updatetime from metadata: 10
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1560): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1560): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1560): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1560): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1017): Activity reported stop, but no longer stopping: ActivityRecord{4207bbd8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/GCM     ( 1404): Message from null null
,E/GCM     ( 1404): Dropping message from null
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1235): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1235): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1235): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1235): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1017): processMsg: ConnectedState
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1017): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1017):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1017): handleMessage: X
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4816 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/Launcher( 1307): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/Launcher( 1307): Deferring update until onResume
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
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/Babel   ( 4816): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4816): MmsConfig.loadMmsSettings
,I/Babel   ( 4816): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4816): MmsConfig.loadFromDatabase
,E/Babel   ( 4816): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4816): MmsConfig.loadFromResources
,E/Babel   ( 4816): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4816): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 4816): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1017): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4852 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm( 1017): GC_EXPLICIT freed 1408K, 65% free 18175K/51204K, paused 3ms+10ms, total 91ms
I/ActivityManager( 1017): Killing 3880:com.android.vending/u0a38 (adj 15): empty #9
I/ActivityManager( 1017): Killing 4534:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1017): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4871 uid=10033 gids={50033, 3003, 1028, 1015}
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4852): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2304): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4889 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4566:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4889): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4889): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4889): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2304): UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
,I/dalvikvm( 4889): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4889): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4889): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4889): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4889): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4889): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4889): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4889): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4889): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4889): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4889): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4889): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4889): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4889): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4889): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4923 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
,I/dalvikvm( 4889): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4889): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/Finsky  ( 4889): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4889): [1] Libraries$2.run: Finished loading 1 libraries.
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
I/dalvikvm( 4889): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4889): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x0017
,D/Ads     ( 4889): Skipping gmscore version check
I/ActivityManager( 1017): Killing 4586:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1404): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1404): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1404): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4923): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42046068, skipping init
I/openssl ( 4923): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4923): Crypto mode 0 already enabled
,D/Finsky  ( 4889): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4889): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1017): Killing 4599:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1404): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1404): GC_CONCURRENT freed 1950K, 29% free 12229K/17224K, paused 5ms+5ms, total 47ms
,D/dalvikvm( 1404): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/Icing   ( 1404): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451954657
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1017): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1017): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1017): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1017): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1017): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1017): sending alarm Alarm{42d24ae0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42b3f540 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1017): cleanup(): cleared. Last call was 45080 ms ago
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4965 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 4612:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1017): sending alarm Alarm{42922ed8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42460a00 type 3 android}
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1
,V/AlarmManager( 1017): sending alarm Alarm{42084510 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42accb38 type 2 android}
,V/AlarmManager( 1017): sending alarm Alarm{4221a520 type 2 android}
,V/AlarmManager( 1017): sending alarm Alarm{4269a0a8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{421e76e0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{42877c08 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{428e62b8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42ac8ed0 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1017): sending alarm Alarm{42ac4ca8 type 0 com.google.android.gms}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/EventLogService( 1404): Aggregate from 1451954645058 (log), 1451953322663 (data)
,V/AlarmManager( 1017): sending alarm Alarm{43e60800 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42adf4e8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42872960 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e85640 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{428e0fa0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e28608 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e58d98 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42accf68 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1235): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1235): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1235): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1017): sending alarm Alarm{428f2bb0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{428f2c88 type 1 com.android.deskclock}
,V/AlarmManager( 1017): sending alarm Alarm{42b16178 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e7bc38 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{421a03b8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{42a0cb40 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{428ffaa0 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
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
,V/AlarmManager( 1017): sending alarm Alarm{435623e8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43615fa0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4472ba58 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{436ed810 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{43492b08 type 3 android}
,I/ProcessStatsService( 1017): Prepared write state in 12ms
,I/ProcessStatsService( 1017): Prepared write state in 26ms
,I/ProcessStatsService( 1017): Prepared write state in 15ms
,I/ProcessStatsService( 1017): Pruning old procstats: /data/system/procstats/state-2016-01-04-03-42-00.bin
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
,V/AlarmManager( 1017): sending alarm Alarm{42128ee0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4290c5b8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{429bff68 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4347d868 type 3 android}
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
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5029): 
D/AndroidRuntime( 5029): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5029): CheckJNI is OFF
D/dalvikvm( 5029): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5029): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5029): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5029): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5029): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5029): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5029): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5029): failed to load memtrack module: -2
D/AndroidRuntime( 5029): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10511 user=-1: uninstall pkg
W/PackageSettings( 1017): Skipping PackageSetting{423141f8 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10511 user=0: pkg removed
D/dalvikvm( 2272): GC_EXPLICIT freed 5587K, 44% free 9660K/17224K, paused 2ms+6ms, total 45ms
D/dalvikvm( 1017): GC_EXPLICIT freed 1857K, 65% free 18181K/51204K, paused 5ms+11ms, total 111ms
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
D/dalvikvm( 1307): GC_EXPLICIT freed 3440K, 33% free 11598K/17224K, paused 2ms+6ms, total 123ms
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/Launcher( 1307): Deferring update until onResume
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
D/VoicemailCleanupService( 4852): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1404): GC_EXPLICIT freed 453K, 31% free 11978K/17224K, paused 93ms+13ms, total 182ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
D/dalvikvm( 2304): GC_EXPLICIT freed 4954K, 42% free 10127K/17224K, paused 40ms+5ms, total 131ms
I/Launcher( 1307): Deferring update until onResume
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10511 #1
D/dalvikvm( 1017): GC_EXPLICIT freed 458K, 65% free 18095K/51204K, paused 6ms+12ms, total 113ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451956431
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/InternalIcingCorporaPro( 2304): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1017): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5065 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451956431
D/AndroidRuntime( 5029): Shutting down VM
D/dalvikvm( 5029): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
I/InternalIcingCorporaPro( 2304): UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
W/ActiveOrDefaultContextProvider( 5065): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 5065): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5099 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 5099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4889): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4889): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4889): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1404): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1404): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1404): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1404): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1404): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1404): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ChimeraCfgMgr( 1404): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1404): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 1404): disk I/O error (code 3850)
E/DriveAsyncService( 1404): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1404): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1404): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1404): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1404): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1404): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1404): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1404): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1404): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1404): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1404): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1404): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1404): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1404): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1404): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1404): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1404): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1404): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1404): threadid=50: thread exiting with uncaught exception (group=0x4176ad40)
E/ClearPendingStateOp( 1404): Runtime exception while performing operation
E/ClearPendingStateOp( 1404): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1404): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1404): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1404): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1404): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1404): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1404): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1404): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 1404): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1404): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1404): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1404): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1404): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1404): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1404): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1404): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1404): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1404): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1404): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1404): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1404): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1404): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1404): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1404): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1404): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1404): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1404): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1404): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1404): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1404): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1404): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1404): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1404): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1404): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1404): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1404): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1404): 	at java.lang.Thread.run(Thread.java:841)
E/PhenotypeInitializer( 1404): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1404): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1404): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1404): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1404): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1404): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1404): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1404): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1404): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1404): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1404): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/Icing   ( 1404): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1404): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1404): threadid=54: thread exiting with uncaught exception (group=0x4176ad40)
E/SQLiteLog( 1365): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1365): Shutting down VM
W/dalvikvm( 1365): threadid=1: thread exiting with uncaught exception (group=0x4176ad40)
E/SQLiteLog( 1404): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
I/Process ( 1404): Sending signal. PID: 1404 SIG: 9
E/AndroidRuntime( 1365): FATAL EXCEPTION: main
E/AndroidRuntime( 1365): Process: com.google.process.gapps, PID: 1365
E/AndroidRuntime( 1365): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1365): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1365): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1365): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1365): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1365): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1365): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1365): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1365): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1365): 	... 10 more
I/Process ( 1365): Sending signal. PID: 1365 SIG: 9
E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5099): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5099): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5099): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5099): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5099): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5099): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5099): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5099): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5099): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5099): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5099): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
