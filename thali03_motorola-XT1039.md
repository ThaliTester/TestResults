#### Test 54312298af2c956_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{422264f0 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4145): 
D/AndroidRuntime( 4145): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4145): CheckJNI is OFF
D/dalvikvm( 4145): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4145): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4145): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4145): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4145): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4145): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4145): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4145): failed to load memtrack module: -2
D/AndroidRuntime( 4145): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4145
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4162 uid=10507 gids={50507, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4145): Shutting down VM
D/dalvikvm( 4145): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4162): Binding Chromium to main looper Looper (main, tid 1) {41fe5a40}
I/LibraryLoader( 4162): Expected native library version number "",actual native library version number ""
I/chromium( 4162): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4162): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428553b0:true
I/Adreno-EGL( 4162): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4162): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4162): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4162): Local Branch: 
I/Adreno-EGL( 4162): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4162): Local Patches: NONE
I/Adreno-EGL( 4162): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4162): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4162): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4162): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4162): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4162): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4162): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4162): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4162): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4162): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4162): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4162): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4162): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4162): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4162): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4162): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4162): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4162): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4162): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4162): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4162): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4162): Enabling debug mode 0
,W/AwContents( 4162): nativeOnDraw failed; clearing to background color.
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,W/AwContents( 4162): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,376
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +352ms (total +377ms)
W/IInputConnectionWrapper( 4162): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4162): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4162): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fea3f0
,D/dalvikvm( 4162): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fea3f0
,D/jxcore_app_log( 4162): JniHelper::setJavaVM(0x41639fa8), pthread_self() = 1614756040
,D/JX-Cordova( 4162): jxcore cordova android initializing
,D/dalvikvm( 4162): GC_CONCURRENT freed 2806K, 17% free 14366K/17224K, paused 3ms+3ms, total 61ms
,D/dalvikvm( 4162): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 113K, 17% free 14363K/17224K, paused 29ms, total 29ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 127K, 17% free 14383K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 16.170MB for 96598-byte allocation
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 180K, 17% free 14418K/17320K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 16.250MB for 144892-byte allocation
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 255K, 18% free 14466K/17464K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 16.366MB for 217334-byte allocation
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 372K, 18% free 14540K/17680K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 16.542MB for 325996-byte allocation
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 573K, 19% free 14662K/18000K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 16.817MB for 488990-byte allocation
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 873K, 20% free 14839K/18480K, paused 27ms, total 27ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 1292K, 19% free 15096K/18480K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 17.824MB for 1100216-byte allocation
,D/dalvikvm( 4162): GC_CONCURRENT freed 1788K, 21% free 15482K/19556K, paused 3ms+4ms, total 50ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 283K, 22% free 15412K/19556K, paused 26ms, total 26ms
I/dalvikvm-heap( 4162): Grow heap (frag case) to 18.657MB for 1650320-byte allocation
,D/dalvikvm( 4162): GC_CONCURRENT freed 1667K, 25% free 15999K/21168K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 1400K, 25% free 16080K/21168K, paused 30ms, total 32ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 20.096MB for 2475476-byte allocation
,D/dalvikvm( 4162): GC_CONCURRENT freed 293K, 22% free 18504K/23588K, paused 4ms+8ms, total 70ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 4366K, 28% free 17052K/23588K, paused 36ms, total 36ms
,I/dalvikvm-heap( 4162): Grow heap (frag case) to 22.226MB for 3713210-byte allocation
,D/dalvikvm( 4162): GC_CONCURRENT freed 198K, 24% free 20727K/27216K, paused 5ms+18ms, total 58ms
,D/dalvikvm( 4162): GC_FOR_ALLOC freed 3299K, 34% free 18010K/27216K, paused 29ms, total 29ms
,W/jxcore-log( 4162): Initializing JXcore engine
,W/jxcore-log( 4162): JXcore engine is ready
,D/dalvikvm( 4162): GC_CONCURRENT freed 333K, 25% free 20680K/27216K, paused 2ms+2ms, total 36ms
D/dalvikvm( 4162): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4162): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/jxcore-log( 4162): Starting JXcore engine
,W/jxcore-log( 4162): Platform android
W/jxcore-log( 4162): 
,W/jxcore-log( 4162): Process ARCH arm
W/jxcore-log( 4162): 
,I/jxcore-log( 4162): JXcore Cordova bridge is ready!
I/jxcore-log( 4162): 
,W/jxcore-log( 4162): JXcore engine is started
,I/chromium( 4162): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4162): Toggling radios to true
I/jxcore-log( 4162): 
,D/BluetoothAdapter( 4162): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4162, uid=10507
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4162): Radios toggled
I/jxcore-log( 4162): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4162): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4162): 
I/jxcore-log( 4162): Perf Test app loaded loaded
I/jxcore-log( 4162): 
,I/jxcore-log( 4162): check test folder
I/jxcore-log( 4162): 
,I/jxcore-log( 4162): found test : ./testFindPeers.js
I/jxcore-log( 4162): 
,I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=0
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
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
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4162): found test : ./testSendData.js
I/jxcore-log( 4162): 
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 21
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 306022
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6005e508 clazz=0x63500001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1019): DisconnectingState
I/jxcore-log( 4162): found test : ./testSendData2.js
I/jxcore-log( 4162): 
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSI
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSI
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1409): Read error: ssl=0x62de5e20: I/O error during system call, Connection timed out
,V/NativeCrypto( 1409): SSL shutdown failed: ssl=0x62de5e20: I/O error during system call, Broken pipe
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
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
D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1205): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1205): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1205): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1205): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1205): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1205): onReceive() - done, currentInetCondition=0
,I/chromium( 4162): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TCMD    (  457): NL - Read 56 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e44ca0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e44ca0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e44ca0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1308): Active network info is not available
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1581): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,E/ActivityThread( 1581): Failed to find provider info for com.motorola.blur.setupprovider
D/Tethering( 1019): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1308): Active network info is not available
D/PollingManager( 1581): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1581): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,E/ActivityThread( 1581): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1581): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1581): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1581): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4243 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,V/MmsConfig( 4243): mnc/mcc: 
V/MmsConfig( 4243): tag: bool value: enabledMMS - true
,V/MmsConfig( 4243): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4243): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4243): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4243): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4243): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4243): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4243): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4243): tag: int value: recipientLimit - 20
V/MmsConfig( 4243): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4243): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4243): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4243): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4243): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4243): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4243): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4243): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4243): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/dalvikvm( 1019): GC_EXPLICIT freed 1080K, 65% free 18015K/50744K, paused 5ms+10ms, total 94ms
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4262 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3926:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4262): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4262): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4262): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4262): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4275 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3973:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4288 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3988:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4288): Binding Chromium to main looper Looper (main, tid 1) {41fe9de0}
,I/LibraryLoader( 4288): Expected native library version number "",actual native library version number ""
,I/chromium( 4288): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4288): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4288): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4288): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4288): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4288): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4288): Local Branch: 
I/Adreno-EGL( 4288): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4288): Local Patches: NONE
I/Adreno-EGL( 4288): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4288): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4288): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4288): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4288): Starting up...
,I/ImageResourceManager( 4032): ImageResourceManager: uninitalized
,I/iu.Environment( 4032): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 4032): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 4004:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1390): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1390): num queued entries: 0
,I/iu.UploadsManager( 1390): num updated entries: 0
,I/iu.SyncManager( 1390): NEXT; no task
,D/MobileConnectivityChangeReceiver( 4262): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4262): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4032): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.UploadsManager( 4032): num queued entries: 0
,I/iu.UploadsManager( 4032): num updated entries: 0
,I/iu.SyncManager( 4032): NEXT; no task
,D/DEBUG   ( 1581): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1581): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1581): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1581): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1581): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1581): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1581): onServiceConnected()
,D/GetNotificationsWS( 1581): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1581): unbindWebServices(): un-registering our AIDL callback...
,I/dalvikvm( 4162): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4162): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4162): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4162): Shutting down VM
,W/dalvikvm( 4162): threadid=1: thread exiting with uncaught exception (group=0x41718d40)
,E/AndroidRuntime( 4162): FATAL EXCEPTION: main
E/AndroidRuntime( 4162): Process: com.test.thalitest, PID: 4162
E/AndroidRuntime( 4162): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4162): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4162): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4162): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4162): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4162): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4162): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4162): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4162): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4162): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4162): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4162): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4162): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4162): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4162): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4162): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4162): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1019):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1019): Killing 3950:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4162): Sending signal. PID: 4162 SIG: 9
,I/ActivityManager( 1019): Process com.test.thalitest (pid 4162) has died.
,I/WindowState( 1019): WIN DEATH: Window{420a95f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/SFPerfTracer(  275):      triggers: (rate: 2:32) (compose: 0:4) (post: 0:1) (render: 0:5) (0:98 frames) (1:553)
,D/SFPerfTracer(  275):        layers: (0:13) (FocusedStackFrame: 0:8)* (StatusBar: 0:212)* (NavigationBar: 0:39)* (com.android.systemui.ImageWallpaper: 0:6)* (com.android.launcher/com.android.launcher2.Launcher: 0:11)* (Starting com.motorola.ccc.ota: 0:31)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:25)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:4)* 
,I/OtaApp  ( 1581): [info] > Updatetime from metadata: 10
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1581): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 4162 uid 10507
,W/Binder  ( 1234): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1234): java.lang.NullPointerException
W/Binder  ( 1234): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1234): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1234): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1234): 	at dalvik.system.NativeStart.run(Native Method)
,I/GAV2    ( 4288): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/wpa_supplicant( 1151): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  457): NL - Read 56 bytes from update socket.,
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461,
D/WifiStateMachine( 1019): processMsg: DisconnectedState,
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState,
,E/wpa_supplicant( 1151): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1151): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  457): NL - Read 312 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 88 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/wpa_supplicant( 1151): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 80 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 80 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1151): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1151): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!,
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197819056,
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19,
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-47ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@423d7828 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-46ms what=147462 obj=android.net.wifi.StateChangeResult@42208c40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42222e08 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42222e08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
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
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  457): NL - Read 56 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 20
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-5ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): DHCP successful
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
,D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42120a78
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
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
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1205): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1205): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1205): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42120a78
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1205): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1205): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1205): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1390): Checkin interval check for package: unspecified last checkin: 1450836435571 min interval config: 0 actual interval: 309987
,I/CheckinService( 1390): Checking schedule, now: 1450836745564 next: 1450836465537
,I/CheckinService( 1390): active receiver: enabled
,I/CheckinService( 1390): Preparing to send checkin request
,I/EventLogService( 1390): Accumulating logs since 1450836496294
,I/CheckinRequestBuilder( 1390): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1390): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1409): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1409): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4435 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4435): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4435): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4435): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4435): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4435): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4435): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4435): install
,I/MultiDex( 4435): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4435): loading existing secondary dex files
,I/MultiDex( 4435): load found 3 secondary dex files
,I/MultiDex( 4435): install done
,D/dalvikvm( 4435): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4435): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4435): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4435): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4435): VFY: unable to resolve instance field 36
,D/dalvikvm( 4435): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4435): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4435): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4435): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4435): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4435): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4435): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fef9b0
D/dalvikvm( 4435): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fef9b0
,D/dalvikvm( 4435): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fef9b0, skipping init
,D/dalvikvm( 4435): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fef9b0
D/dalvikvm( 4435): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fef9b0
,V/JNIHelp ( 4435): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4435): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fef9b0
,D/dalvikvm( 4435): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fef9b0
D/dalvikvm( 4435): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fef9b0
,D/dalvikvm( 4435): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fef9b0
,I/ProviderInstaller( 4435): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1250): callingUid 10022, callindPid: 1250
,E/MDM     ( 1250): [132] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1409): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1409): Proximity feature is not enabled.
,D/LocationInitializer( 1390): Restart initialization of location
,V/GLSActivity( 1409): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1250): No location to return for getLastLocation()
,W/FusedLocationProvider( 1250): location=null
,I/dalvikvm( 4435): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4435): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4435): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4435): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4435): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4435): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4435): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4435): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4435): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4435): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4435): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4435): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4435): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4435): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4435): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4435): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4435): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb512f000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb512f000
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
D/WVCdm   (  278): PrepareKeyRequest: nonce=4098640877
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4435): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4435): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4222f4c8
D/dalvikvm( 4435): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4222f4c8
,D/dalvikvm( 4435): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4222f4c8, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=2007584808
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 4435): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4435): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4473): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4435): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4435): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 83ms
,I/Adreno-EGL( 4435): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4435): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4435): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4435): Local Branch: 
I/Adreno-EGL( 4435): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4435): Local Patches: NONE
I/Adreno-EGL( 4435): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4435): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4435): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4435): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4435): Local Branch: 
I/Adreno-EGL( 4435): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4435): Local Patches: NONE
I/Adreno-EGL( 4435): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4435): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4435): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4435): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4435): Local Branch: 
I/Adreno-EGL( 4435): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4435): Local Patches: NONE
I/Adreno-EGL( 4435): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4435): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4435): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4435): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4435): Local Branch: 
I/Adreno-EGL( 4435): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4435): Local Patches: NONE
I/Adreno-EGL( 4435): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1390): Classify the device as Phone.
,V/NativeCrypto( 1390): SSL shutdown failed: ssl=0x6b9f6200: I/O error during system call, Connection timed out
,I/CheckinTask( 1390): Sending checkin request (11630 bytes)
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1581): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1581): now: 353360 ,futureTime: 63238919
,D/PollingManager( 1581): Polling alarm set to expire at: 63238919 Current Time: 353361
,E/ActivityThread( 1581): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,D/OtaApp  ( 1581): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1581): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1581): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/XTWiFiOS( 1308): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1581): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1581): now: 353399 ,futureTime: 63238919
,D/PollingManager( 1581): Polling alarm set to expire at: 63238919 Current Time: 353399
E/ActivityThread( 1581): Failed to find provider info for com.motorola.blur.setupprovider
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1581): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1581): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1581): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1581): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/openssl ( 4056): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4056): Crypto mode 0 already enabled
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/OtaApp  ( 1581): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1581): [debug] > CusSM.onRadioUp
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
D/OtaApp  ( 1581): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1581): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1581): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4262): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4262): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1581): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1581): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
D/OtaApp  ( 1581): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 4032): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/CheckinService( 1390): Checkin interval check for package: unspecified last checkin: 1450836435571 min interval config: 0 actual interval: 313126
,D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
I/iu.Environment( 1390): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1390): num queued entries: 0
I/iu.UploadsManager( 1390): num updated entries: 0
I/iu.SyncManager( 1390): NEXT; no task
D/dalvikvm( 4032): GC_FOR_ALLOC freed 598K, 5% free 16452K/17224K, paused 21ms, total 21ms
D/DEBUG   ( 1581): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1581): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1581): bindWebServices(): registering our AIDL callback...
I/SundryService( 1581): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1581): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1581): onServiceConnected()
D/GetNotificationsWS( 1581): onServiceConnected(): Registered for remote service callbacks...
I/dalvikvm-heap( 4032): Grow heap (frag case) to 19.835MB for 1821008-byte allocation
D/WaitableIntentService( 1581): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1581): unbindWebServices(): un-registering our AIDL callback...
I/iu.UploadsManager( 4032): num queued entries: 0
I/openssl ( 4056): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4056): Crypto mode 0 already enabled
I/iu.UploadsManager( 4032): num updated entries: 0
I/iu.SyncManager( 4032): NEXT; no task
D/MobileConnectivityChangeReceiver( 4262): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4262): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4032): GC_FOR_ALLOC freed 38K, 5% free 18204K/19004K, paused 11ms, total 11ms
I/iu.Environment( 4032): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/CheckinService( 1390): Checkin interval check for package: unspecified last checkin: 1450836435571 min interval config: 0 actual interval: 313194
D/DEBUG   ( 1581): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1581): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1581): bindWebServices(): registering our AIDL callback...
I/SundryService( 1581): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1581): onServiceConnected()
D/GetNotificationsWS( 1581): onServiceConnected(): Registered for remote service callbacks...
D/EmailService.MarketingOptInSetter( 1581): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1581): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1581): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,I/CheckinRequestBuilder( 1390): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1390): Failed to find provider info for com.google.android.wearable.settings
,D/OtaApp  ( 1581): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1581
,D/GetNotificationsWS( 1581): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1581): [info] > Updatetime from metadata: 10
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1581): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1581): [info] > Updatetime from metadata: 10
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1581): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1581): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1581): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1581
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1581): [info] > Updatetime from metadata: 10
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1581): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1581): [info] > Updatetime from metadata: 10
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1581): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{42978c40 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1390): Classify the device as Phone.
,I/CheckinTask( 1390): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1390): Checking schedule, now: 1450836748907 next: 1451429818904
,I/CheckinService( 1390): active receiver: disabled
,I/CheckinService( 1390): Checking schedule, now: 1450836748923 next: 1451429818904
,I/CheckinService( 1390): active receiver: disabled
,D/CheckinService( 1390): Recording last checkin time for package unspecified as 1450836748929
,D/GCM     ( 1409): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
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
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1019): GC_EXPLICIT freed 1346K, 65% free 17982K/50744K, paused 12ms+9ms, total 113ms
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1205): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1205): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1205): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1205): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4520 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/Launcher( 1323): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1323): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/GCoreNlp( 1250): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4520): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4520): MmsConfig.loadMmsSettings
,I/Babel   ( 4520): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4520): MmsConfig.loadFromDatabase
,E/Babel   ( 4520): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4520): MmsConfig.loadFromResources
,E/Babel   ( 4520): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4520): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4520): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4557 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3581:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4576 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,I/ActivityManager( 1019): Killing 4056:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/InternalIcingCorporaPro( 2318): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4594 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4243:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4557): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4594): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4594): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4594): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2318): UpdateCorporaTask done [took 184 ms] updated apps [took 184 ms] 
,I/dalvikvm( 4594): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4594): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4594): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4594): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4594): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4594): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4594): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4594): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4594): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4594): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4594): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4594): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4594): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4594): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4594): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4628 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4594): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4594): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4594): Skipping gmscore version check
,D/Finsky  ( 4594): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4594): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4594): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4594): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4594): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1019): Killing 4262:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1390): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1390): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1390): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4628): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41feb4a0, skipping init
I/openssl ( 4628): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4628): Crypto mode 0 already enabled
,D/Finsky  ( 4594): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/dalvikvm( 1390): GC_CONCURRENT freed 2021K, 31% free 12038K/17224K, paused 4ms+6ms, total 49ms
,D/dalvikvm( 1390): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Finsky  ( 4594): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1019): Killing 4275:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1390): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1390): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1234): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450836757
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{43ce3548 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4353aaa8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4202ad40 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ce3418 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 144687 ms ago
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4670 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 4288:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1297): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2
,V/AlarmManager( 1019): sending alarm Alarm{439c33e8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4290bbc0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43d706d0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4283ac90 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{428480e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ce3318 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
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
,V/AlarmManager( 1019): sending alarm Alarm{421cd098 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{440fdb98 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{433d4b48 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{434fb900 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43a049e0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42914590 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{437e8c90 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{427e84b8 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1205): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1205): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1205): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1019): sending alarm Alarm{43e22068 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43e44430 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43427330 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4296a848 type 1 com.android.deskclock}
,V/AlarmManager( 1019): sending alarm Alarm{43236e00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43b16a00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4296a920 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
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
,V/AlarmManager( 1019): sending alarm Alarm{4386f608 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43d3bcf8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43a08ce0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{433f0a20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428511d0 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 11ms
,I/ProcessStatsService( 1019): Prepared write state in 14ms
,I/ProcessStatsService( 1019): Prepared write state in 34ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-22-02-25-20.bin
,D/dalvikvm( 1019): GC_CONCURRENT freed 2058K, 65% free 18144K/50744K, paused 23ms+9ms, total 134ms
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
,V/AlarmManager( 1019): sending alarm Alarm{433ec670 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4413e7b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43e1a8c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43d18b20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ce3418 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms)
```
