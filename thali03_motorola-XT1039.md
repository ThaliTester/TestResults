#### Test 50650278161ce7f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{44159f28 type 3 android}
,D/AndroidRuntime( 3945): 
D/AndroidRuntime( 3945): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3945): CheckJNI is OFF
D/dalvikvm( 3945): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3945): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3945): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3945): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3945): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3945): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3945): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3945): failed to load memtrack module: -2
D/AndroidRuntime( 3945): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3945
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3961 uid=10497 gids={50497, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3945): Shutting down VM
D/dalvikvm( 3945): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3961): Binding Chromium to main looper Looper (main, tid 1) {41fe3b48}
I/LibraryLoader( 3961): Expected native library version number "",actual native library version number ""
I/chromium( 3961): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3961): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@439e3968:true
I/Adreno-EGL( 3961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3961): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3961): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3961): Local Branch: 
I/Adreno-EGL( 3961): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3961): Local Patches: NONE
I/Adreno-EGL( 3961): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3961): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3961): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3961): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3961): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3961): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3961): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3961): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3961): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3961): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3961): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3961): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3961): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3961): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3961): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3961): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3961): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3961): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3961): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3961): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3961): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3961): Enabling debug mode 0
,W/AwContents( 3961): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3961): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,416
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +386ms (total +416ms)
,D/JsMessageQueue( 3961): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3961): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe8330
,D/dalvikvm( 3961): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe8330
,D/jxcore_app_log( 3961): JniHelper::setJavaVM(0x41636fa8), pthread_self() = 1614719680
,D/JX-Cordova( 3961): jxcore cordova android initializing
,D/dalvikvm( 3961): GC_CONCURRENT freed 2809K, 17% free 14380K/17224K, paused 2ms+2ms, total 55ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 220K, 17% free 14361K/17224K, paused 26ms, total 27ms
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 187K, 17% free 14388K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 16.221MB for 144892-byte allocation
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 255K, 17% free 14436K/17368K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 16.337MB for 217334-byte allocation
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 371K, 18% free 14511K/17584K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 16.513MB for 325996-byte allocation
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 572K, 19% free 14632K/17904K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 16.788MB for 488990-byte allocation
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 872K, 20% free 14809K/18384K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 17.194MB for 733480-byte allocation
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 1292K, 22% free 15066K/19104K, paused 28ms, total 29ms
,D/dalvikvm( 3961): GC_CONCURRENT freed 1676K, 20% free 15438K/19104K, paused 1ms+3ms, total 34ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 380K, 20% free 15396K/19104K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 18.641MB for 1650320-byte allocation
,D/dalvikvm( 3961): GC_CONCURRENT freed 1574K, 23% free 15960K/20716K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 1498K, 23% free 16058K/20716K, paused 31ms, total 31ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 20.075MB for 2475476-byte allocation
,D/dalvikvm( 3961): GC_CONCURRENT freed 1884K, 28% free 16758K/23136K, paused 2ms+3ms, total 43ms
,D/dalvikvm( 3961): GC_CONCURRENT freed 2368K, 27% free 16976K/23136K, paused 1ms+6ms, total 44ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 548K, 28% free 16874K/23136K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3961): Grow heap (frag case) to 22.051MB for 3713210-byte allocation
,D/dalvikvm( 3961): GC_CONCURRENT freed 288K, 24% free 20431K/26764K, paused 5ms+4ms, total 54ms
,D/dalvikvm( 3961): GC_FOR_ALLOC freed 3023K, 33% free 17969K/26764K, paused 27ms, total 27ms
,W/jxcore-log( 3961): Initializing JXcore engine
,W/jxcore-log( 3961): JXcore engine is ready
,D/dalvikvm( 3961): GC_CONCURRENT freed 321K, 23% free 20638K/26764K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/PluginManager( 3961): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
D/dalvikvm( 3961): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 3961): Starting JXcore engine
,W/jxcore-log( 3961): Platform android
W/jxcore-log( 3961): 
,W/jxcore-log( 3961): Process ARCH arm
W/jxcore-log( 3961): 
,I/jxcore-log( 3961): JXcore Cordova bridge is ready!
I/jxcore-log( 3961): 
,W/jxcore-log( 3961): JXcore engine is started
,I/chromium( 3961): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3961): Toggling radios to true
I/jxcore-log( 3961): 
,D/BluetoothAdapter( 3961): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=3961, uid=10497
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 3961): Radios toggled
I/jxcore-log( 3961): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3961): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3961): 
I/jxcore-log( 3961): Perf Test app loaded loaded
I/jxcore-log( 3961): 
I/jxcore-log( 3961): check test folder
I/jxcore-log( 3961): 
I/jxcore-log( 3961): found test : ./testFindPeers.js
I/jxcore-log( 3961): 
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
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
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/jxcore-log( 3961): found test : ./testSendData.js
I/jxcore-log( 3961): 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1019): connected time updated 313220
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6122cdc0 clazz=0x62500001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1360): Read error: ssl=0x62e20ac8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x62e20ac8: I/O error during system call, Broken pipe
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1019): DisconnectingState
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
,D/WifiStateMachine( 1019): handleMessage: X
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,I/chromium( 3961): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG700'
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1150): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 192 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
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
,I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1225032880
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
,E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@43aae8b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-10ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43a32530 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43a32530 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43a32530 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-8ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
,D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/jxcore-log( 3961): Connected to the server!
I/jxcore-log( 3961): 
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/chromium( 3961): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
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
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
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
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_3_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi three bars."
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
I/openssl ( 3854): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3854): Crypto mode 0 already enabled
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/dalvikvm( 1019): GC_EXPLICIT freed 23348K, 65% free 18131K/50780K, paused 11ms+10ms, total 148ms
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4119 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,V/MmsConfig( 4119): mnc/mcc: 
V/MmsConfig( 4119): tag: bool value: enabledMMS - true
,V/MmsConfig( 4119): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4119): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4119): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4119): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4119): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4119): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4119): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4119): tag: int value: recipientLimit - 20
,V/MmsConfig( 4119): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4119): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4119): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4119): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4119): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4119): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4119): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4119): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4119): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4139 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3630:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4139): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4139): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4139): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4139): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4152 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3730:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450488608396 min interval config: 0 actual interval: 302140
,I/CheckinService( 1401): Checking schedule, now: 1450488910550 next: 1450488638351
,I/CheckinService( 1401): active receiver: enabled
,I/CheckinService( 1401): Preparing to send checkin request
,I/EventLogService( 1401): Accumulating logs since 1450488604892
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4170 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3788:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4170): Binding Chromium to main looper Looper (main, tid 1) {41fe7c38}
,I/LibraryLoader( 4170): Expected native library version number "",actual native library version number ""
,I/chromium( 4170): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4170): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4170): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4170): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4170): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4170): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4170): Local Branch: 
I/Adreno-EGL( 4170): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4170): Local Patches: NONE
I/Adreno-EGL( 4170): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4191 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4191): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4191): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4191): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4191): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4191): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4191): install
,I/MultiDex( 4191): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/chromium( 4170): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/MultiDex( 4191): loading existing secondary dex files
,I/MultiDex( 4191): load found 3 secondary dex files
,I/MultiDex( 4191): install done
,W/GAV2    ( 4170): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4170): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4191): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4191): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4191): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4191): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4191): VFY: unable to resolve instance field 36
,D/dalvikvm( 4191): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4191): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4191): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4191): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4191): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4191): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4191): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed8f8
D/dalvikvm( 4191): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed8f8
,D/dalvikvm( 4191): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed8f8, skipping init
,D/dalvikvm( 4191): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fed8f8
D/dalvikvm( 4191): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fed8f8
,V/JNIHelp ( 4191): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4191): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed8f8
,D/dalvikvm( 4191): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fed8f8
D/dalvikvm( 4191): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fed8f8
,D/dalvikvm( 4191): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fed8f8
,I/NSApplication( 4170): Starting up...
,I/ProviderInstaller( 4191): Installed default security provider GmsCore_OpenSSL
,I/ImageResourceManager( 3833): ImageResourceManager: uninitalized
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 3436:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/dalvikvm( 4191): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4191): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4191): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4191): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x000d
I/openssl ( 3854): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3854): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4139): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4139): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4191): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4191): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4191): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4191): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4191): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4191): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4191): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4191): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4191): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4191): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,E/MDM     ( 1222): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1401): Restart initialization of location
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=998104313
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4191): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4191): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e5b00
D/dalvikvm( 4191): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e5b00
,D/dalvikvm( 4191): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e5b00, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): now: 344455 ,futureTime: 65459106
,D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 344456
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1562): now: 344481 ,futureTime: 65459106
D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 344481
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/openssl ( 3854): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3854): Crypto mode 0 already enabled
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
I/dalvikvm( 3961): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 3961): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3961): VFY: replacing opcode 0x6e at 0x0002
,D/MobileConnectivityChangeReceiver( 4139): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4139): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/AndroidRuntime( 3961): Shutting down VM
,W/dalvikvm( 3961): threadid=1: thread exiting with uncaught exception (group=0x41715d40)
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
E/AndroidRuntime( 3961): FATAL EXCEPTION: main
E/AndroidRuntime( 3961): Process: com.test.thalitest, PID: 3961
E/AndroidRuntime( 3961): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3961): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 3961): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 3961): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 3961): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 3961): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 3961): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 3961): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3961): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3961): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3961): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3961): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3961): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 3961): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 3961): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3961): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3961): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 3961): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 3961): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1019):   Force finishing activity com.test.thalitest/.MainActivity
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
I/Process ( 3961): Sending signal. PID: 3961 SIG: 9
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1562): GC_CONCURRENT freed 2014K, 38% free 10736K/17224K, paused 7ms+4ms, total 48ms
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 3808:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450488608396 min interval config: 0 actual interval: 303603
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1019): Process com.test.thalitest (pid 3961) has died.
,D/WifiService( 1019): Client connection lost with reason: 4
,I/WindowState( 1019): WIN DEATH: Window{444d12b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
I/openssl ( 3854): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3854): Crypto mode 0 already enabled
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
D/MobileConnectivityChangeReceiver( 4139): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4139): onReceive CONNECTIVITY_CHANGE networkType=1
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 3961 uid 10497
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=227734393
D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450488608396 min interval config: 0 actual interval: 303689
W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/dalvikvm( 3833): GC_FOR_ALLOC freed 595K, 5% free 16434K/17224K, paused 32ms, total 35ms
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/SFPerfTracer(  278):      triggers: (rate: 2:34) (compose: 0:4) (post: 0:1) (render: 0:6) (0:111 frames) (1:554)
,D/SFPerfTracer(  278):        layers: (0:13) (FocusedStackFrame: 1:11)* (StatusBar: 0:211)* (NavigationBar: 0:40)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:4)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 1:3)* 
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,4
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
I/dalvikvm-heap( 3833): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429f7860 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4191): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4267): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4191): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4191): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 77ms
,I/Adreno-EGL( 4191): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4191): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4191): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4191): Local Branch: 
I/Adreno-EGL( 4191): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4191): Local Patches: NONE
I/Adreno-EGL( 4191): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4191): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4191): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4191): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4191): Local Branch: 
I/Adreno-EGL( 4191): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4191): Local Patches: NONE
I/Adreno-EGL( 4191): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4191): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4191): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4191): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4191): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4191): Local Branch: 
I/Adreno-EGL( 4191): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4191): Local Patches: NONE
I/Adreno-EGL( 4191): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4191): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4191): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4191): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4191): Local Branch: 
I/Adreno-EGL( 4191): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4191): Local Patches: NONE
I/Adreno-EGL( 4191): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,V/NativeCrypto( 1401): SSL shutdown failed: ssl=0x6bb524d0: I/O error during system call, Connection timed out
,I/CheckinTask( 1401): Sending checkin request (11680 bytes)
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1019): GC_EXPLICIT freed 813K, 65% free 18024K/50780K, paused 5ms+9ms, total 101ms
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,D/dalvikvm( 1360): GC_EXPLICIT freed 1385K, 41% free 10295K/17224K, paused 2ms+4ms, total 29ms
,I/CheckinTask( 1401): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1401): Checking schedule, now: 1450488913813 next: 1451081983809
,I/CheckinService( 1401): active receiver: disabled
,I/CheckinService( 1401): Checking schedule, now: 1450488913831 next: 1451081983809
,I/CheckinService( 1401): active receiver: disabled
,D/CheckinService( 1401): Recording last checkin time for package unspecified as 1450488913837
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ConnectedState
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1238): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1238): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
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
,I/GAV2    ( 4170): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4302 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1309): Deferring update until onResume
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
,I/Babel   ( 4302): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4302): MmsConfig.loadMmsSettings
,I/Babel   ( 4302): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4302): MmsConfig.loadFromDatabase
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel   ( 4302): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4302): MmsConfig.loadFromResources
,E/Babel   ( 4302): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4302): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4302): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4342 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
,I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 3833): GC_FOR_ALLOC freed 31K, 5% free 18188K/19004K, paused 13ms, total 13ms
,D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1401): Null package name or gms related package.  Ignoreing.
I/ActivityManager( 1019): Killing 3854:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1401): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1019): Killing 4119:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1401): GC_CONCURRENT freed 2185K, 31% free 12019K/17224K, paused 4ms+5ms, total 43ms
,I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 315 ms] updated apps [took 315 ms] 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/Icing   ( 1401): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1401): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450488922
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42322d58 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43df7b80 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1019): InitialState.processMessage what=4
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 467128
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService( 1019): Attempting to switch to mobile
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
,D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6122cdc0 clazz=0x89300001 iface=wlan0 mask=0x3
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
V/NativeCrypto( 1360): Read error: ssl=0x62e27008: I/O error during system call, Connection timed out
V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x62e27008: I/O error during system call, Broken pipe
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
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
,D/WifiStateMachine( 1019): handleMessage: X
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/dalvikvm( 1222): GC_CONCURRENT freed 1717K, 33% free 11599K/17224K, paused 3ms+7ms, total 39ms
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1295): Active network info is not available
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 144980 ms ago
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4415 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/dalvikvm( 4415): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe7fa8, skipping init
I/openssl ( 4415): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4415): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4442 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4139:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4442): mnc/mcc: 
V/MmsConfig( 4442): tag: bool value: enabledMMS - true
,V/MmsConfig( 4442): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4442): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4442): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4442): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4442): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4442): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4442): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4442): tag: int value: recipientLimit - 20
V/MmsConfig( 4442): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4442): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4442): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4442): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4442): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4442): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4442): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4442): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4442): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4460 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 4152:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4460): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4460): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4460): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4460): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4473 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4170:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4486 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4191:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4486): Binding Chromium to main looper Looper (main, tid 1) {41fe4b40}
,I/LibraryLoader( 4486): Expected native library version number "",actual native library version number ""
,I/chromium( 4486): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4486): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4486): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4486): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4486): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4486): Local Branch: 
I/Adreno-EGL( 4486): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4486): Local Patches: NONE
I/Adreno-EGL( 4486): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4486): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4486): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4486): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4486): Starting up...
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3833): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 4302:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/iu.UploadsManager( 1401): num queued entries: 0
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,I/iu.UploadsManager( 1401): num updated entries: 0
,I/iu.SyncManager( 1401): NEXT; no task
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,I/iu.UploadsManager( 3833): num queued entries: 0
,I/iu.UploadsManager( 3833): num updated entries: 0
,I/iu.SyncManager( 3833): NEXT; no task
D/MobileConnectivityChangeReceiver( 4460): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4460): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/dalvikvm( 1019): GC_EXPLICIT freed 1963K, 65% free 18106K/50780K, paused 10ms+10ms, total 109ms
,I/GAV2    ( 4486): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 ,
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH ,
D/TCMD    (  437): NL - Read 56 bytes from update socket.,
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager( 1019): sending alarm Alarm{428b88d0 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
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
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{43ccbe20 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
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
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{428b0ac8 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
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
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
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
,V/AlarmManager( 1019): sending alarm Alarm{427f7e28 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState,
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState,
,D/WifiP2pService( 1019): InactiveState{ when=-20ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-21ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-22ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{4234d960 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiP2pService( 1019): InactiveState{ when=-17ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-18ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-18ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{4393aa48 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-13ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiP2pService( 1019): DefaultState{ when=-15ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-13ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{4282fb50 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 9e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState,
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-17ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{4215e890 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428b8980 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{428b8a58 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4549 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 4342:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 11 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 11 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-19ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-19ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-19ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState,
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState,
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 12 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 12 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 13 4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 13 4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
,D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461,
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState,
,D/WifiP2pService( 1019): InactiveState{ when=-21ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-22ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-24ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{431d1e90 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-15ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-18ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiP2pService( 1019): InactiveState{ when=-20ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-20ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-23ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with,
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1150): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant( 1150): Retrying assoc: 1 
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-ASSOC-REJECT 
D/MDMCTBK (  275): Event received = CTRL-EVENT-ASSOC-REJECT 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
,I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
,I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=0
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147499
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X,
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460,
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1150): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 88 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1225032880
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-40ms what=147462 obj=android.net.wifi.StateChangeResult@42315430 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-24ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@421bab88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 14 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 14 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 15 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 15 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 13
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 13
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{43a1b958 type 3 android}
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
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
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
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
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
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
,D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450488913837 min interval config: 0 actual interval: 706821
I/CheckinService( 1401): Checking schedule, now: 1450489620661 next: 1450488943809
I/CheckinService( 1401): active receiver: enabled
,I/CheckinService( 1401): Preparing to send checkin request
,I/EventLogService( 1401): Accumulating logs since 1450488910569
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4623 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4623): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4623): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4623): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4623): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4623): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4623): install
,I/MultiDex( 4623): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4623): loading existing secondary dex files
,I/MultiDex( 4623): load found 3 secondary dex files
,I/MultiDex( 4623): install done
,D/dalvikvm( 4623): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4623): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4623): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4623): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4623): VFY: unable to resolve instance field 36
,D/dalvikvm( 4623): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4623): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4623): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4623): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4623): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4623): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41feba10
D/dalvikvm( 4623): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41feba10
,D/dalvikvm( 4623): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41feba10, skipping init
,D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41feba10
D/dalvikvm( 4623): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41feba10
,V/JNIHelp ( 4623): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41feba10
,D/dalvikvm( 4623): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41feba10
D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41feba10
,D/dalvikvm( 4623): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41feba10
,I/ProviderInstaller( 4623): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,D/LocationInitializer( 1401): Restart initialization of location
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,E/MDM     ( 1222): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,I/dalvikvm( 4623): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4623): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4623): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4623): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4623): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4623): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4623): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4623): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4623): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4623): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4623): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4623): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4623): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4623): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3008478735
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4623): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4623): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421d14c0
,D/dalvikvm( 4623): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421d14c0
,D/dalvikvm( 4623): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421d14c0, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=85427777
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4623): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4668): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4623): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4623): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 90ms
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4623): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,V/NativeCrypto( 1401): SSL shutdown failed: ssl=0x69d00cb0: I/O error during system call, Connection timed out
,I/CheckinTask( 1401): Sending checkin request (11678 bytes)
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1401): Checking schedule, now: 1450489623517 next: 1451082693510
,I/CheckinService( 1401): active receiver: disabled
,D/CheckinService( 1401): Recording last checkin time for package unspecified as 1450489623530
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): now: 1056289 ,futureTime: 65459106
,D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1056290
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/PollingManager( 1562): now: 1056314 ,futureTime: 65459106
D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1056315
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4415): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4415): Crypto mode 0 already enabled
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4460): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4460): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3833): num queued entries: 0
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/iu.UploadsManager( 3833): num updated entries: 0
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.SyncManager( 3833): NEXT; no task
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1401): num queued entries: 0
,I/iu.UploadsManager( 1401): num updated entries: 0
I/openssl ( 4415): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4415): Crypto mode 0 already enabled
I/iu.SyncManager( 1401): NEXT; no task
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4460): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4460): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429f7860 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1238): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1238): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Killing 3471:com.android.vending/u0a38 (adj 15): empty #9,
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4718 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
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
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,D/dalvikvm( 1019): GC_CONCURRENT freed 2225K, 65% free 18163K/50780K, paused 26ms+8ms, total 118ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 74ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 75ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 75ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 74ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 74ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 75ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Babel   ( 4718): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4718): MmsConfig.loadMmsSettings
I/Babel   ( 4718): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4718): MmsConfig.loadFromDatabase
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel   ( 4718): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4718): MmsConfig.loadFromResources
,E/Babel   ( 4718): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4718): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4718): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4755 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4777 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4549:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3833): GC_FOR_ALLOC freed 56K, 3% free 20654K/21288K, paused 23ms, total 27ms
,I/ActivityManager( 1019): Killing 4415:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4777): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4777): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4777): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1401): GC_CONCURRENT freed 2005K, 31% free 12015K/17224K, paused 3ms+4ms, total 47ms
,I/dalvikvm( 4777): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4777): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x01d3
,I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 222 ms] updated apps [took 222 ms] 
,I/dalvikvm( 4777): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4777): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4777): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4777): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4777): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4777): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4777): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4777): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4777): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4777): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4777): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4777): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4777): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4812 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 24ms
,I/dalvikvm( 4777): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4777): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,D/Finsky  ( 4777): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 4777): Skipping gmscore version check
,D/Finsky  ( 4777): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4777): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4777): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1019): Killing 4442:com.android.mms/u0a30 (adj 15): empty #9
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1401): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1401): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4812): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ff0fd0, skipping init
I/openssl ( 4812): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4812): Crypto mode 0 already enabled
,D/Finsky  ( 4777): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1019): Killing 4460:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4777): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1401): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1401): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450489632
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{44512b98 type 3 android}
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/Tethering( 1019): InitialState.processMessage what=4
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 528900
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService( 1019): Attempting to switch to mobile
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6122cdc0 clazz=0xc4f00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1360): Read error: ssl=0x62e1d9c8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x62e1d9c8: I/O error during system call, Broken pipe
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1295): Active network info is not available
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1295): Active network info is not available
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 54122 ms ago
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4892 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,V/MmsConfig( 4892): mnc/mcc: 
V/MmsConfig( 4892): tag: bool value: enabledMMS - true
,V/MmsConfig( 4892): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4892): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4892): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4892): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4892): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4892): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4892): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4892): tag: int value: recipientLimit - 20
V/MmsConfig( 4892): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4892): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4892): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4892): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4892): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4892): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4892): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4892): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4892): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4912 uid=10041 gids={50041, 3003}
I/ActivityManager( 1019): Killing 4473:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4912): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4912): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4912): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4912): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4925 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4486:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4938 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4623:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4938): Binding Chromium to main looper Looper (main, tid 1) {41fe3708}
,I/LibraryLoader( 4938): Expected native library version number "",actual native library version number ""
,I/chromium( 4938): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4938): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4938): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4938): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4938): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4938): Local Branch: 
I/Adreno-EGL( 4938): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4938): Local Patches: NONE
I/Adreno-EGL( 4938): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4938): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4938): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4938): Starting up...
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/ActivityManager( 1019): Killing 4718:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3833): num queued entries: 0
,I/iu.UploadsManager( 3833): num updated entries: 0
,I/iu.UploadsManager( 1401): num queued entries: 0
,I/iu.UploadsManager( 1401): num updated entries: 0
,I/iu.SyncManager( 1401): NEXT; no task
,I/iu.SyncManager( 3833): NEXT; no task
,D/MobileConnectivityChangeReceiver( 4912): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4912): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,V/AlarmManager( 1019): sending alarm Alarm{4454df88 type 2 android}
,I/GAV2    ( 4938): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1150): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 192 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  275): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1225032880
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-35ms what=147462 obj=android.net.wifi.StateChangeResult@441a7998 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-28ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@44118d80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 16 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 16 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
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
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450489623530 min interval config: 0 actual interval: 78262
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1401): Checking schedule, now: 1450489701810 next: 1450489653510
,I/CheckinService( 1401): active receiver: enabled
,I/CheckinService( 1401): Preparing to send checkin request
,I/EventLogService( 1401): Accumulating logs since 1450489620720
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1019): GC_EXPLICIT freed 2183K, 65% free 18114K/50780K, paused 3ms+9ms, total 93ms
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5046 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 5046): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5046): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5046): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5046): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5046): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 5046): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5046): install
,I/MultiDex( 5046): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5046): loading existing secondary dex files
,I/MultiDex( 5046): load found 3 secondary dex files
,I/MultiDex( 5046): install done
,D/dalvikvm( 1360): GC_EXPLICIT freed 904K, 41% free 10292K/17224K, paused 2ms+5ms, total 30ms
,D/dalvikvm( 5046): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5046): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5046): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5046): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5046): VFY: unable to resolve instance field 36
,D/dalvikvm( 5046): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5046): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5046): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5046): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5046): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5046): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5046): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe9b60
,D/dalvikvm( 5046): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe9b60
,D/dalvikvm( 5046): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe9b60, skipping init
D/dalvikvm( 5046): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe9b60
,D/dalvikvm( 5046): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe9b60
,V/JNIHelp ( 5046): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5046): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe9b60
,D/dalvikvm( 5046): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fe9b60
D/dalvikvm( 5046): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe9b60
,D/dalvikvm( 5046): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe9b60
,I/ProviderInstaller( 5046): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 1401): Restart initialization of location
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,E/MDM     ( 1222): [79] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,I/dalvikvm( 5046): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 5046): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5046): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 5046): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5046): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5046): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5046): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5046): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5046): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5046): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 5046): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5046): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 5046): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5046): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 5046): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 5046): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 5046): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=654867198
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5046): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421d6788
D/dalvikvm( 5046): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421d6788
,D/dalvikvm( 5046): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421d6788, skipping init
,D/NativeLibraryUtils( 5046): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=2236450456
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5046): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5090): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5046): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5046): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 84ms
,I/Adreno-EGL( 5046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5046): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5046): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5046): Local Branch: 
I/Adreno-EGL( 5046): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5046): Local Patches: NONE
I/Adreno-EGL( 5046): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5046): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5046): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5046): Local Branch: 
I/Adreno-EGL( 5046): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5046): Local Patches: NONE
I/Adreno-EGL( 5046): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 5046): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5046): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5046): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5046): Local Branch: 
I/Adreno-EGL( 5046): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5046): Local Patches: NONE
I/Adreno-EGL( 5046): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5046): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5046): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5046): Local Branch: 
I/Adreno-EGL( 5046): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5046): Local Patches: NONE
I/Adreno-EGL( 5046): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Sending checkin request (11678 bytes)
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): now: 1137424 ,futureTime: 65459106
,D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1137424
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): now: 1137458 ,futureTime: 65459106
,D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1137458
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4812): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4812): Crypto mode 0 already enabled
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
D/MobileConnectivityChangeReceiver( 4912): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4912): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
I/iu.UploadsManager( 3833): num queued entries: 0
I/iu.UploadsManager( 3833): num updated entries: 0
I/iu.SyncManager( 3833): NEXT; no task
I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450489623530 min interval config: 0 actual interval: 81404
I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1401): num queued entries: 0
I/iu.UploadsManager( 1401): num updated entries: 0
,I/iu.SyncManager( 1401): NEXT; no task
D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4812): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4812): Crypto mode 0 already enabled
D/MobileConnectivityChangeReceiver( 4912): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4912): onReceive CONNECTIVITY_CHANGE networkType=1
I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450489623530 min interval config: 0 actual interval: 81453
D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/dalvikvm( 1562): GC_CONCURRENT freed 1956K, 38% free 10831K/17224K, paused 2ms+5ms, total 53ms
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429f7860 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1401): Checking schedule, now: 1450489705128 next: 1451082775125
,I/CheckinService( 1401): active receiver: disabled
,I/CheckinService( 1401): Checking schedule, now: 1450489705150 next: 1451082775125
,I/CheckinService( 1401): active receiver: disabled
,D/CheckinService( 1401): Recording last checkin time for package unspecified as 1450489705157
,D/dalvikvm( 1401): GC_CONCURRENT freed 1992K, 31% free 12028K/17224K, paused 5ms+7ms, total 50ms
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
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
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1238): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1238): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Killing 4755:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5136 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/Launcher( 1309): Deferring update until onResume
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
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5136): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5136): MmsConfig.loadMmsSettings
I/Babel   ( 5136): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 5136): MmsConfig.loadFromDatabase
,E/Babel   ( 5136): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5136): MmsConfig.loadFromResources
,E/Babel   ( 5136): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5136): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 5136): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5176 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Killing 4812:android.process.media/u0a18 (adj 15): empty #9
,D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageBroadcastService( 1401): Null package name or gms related package.  Ignoreing.
,D/dalvikvm( 1019): GC_EXPLICIT freed 1378K, 65% free 18137K/50780K, paused 5ms+10ms, total 92ms
,I/ActivityManager( 1019): Killing 4892:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1401): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 403 ms] updated apps [took 403 ms] 
,I/Icing   ( 1401): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1401): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450489713
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{42591948 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{441ae3b0 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
,D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1019): InitialState.processMessage what=4
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 675326
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6122cdc0 clazz=0xebd00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1360): Read error: ssl=0x634505d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x634505d0: I/O error during system call, Broken pipe
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1295): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 139102 ms ago
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5241 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1295): Active network info is not available
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
,D/dalvikvm( 5241): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41feec28, skipping init
I/openssl ( 5241): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5241): Crypto mode 0 already enabled
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5267 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4912:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 5267): mnc/mcc: 
V/MmsConfig( 5267): tag: bool value: enabledMMS - true
,V/MmsConfig( 5267): tag: int value: maxMessageSize - 307200
V/MmsConfig( 5267): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5267): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5267): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5267): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 5267): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5267): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 5267): tag: int value: recipientLimit - 20
V/MmsConfig( 5267): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 5267): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5267): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 5267): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 5267): tag: int value: maxSubjectLength - 80
V/MmsConfig( 5267): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 5267): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 5267): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5267): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5287 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 4925:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5287): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5287): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5287): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5287): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5300 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4938:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 4ms+3ms, total 22ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5313 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5046:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 5313): Binding Chromium to main looper Looper (main, tid 1) {41fe0c38}
,I/LibraryLoader( 5313): Expected native library version number "",actual native library version number ""
,I/chromium( 5313): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5313): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5313): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5313): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5313): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5313): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5313): Local Branch: 
I/Adreno-EGL( 5313): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5313): Local Patches: NONE
I/Adreno-EGL( 5313): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5313): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 5313): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5313): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 5313): Starting up...
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/ActivityManager( 1019): Killing 5136:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.UploadsManager( 3833): num queued entries: 0
,I/iu.UploadsManager( 3833): num updated entries: 0
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,I/iu.SyncManager( 3833): NEXT; no task
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,I/iu.UploadsManager( 1401): num queued entries: 0
,I/iu.UploadsManager( 1401): num updated entries: 0
,I/iu.SyncManager( 1401): NEXT; no task
,D/MobileConnectivityChangeReceiver( 5287): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5287): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/GAV2    ( 5313): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1019): sending alarm Alarm{42329f28 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 14
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 14
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 12,
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 12
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 15
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 15
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 16
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 16
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH ,
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
,D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState,
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=-29ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-29ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-30ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
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
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState,
D/WifiStateMachine( 1019): processMsg: DriverStartedState,
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState,
,E/wpa_supplicant( 1150): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 88 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1225032880
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
D/WifiStateMachine( 1019): processMsg: DisconnectedState
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-10ms what=147462 obj=android.net.wifi.StateChangeResult@4319d510 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 17 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 17 c
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS ,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH ,
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
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
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
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
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450489705157 min interval config: 0 actual interval: 179600
I/CheckinService( 1401): Checking schedule, now: 1450489884760 next: 1450489735125
,I/CheckinService( 1401): active receiver: enabled
,I/CheckinService( 1401): Preparing to send checkin request
,I/EventLogService( 1401): Accumulating logs since 1450489701857
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5419 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 5419): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5419): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5419): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5419): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5419): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 5419): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5419): install
,I/MultiDex( 5419): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5419): loading existing secondary dex files
,I/MultiDex( 5419): load found 3 secondary dex files
,I/MultiDex( 5419): install done
,D/dalvikvm( 5419): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5419): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5419): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5419): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5419): VFY: unable to resolve instance field 36
,D/dalvikvm( 5419): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5419): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5419): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5419): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5419): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5419): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5419): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe6d80
D/dalvikvm( 5419): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe6d80
,D/dalvikvm( 5419): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe6d80, skipping init
,D/dalvikvm( 5419): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe6d80
D/dalvikvm( 5419): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe6d80
,V/JNIHelp ( 5419): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5419): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe6d80
,D/dalvikvm( 5419): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fe6d80
D/dalvikvm( 5419): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe6d80
,D/dalvikvm( 5419): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe6d80
,I/ProviderInstaller( 5419): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,E/MDM     ( 1222): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,D/LocationInitializer( 1401): Restart initialization of location
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
I/dalvikvm( 5419): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 5419): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5419): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 5419): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5419): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5419): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5419): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5419): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5419): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5419): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 5419): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5419): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 5419): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5419): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 5419): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5419): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 5419): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3362981040
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 5419): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 5419): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421fc218
D/dalvikvm( 5419): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421fc218
,D/dalvikvm( 5419): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421fc218, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=2537096946
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5419): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5466): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5419): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5419): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 81ms
,I/Adreno-EGL( 5419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5419): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5419): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5419): Local Branch: 
I/Adreno-EGL( 5419): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5419): Local Patches: NONE
I/Adreno-EGL( 5419): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5419): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5419): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5419): Local Branch: 
I/Adreno-EGL( 5419): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5419): Local Patches: NONE
I/Adreno-EGL( 5419): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 5419): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5419): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5419): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5419): Local Branch: 
I/Adreno-EGL( 5419): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5419): Local Patches: NONE
I/Adreno-EGL( 5419): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5419): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5419): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5419): Local Branch: 
I/Adreno-EGL( 5419): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5419): Local Patches: NONE
I/Adreno-EGL( 5419): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Sending checkin request (11673 bytes)
,D/dalvikvm( 1401): GC_CONCURRENT freed 2002K, 31% free 12046K/17224K, paused 3ms+4ms, total 39ms
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1019): GC_EXPLICIT freed 1744K, 65% free 18095K/50780K, paused 4ms+9ms, total 95ms
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1401): Checking schedule, now: 1450489887695 next: 1451082957692
,I/CheckinService( 1401): active receiver: disabled
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): now: 1320331 ,futureTime: 65459106
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1320333
I/openssl ( 5241): Crypto mode not selected, openssl will run on its regular mode.
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/Tethering( 1019): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1562): now: 1320348 ,futureTime: 65459106
D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1320348
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
,I/openssl ( 5241): Crypto mode 0 already enabled
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 5287): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5287): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.UploadsManager( 3833): num queued entries: 0
,I/iu.UploadsManager( 3833): num updated entries: 0
D/CheckinService( 1401): Recording last checkin time for package unspecified as 1450489887797
,I/iu.SyncManager( 3833): NEXT; no task
,D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/iu.UploadsManager( 1401): num queued entries: 0
,I/iu.UploadsManager( 1401): num updated entries: 0
,I/iu.SyncManager( 1401): NEXT; no task
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 5241): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5241): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 5287): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5287): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429f7860 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1238): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1238): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager( 1019): Killing 5176:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5511 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
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
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1309): Deferring update until onResume
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5511): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5511): MmsConfig.loadMmsSettings
I/Babel   ( 5511): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 5511): MmsConfig.loadFromDatabase
,E/Babel   ( 5511): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5511): MmsConfig.loadFromResources
,E/Babel   ( 5511): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5511): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 5511): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1360): GC_EXPLICIT freed 813K, 41% free 10287K/17224K, paused 2ms+4ms, total 31ms
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5550 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Killing 5241:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1401): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1401): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1019): Killing 5267:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 281 ms] updated apps [took 281 ms] 
,I/Icing   ( 1401): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1401): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450489896
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{428fbff8 type 3 android}
,D/Tethering( 1019): InitialState.processMessage what=4
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 716084
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6122cdc0 clazz=0x12500001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,V/NativeCrypto( 1360): Read error: ssl=0x62e2f0b8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x62e2f0b8: I/O error during system call, Broken pipe
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
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
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 18 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 18 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 19 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 19 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1295): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 33420 ms ago
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5609 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1295): Active network info is not available
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1562): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > CusSM.onRadioDown
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/dalvikvm( 5609): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41febe50, skipping init
I/openssl ( 5609): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5609): Crypto mode 0 already enabled
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5634 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5287:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 5634): mnc/mcc: 
V/MmsConfig( 5634): tag: bool value: enabledMMS - true
,V/MmsConfig( 5634): tag: int value: maxMessageSize - 307200
V/MmsConfig( 5634): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5634): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5634): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5634): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 5634): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5634): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 5634): tag: int value: recipientLimit - 20
,V/MmsConfig( 5634): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 5634): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5634): tag: bool value: enableSlideDuration - true
V/MmsConfig( 5634): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 5634): tag: int value: maxSubjectLength - 80
V/MmsConfig( 5634): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 5634): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 5634): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5634): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5654 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 5300:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5654): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5654): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5654): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5654): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm( 1265): GC_EXPLICIT freed 1100K, 45% free 9549K/17224K, paused 2ms+5ms, total 56ms
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5667 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5313:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5684 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5419:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1019): GC_EXPLICIT freed 2028K, 65% free 18181K/50780K, paused 4ms+10ms, total 91ms
,V/WebViewChromiumFactoryProvider( 5684): Binding Chromium to main looper Looper (main, tid 1) {41fe8d88}
I/LibraryLoader( 5684): Expected native library version number "",actual native library version number ""
,I/chromium( 5684): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5684): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5684): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5684): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5684): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5684): Local Branch: 
I/Adreno-EGL( 5684): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5684): Local Patches: NONE
I/Adreno-EGL( 5684): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5684): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 5684): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 5684): Starting up...
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/ActivityManager( 1019): Killing 5511:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3833): num queued entries: 0
,I/iu.UploadsManager( 3833): num updated entries: 0
,I/iu.SyncManager( 3833): NEXT; no task
,I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1401): num queued entries: 0
,I/iu.UploadsManager( 1401): num updated entries: 0
,D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.SyncManager( 1401): NEXT; no task
,W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 5654): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5654): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/GAV2    ( 5684): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 17
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 17
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10,
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 10
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.,
,D/TCMD    (  437): NL - message type is RTM_NEWLINK,
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-15ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-15ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-15ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState,
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-13ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-13ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1150): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 192 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,I/wpa_supplicant( 1150): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1225032880
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
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
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-35ms what=147462 obj=android.net.wifi.StateChangeResult@42168030 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-21ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@423376c0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-9ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4222d778 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 20 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 20 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 21 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 21 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
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
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f750
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1238): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1401): Checkin interval check for package: unspecified last checkin: 1450489887797 min interval config: 0 actual interval: 86658
,I/CheckinService( 1401): Checking schedule, now: 1450489974463 next: 1450489917692
,I/CheckinService( 1401): active receiver: enabled
,I/CheckinService( 1401): Preparing to send checkin request
,I/EventLogService( 1401): Accumulating logs since 1450489884817
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5786 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 5786): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5786): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5786): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5786): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5786): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 5786): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5786): install
,I/MultiDex( 5786): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5786): loading existing secondary dex files
,I/MultiDex( 5786): load found 3 secondary dex files
,I/MultiDex( 5786): install done
,D/dalvikvm( 5786): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5786): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5786): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5786): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5786): VFY: unable to resolve instance field 36
,D/dalvikvm( 5786): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5786): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5786): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5786): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5786): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5786): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5786): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fee968
D/dalvikvm( 5786): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fee968
,D/dalvikvm( 5786): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fee968, skipping init
,D/dalvikvm( 5786): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fee968
D/dalvikvm( 5786): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fee968
,V/JNIHelp ( 5786): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5786): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fee968
,D/dalvikvm( 5786): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fee968
D/dalvikvm( 5786): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fee968
,D/dalvikvm( 5786): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fee968
,I/ProviderInstaller( 5786): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,E/MDM     ( 1222): [108] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1401): Restart initialization of location
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,I/dalvikvm( 5786): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 5786): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5786): VFY: replacing opcode 0x6e at 0x00ce
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 5786): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5786): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5786): VFY: replacing opcode 0x6e at 0x000d
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,D/dalvikvm( 1401): GC_CONCURRENT freed 1917K, 31% free 12054K/17224K, paused 5ms+8ms, total 73ms
I/dalvikvm( 5786): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5786): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5786): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5786): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 5786): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5786): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 5786): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5786): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 5786): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 5786): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 5786): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50b0000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=2468438063
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 5786): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 5786): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e2ef8
,D/dalvikvm( 5786): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e2ef8
,D/dalvikvm( 5786): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e2ef8, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=86774929
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5786): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5827): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5786): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5786): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 77ms
,I/Adreno-EGL( 5786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5786): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5786): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5786): Local Branch: 
I/Adreno-EGL( 5786): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5786): Local Patches: NONE
I/Adreno-EGL( 5786): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5786): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5786): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5786): Local Branch: 
I/Adreno-EGL( 5786): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5786): Local Patches: NONE
I/Adreno-EGL( 5786): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 5786): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5786): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5786): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5786): Local Branch: 
I/Adreno-EGL( 5786): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5786): Local Patches: NONE
I/Adreno-EGL( 5786): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5786): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5786): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5786): Local Branch: 
I/Adreno-EGL( 5786): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5786): Local Patches: NONE
I/Adreno-EGL( 5786): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,V/NativeCrypto( 1401): SSL shutdown failed: ssl=0x69d00cb0: I/O error during system call, Connection timed out
,I/CheckinTask( 1401): Sending checkin request (11684 bytes)
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1401): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1401): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1401): Classify the device as Phone.
,I/CheckinTask( 1401): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1401): Checking schedule, now: 1450489977304 next: 1451083047297
,I/CheckinService( 1401): active receiver: disabled
,D/CheckinService( 1401): Recording last checkin time for package unspecified as 1450489977319
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/PollingManager( 1562): now: 1410058 ,futureTime: 65459106
,D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1410058
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1562): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1562): now: 1410079 ,futureTime: 65459106
D/PollingManager( 1562): Polling alarm set to expire at: 65459106 Current Time: 1410079
,D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
E/ActivityThread( 1562): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/openssl ( 5609): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 5609): Crypto mode 0 already enabled
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1562): [debug] > CusSM.onRadioUp
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 5654): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5654): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1562): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1562): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 3833): num queued entries: 0
I/iu.UploadsManager( 3833): num updated entries: 0
I/iu.SyncManager( 3833): NEXT; no task
I/iu.Environment( 1401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1401): num queued entries: 0
I/iu.UploadsManager( 1401): num updated entries: 0
D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
V/NativeCrypto( 1360): SSL handshake aborted: ssl=0x62e27008: SSL_ERROR_WANT_READ occurred. You should never see this.
W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
I/iu.SyncManager( 1401): NEXT; no task
D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 5609): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5609): Crypto mode 0 already enabled
D/MobileConnectivityChangeReceiver( 5654): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5654): onReceive CONNECTIVITY_CHANGE networkType=1
I/iu.Environment( 3833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/DEBUG   ( 1562): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1562): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1562): bindWebServices(): registering our AIDL callback...
I/SundryService( 1562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1562): onServiceConnected()
,D/GetNotificationsWS( 1562): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1562): ServiceHandler.handleMessage: mWaitCount=0
D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
,D/GetNotificationsWS( 1562): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1562): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1562
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1562): [info] > Updatetime from metadata: 10
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1562): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1562): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{429f7860 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/dalvikvm( 1562): GC_CONCURRENT freed 2097K, 38% free 10767K/17224K, paused 2ms+5ms, total 40ms
,V/AlarmManager( 1019): sending alarm Alarm{42813bf0 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42ce6978 type 3 android}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1238): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1238): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1238): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1238): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Killing 5550:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5876 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 32ms
,I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1019):   Scheme: "sms"
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 28ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1309): Deferring update until onResume
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
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5876): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5876): MmsConfig.loadMmsSettings
I/Babel   ( 5876): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 5876): MmsConfig.loadFromDatabase
,E/Babel   ( 5876): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5876): MmsConfig.loadFromResources
,E/Babel   ( 5876): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5876): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 5876): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5914 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/dalvikvm( 1019): GC_EXPLICIT freed 2043K, 65% free 18231K/50780K, paused 5ms+11ms, total 110ms
I/ActivityManager( 1019): Killing 5609:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1401): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1401): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager( 1019): Killing 5634:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 306 ms] updated apps [took 306 ms] 
,I/Icing   ( 1401): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1401): GC_CONCURRENT freed 1931K, 30% free 12171K/17224K, paused 5ms+5ms, total 46ms
,D/dalvikvm( 1401): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/Icing   ( 1401): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450489986
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1019): sending alarm Alarm{420d2f78 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{441875f8 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 18
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 18
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 19
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 19
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 20
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 20
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 21
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 21
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 11
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 11
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
,V/AlarmManager( 1019): sending alarm Alarm{44111b10 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43e84a70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43e50470 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ccbe20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42877e08 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 27ms
,I/ProcessStatsService( 1019): Prepared write state in 24ms
,I/ProcessStatsService( 1019): Prepared write state in 16ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-18-14-27-06.bin
,V/AlarmManager( 1019): sending alarm Alarm{43a756b0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{43a75770 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43a757c0 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{43a75810 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 416208 ms ago
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5963 uid=10015 gids={50015, 1028}
,I/EventLogService( 1401): Aggregate from 1450489974519 (log), 1450488314126 (data)
,I/ActivityManager( 1019): Killing 5654:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1274): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{421730a8 type 3 com.google.android.gms}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1360): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1360): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1360): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1360): VFY: replacing opcode 0x1f at 0x0011
,I/dalvikvm( 1360): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1360): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1360): VFY: replacing opcode 0x6e at 0x003d
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
,V/AlarmManager( 1019): sending alarm Alarm{42162770 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{445434b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{421971e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44107ee0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4283b0a0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6007): 
D/AndroidRuntime( 6007): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6007): CheckJNI is OFF
D/dalvikvm( 6007): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6007): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6007): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6007): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6007): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 6007): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 6007): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6007): failed to load memtrack module: -2
D/AndroidRuntime( 6007): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10497 user=-1: uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{422be1d0 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10497 user=0: pkg removed
D/dalvikvm( 2282): GC_EXPLICIT freed 5923K, 44% free 9677K/17224K, paused 4ms+5ms, total 40ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450490711
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/VoicemailCleanupService( 3765): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm( 1401): GC_EXPLICIT freed 508K, 31% free 11947K/17224K, paused 3ms+7ms, total 127ms
W/SQLiteConnectionPool( 1401): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2314): GC_EXPLICIT freed 4550K, 42% free 10103K/17224K, paused 2ms+13ms, total 143ms
D/dalvikvm( 1309): GC_EXPLICIT freed 3638K, 33% free 11601K/17224K, paused 2ms+23ms, total 152ms
I/Launcher( 1309): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 1832K, 65% free 18172K/50780K, paused 5ms+12ms, total 144ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 48ms
D/dalvikvm( 1019): GC_EXPLICIT freed 91K, 65% free 18081K/50780K, paused 4ms+8ms, total 85ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2314): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6036 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1207): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450490712
I/Launcher( 1309): Deferring update until onResume
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10497 #1
D/AndroidRuntime( 6007): Shutting down VM
D/dalvikvm( 6007): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/InternalIcingCorporaPro( 2314): UpdateCorporaTask done [took 109 ms] updated apps [took 108 ms] 
W/ActiveOrDefaultContextProvider( 6036): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 6036): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6067 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 6067): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1401): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1401): Clearing selected account for com.test.thalitest
I/dalvikvm( 4777): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4777): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4777): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1401): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1401): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1401): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1401): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ChimeraCfgMgr( 1401): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1401): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 1401): disk I/O error (code 3850)
E/DriveAsyncService( 1401): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1401): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1401): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1401): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1401): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1401): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1401): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1401): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1401): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1401): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1401): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1401): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1401): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1401): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1360): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1360): Shutting down VM
W/dalvikvm( 1360): threadid=1: thread exiting with uncaught exception (group=0x41715d40)
E/SQLiteLog( 1401): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1401): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1401): threadid=50: thread exiting with uncaught exception (group=0x41715d40)
E/SQLiteDatabase( 1401): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1401): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1401): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1401): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1401): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1401): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1401): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1401): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1401): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1401): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1401): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1401): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1401): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1401): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1401): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1401): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1401): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1401): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1401): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1401): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1401): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1401): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1401): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1401): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1401): Runtime exception while performing operation
E/ClearPendingStateOp( 1401): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1401): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1401): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1401): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1401): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1401): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1401): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1401): 	at java.lang.Thread.run(Thread.java:841)
E/GMPM-SVC( 1401): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteOpenHelper( 1401): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1401): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1401): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1401): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1401): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1401): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1401): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1401): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1401): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1401): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1401): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1401): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
F/ClearPendingStateOp( 1401): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1401): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1401): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1401): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1401): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1401): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1401): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1401): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1401): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1401): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 1401): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 1401): Process: com.google.android.gms, PID: 1401
E/AndroidRuntime( 1401): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1401): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1401): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1401): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1401): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1401): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1401): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1401): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1401): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1401): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 1401): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/AndroidRuntime( 1401): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1401): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1401): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1401): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1401): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1401): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1401): 	at java.lang.Thread.run(Thread.java:841)
I/dalvikvm( 1401): Jit: resizing JitTable from 4096 to 8192
E/SQLiteLog( 1401): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1401): threadid=54: thread exiting with uncaught exception (group=0x41715d40)
I/Icing   ( 1401): doRemovePackageData com.test.thalitest
I/Process ( 1401): Sending signal. PID: 1401 SIG: 9
E/AndroidRuntime( 1360): FATAL EXCEPTION: main
E/AndroidRuntime( 1360): Process: com.google.process.gapps, PID: 1360
E/AndroidRuntime( 1360): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1360): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1360): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1360): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1360): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1360): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1360): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1360): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1360): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1360): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1360): 	... 10 more

```
