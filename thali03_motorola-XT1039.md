#### Test 55742142a5c2fdb_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4074): 
D/AndroidRuntime( 4074): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4074): CheckJNI is OFF
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{424f2118 type 3 android}
D/dalvikvm( 4074): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4074): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4074): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4074): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4074): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4074): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4074): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4074): failed to load memtrack module: -2
D/AndroidRuntime( 4074): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4074
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4090 uid=10545 gids={50545, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4074): Shutting down VM
D/dalvikvm( 4074): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 5ms
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4090): Binding Chromium to main looper Looper (main, tid 1) {42416eb0}
I/LibraryLoader( 4090): Expected native library version number "",actual native library version number ""
I/chromium( 4090): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4090): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d78040:true
I/Adreno-EGL( 4090): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4090): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4090): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4090): Local Branch: 
I/Adreno-EGL( 4090): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4090): Local Patches: NONE
I/Adreno-EGL( 4090): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4090): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4090): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4090): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4090): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4090): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4090): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4090): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4090): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4090): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4090): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4090): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4090): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4090): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4090): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4090): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4090): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4090): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4090): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4090): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4090): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4090): Enabling debug mode 0
,W/AwContents( 4090): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4090): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,391
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +348ms (total +391ms)
,D/JsMessageQueue( 4090): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4090): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4241b180
,D/dalvikvm( 4090): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4241b180
,D/jxcore_app_log( 4090): JniHelper::setJavaVM(0x41b33f78), pthread_self() = 1615019248
,D/JX-Cordova( 4090): jxcore cordova android initializing
,D/dalvikvm( 4090): GC_CONCURRENT freed 2777K, 17% free 14406K/17224K, paused 3ms+2ms, total 61ms
,D/dalvikvm( 4090): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 179K, 17% free 14413K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 132K, 17% free 14427K/17224K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 16.213MB for 96598-byte allocation
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 181K, 17% free 14462K/17320K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 16.293MB for 144892-byte allocation
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 255K, 17% free 14510K/17464K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 16.410MB for 217334-byte allocation
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 371K, 18% free 14584K/17680K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 16.585MB for 325996-byte allocation
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 572K, 19% free 14706K/18000K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 16.860MB for 488990-byte allocation
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 871K, 20% free 14883K/18480K, paused 26ms, total 27ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 1292K, 19% free 15140K/18480K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 17.867MB for 1100216-byte allocation
,D/dalvikvm( 4090): GC_CONCURRENT freed 1760K, 21% free 15529K/19556K, paused 2ms+3ms, total 43ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 292K, 21% free 15475K/19556K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 18.718MB for 1650320-byte allocation
,D/dalvikvm( 4090): GC_CONCURRENT freed 1793K, 25% free 16064K/21168K, paused 1ms+6ms, total 45ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 1259K, 24% free 16097K/21168K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 20.114MB for 2475476-byte allocation
,D/dalvikvm( 4090): GC_CONCURRENT freed 1889K, 29% free 16812K/23588K, paused 5ms+5ms, total 51ms
,D/dalvikvm( 4090): GC_CONCURRENT freed 2360K, 28% free 17056K/23588K, paused 3ms+6ms, total 49ms
,D/dalvikvm( 4090): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 662K, 29% free 16863K/23588K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4090): Grow heap (frag case) to 22.041MB for 3713210-byte allocation
,D/dalvikvm( 4090): GC_CONCURRENT freed 282K, 25% free 20430K/27216K, paused 4ms+3ms, total 45ms
,D/dalvikvm( 4090): GC_FOR_ALLOC freed 3076K, 34% free 18056K/27216K, paused 28ms, total 29ms
,W/jxcore-log( 4090): Initializing JXcore engine
,W/jxcore-log( 4090): JXcore engine is ready
,D/dalvikvm( 4090): GC_CONCURRENT freed 334K, 24% free 20722K/27216K, paused 1ms+2ms, total 28ms
,D/dalvikvm( 4090): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4090): Starting JXcore engine
,W/jxcore-log( 4090): Platform android
W/jxcore-log( 4090): 
,W/jxcore-log( 4090): Process ARCH arm
W/jxcore-log( 4090): 
,I/jxcore-log( 4090): JXcore Cordova bridge is ready!
I/jxcore-log( 4090): 
,W/jxcore-log( 4090): JXcore engine is started
,I/chromium( 4090): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4090): Toggling radios to true
I/jxcore-log( 4090): 
,D/BluetoothAdapter( 4090): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4090, uid=10545
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4090): Radios toggled
I/jxcore-log( 4090): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4090): Received device characteristics:
I/jxcore-log( 4090): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4090): Bluetooth name: XT1039
I/jxcore-log( 4090): Device name: motorola-XT1039
I/jxcore-log( 4090): 
I/jxcore-log( 4090): Perf Test app loaded loaded
I/jxcore-log( 4090): 
,I/jxcore-log( 4090): check test folder
I/jxcore-log( 4090): 
,I/jxcore-log( 4090): found test : ./testFindPeers.js
I/jxcore-log( 4090): 
,I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  272): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  272):  STA Disconnected !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  425): NL - Read 60 bytes from update socket.
D/TCMD    (  425): NL - ignore NL message, type = 21
,D/TCMD    (  425): Listening for incoming client connection request
,I/jxcore-log( 4090): found test : ./testSendData.js
I/jxcore-log( 4090): 
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 334696
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x611a9f70 clazz=0x62800001 iface=wlan0 mask=0x3
V/NativeCrypto( 1354): Read error: ssl=0x62d97040: I/O error during system call, Connection timed out
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1019): DisconnectingState
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1354): SSL shutdown failed: ssl=0x62d97040: I/O error during system call, Broken pipe
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1175): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
,I/chromium( 4090): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 38
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 0 38
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/TCMD    (  425): NL - Read 56 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43e5ca68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e5ca68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e5ca68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1262): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1262): Active network info is not available
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1262): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1262): Active network info is not available
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1557): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1557): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1557): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4172 uid=10030 gids={50030, 3003, 1028, 1015}
,V/MmsConfig( 4172): mnc/mcc: 
V/MmsConfig( 4172): tag: bool value: enabledMMS - true
V/MmsConfig( 4172): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4172): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4172): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4172): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4172): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4172): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4172): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4172): tag: int value: recipientLimit - 20
V/MmsConfig( 4172): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4172): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4172): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4172): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4172): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4172): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4172): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4172): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4172): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/dalvikvm( 1019): GC_EXPLICIT freed 1197K, 65% free 18105K/51016K, paused 3ms+9ms, total 89ms
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4190 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3888:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4190): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4190): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4190): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4190): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4203 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3935:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4216 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3422:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  275): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 25ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,V/WebViewChromiumFactoryProvider( 4216): Binding Chromium to main looper Looper (main, tid 1) {4241ab68}
,I/LibraryLoader( 4216): Expected native library version number "",actual native library version number ""
,I/chromium( 4216): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,I/BrowserStartupController( 4216): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4216): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4216): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4216): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4216): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4216): Local Branch: 
I/Adreno-EGL( 4216): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4216): Local Patches: NONE
I/Adreno-EGL( 4216): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4216): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4216): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4216): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4216): Starting up...
,I/ImageResourceManager( 3982): ImageResourceManager: uninitalized
,I/iu.Environment( 3982): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3982): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3957:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1220): GC_EXPLICIT freed 921K, 36% free 11072K/17224K, paused 4ms+9ms, total 46ms
,I/iu.Environment( 1409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1409): num queued entries: 0
,I/iu.UploadsManager( 1409): num updated entries: 0
,I/iu.SyncManager( 1409): NEXT; no task
,D/MobileConnectivityChangeReceiver( 4190): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4190): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.UploadsManager( 3982): num queued entries: 0
,I/iu.UploadsManager( 3982): num updated entries: 0
,I/iu.SyncManager( 3982): NEXT; no task
,I/iu.Environment( 3982): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
,D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,I/dalvikvm( 4090): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4090): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4090): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4090): Shutting down VM
,W/dalvikvm( 4090): threadid=1: thread exiting with uncaught exception (group=0x41b45d40)
,E/AndroidRuntime( 4090): FATAL EXCEPTION: main
E/AndroidRuntime( 4090): Process: com.test.thalitest, PID: 4090
E/AndroidRuntime( 4090): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4090): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4090): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4090): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4090): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4090): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4090): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4090): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4090): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4090): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4090): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4090): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4090): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4090): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4090): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4090): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4090): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4090): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4090): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1019):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1019): Killing 3403:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4090): Sending signal. PID: 4090 SIG: 9
,I/ActivityManager( 1019): Process com.test.thalitest (pid 4090) has died.
,I/WindowState( 1019): WIN DEATH: Window{42d313b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 4090 uid 10545
W/Binder  ( 1201): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1201): java.lang.NullPointerException
W/Binder  ( 1201): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1201): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1201): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1201): 	at dalvik.system.NativeStart.run(Native Method)
,I/GAV2    ( 4216): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 1175): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  272): Event received = Trying to associate with
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  425): NL - Read 56 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState,
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1175): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1175): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  425): NL - Read 312 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 192 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
,I/wpa_supplicant( 1175): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1175): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  272): Event received = Associated with c0:ff:d4
D/TCMD    (  425): NL - Read 80 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 80 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
D/TCMD    (  425): Listening for incoming client connection request
D/TCMD    (  425): NL - Read 68 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: X
I/wpa_supplicant( 1175): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  272): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  272): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  272):  STA Connected !!
D/TCMD    (  425): NL - Read 1000 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
E/MDMCTBK (  272): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  272): get_freq !!, resp=0
I/MDMCTBK (  272): get_freq !!, Strip data
I/MDMCTBK (  272): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  272): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  272): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  272): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1196326136
I/MDMCTBK (  272): return from set_get_from_wpa_supplicant
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  272): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  272): , reply_len: 3, ret: 0
E/MDMCTBK (  272): MdmCutbackHndler, resp=OK
E/MDMCTBK (  272): 
,D/MDMCTBK (  272): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-45ms what=147462 obj=android.net.wifi.StateChangeResult@425a5f50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-38ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@425c54d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425128b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425128b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  425): NL - Read 56 bytes from update socket.
D/TCMD    (  425): NL - message type is RTM_NEWLINK
,D/TCMD    (  425): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,D/TCMD    (  425): NL - Read 60 bytes from update socket.
D/TCMD    (  425): NL - ignore NL message, type = 20
,D/TCMD    (  425): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
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
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
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
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@424fd400
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
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
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@424fd400
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1409): Checkin interval check for package: unspecified last checkin: 1452600886536 min interval config: 0 actual interval: 339112
,I/CheckinService( 1409): Checking schedule, now: 1452601225655 next: 1452600916462
,I/CheckinService( 1409): active receiver: enabled
,I/CheckinService( 1409): Preparing to send checkin request
,I/EventLogService( 1409): Accumulating logs since 1452600882963
,I/CheckinRequestBuilder( 1409): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1409): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4354 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4354): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4354): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4354): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4354): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4354): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4354): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4354): install
,I/MultiDex( 4354): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4354): loading existing secondary dex files
,I/MultiDex( 4354): load found 3 secondary dex files
,I/MultiDex( 4354): install done
,D/dalvikvm( 4354): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4354): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4354): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4354): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4354): VFY: unable to resolve instance field 36
,D/dalvikvm( 4354): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4354): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4354): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4354): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4354): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4354): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4354): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42415e00
D/dalvikvm( 4354): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42415e00
,D/dalvikvm( 4354): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42415e00, skipping init
,D/dalvikvm( 4354): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42415e00
D/dalvikvm( 4354): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42415e00
,V/JNIHelp ( 4354): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4354): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42415e00
,D/dalvikvm( 4354): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42415e00
D/dalvikvm( 4354): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42415e00
,D/dalvikvm( 4354): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42415e00
,I/ProviderInstaller( 4354): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 1409): Restart initialization of location
,D/AuthorizationBluetoothService( 1354): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1354): Proximity feature is not enabled.
,D/WearableService( 1220): callingUid 10022, callindPid: 1220
,E/MDM     ( 1220): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4354): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4354): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4354): VFY: replacing opcode 0x6e at 0x00ce
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
,I/dalvikvm( 4354): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 4354): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4354): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4354): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4354): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4354): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4354): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4354): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4354): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4354): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4354): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4354): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4354): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4354): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53c1000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53c1000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1674421638
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4354): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4354): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426584e0
D/dalvikvm( 4354): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426584e0
,D/dalvikvm( 4354): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426584e0, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4354): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4397): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4354): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4354): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 4354): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4354): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4354): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4354): Local Branch: 
I/Adreno-EGL( 4354): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4354): Local Patches: NONE
I/Adreno-EGL( 4354): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4354): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4354): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4354): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4354): Local Branch: 
I/Adreno-EGL( 4354): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4354): Local Patches: NONE
I/Adreno-EGL( 4354): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4354): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4354): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4354): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4354): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4354): Local Branch: 
I/Adreno-EGL( 4354): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4354): Local Patches: NONE
I/Adreno-EGL( 4354): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4354): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4354): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4354): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4354): Local Branch: 
I/Adreno-EGL( 4354): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4354): Local Patches: NONE
I/Adreno-EGL( 4354): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
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
D/WVCdm   (  278): PrepareKeyRequest: nonce=3122122380
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1409): Classify the device as Phone.
,V/NativeCrypto( 1409): SSL shutdown failed: ssl=0x6a972090: I/O error during system call, Connection timed out
,D/dalvikvm( 1409): GC_CONCURRENT freed 1853K, 30% free 12069K/17224K, paused 4ms+6ms, total 45ms
,I/CheckinTask( 1409): Sending checkin request (11749 bytes)
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1262): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,D/PollingManager( 1557): now: 382603 ,futureTime: 82270708
,D/PollingManager( 1557): Polling alarm set to expire at: 82270708 Current Time: 382603
E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1262): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1557): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1557): now: 382640 ,futureTime: 82270708
D/PollingManager( 1557): Polling alarm set to expire at: 82270708 Current Time: 382641
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,E/ActivityThread( 1557): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): handleMessage: X
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/OtaApp  ( 1557): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4002): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4002): Crypto mode 0 already enabled
D/OtaApp  ( 1557): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1557): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1257): Column apn id key is 'apn_id'
,I/CheckinRequestBuilder( 1409): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1409): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1557): GC_CONCURRENT freed 1980K, 38% free 10734K/17224K, paused 4ms+3ms, total 40ms
,D/dalvikvm( 1557): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1557): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1557): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4190): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4190): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3982): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 1409): Checkin interval check for package: unspecified last checkin: 1452600886536 min interval config: 0 actual interval: 342301
,I/iu.UploadsManager( 3982): num queued entries: 0
,I/iu.UploadsManager( 3982): num updated entries: 0
,I/iu.SyncManager( 3982): NEXT; no task
,I/iu.Environment( 1409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1409): num queued entries: 0
,I/iu.UploadsManager( 1409): num updated entries: 0
,I/iu.SyncManager( 1409): NEXT; no task
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 3982): GC_CONCURRENT freed 617K, 5% free 16458K/17224K, paused 3ms+3ms, total 26ms
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1557): onServiceConnected()
,D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4002): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4002): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4190): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4190): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3982): GC_FOR_ALLOC freed 37K, 5% free 16423K/17224K, paused 16ms, total 16ms
,I/dalvikvm-heap( 3982): Grow heap (frag case) to 19.807MB for 1821008-byte allocation
,I/iu.Environment( 3982): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1409): Checkin interval check for package: unspecified last checkin: 1452600886536 min interval config: 0 actual interval: 342385
,D/dalvikvm( 3982): GC_FOR_ALLOC freed 7K, 5% free 18199K/19004K, paused 14ms, total 14ms
,I/CheckinRequestBuilder( 1409): Classify the device as Phone.
,D/DEBUG   ( 1557): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1557): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1557): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1557): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1557): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1557): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1557): onServiceConnected()
,D/GetNotificationsWS( 1557): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1557): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/CheckinTask( 1409): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1409): Checking schedule, now: 1452601228963 next: 1453194298956
I/CheckinService( 1409): active receiver: disabled
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1409): Checking schedule, now: 1452601229005 next: 1453194298956
,I/CheckinService( 1409): active receiver: disabled
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/CheckinService( 1409): Recording last checkin time for package unspecified as 1452601229012
,D/OtaApp  ( 1557): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1557): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1557
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1354): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1019): GC_EXPLICIT freed 1335K, 65% free 18111K/51016K, paused 5ms+11ms, total 106ms
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1557): [info] > Updatetime from metadata: 10
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1557): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1557): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1557): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{425a8328 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 10401 seconds from now (1452601229356)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1354): GC_EXPLICIT freed 1870K, 40% free 10346K/17224K, paused 2ms+4ms, total 34ms
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1085): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1273): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1220): GC_CONCURRENT freed 1302K, 32% free 11717K/17224K, paused 4ms+9ms, total 44ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4461 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1300): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/Launcher( 1300): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4461): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4461): MmsConfig.loadMmsSettings
I/Babel   ( 4461): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4461): MmsConfig.loadFromDatabase
,E/Babel   ( 4461): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4461): MmsConfig.loadFromResources
,E/Babel   ( 4461): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4461): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4461): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4498 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3470:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4518 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4002:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2306): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4536 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4172:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4498): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4536): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4536): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4536): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2306): UpdateCorporaTask done [took 197 ms] updated apps [took 197 ms] 
,I/dalvikvm( 4536): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4536): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4536): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4536): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4536): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4536): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4536): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4536): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4536): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4536): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4536): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4536): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4536): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4536): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4536): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4570 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4536): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4536): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4536): Skipping gmscore version check
,D/Finsky  ( 4536): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4536): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4536): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4536): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4536): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1019): Killing 4190:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1409): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1409): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1409): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4570): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4241c310, skipping init
I/openssl ( 4570): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4570): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Killing 4203:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4536): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4536): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1409): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1409): GC_CONCURRENT freed 1908K, 30% free 12209K/17224K, paused 5ms+7ms, total 52ms
,D/dalvikvm( 1409): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/Icing   ( 1409): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452601237
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{425f5730 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43ce7c38 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{439e82b8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 6
,V/AlarmManager( 1019): sending alarm Alarm{441eb378 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{437ee0e0 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43f03500 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42dbebb8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43824340 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43ad67d8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{439b5cb0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{425f4980 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{425f4540 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 564596 ms ago
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4621 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ActivityManager( 1019): Killing 4216:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43ac2c40 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42dab4f0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43807868 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4462f858 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d08328 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{425e8348 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1273): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1019): sending alarm Alarm{42d799a0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43a2be88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42571480 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{437f9340 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{445769d0 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{442774d8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43846518 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4380d5d0 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{441f7fd8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42d72028 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 9ms
,I/ProcessStatsService( 1019): Prepared write state in 53ms
,D/dalvikvm( 1019): GC_CONCURRENT freed 2129K, 65% free 18151K/51016K, paused 12ms+14ms, total 159ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2016-01-11-16-25-28.bin
,V/AlarmManager( 1019): sending alarm Alarm{42d79b38 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{42d79b88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d79bd8 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42d79d00 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42d79a60 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1409): Aggregate from 1452601225677 (log), 1452600351421 (data)
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42dcc430 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42c1b170 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c12380 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42db9a70 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c0f758 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42a46288 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4711): 
D/AndroidRuntime( 4711): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4711): CheckJNI is OFF
D/dalvikvm( 4711): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4711): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4711): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4711): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4711): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4711): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4711): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4711): failed to load memtrack module: -2
D/AndroidRuntime( 4711): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10545 user=-1: uninstall pkg
I/dalvikvm( 1019): Total arena pages for JIT: 15
W/PackageSettings( 1019): Skipping PackageSetting{426d8578 com.example.hello/10543} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10545 user=0: pkg removed
D/dalvikvm( 2265): GC_EXPLICIT freed 5518K, 44% free 9650K/17224K, paused 2ms+6ms, total 37ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1409): GC_EXPLICIT freed 503K, 31% free 11935K/17224K, paused 4ms+29ms, total 139ms
W/SQLiteConnectionPool( 1409): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1300): GC_EXPLICIT freed 3331K, 33% free 11596K/17224K, paused 2ms+4ms, total 138ms
I/Launcher( 1300): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 1021K, 65% free 17984K/51016K, paused 6ms+18ms, total 111ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/VoicemailCleanupService( 4498): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2306): GC_EXPLICIT freed 4338K, 42% free 10091K/17224K, paused 2ms+4ms, total 149ms
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1300): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 114K, 65% free 17961K/51016K, paused 17ms+10ms, total 113ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452603011
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
I/InternalIcingCorporaPro( 2306): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4741 uid=10059 gids={50059, 3003, 1028, 1015}
D/AndroidRuntime( 4711): Shutting down VM
D/dalvikvm( 4711): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10545 #1
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452603011
I/InternalIcingCorporaPro( 2306): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
W/ActiveOrDefaultContextProvider( 4741): Missing scope.enter somewhere. Returning default context
E/SQLiteDatabase( 4741): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4741): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4741): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4741): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4741): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4741): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 4741): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 4741): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 4741): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4741): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 4741): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 4741): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4741): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 4741): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4741): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 4741): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4741): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4741): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4741): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4741): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4741): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4741): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4741): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4741): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4741): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4741): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4741): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4741): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4741): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4741): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4741): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4741): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4741): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 4741): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 4741): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4741): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 4741): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 4741): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4741): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4741): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 4741): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 4741): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4741): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4741): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4741): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 4741): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4741): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4741): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4741): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4741): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4741): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4741): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4741): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4741): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4741): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4741): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4741): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4741): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4741): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4741): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4741): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4741): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4741): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4741): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4741): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 4741): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 4741): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 4741): threadid=11: thread exiting with uncaught exception (group=0x41b45d40)
E/AndroidRuntime( 4741): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4741): Process: com.google.android.apps.docs, PID: 4741
E/AndroidRuntime( 4741): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4741): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4741): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4741): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4741): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4741): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 4741): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 4741): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 4741): 	at WT.run(AbstractDatabaseInstance.java:411)
I/Process ( 4741): Sending signal. PID: 4741 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1019): Process com.google.android.apps.docs (pid 4741) has died.

```
