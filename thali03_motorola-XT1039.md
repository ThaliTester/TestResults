#### Test 5615109370bee58_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1006): sending alarm Alarm{4400ef40 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4254): 
D/AndroidRuntime( 4254): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4254): CheckJNI is OFF
D/dalvikvm( 4254): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4254): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4254): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4254): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4254): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4254): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4254): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4254): failed to load memtrack module: -2
D/AndroidRuntime( 4254): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1006): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4254
W/WindowManager( 1006): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1006): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4270 uid=10122 gids={50122, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4254): Shutting down VM
D/dalvikvm( 4254): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4270): Binding Chromium to main looper Looper (main, tid 1) {41fbd7c0}
I/LibraryLoader( 4270): Expected native library version number "",actual native library version number ""
I/chromium( 4270): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4270): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1006): Message: 20
D/BluetoothManagerService( 1006): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441d54d8:true
I/Adreno-EGL( 4270): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4270): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4270): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4270): Local Branch: 
I/Adreno-EGL( 4270): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4270): Local Patches: NONE
I/Adreno-EGL( 4270): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4270): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4270): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4270): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4270): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4270): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4270): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4270): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4270): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4270): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4270): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4270): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4270): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4270): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4270): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4270): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4270): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4270): Enabling debug mode 0
,W/AwContents( 4270): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1222): onFinishInput()
,I/LaunchCheckinHandler( 1006): Displayed com.test.thalitest/.MainActivity,cp,ca,432
I/ActivityManager( 1006): Displayed com.test.thalitest/.MainActivity: +404ms (total +432ms)
W/AwContents( 4270): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4270): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4270): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4270): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fc3f98
,D/dalvikvm( 4270): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fc3f98
,D/jxcore_app_log( 4270): JniHelper::setJavaVM(0x4160efa8), pthread_self() = 1615072192
,D/JX-Cordova( 4270): jxcore cordova android initializing
,D/dalvikvm( 4270): GC_CONCURRENT freed 2655K, 16% free 14534K/17224K, paused 3ms+3ms, total 44ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 417K, 14% free 14889K/17224K, paused 28ms, total 29ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 105K, 14% free 14896K/17224K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.640MB for 63974-byte allocation
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 127K, 14% free 14916K/17288K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.690MB for 95956-byte allocation
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 180K, 14% free 14951K/17384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.770MB for 143930-byte allocation
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 253K, 15% free 14997K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 16.884MB for 215890-byte allocation
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 368K, 16% free 15072K/17740K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 17.060MB for 323830-byte allocation
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 568K, 16% free 15192K/18060K, paused 28ms, total 28ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 864K, 15% free 15369K/18060K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 17.736MB for 728606-byte allocation
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 1283K, 17% free 15624K/18772K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 18.333MB for 1092904-byte allocation
,D/dalvikvm( 4270): GC_CONCURRENT freed 1912K, 20% free 16032K/19840K, paused 1ms+6ms, total 46ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 55K, 20% free 16026K/19840K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 19.246MB for 1639352-byte allocation
,D/dalvikvm( 4270): GC_CONCURRENT freed 2053K, 23% free 16552K/21444K, paused 1ms+6ms, total 56ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 963K, 24% free 16510K/21444K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 20.500MB for 2459024-byte allocation
,D/dalvikvm( 4270): GC_CONCURRENT freed 1873K, 28% free 17313K/23848K, paused 2ms+4ms, total 40ms
,D/dalvikvm( 4270): GC_CONCURRENT freed 2540K, 27% free 17544K/23848K, paused 2ms+7ms, total 52ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 191K, 27% free 17455K/23848K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4270): Grow heap (frag case) to 22.596MB for 3688532-byte allocation
,D/dalvikvm( 4270): GC_CONCURRENT freed 2667K, 33% free 18532K/27452K, paused 2ms+5ms, total 45ms
,D/dalvikvm( 4270): GC_FOR_ALLOC freed 1996K, 32% free 18670K/27452K, paused 33ms, total 33ms
,W/jxcore-log( 4270): Initializing JXcore engine
,W/jxcore-log( 4270): JXcore engine is ready
,D/dalvikvm( 4270): GC_CONCURRENT freed 420K, 22% free 21473K/27452K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 4270): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4270): Starting JXcore engine
,W/jxcore-log( 4270): Platform android
W/jxcore-log( 4270): 
,W/jxcore-log( 4270): Process ARCH arm
W/jxcore-log( 4270): 
,I/jxcore-log( 4270): JXcore Cordova bridge is ready!
I/jxcore-log( 4270): 
,W/jxcore-log( 4270): JXcore engine is started
,I/chromium( 4270): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4270): Toggling radios to true
I/jxcore-log( 4270): 
,D/BluetoothAdapter( 4270): enable(): BT is already enabled..!
D/WifiService( 1006): New client listening to asynchronous messages
D/WifiService( 1006): setWifiEnabled: true pid=4270, uid=10122
,E/WifiService( 1006): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1006): handleMessage: E msg.what=131145
D/WifiStateMachine( 1006): processMsg: ConnectedState
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
I/jxcore-log( 4270): Radios toggled
I/jxcore-log( 4270): 
I/jxcore-log( 4270): My device name is: motorola-XT1039
I/jxcore-log( 4270): 
,I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276):  STA Disconnected !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
,D/Tethering( 1006): InitialState.processMessage what=4
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,V/ConnectivityService( 1006): WiFi NOT Tethered!
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/Tethering( 1006): sendTetherStateChangedBroadcast 0, 0, 0
D/TCMD    (  381): NL - Read 1000 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/WifiStateMachine( 1006): transitionTo: destState=DisconnectingState
D/TCMD    (  381): NL - Read 1000 bytes from update socket.
D/WifiStateMachine( 1006): handleMessage: new destination call exit/enter
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 68 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 68 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/WifiStateMachine( 1006): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1006): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1006): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1006): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1006): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1006): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1006): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  381): NL - Read 60 bytes from update socket.
D/TCMD    (  381): NL - ignore NL message, type = 21
,D/TCMD    (  381): Listening for incoming client connection request
,D/WifiStateMachine( 1006): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1006): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1006): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1006): connected time updated 311126
,D/ConnectivityService( 1006): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1006): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1006): Attempting to switch to mobile
D/ConnectivityService( 1006): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1006): Attempting to switch to ETHERNET
,D/ConnectivityService( 1006): resetConnections(wlan0, 3)
D/NetUtils( 1006): android_net_utils_resetConnections in env=0x61664d08 clazz=0x62200001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1006): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1006): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1006): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1006): DisconnectingState
D/Checkin ( 1006): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=131146
D/WifiStateMachine( 1006): processMsg: DisconnectingState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,V/NativeCrypto( 1388): Read error: ssl=0x62fedfc8: I/O error during system call, Connection timed out
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=131101
D/WifiStateMachine( 1006): processMsg: DisconnectingState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): processMsg: DriverStartedState
D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
D/WifiStateMachine( 1006): processMsg: DefaultState
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=147460
D/WifiStateMachine( 1006): processMsg: DisconnectingState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): Network connection lost
D/WifiStateMachine( 1006): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1006): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1388): SSL shutdown failed: ssl=0x62fedfc8: I/O error during system call, Broken pipe
,D/WifiP2pService( 1006): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1006): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1006): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1006): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1006): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1006): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1006): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1006): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1006): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1006): invokeEnterMethods: DisconnectedState
D/Checkin ( 1006): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=131216
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): processMsg: DriverStartedState
D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
D/WifiStateMachine( 1006): processMsg: DefaultState
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=131216
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): processMsg: DriverStartedState
D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
D/WifiStateMachine( 1006): processMsg: DefaultState
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): handleMessage: X
,D/Nat464Xlat( 1006): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1207): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1006): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1207): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1207): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1006): Attempting to switch to mobile
D/ConnectivityService( 1006): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1006): Attempting to switch to ETHERNET
D/Nat464Xlat( 1006): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1006): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1207): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1207): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1207): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1161): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147461
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
E/wpa_supplicant( 1161): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  381): NL - Read 56 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
,D/TCMD    (  381): Listening for incoming client connection request
D/WifiStateMachine( 1006): processMsg: DriverStartedState
,D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/WifiStateMachine( 1006): handleMessage: X
,I/wpa_supplicant( 1161): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1161): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  381): NL - Read 312 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 192 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 68 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
,D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 1000 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
,D/TCMD    (  381): Listening for incoming client connection request
I/wpa_supplicant( 1161): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  381): NL - Read 80 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 80 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/TCMD    (  381): NL - Read 68 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1006): processMsg: DisconnectedState
,D/WifiStateMachine( 1006): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/WifiStateMachine( 1006): handleMessage: X
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1161): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  381): NL - Read 1000 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  276): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  276): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197982896
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1006): processMsg: DisconnectedState
D/WifiStateMachine( 1006): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147459
,D/Tethering( 1006): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1006): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1006): processMsg: DisconnectedState
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/WifiStateMachine( 1006): Network connection established
,D/WifiStateMachine( 1006): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1006): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1006): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1006): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1006): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1006): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1006): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1006): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1006): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1006): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147462
D/WifiStateMachine( 1006): processMsg: ObtainingIpState
D/WifiStateMachine( 1006): ObtainingIpState{ when=-36ms what=147462 obj=android.net.wifi.StateChangeResult@43cf0ef8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1006): processMsg: L2ConnectedState
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=131101
D/WifiStateMachine( 1006): processMsg: ObtainingIpState
D/WifiStateMachine( 1006): ObtainingIpState{ when=-34ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43cc3c30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): processMsg: DriverStartedState
D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
D/WifiStateMachine( 1006): processMsg: DefaultState
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=196612
D/WifiStateMachine( 1006): processMsg: ObtainingIpState
D/WifiStateMachine( 1006): ObtainingIpState{ when=-9ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
,D/WifiStateMachine( 1006): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1006): Unexpected BatchedScanResults :OK
,D/WifiP2pService( 1006): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427d94d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1006): handleMessage: X
D/WifiP2pService( 1006): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427d94d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  381): NL - Read 56 bytes from update socket.
D/TCMD    (  381): NL - message type is RTM_NEWLINK
D/TCMD    (  381): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1006): handleMessage: E msg.what=147461
D/WifiStateMachine( 1006): processMsg: ObtainingIpState
,D/WifiStateMachine( 1006): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
,D/WifiP2pService( 1006): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): processMsg: DriverStartedState
,D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
D/WifiP2pService( 1006): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1006): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1006): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43beebe8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1006): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@43beebe8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1006): handleMessage: X
D/WifiP2pService( 1006): DefaultState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@43beebe8 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  381): NL - Read 60 bytes from update socket.
D/TCMD    (  381): NL - ignore NL message, type = 20
,D/TCMD    (  381): Listening for incoming client connection request
,D/WifiStateMachine( 1006): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1006): handleMessage: E msg.what=131215
D/WifiStateMachine( 1006): processMsg: ObtainingIpState
D/WifiStateMachine( 1006): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
,D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): processMsg: DriverStartedState
D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1006): processMsg: DefaultState
D/WifiStateMachine( 1006): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=196613
D/WifiStateMachine( 1006): processMsg: ObtainingIpState
D/WifiStateMachine( 1006): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
,D/WifiStateMachine( 1006): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1006): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1006): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1006): DHCP successful
D/WifiStateMachine( 1006): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1006): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1006): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1006): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1006): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1006): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1006): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1006): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1006): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1006): VerifyingLinkState enter
D/WifiStateMachine( 1006): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=151572
D/WifiStateMachine( 1006): processMsg: VerifyingLinkState
D/WifiStateMachine( 1006): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1006): handleMessage: X
,D/WifiStateMachine( 1006): handleMessage: E msg.what=135190
D/WifiStateMachine( 1006): processMsg: VerifyingLinkState
D/WifiStateMachine( 1006): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1006): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1006): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1006): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1006): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1006): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1006): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1006): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1006): CaptivePortalCheckState enter
,D/WifiStateMachine( 1006): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1006): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1006): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1006): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1006): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=131092
D/WifiStateMachine( 1006): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1006): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1006): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1006): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1006): WiFi NOT Tethered!
,E/ConnectivityService( 1006): Unexpected mtu value: android.net.wifi.WifiStateTracker@4208c858
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1006): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1006): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1006): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1006): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1006): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1006): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1006): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1006): handleMessage: X
D/WifiStateMachine( 1006): handleMessage: E msg.what=131092
D/WifiStateMachine( 1006): processMsg: ConnectedState
D/WifiStateMachine( 1006): processMsg: L2ConnectedState
D/WifiStateMachine( 1006): processMsg: ConnectModeState
D/WifiStateMachine( 1006): processMsg: DriverStartedState
D/WifiStateMachine( 1006): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1006): processMsg: DefaultState
D/WifiStateMachine( 1006): handleMessage: X
,D/Checkin ( 1006): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/Nat464Xlat( 1006): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1207): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1207): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1207): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1006): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1006): WiFi NOT Tethered!
E/ConnectivityService( 1006): Unexpected mtu value: android.net.wifi.WifiStateTracker@4208c858
,D/ConnectivityService( 1006): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1006): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1207): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1207): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1207): onReceive() - done, currentInetCondition=0
,D/Tethering( 1006): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1291): No entry in secure settings for enhanced location services: false
D/CaptivePortalTracker( 1006): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1092): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,D/ConnectivityService( 1006): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/ActivityManager( 1006): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4387 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
W/XTWiFiOS( 1291): No entry in secure settings for enhanced location services: false
D/PollingManager( 1628): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1006): MasterInitialState.processMessage what=3
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/CaptivePortalTracker( 1006): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1628): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1628): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1628): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1628): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1628): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/OtaApp  ( 1628): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1628): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/dalvikvm( 4387): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fc7a40, skipping init
I/openssl ( 4387): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4387): Crypto mode 0 already enabled
I/ActivityManager( 1006): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4412 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1006): Killing 3957:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4412): mnc/mcc: 
V/MmsConfig( 4412): tag: bool value: enabledMMS - true
,V/MmsConfig( 4412): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4412): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4412): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4412): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4412): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4412): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4412): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4412): tag: int value: recipientLimit - 20
V/MmsConfig( 4412): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4412): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4412): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4412): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4412): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4412): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4412): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4412): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4412): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1006): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4432 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1006): Killing 4082:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+4ms, total 29ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,D/MobileConnectivityChangeReceiver( 4432): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4432): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4432): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4432): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,I/ActivityManager( 1006): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4447 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1006): Killing 4131:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1762): Checkin interval check for package: unspecified last checkin: 1453126512809 min interval config: 0 actual interval: 296308
,I/CheckinService( 1762): Checking schedule, now: 1453126809129 next: 1453126542790
,I/CheckinService( 1762): active receiver: enabled
,I/CheckinService( 1762): Preparing to send checkin request
,I/EventLogService( 1762): Accumulating logs since 1453126509008
,I/CheckinRequestBuilder( 1762): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1762): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4447): Binding Chromium to main looper Looper (main, tid 1) {41fb8d68}
,I/LibraryLoader( 4447): Expected native library version number "",actual native library version number ""
,I/chromium( 4447): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4447): Initializing chromium process, renderers=0
,D/dalvikvm( 1006): GC_EXPLICIT freed 25293K, 66% free 18739K/53572K, paused 4ms+10ms, total 149ms
,E/AudioManagerAndroid( 4447): BLUETOOTH permission is missing!
D/ConnectivityService( 1006): NetTransition Wakelock for ConnectedState released by timeout
,I/Adreno-EGL( 4447): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4447): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4447): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4447): Local Branch: 
I/Adreno-EGL( 4447): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4447): Local Patches: NONE
I/Adreno-EGL( 4447): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4447): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4447): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4447): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1006): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4482 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4482): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4482): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4482): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4482): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4482): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4482): install
,I/MultiDex( 4482): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4482): loading existing secondary dex files
,I/MultiDex( 4482): load found 3 secondary dex files
,I/MultiDex( 4482): install done
,D/dalvikvm( 4482): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4482): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4482): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4482): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4482): VFY: unable to resolve instance field 36
,D/dalvikvm( 4482): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4482): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4482): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4482): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4482): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4482): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4482): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbee58
D/dalvikvm( 4482): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbee58
,D/dalvikvm( 4482): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbee58, skipping init
,D/dalvikvm( 4482): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fbee58
D/dalvikvm( 4482): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fbee58
,V/JNIHelp ( 4482): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4482): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fbee58
,D/dalvikvm( 4482): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fbee58
D/dalvikvm( 4482): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fbee58
,D/dalvikvm( 4482): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fbee58
,I/NSApplication( 4447): Starting up...
,I/ActivityManager( 1006): Killing 3851:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1006): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4503 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4482): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4482): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4482): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4482): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4482): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4482): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4482): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4482): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4482): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4482): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4482): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4503): VFY: unable to resolve instance field 68
D/dalvikvm( 4503): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4503): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4503): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,W/dalvikvm( 4482): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4482): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4482): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4482): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4482): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/openssl ( 4387): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4387): Crypto mode 0 already enabled
,D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4503): VFY: unable to resolve instance field 68
,D/dalvikvm( 4503): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4503): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4503): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4503): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4503): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/MobileConnectivityChangeReceiver( 4432): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4432): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager( 1006): Killing 4170:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5123000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5123000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/DEBUG   ( 1628): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,W/ContextImpl( 1628): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1628): bindWebServices(): registering our AIDL callback...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/SundryService( 1628): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1628): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1628): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1628): onServiceConnected()
D/GetNotificationsWS( 1628): onServiceConnected(): Registered for remote service callbacks...
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/GetNotificationsWS( 1628): unbindWebServices(): un-registering our AIDL callback...
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/WearableService( 1235): callingUid 10022, callindPid: 1235
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,E/MDM     ( 1235): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1388): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1388): Proximity feature is not enabled.
D/LocationInitializer( 1762): Restart initialization of location
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  280): PrepareKeyRequest: nonce=1500522024
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/GCoreFlp( 1235): No location to return for getLastLocation()
,W/FusedLocationProvider( 1235): location=null
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4270): 
,D/NativeLibraryUtils( 4482): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4482): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421a9350
D/dalvikvm( 4482): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421a9350
,D/dalvikvm( 4482): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421a9350, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4482): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4537): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4482): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4482): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 94ms
,I/Adreno-EGL( 4482): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4482): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4482): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4482): Local Branch: 
I/Adreno-EGL( 4482): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4482): Local Patches: NONE
I/Adreno-EGL( 4482): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4482): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4482): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4482): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4482): Local Branch: 
I/Adreno-EGL( 4482): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4482): Local Patches: NONE
I/Adreno-EGL( 4482): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4270): 
,W/Settings( 4482): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
D/WVCdm   (  280): PrepareKeyRequest: nonce=3801424530
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4482): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4482): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4482): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4482): Local Branch: 
I/Adreno-EGL( 4482): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4482): Local Patches: NONE
I/Adreno-EGL( 4482): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/Tethering( 1006): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1006): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1291): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/PollingManager( 1628): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1628): now: 343726 ,futureTime: 46522646
,D/PollingManager( 1628): Polling alarm set to expire at: 46522646 Current Time: 343727
,E/ActivityThread( 1628): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1628): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1628): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1628): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/Tethering( 1006): MasterInitialState.processMessage what=3
,D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1628): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,I/Adreno-EGL( 4482): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4482): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4482): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4482): Local Branch: 
I/Adreno-EGL( 4482): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4482): Local Patches: NONE
I/Adreno-EGL( 4482): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
D/CaptivePortalTracker( 1006): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1628): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1628): now: 343791 ,futureTime: 46522646
D/PollingManager( 1628): Polling alarm set to expire at: 46522646 Current Time: 343793
W/XTWiFiOS( 1291): No entry in secure settings for enhanced location services: false
D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
E/ActivityThread( 1628): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1628): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/openssl ( 4387): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4387): Crypto mode 0 already enabled
D/OtaApp  ( 1628): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4432): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4432): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1628): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1628): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/CheckinService( 1762): Checkin interval check for package: unspecified last checkin: 1453126512809 min interval config: 0 actual interval: 298735
,D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1628): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1628): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 1628): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DEBUG   ( 1628): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 1628): GC_CONCURRENT freed 6394K, 38% free 10733K/17224K, paused 2ms+5ms, total 52ms
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,W/ContextImpl( 1628): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1628): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1628): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1628): onServiceConnected()
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/GetNotificationsWS( 1628): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1628): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1628): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1628): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4387): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4387): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4432): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4432): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1762): Checkin interval check for package: unspecified last checkin: 1453126512809 min interval config: 0 actual interval: 298857
,D/DEBUG   ( 1628): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/jxcore-log( 4270): Test app app.js loaded
I/jxcore-log( 4270): 
,I/dalvikvm( 4270): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4270): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4270): VFY: replacing opcode 0x6e at 0x0002
,W/ContextImpl( 1628): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1628): bindWebServices(): registering our AIDL callback...
I/SundryService( 1628): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1628): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1628): onServiceConnected()
,D/GetNotificationsWS( 1628): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1628): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1628): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4270): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4270): BLE advertisement is supported
I/jxcore-log( 4270): 
,D/OtaApp  ( 1628): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1006): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1628
,I/chromium( 4270): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1628): unbindWebServices(): un-registering our AIDL callback...
I/CheckinRequestBuilder( 1762): Classify the device as Phone.
,D/OtaApp  ( 1628): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1628): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1628): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1628): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1628): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1628): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1628): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1628): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1006): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1628
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1628): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1628): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1628): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1628): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1628): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1628): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1628): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1628): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1222): onFinishInput()
,W/IInputConnectionWrapper( 4270): showStatusIcon on inactive InputConnection
I/ActivityManager( 1006): Activity reported stop, but no longer stopping: ActivityRecord{41fb2178 u0 com.motorola.ccc.ota/.ui.DownloadActivity t2}
,I/LaunchCheckinHandler( 1006): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,166
,I/jxcore-log( 4270): --= Surplus to requirements =--
I/jxcore-log( 4270): 
I/jxcore-log( 4270): ****TEST TOOK:  ms ****
I/jxcore-log( 4270): 
,I/jxcore-log( 4270): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4270): 
,I/CheckinTask( 1762): Sending checkin request (11752 bytes)
,D/AndroidRuntime( 4577): 
D/AndroidRuntime( 4577): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4577): CheckJNI is OFF
,D/dalvikvm( 4577): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4577): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4577): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4577): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4577): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4577): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,I/CheckinRequestBuilder( 1762): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1762): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1762): Classify the device as Phone.
,E/memtrack( 4577): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4577): failed to load memtrack module: -2
,I/CheckinTask( 1762): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/dalvikvm( 1762): GC_CONCURRENT freed 1782K, 30% free 12101K/17224K, paused 6ms+6ms, total 42ms
,I/CheckinService( 1762): Checking schedule, now: 1453126812556 next: 1453676466549
,I/CheckinService( 1762): active receiver: disabled
,D/AndroidRuntime( 4577): Calling main entry com.android.commands.pm.Pm
,I/CheckinService( 1762): Checking schedule, now: 1453126812575 next: 1453676466549
,I/CheckinService( 1762): active receiver: disabled
,D/CheckinService( 1762): Recording last checkin time for package unspecified as 1453126812581
I/ActivityManager( 1006): Force stopping com.test.thalitest appid=10122 user=-1: uninstall pkg
I/ActivityManager( 1006): Killing 4270:com.test.thalitest/u0a122 (adj 9): stop com.test.thalitest
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1006):   Force finishing activity ActivityRecord{44768c88 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1006): WIN DEATH: Window{446a5470 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1006): Client connection lost with reason: 4
,I/ActivityManager( 1006): Force stopping com.test.thalitest appid=10122 user=0: pkg removed
,I/Keyboard.Facilitator( 1222): resetDictionaries() : en_GB
,I/Keyboard.Facilitator.DecoderInitializer( 1222): run()
,I/Decoder ( 1222): createOrResetDecoder
,W/GeofencerStateMachine( 1235): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1006): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "sms"
D/VoicemailCleanupService( 1192): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2335): GC_EXPLICIT freed 5161K, 44% free 9647K/17224K, paused 2ms+6ms, total 52ms
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "smsto"
,D/dalvikvm( 1306): GC_EXPLICIT freed 3253K, 33% free 11596K/17224K, paused 2ms+5ms, total 68ms
,I/Launcher( 1306): Deferring update until onResume
,D/dalvikvm( 2371): GC_EXPLICIT freed 2771K, 43% free 9819K/17224K, paused 2ms+3ms, total 87ms
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1006):   Scheme: "mms"
D/BackupManagerService( 1006): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1006): removePackageParticipantsLocked: uid=10122 #1
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "mmsto"
,I/ConfigService( 1235): onCreate
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "sms"
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "smsto"
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "mms"
,I/ActivityManager( 1006): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4609 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1006): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1006):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1006):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1006):   Scheme: "mmsto"
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): run()
,I/Launcher( 1306): Deferring update until onResume
,D/dalvikvm( 1006): GC_EXPLICIT freed 1578K, 65% free 18861K/53572K, paused 6ms+17ms, total 158ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = contacts
,I/InternalIcingCorporaPro( 2371): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1222): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1222): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1222): run()
,I/ActivityManager( 1006): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4627 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/StatsUtilsManager( 1222): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1222): shouldRecordStats() = Too Soon
,D/AndroidRuntime( 4577): Shutting down VM
,D/dalvikvm( 4577): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/ActivityManager( 1006): Killing 4202:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 4627): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1762): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1762): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1762): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1762): Module APK com.google.android.play.games already loaded
I/dalvikvm( 3604): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3604): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3604): VFY: replacing opcode 0x6e at 0x0013
,D/ChimeraCfgMgr( 1762): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/LocationSettingsChecker( 1762): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraModuleLdr( 1762): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1388): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1388): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1762): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1762): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1762): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1762): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Icing   ( 1762): doRemovePackageData com.test.thalitest
,D/gH_CompatibleDatabase( 1762): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1762): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1762): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1762): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1762): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1762): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1762): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1762): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1762): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 1006): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4654 uid=10059 gids={50059, 1028, 3003, 1015}
,I/ActivityManager( 1006): Killing 4387:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2371): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
,I/dalvikvm( 4654): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
,W/dalvikvm( 4654): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x001b
,I/dalvikvm( 4654): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 4654): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4654): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4654):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4654):   adb logcat -s GAv4
,W/GAv4    ( 4654): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SQLiteDatabase( 4654): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4654): 	at avm.getWritableDatabase(PG:244)
E/SQLiteDatabase( 4654): 	at avc.a(PG:1573)
E/SQLiteDatabase( 4654): 	at jep$b.a(PG:131)
E/SQLiteDatabase( 4654): 	at ave.run(PG:588)
,W/dalvikvm( 4654): threadid=11: thread exiting with uncaught exception (group=0x416edd40)
I/dalvikvm( 4654): Could not find method android.app.Activity.finishAfterTransition, referenced from method ce.onBackPressed
W/dalvikvm( 4654): VFY: unable to resolve virtual method 1245: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x0012
E/CAKEMIX_CRASHED( 4654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/CAKEMIX_CRASHED( 4654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/CAKEMIX_CRASHED( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/CAKEMIX_CRASHED( 4654): 	at avm.getWritableDatabase(PG:244)
E/CAKEMIX_CRASHED( 4654): 	at avc.a(PG:1573)
E/CAKEMIX_CRASHED( 4654): 	at jep$b.a(PG:131)
E/CAKEMIX_CRASHED( 4654): 	at ave.run(PG:588)
,W/GAv4    ( 4654): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4654): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4654): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4654): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4654): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager( 1006): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from pid 4654
W/WindowManager( 1006): Not okToDisplay, so not showing Starting Window
E/SQLiteDatabase( 4654): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4654): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4654): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4654): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4654): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4654): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4654): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4654): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4654): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4654): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4654): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4654): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4654): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4654): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4654): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Process ( 4654): Sending signal. PID: 4654 SIG: 9
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
E/SQLiteLog( 2335): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2335): Error inserting state=component=com.google.android.apps.docs/.app.ErrorNotificationActivity event=am_restart_activity timestamp=1453126813338 timezone=3600 name=PauseResumeTrigger
E/SQLiteDatabase( 2335): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2335): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2335): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2335): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2335): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1006): Process com.google.android.apps.docs (pid 4654) has died.
,W/WindowManager( 1006): Not okToDisplay, so not showing Starting Window
E/SQLiteLog( 2335): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2335): Error inserting state=component=com.google.android.apps.docs/.app.ErrorNotificationActivity event=am_pause_activity timestamp=1453126813340 timezone=3600 name=PauseResumeTrigger
E/SQLiteDatabase( 2335): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2335): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2335): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2335): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2335): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2335): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2335): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1006): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=4681 uid=10059 gids={50059, 1028, 3003, 1015}
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 

```
