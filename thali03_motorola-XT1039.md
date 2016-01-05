#### Test 5507315224df3aa_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4483): 
D/AndroidRuntime( 4483): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4483): CheckJNI is OFF
D/dalvikvm( 4483): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4483): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4483): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4483): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4483): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4483): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4483): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4483): failed to load memtrack module: -2
D/AndroidRuntime( 4483): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1002): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4483
W/WindowManager( 1002): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1002): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4499 uid=10514 gids={50514, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4483): Shutting down VM
D/dalvikvm( 4483): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4499): Binding Chromium to main looper Looper (main, tid 1) {41f0bca0}
I/LibraryLoader( 4499): Expected native library version number "",actual native library version number ""
I/chromium( 4499): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4499): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1002): Message: 20
D/BluetoothManagerService( 1002): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427f6700:true
I/Adreno-EGL( 4499): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4499): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4499): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4499): Local Branch: 
I/Adreno-EGL( 4499): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4499): Local Patches: NONE
I/Adreno-EGL( 4499): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4499): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4499): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4499): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4499): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4499): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4499): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4499): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4499): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4499): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4499): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4499): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4499): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4499): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4499): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4499): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4499): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4499): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4499): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4499): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4499): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4499): Enabling debug mode 0
,W/AwContents( 4499): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4499): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1002): Displayed com.test.thalitest/.MainActivity,cp,ca,468
I/ActivityManager( 1002): Displayed com.test.thalitest/.MainActivity: +430ms (total +468ms)
,D/JsMessageQueue( 4499): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4499): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f10468
,D/dalvikvm( 4499): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f10468
D/jxcore_app_log( 4499): JniHelper::setJavaVM(0x41560fa8), pthread_self() = 1613948088
,D/JX-Cordova( 4499): jxcore cordova android initializing
,D/dalvikvm( 4499): GC_CONCURRENT freed 2734K, 17% free 14454K/17224K, paused 3ms+2ms, total 47ms
,D/dalvikvm( 4499): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 162K, 17% free 14445K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 131K, 17% free 14460K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 16.246MB for 96598-byte allocation
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 179K, 17% free 14495K/17320K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 16.326MB for 144892-byte allocation
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 253K, 17% free 14542K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 16.441MB for 217334-byte allocation
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 369K, 18% free 14617K/17680K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 16.618MB for 325996-byte allocation
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 568K, 19% free 14739K/18000K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 16.892MB for 488990-byte allocation
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 866K, 20% free 14915K/18480K, paused 26ms, total 27ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 1284K, 18% free 15172K/18480K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 17.898MB for 1100216-byte allocation
,D/dalvikvm( 4499): GC_CONCURRENT freed 1762K, 21% free 15558K/19556K, paused 1ms+3ms, total 34ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 296K, 21% free 15492K/19556K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 18.735MB for 1650320-byte allocation
,D/dalvikvm( 4499): GC_CONCURRENT freed 1705K, 25% free 16075K/21168K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 1302K, 24% free 16138K/21168K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 20.153MB for 2475476-byte allocation
,D/dalvikvm( 4499): GC_CONCURRENT freed 1752K, 28% free 16984K/23588K, paused 5ms+3ms, total 45ms
,D/dalvikvm( 4499): GC_CONCURRENT freed 2544K, 28% free 17101K/23588K, paused 2ms+6ms, total 42ms
,D/dalvikvm( 4499): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 497K, 29% free 16962K/23588K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4499): Grow heap (frag case) to 22.138MB for 3713210-byte allocation
,D/dalvikvm( 4499): GC_CONCURRENT freed 2626K, 34% free 18063K/27216K, paused 4ms+4ms, total 34ms
,D/dalvikvm( 4499): GC_FOR_ALLOC freed 858K, 34% free 18104K/27216K, paused 27ms, total 27ms
,W/jxcore-log( 4499): Initializing JXcore engine
,W/jxcore-log( 4499): JXcore engine is ready
,D/dalvikvm( 4499): GC_CONCURRENT freed 383K, 24% free 20740K/27216K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 4499): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4499): Starting JXcore engine
,W/jxcore-log( 4499): Platform android
W/jxcore-log( 4499): 
,W/jxcore-log( 4499): Process ARCH arm
W/jxcore-log( 4499): 
,I/jxcore-log( 4499): JXcore Cordova bridge is ready!
I/jxcore-log( 4499): 
,W/jxcore-log( 4499): JXcore engine is started
,I/chromium( 4499): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4499): Toggling radios to true
I/jxcore-log( 4499): 
,D/BluetoothAdapter( 4499): enable(): BT is already enabled..!
D/WifiService( 1002): New client listening to asynchronous messages
D/WifiService( 1002): setWifiEnabled: true pid=4499, uid=10514
,E/WifiService( 1002): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1002): handleMessage: E msg.what=131145
D/WifiStateMachine( 1002): processMsg: ConnectedState
D/WifiStateMachine( 1002): processMsg: L2ConnectedState
I/jxcore-log( 4499): Radios toggled
I/jxcore-log( 4499): 
D/BluetoothManagerService( 1002): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1002): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4499): Received device characteristics:
I/jxcore-log( 4499): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4499): Bluetooth name: XT1039
I/jxcore-log( 4499): Device name: motorola-XT1039
I/jxcore-log( 4499): 
I/jxcore-log( 4499): Perf Test app loaded loaded
I/jxcore-log( 4499): 
,I/jxcore-log( 4499): check test folder
I/jxcore-log( 4499): 
,I/jxcore-log( 4499): found test : ./testFindPeers.js
I/jxcore-log( 4499): 
,D/TCMD    (  432): NL - Read 1000 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 68 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 68 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
,D/TCMD    (  432): Listening for incoming client connection request
,I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1002): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1002): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1002): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1002): invokeExitMethods: ConnectedState
,D/Tethering( 1002): InitialState.processMessage what=4
,V/ConnectivityService( 1002): WiFi NOT Tethered!
D/Tethering( 1002): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1002): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1002): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1002): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1002): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1002): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,I/jxcore-log( 4499): found test : ./testSendData.js
I/jxcore-log( 4499): 
D/TCMD    (  432): NL - Read 60 bytes from update socket.
D/TCMD    (  432): NL - ignore NL message, type = 21
,D/TCMD    (  432): Listening for incoming client connection request
,D/WifiStateMachine( 1002): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1002): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1002): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1002): connected time updated 334940
,D/ConnectivityService( 1002): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1002): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1002): Attempting to switch to mobile
D/ConnectivityService( 1002): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1002): Attempting to switch to ETHERNET
,D/ConnectivityService( 1002): resetConnections(wlan0, 3)
D/NetUtils( 1002): android_net_utils_resetConnections in env=0x61665e20 clazz=0x61000001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1002): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1002): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1002): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1002): DisconnectingState
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=131146
D/Checkin ( 1002): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1002): processMsg: DisconnectingState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=147460
D/WifiStateMachine( 1002): processMsg: DisconnectingState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): Network connection lost
D/WifiStateMachine( 1002): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1002): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1370): Read error: ssl=0x62fe45c8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x62fe45c8: I/O error during system call, Broken pipe
D/WifiP2pService( 1002): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1002): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1002): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1002): transitionTo: destState=DisconnectedState
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1002): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1002): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1002): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1002): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1002): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1002): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1002): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/WifiStateMachine( 1002): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=131101
D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
D/WifiStateMachine( 1002): processMsg: DefaultState
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
D/WifiStateMachine( 1002): processMsg: DefaultState
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=131216
D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
,D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
D/WifiStateMachine( 1002): processMsg: DefaultState
,D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/WifiStateMachine( 1002): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1002): processMsg: ConnectModeState
,D/WifiStateMachine( 1002): handleMessage: X
,D/Nat464Xlat( 1002): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1002): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1291): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1002): Attempting to switch to mobile
D/ConnectivityService( 1002): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1002): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1291): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1291): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat( 1002): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1002): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1291): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1291): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1291): onReceive() - done, currentInetCondition=0
,I/chromium( 4499): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TCMD    (  432): NL - Read 56 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1169): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/WifiStateMachine( 1002): handleMessage: E msg.what=147461
D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
,D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1169): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
D/WifiStateMachine( 1002): processMsg: DisconnectedState
,V/AlarmManager( 1002): sending alarm Alarm{43c769b0 type 3 android}
D/WifiStateMachine( 1002): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): handleMessage: X
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  432): NL - Read 312 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 192 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 68 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 1000 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  432): NL - Read 80 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 80 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
D/TCMD    (  432): NL - Read 68 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
,D/TCMD    (  432): Listening for incoming client connection request
,D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
D/WifiStateMachine( 1002): processMsg: DisconnectedState
,D/WifiStateMachine( 1002): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1002): processMsg: ConnectModeState
,D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1002): processMsg: DisconnectedState
,D/WifiStateMachine( 1002): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
,D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/TCMD    (  432): NL - Read 1000 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
,D/TCMD    (  432): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202545840
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1002): handleMessage: X
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1002): processMsg: DisconnectedState
,D/WifiStateMachine( 1002): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/Tethering( 1002): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/WifiStateMachine( 1002): handleMessage: X
,D/Tethering( 1002): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1002): handleMessage: E msg.what=147459
D/WifiStateMachine( 1002): processMsg: DisconnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): Network connection established
,D/WifiStateMachine( 1002): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1002): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1002): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1002): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1002): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1002): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1002): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1002): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1002): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1002): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1002): processMsg: ObtainingIpState
,D/WifiStateMachine( 1002): ObtainingIpState{ when=-52ms what=147462 obj=android.net.wifi.StateChangeResult@43da63f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1002): processMsg: L2ConnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
,D/WifiStateMachine( 1002): handleMessage: X
,D/WifiStateMachine( 1002): handleMessage: E msg.what=131101
D/WifiStateMachine( 1002): processMsg: ObtainingIpState
,D/WifiStateMachine( 1002): ObtainingIpState{ when=-34ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@427d50e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1002): processMsg: L2ConnectedState
,D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1002): processMsg: DefaultState
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1002): processMsg: ObtainingIpState
D/WifiStateMachine( 1002): ObtainingIpState{ when=-9ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1002): processMsg: L2ConnectedState
,D/WifiStateMachine( 1002): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1002): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1002): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420c7830 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1002): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420c7830 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1002): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1002): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1002): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1002): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1002): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4387b8b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1002): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4387b8b0 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  432): NL - Read 56 bytes from update socket.
D/TCMD    (  432): NL - message type is RTM_NEWLINK
D/TCMD    (  432): Listening for incoming client connection request
,D/WifiP2pService( 1002): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4387b8b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1002): handleMessage: E msg.what=147461
D/WifiStateMachine( 1002): processMsg: ObtainingIpState
D/WifiStateMachine( 1002): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1002): processMsg: L2ConnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
D/WifiStateMachine( 1002): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/TCMD    (  432): NL - Read 60 bytes from update socket.
D/TCMD    (  432): NL - ignore NL message, type = 20
,D/TCMD    (  432): Listening for incoming client connection request
,D/WifiStateMachine( 1002): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1002): handleMessage: E msg.what=131215
D/WifiStateMachine( 1002): processMsg: ObtainingIpState
,D/WifiStateMachine( 1002): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1002): processMsg: L2ConnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
,D/WifiStateMachine( 1002): processMsg: DriverStartedState
,D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1002): processMsg: DefaultState
,D/WifiStateMachine( 1002): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1002): handleMessage: X
,D/WifiStateMachine( 1002): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1002): processMsg: ObtainingIpState
,D/WifiStateMachine( 1002): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1002): processMsg: L2ConnectedState
,D/WifiStateMachine( 1002): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1002): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1002): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1002): DHCP successful
D/WifiStateMachine( 1002): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1002): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1002): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1002): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1002): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1002): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1002): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1002): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1002): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1002): VerifyingLinkState enter
D/WifiStateMachine( 1002): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1002): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1002): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1002): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1002): handleMessage: X
,D/WifiStateMachine( 1002): handleMessage: E msg.what=135190
,D/WifiStateMachine( 1002): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1002): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1002): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1002): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1002): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1002): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1002): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1002): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1002): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1002): CaptivePortalCheckState enter
,D/WifiStateMachine( 1002): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1002): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1002): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1002): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1002): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1002): handleMessage: X
,D/WifiStateMachine( 1002): handleMessage: E msg.what=131092
D/WifiStateMachine( 1002): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1002): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1002): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1002): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1002): WiFi NOT Tethered!
E/ConnectivityService( 1002): Unexpected mtu value: android.net.wifi.WifiStateTracker@41fea3e8
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1002): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1291): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1291): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1291): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1002): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1002): WiFi NOT Tethered!
,E/ConnectivityService( 1002): Unexpected mtu value: android.net.wifi.WifiStateTracker@41fea3e8
D/WifiStateMachine( 1002): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1002): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1002): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1002): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1002): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1002): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1002): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1002): handleMessage: X
D/WifiStateMachine( 1002): handleMessage: E msg.what=131092
D/WifiStateMachine( 1002): processMsg: ConnectedState
D/WifiStateMachine( 1002): processMsg: L2ConnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
D/WifiStateMachine( 1002): processMsg: DefaultState
D/WifiStateMachine( 1002): handleMessage: X
D/Checkin ( 1002): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1002): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1002): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1291): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1291): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1291): onReceive() - done, currentInetCondition=0
,D/Tethering( 1002): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1587): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1002): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1002): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager( 1002): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4630 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1002): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1002): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,E/ActivityThread( 1587): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1587): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1587): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1587): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1587): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/ActivityThread( 1587): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1587): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/dalvikvm( 4630): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f13f08, skipping init
I/openssl ( 4630): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4630): Crypto mode 0 already enabled
,I/ActivityManager( 1002): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4670 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1002): Killing 4365:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4670): mnc/mcc: 
,V/MmsConfig( 4670): tag: bool value: enabledMMS - true
V/MmsConfig( 4670): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4670): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4670): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4670): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4670): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4670): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4670): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4670): tag: int value: recipientLimit - 20
V/MmsConfig( 4670): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4670): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4670): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4670): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4670): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4670): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4670): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4670): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4670): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1002): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4689 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1002): Killing 4335:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4689): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4689): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4689): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4689): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1002): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4702 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1002): Killing 3853:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1402): Checkin interval check for package: unspecified last checkin: 1452008622324 min interval config: 0 actual interval: 320765
,I/CheckinService( 1402): Checking schedule, now: 1452008943099 next: 1452008652279
,I/CheckinService( 1402): active receiver: enabled
,I/CheckinService( 1402): Preparing to send checkin request
,I/EventLogService( 1402): Accumulating logs since 1452008617461
,I/CheckinRequestBuilder( 1402): Checkin reason type: 8 attempt count: 1
I/ActivityManager( 1002): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4717 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1002): Killing 4399:com.google.android.partnersetup/u0a25 (adj 15): empty #9
E/ActivityThread( 1402): Failed to find provider info for com.google.android.wearable.settings
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4717): Binding Chromium to main looper Looper (main, tid 1) {41f10e40}
,I/LibraryLoader( 4717): Expected native library version number "",actual native library version number ""
,I/chromium( 4717): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4717): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4717): BLUETOOTH permission is missing!
,D/dalvikvm( 1002): GC_EXPLICIT freed 1833K, 65% free 18223K/51268K, paused 3ms+10ms, total 94ms
,D/ConnectivityService( 1002): NetTransition Wakelock for ConnectedState released by timeout
,I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4717): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4717): Local Branch: 
I/Adreno-EGL( 4717): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4717): Local Patches: NONE
I/Adreno-EGL( 4717): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4717): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1002): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4748 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/GAV2    ( 4717): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4717): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4748): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4748): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4748): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4748): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4748): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4748): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4748): install
,I/MultiDex( 4748): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4748): loading existing secondary dex files
,I/MultiDex( 4748): load found 3 secondary dex files
,I/MultiDex( 4748): install done
,D/dalvikvm( 4748): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4748): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4748): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4748): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4748): VFY: unable to resolve instance field 36
,D/dalvikvm( 4748): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4748): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4748): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4748): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4748): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4748): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4748): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f16a18
,D/dalvikvm( 4748): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f16a18
,D/dalvikvm( 4748): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f16a18, skipping init
,D/dalvikvm( 4748): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f16a18
,D/dalvikvm( 4748): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f16a18
,V/JNIHelp ( 4748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4748): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f16a18
,D/dalvikvm( 4748): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f16a18
D/dalvikvm( 4748): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f16a18
,D/dalvikvm( 4748): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f16a18
,I/NSApplication( 4717): Starting up...
,I/ImageResourceManager( 3887): ImageResourceManager: uninitalized
,I/iu.Environment( 3887): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1002): Killing 3870:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1587): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1587): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1587): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1587): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1587): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1587): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1587): onServiceConnected()
,D/GetNotificationsWS( 1587): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1587): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4630): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4630): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4689): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4689): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 1587): GC_CONCURRENT freed 1906K, 38% free 10695K/17224K, paused 2ms+3ms, total 35ms
,I/iu.Environment( 3887): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ProviderInstaller( 4748): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 3887): GC_CONCURRENT freed 619K, 5% free 16443K/17224K, paused 3ms+4ms, total 26ms
,D/dalvikvm( 1402): GC_CONCURRENT freed 1819K, 29% free 12292K/17224K, paused 4ms+5ms, total 54ms
,D/WearableService( 1216): callingUid 10022, callindPid: 1216
,D/LocationInitializer( 1402): Restart initialization of location
,E/MDM     ( 1216): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4748): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4748): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4748): VFY: replacing opcode 0x6e at 0x00ce
,W/GCoreFlp( 1216): No location to return for getLastLocation()
,W/FusedLocationProvider( 1216): location=null
I/dalvikvm( 4748): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 4748): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4748): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4748): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4748): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4748): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4748): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4748): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 4748): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4748): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4748): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4748): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4748): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4748): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/jxcore-log( 4499): Connected to the server!
I/jxcore-log( 4499): 
,I/chromium( 4499): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51c5000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51c5000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=1323417833
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4748): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4748): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f41e0
D/dalvikvm( 4748): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f41e0
,D/dalvikvm( 4748): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f41e0, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=1487656475
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
I/dalvikvm( 4499): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4499): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4499): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4499): Shutting down VM
,W/dalvikvm( 4499): threadid=1: thread exiting with uncaught exception (group=0x4163fd40)
E/AndroidRuntime( 4499): FATAL EXCEPTION: main
E/AndroidRuntime( 4499): Process: com.test.thalitest, PID: 4499
E/AndroidRuntime( 4499): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4499): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4499): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4499): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4499): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4499): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4499): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4499): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4499): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4499): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4499): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4499): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4499): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4499): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4499): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4499): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4499): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4499): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4499): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1002):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1002): Killing 4285:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4499): Sending signal. PID: 4499 SIG: 9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1002): Process com.test.thalitest (pid 4499) has died.
,I/WindowState( 1002): WIN DEATH: Window{41fd76d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1002): Client connection lost with reason: 4
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/OtaApp  ( 1587): [info] > Updatetime from metadata: 10
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1587): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1587): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1002): Got RemoteException sending setActive(false) notification to pid 4499 uid 10514
W/Binder  ( 1199): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1199): java.lang.NullPointerException
W/Binder  ( 1199): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1199): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1199): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1199): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 4748): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4819): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4748): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4748): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 74ms
,I/Adreno-EGL( 4748): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4748): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4748): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4748): Local Branch: 
I/Adreno-EGL( 4748): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4748): Local Patches: NONE
I/Adreno-EGL( 4748): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4748): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4748): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4748): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4748): Local Branch: 
I/Adreno-EGL( 4748): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4748): Local Patches: NONE
I/Adreno-EGL( 4748): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiStateMachine( 1002): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1002): handleMessage: E msg.what=131215
D/WifiStateMachine( 1002): processMsg: ConnectedState
D/WifiStateMachine( 1002): processMsg: L2ConnectedState
D/WifiStateMachine( 1002): processMsg: ConnectModeState
D/WifiStateMachine( 1002): processMsg: DriverStartedState
D/WifiStateMachine( 1002): processMsg: SupplicantStartedState
D/WifiStateMachine( 1002): processMsg: DefaultState
D/WifiStateMachine( 1002): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1002): handleMessage: X
D/ConnectivityService( 1002): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1002):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1002): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1002): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1002): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 4748): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4748): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4748): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4748): Local Branch: 
I/Adreno-EGL( 4748): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4748): Local Patches: NONE
I/Adreno-EGL( 4748): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4748): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4748): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4748): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4748): Local Branch: 
I/Adreno-EGL( 4748): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4748): Local Patches: NONE
I/Adreno-EGL( 4748): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/Tethering( 1002): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1002): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/Tethering( 1002): MasterInitialState.processMessage what=3
W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/PollingManager( 1587): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker( 1002): DelayedCaptiveCheckState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1587): now: 365574 ,futureTime: 22990963
D/PollingManager( 1587): Polling alarm set to expire at: 22990963 Current Time: 365574
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
E/ActivityThread( 1587): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1587): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1587): now: 365584 ,futureTime: 22990963
D/PollingManager( 1587): Polling alarm set to expire at: 22990963 Current Time: 365585
E/ActivityThread( 1587): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1587): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1587): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1587): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1587): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4630): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4630): Crypto mode 0 already enabled
D/OtaApp  ( 1587): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1587): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1587): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4689): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4689): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1587): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,W/Settings( 4748): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 3887): GC_FOR_ALLOC freed 41K, 5% free 16405K/17224K, paused 16ms, total 16ms
,I/dalvikvm-heap( 3887): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
,I/iu.Environment( 3887): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1587): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1587): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1402): Checkin interval check for package: unspecified last checkin: 1452008622324 min interval config: 0 actual interval: 323130
,D/OtaApp  ( 1587): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1587): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1587): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/openssl ( 4630): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4630): Crypto mode 0 already enabled
D/OtaApp  ( 1587): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3887): GC_FOR_ALLOC freed 4K, 5% free 18183K/19004K, paused 28ms, total 30ms
,D/MobileConnectivityChangeReceiver( 4689): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4689): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3887): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinRequestBuilder( 1402): Classify the device as Phone.
,I/CheckinService( 1402): Checkin interval check for package: unspecified last checkin: 1452008622324 min interval config: 0 actual interval: 323177
,D/DEBUG   ( 1587): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1587): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1587): bindWebServices(): registering our AIDL callback...
I/SundryService( 1587): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1587): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1587): onServiceConnected()
,D/GetNotificationsWS( 1587): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1587): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1587): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1587): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1587): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1587): bindWebServices(): registering our AIDL callback...
I/SundryService( 1587): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1587): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1587): onServiceConnected()
,D/GetNotificationsWS( 1587): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1587): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1587): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1587): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1002): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1587
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1587): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 1370): GC_EXPLICIT freed 1665K, 39% free 10588K/17224K, paused 2ms+5ms, total 40ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1587): [info] > Updatetime from metadata: 10
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1587): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1587): [info] > Updatetime from metadata: 10
,V/NativeCrypto( 1402): SSL shutdown failed: ssl=0x6b85de58: I/O error during system call, Connection timed out
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1587): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1587): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1587): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1002): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1587
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1587): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1587): [info] > Updatetime from metadata: 10
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1587): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1587): [info] > Updatetime from metadata: 10
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1587): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1587): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1587): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1002): Activity reported stop, but no longer stopping: ActivityRecord{42888db0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinTask( 1402): Sending checkin request (11634 bytes)
,I/CheckinRequestBuilder( 1402): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1402): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1402): Classify the device as Phone.
,I/CheckinTask( 1402): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1402): Checking schedule, now: 1452008946318 next: 1452602016310
,I/CheckinService( 1402): active receiver: disabled
,I/CheckinService( 1402): Checking schedule, now: 1452008946340 next: 1452602016310
,I/CheckinService( 1402): active receiver: disabled
,D/CheckinService( 1402): Recording last checkin time for package unspecified as 1452008946346
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1216): GC_EXPLICIT freed 831K, 35% free 11250K/17224K, paused 3ms+6ms, total 38ms
,I/PhenotypeConfigurator( 1216): Scheduling Phenotype for one-off execution 10124 seconds from now (1452008946856)
,D/GetConfigurationSnapshotOperation( 1216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1216): Using platform SSLCertificateSocketFactory
,V/NativeCrypto( 1216): SSL shutdown failed: ssl=0x62c32b58: I/O error during system call, Connection timed out
,D/ConnectivityService( 1002): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1291): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1291): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1291): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1291): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1216): GC_CONCURRENT freed 1431K, 32% free 11850K/17224K, paused 4ms+9ms, total 54ms
,I/GAV2    ( 4717): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1002): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4882 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/Launcher( 1303): Deferring update until onResume
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "sms"
,I/InputReader( 1002): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "smsto"
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mms"
,I/Launcher( 1303): Deferring update until onResume
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mmsto"
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "sms"
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "smsto"
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mms"
,I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mmsto"
,I/Babel   ( 4882): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4882): MmsConfig.loadMmsSettings
I/Babel   ( 4882): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4882): MmsConfig.loadFromDatabase
,E/Babel   ( 4882): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4882): MmsConfig.loadFromResources
,E/Babel   ( 4882): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4882): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4882): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1216): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 1002): GC_EXPLICIT freed 1626K, 65% free 18251K/51268K, paused 4ms+11ms, total 105ms
,I/ActivityManager( 1002): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4918 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1002): Killing 3905:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1002): Killing 4630:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1002): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4940 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/InternalIcingCorporaPro( 2381): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1002): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4957 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1002): Killing 4670:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4918): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4957): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4957): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4957): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2381): UpdateCorporaTask done [took 201 ms] updated apps [took 201 ms] 
,I/dalvikvm( 4957): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4957): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4957): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4957): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4957): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4957): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4957): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4957): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4957): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4957): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4957): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4957): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4957): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4957): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4957): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1002): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4995 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4957): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4957): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4957): Skipping gmscore version check
,D/Finsky  ( 4957): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4957): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4957): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4957): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1002): Killing 4689:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1402): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1402): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1402): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4995): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f12550, skipping init
I/openssl ( 4995): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4995): Crypto mode 0 already enabled
,D/Finsky  ( 4957): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4957): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1002): Killing 4702:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1402): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1402): GC_CONCURRENT freed 2018K, 30% free 12228K/17224K, paused 5ms+5ms, total 45ms
,I/Icing   ( 1402): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452008955
,D/CaptivePortalTracker( 1002): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1002): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1002): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1002): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1002): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1002): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1002): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1002): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1002): sending alarm Alarm{42772cf0 type 2 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1002): sending alarm Alarm{42772dc8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1002): sending alarm Alarm{42718868 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{427e9c98 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7,
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1,
,V/AlarmManager( 1002): sending alarm Alarm{4223d430 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{427dcb38 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{4209b080 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42130f68 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{430920f8 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{4276a110 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42787d20 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{43288bb0 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42772ea0 type 2 android}
,D/ConnectivityService( 1002): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1002): sending alarm Alarm{4277b7e8 type 0 com.google.android.gms}
,V/AlarmManager( 1002): sending alarm Alarm{4277b838 type 1 com.android.deskclock}
,D/ConnectivityService( 1002): Done.
,D/ConnectivityService( 1002): Setting timer for 720seconds
,I/LaunchCheckinHandler( 1002): cleanup(): cleared. Last call was 647102 ms ago
,I/ActivityManager( 1002): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5046 uid=10015 gids={50015, 1028}
,I/EventLogService( 1402): Aggregate from 1452008943118 (log), 1452007280299 (data)
,I/ActivityManager( 1002): Killing 4717:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1002): sending alarm Alarm{428880c0 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{427eb238 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{4207f720 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{4230cbe0 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{428c8e68 type 2 com.google.android.gms}
,D/ConnectivityService( 1002): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1291): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1291): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1291): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1002): sending alarm Alarm{4290ea38 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{43c7daa0 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42868528 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{4278faf0 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42939c88 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{4276c230 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{43e63d60 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{427a1c20 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{420d6290 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1002): sending alarm Alarm{428b7150 type 3 android}
,I/ProcessStatsService( 1002): Prepared write state in 24ms
,I/ProcessStatsService( 1002): Prepared write state in 25ms
,I/ProcessStatsService( 1002): Prepared write state in 14ms
,I/ProcessStatsService( 1002): Pruning old procstats: /data/system/procstats/state-2016-01-04-23-36-58.bin
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1002): sending alarm Alarm{432cd408 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42940b18 type 2 android}
,D/ConnectivityService( 1002): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1002): sending alarm Alarm{42940bd8 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{42940c28 type 3 com.google.android.gms}
,V/AlarmManager( 1002): sending alarm Alarm{4317db48 type 1 com.android.deskclock}
,D/ConnectivityService( 1002): Done.
,D/ConnectivityService( 1002): Setting timer for 720seconds
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x61157758: I/O error during system call, Connection timed out
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x62d5e1e8: I/O error during system call, Connection timed out
,D/ChimeraCfgMgr( 1402): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1402): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 1402): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1402): Failed to execute periodic sync, missing client context - aborting
,V/AlarmManager( 1002): sending alarm Alarm{428e0700 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{427c74f8 type 3 android}
,V/AlarmManager( 1002): sending alarm Alarm{43dcd308 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1002): sending alarm Alarm{43e39e00 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5118): 
D/AndroidRuntime( 5118): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5118): CheckJNI is OFF
D/dalvikvm( 5118): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5118): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5118): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5118): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5118): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5118): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5118): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5118): failed to load memtrack module: -2
D/AndroidRuntime( 5118): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1002): Force stopping com.test.thalitest appid=10514 user=-1: uninstall pkg
W/PackageSettings( 1002): Skipping PackageSetting{421d1f38 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1002): Force stopping com.test.thalitest appid=10514 user=0: pkg removed
I/InputReader( 1002): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "sms"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "smsto"
D/dalvikvm( 2349): GC_EXPLICIT freed 5334K, 44% free 9649K/17224K, paused 2ms+14ms, total 76ms
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mms"
I/Launcher( 1303): Deferring update until onResume
D/dalvikvm( 2381): GC_EXPLICIT freed 4732K, 42% free 10124K/17224K, paused 2ms+4ms, total 160ms
D/dalvikvm( 1402): GC_EXPLICIT freed 665K, 30% free 12151K/17224K, paused 11ms+5ms, total 174ms
W/SQLiteConnectionPool( 1402): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1002): GC_EXPLICIT freed 2059K, 65% free 18218K/51268K, paused 4ms+14ms, total 147ms
D/dalvikvm( 1303): GC_EXPLICIT freed 3575K, 33% free 11647K/17224K, paused 2ms+5ms, total 44ms
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mmsto"
D/VoicemailCleanupService( 4918): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "sms"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452010744
I/Launcher( 1303): Deferring update until onResume
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "smsto"
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mms"
I/PackageManager( 1002): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1002):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1002):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1002):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2381): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1002): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5155 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452010744
D/BackupManagerService( 1002): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1002): removePackageParticipantsLocked: uid=10514 #1
I/InternalIcingCorporaPro( 2381): UpdateCorporaTask done [took 96 ms] updated apps [took 96 ms] 
D/dalvikvm( 1002): GC_EXPLICIT freed 652K, 65% free 18139K/51268K, paused 5ms+12ms, total 156ms
D/AndroidRuntime( 5118): Shutting down VM
D/dalvikvm( 5118): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 5155): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 5155): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1002): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5184 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 5184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4957): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4957): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4957): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1402): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1402): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1402): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1402): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1402): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1402): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1402): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1370): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1370): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/SQLiteLog( 1402): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1402): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1402): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1402): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1402): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1402): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1402): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1402): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1402): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1402): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1402): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1402): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/dalvikvm( 1402): Jit: resizing JitTable from 4096 to 8192
I/ActivityManager( 1002): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5207 uid=10058 gids={50058}
E/GMPM-SVC( 1402): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteOpenHelper( 1402): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1402): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1402): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1402): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1402): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1402): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1402): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1402): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1402): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1402): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1402): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
W/SQLiteOpenHelper( 1402): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1402): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1402): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1402): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1402): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1402): threadid=48: thread exiting with uncaught exception (group=0x4163fd40)
E/ClearPendingStateOp( 1402): Runtime exception while performing operation
E/ClearPendingStateOp( 1402): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1402): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1402): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1402): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1402): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1402): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1402): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1402): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1402): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
V/AlarmManager( 1002): sending alarm Alarm{423288d8 type 2 com.motorola.ccc.cce}
F/ClearPendingStateOp( 1402): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1402): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1402): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1402): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1402): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1402): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1402): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1402): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1402): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1402): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1402): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 1402): threadid=52: thread exiting with uncaught exception (group=0x4163fd40)
I/Process ( 1402): Sending signal. PID: 1402 SIG: 9
E/AndroidRuntime( 1402): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1402): Process: com.google.android.gms, PID: 1402
E/AndroidRuntime( 1402): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1402): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1402): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1402): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1402): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1402): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1402): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1402): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1402): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 5184): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5184): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5184): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5184): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5184): threadid=10: thread exiting with uncaught exception (group=0x4163fd40)
E/AndroidRuntime( 5184): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5184): Process: com.android.keychain, PID: 5184
E/AndroidRuntime( 5184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5184): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5184): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5184): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 5184): Sending signal. PID: 5184 SIG: 9
E/DropBoxManagerService( 1002): Can't write: system_app_crash
E/DropBoxManagerService( 1002): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1002): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1002): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1002): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1002): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1002): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1002): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1002): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1002): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1002): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1002): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1002): 	... 5 more
I/ActivityManager( 1002): Process com.google.android.gms (pid 1402) has died.
D/WifiService( 1002): Client connection lost with reason: 4
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 10999ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 20999ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30999ms
W/ActivityManager( 1002): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 30999ms
I/ActivityManager( 1002): Process com.android.keychain (pid 5184) has died.
W/ActivityManager( 1002): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 40997ms
D/Documents( 5207): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 5207): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5207): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5207): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5207): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5207): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 5207): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 5207): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 5207): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 5207): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 5207): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 5207): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 5207): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 5207): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5207): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5207): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 5207): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5207): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5207): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 5207): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 5207): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 5207): Shutting down VM
W/dalvikvm( 5207): threadid=1: thread exiting with uncaught exception (group=0x4163fd40)
D/Documents( 5207): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 5207): FATAL EXCEPTION: main
E/AndroidRuntime( 5207): Process: com.android.documentsui, PID: 5207
E/AndroidRuntime( 5207): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5207): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 5207): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 5207): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 5207): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5207): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5207): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 5207): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5207): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5207): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 5207): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 5207): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5207): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5207): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5207): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5207): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 5207): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 5207): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 5207): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 5207): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 5207): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 5207): 	... 10 more
I/ActivityManager( 1002): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5230 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/ActivityManager( 1002): Killing 4748:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 

```
