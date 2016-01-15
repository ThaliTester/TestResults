#### Test 56151093f3290d6_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = ,
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4202): 
D/AndroidRuntime( 4202): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4202): CheckJNI is OFF
D/dalvikvm( 4202): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4202): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4202): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4202): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4202): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4202): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4202): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4202): failed to load memtrack module: -2
D/AndroidRuntime( 4202): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4202
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4218 uid=10113 gids={50113, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4202): Shutting down VM
D/dalvikvm( 4202): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4218): Binding Chromium to main looper Looper (main, tid 1) {425fdb80}
I/LibraryLoader( 4218): Expected native library version number "",actual native library version number ""
I/chromium( 4218): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4218): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44746a30:true
I/Adreno-EGL( 4218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4218): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4218): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4218): Local Branch: 
I/Adreno-EGL( 4218): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4218): Local Patches: NONE
I/Adreno-EGL( 4218): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4218): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4218): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4218): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4218): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4218): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4218): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4218): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4218): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4218): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4218): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4218): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4218): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4218): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4218): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4218): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4218): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4218): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4218): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4218): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4218): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4218): Enabling debug mode 0
,W/AwContents( 4218): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1210): onFinishInput()
,W/IInputConnectionWrapper( 4218): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,401
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +376ms (total +401ms)
,D/JsMessageQueue( 4218): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4218): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42602288
,D/dalvikvm( 4218): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42602288
,D/jxcore_app_log( 4218): JniHelper::setJavaVM(0x41d1df78), pthread_self() = 1614288928
,D/JX-Cordova( 4218): jxcore cordova android initializing
,D/dalvikvm( 4218): GC_CONCURRENT freed 2681K, 16% free 14508K/17224K, paused 3ms+3ms, total 36ms
,D/dalvikvm( 4218): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 312K, 14% free 14847K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 16.573MB for 42652-byte allocation
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 102K, 14% free 14854K/17268K, paused 25ms, total 25ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 125K, 14% free 14874K/17268K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 16.650MB for 95956-byte allocation
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 177K, 15% free 14909K/17364K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 16.729MB for 143930-byte allocation
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 251K, 15% free 14956K/17508K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 16.844MB for 215890-byte allocation
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 366K, 16% free 15030K/17720K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 17.019MB for 323830-byte allocation
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 565K, 17% free 15151K/18040K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 17.291MB for 485740-byte allocation
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 859K, 18% free 15327K/18516K, paused 27ms, total 28ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 1163K, 16% free 15571K/18516K, paused 27ms, total 28ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 167K, 17% free 15526K/18516K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 18.237MB for 1092904-byte allocation
,D/dalvikvm( 4218): GC_CONCURRENT freed 1781K, 19% free 15977K/19584K, paused 1ms+4ms, total 37ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 191K, 19% free 15912K/19584K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 19.134MB for 1639352-byte allocation
,D/dalvikvm( 4218): GC_CONCURRENT freed 1807K, 23% free 16491K/21188K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 1091K, 23% free 16482K/21188K, paused 28ms, total 30ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 20.474MB for 2459024-byte allocation
,D/dalvikvm( 4218): GC_CONCURRENT freed 360K, 20% free 18875K/23592K, paused 5ms+4ms, total 48ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 4134K, 26% free 17507K/23592K, paused 35ms, total 40ms
,I/dalvikvm-heap( 4218): Grow heap (frag case) to 22.646MB for 3688532-byte allocation
,D/dalvikvm( 4218): GC_CONCURRENT freed 225K, 23% free 21045K/27196K, paused 5ms+5ms, total 46ms
,D/dalvikvm( 4218): GC_FOR_ALLOC freed 4433K, 32% free 18620K/27196K, paused 33ms, total 33ms
,W/jxcore-log( 4218): Initializing JXcore engine
,W/jxcore-log( 4218): JXcore engine is ready
,D/dalvikvm( 4218): GC_CONCURRENT freed 417K, 22% free 21409K/27196K, paused 1ms+2ms, total 30ms
,D/dalvikvm( 4218): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4218): Starting JXcore engine
,W/jxcore-log( 4218): Platform android
W/jxcore-log( 4218): 
,W/jxcore-log( 4218): Process ARCH arm
W/jxcore-log( 4218): 
,I/jxcore-log( 4218): JXcore Cordova bridge is ready!
I/jxcore-log( 4218): 
,W/jxcore-log( 4218): JXcore engine is started
,I/chromium( 4218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4218): Toggling radios to true
I/jxcore-log( 4218): 
,D/BluetoothAdapter( 4218): enable(): BT is already enabled..!
D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=4218, uid=10113
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 4218): Radios toggled
I/jxcore-log( 4218): 
I/jxcore-log( 4218): My device name is: motorola-XT1039
I/jxcore-log( 4218): 
,D/TCMD    (  506): NL - Read 1000 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/TCMD    (  506): NL - Read 68 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/TCMD    (  506): NL - Read 68 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
,D/TCMD    (  506): Listening for incoming client connection request
I/wpa_supplicant( 1192): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  275): send SAR ctrl over QMI
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/Tethering( 1020): InitialState.processMessage what=4
,D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
,V/ConnectivityService( 1020): WiFi NOT Tethered!
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1192): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1192): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  506): NL - Read 60 bytes from update socket.
D/TCMD    (  506): NL - ignore NL message, type = 21
,D/TCMD    (  506): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiMetrics( 1020): connected time updated 304358
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1093): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1093): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1093): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1020): DisconnectingState
E/wpa_supplicant( 1192): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1192): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/WifiStateMachine( 1020): handleMessage: X
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x61ab1120 clazz=0x63100001 iface=wlan0 mask=0x3
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1339): Read error: ssl=0x62f258d8: I/O error during system call, Connection timed out
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1192): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1192): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,V/NativeCrypto( 1339): SSL shutdown failed: ssl=0x62f258d8: I/O error during system call, Broken pipe
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1278): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1278): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,D/TCMD    (  506): NL - Read 56 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
,D/TCMD    (  506): Listening for incoming client connection request
I/wpa_supplicant( 1192): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1192): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
W/ProcessCpuTracker( 1020): Skipping unknown process pid 4278
W/ProcessCpuTracker( 1020): Skipping unknown process pid 4279
W/ProcessCpuTracker( 1020): Skipping unknown process pid 4281
,I/wpa_supplicant( 1192): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  506): NL - Read 312 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/TCMD    (  506): NL - Read 192 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
,I/wpa_supplicant( 1192): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  506): NL - Read 68 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
,D/TCMD    (  506): Listening for incoming client connection request
D/TCMD    (  506): NL - Read 1000 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1192): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/TCMD    (  506): NL - Read 80 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/TCMD    (  506): NL - Read 80 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/TCMD    (  506): NL - Read 68 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1192): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1192): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  506): NL - Read 1000 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1220572320
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
I/MDMCTBK (  275): send SAR ctrl over QMI
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-34ms what=147462 obj=android.net.wifi.StateChangeResult@44c939f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42823210 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42823210 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  506): NL - Read 56 bytes from update socket.
D/TCMD    (  506): NL - message type is RTM_NEWLINK
D/TCMD    (  506): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 a
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 a
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 a0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 a0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 8c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 8c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1020): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@44c9fcd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@44c9fcd0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@44c9fcd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  506): NL - Read 60 bytes from update socket.
D/TCMD    (  506): NL - ignore NL message, type = 20
,D/TCMD    (  506): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): DHCP successful
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine( 1020): VerifyingLinkState enter
,D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1093): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1020): WiFi NOT Tethered!
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@426ce028
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/SBar.NetworkController( 1093): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1278): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@426ce028
D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
I/SBar.NetworkController( 1093): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1093): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1278): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=0
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1093): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/ActivityManager( 1020): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4331 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1612): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1612): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1612): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/OtaApp  ( 1612): [debug] > CusSM.onRadioDown
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/dalvikvm( 4331): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42605d28, skipping init
I/openssl ( 4331): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4331): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4351 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3903:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4351): mnc/mcc: 
,V/MmsConfig( 4351): tag: bool value: enabledMMS - true
V/MmsConfig( 4351): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4351): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4351): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4351): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4351): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4351): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4351): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4351): tag: int value: recipientLimit - 20
V/MmsConfig( 4351): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4351): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4351): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4351): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4351): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4351): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4351): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4351): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4351): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4370 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 4047:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4370): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4370): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4370): onOtaspChanged old =0, new =3
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4384 uid=10076 gids={50076, 3003, 1028, 1015}
,V/PhoneMonitor( 4370): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1020): Killing 4080:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1743): Checkin interval check for package: unspecified last checkin: 1452862848261 min interval config: 0 actual interval: 289912
,I/CheckinService( 1743): Checking schedule, now: 1452863138188 next: 1452862878237
,I/CheckinService( 1743): active receiver: enabled
,I/CheckinService( 1743): Preparing to send checkin request
,I/EventLogService( 1743): Accumulating logs since 1452862844573
,I/CheckinRequestBuilder( 1743): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1743): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4384): Binding Chromium to main looper Looper (main, tid 1) {42601b60}
,I/LibraryLoader( 4384): Expected native library version number "",actual native library version number ""
,I/chromium( 4384): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4384): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4384): BLUETOOTH permission is missing!
,D/dalvikvm( 1020): GC_EXPLICIT freed 25446K, 66% free 18429K/53008K, paused 4ms+10ms, total 152ms
,I/Adreno-EGL( 4384): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4384): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4384): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4384): Local Branch: 
I/Adreno-EGL( 4384): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4384): Local Patches: NONE
I/Adreno-EGL( 4384): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4384): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4384): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  263): Returning OperationFailed - no handler for errno 30
I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4421 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/ContextImpl( 4384): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4421): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4421): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4421): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4421): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4421): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4421): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4421): install
,I/MultiDex( 4421): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4421): loading existing secondary dex files
,I/MultiDex( 4421): load found 3 secondary dex files
,I/MultiDex( 4421): install done
,D/dalvikvm( 4421): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4421): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4421): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4421): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4421): VFY: unable to resolve instance field 36
,D/dalvikvm( 4421): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4421): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4421): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4421): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4421): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4421): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4421): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42607918
,D/dalvikvm( 4421): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42607918
D/dalvikvm( 4421): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42607918, skipping init
,D/dalvikvm( 4421): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42607918
D/dalvikvm( 4421): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42607918
,V/JNIHelp ( 4421): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4421): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42607918
,D/dalvikvm( 4421): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42607918
D/dalvikvm( 4421): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42607918
,D/dalvikvm( 4421): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42607918
,I/NSApplication( 4384): Starting up...
,I/ActivityManager( 1020): Killing 3548:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4441 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4421): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4421): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4421): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4421): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4421): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4421): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4421): VFY: replacing opcode 0x6e at 0x000d
D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4441): VFY: unable to resolve instance field 68
D/dalvikvm( 4441): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4441): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4441): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4441): VFY: unable to resolve instance field 68
,D/dalvikvm( 4441): VFY: replacing opcode 0x54 at 0x0011
,D/DEBUG   ( 1612): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4441): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4441): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4441): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4441): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager( 1020): Killing 4118:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1612): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/GetNotificationsWS( 1612): bindWebServices(): registering our AIDL callback...
,I/dalvikvm( 4421): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,I/SundryService( 1612): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1612): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1612): ServiceHandler.handleMessage: mWaitCount=0
,W/dalvikvm( 4421): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/GetNotificationsWS( 1612): onServiceConnected()
D/GetNotificationsWS( 1612): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1612): unbindWebServices(): un-registering our AIDL callback...
E/dalvikvm( 4421): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4421): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4421): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4421): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4421): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4421): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4421): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4421): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4421): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/openssl ( 4331): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4331): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4370): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4370): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50e2000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50e2000
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,E/MDM     ( 1222): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/AuthorizationBluetoothService( 1339): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/LocationInitializer( 1743): Restart initialization of location
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3906471752
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1222): GC_EXPLICIT freed 1125K, 36% free 11087K/17224K, paused 7ms+6ms, total 46ms
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@427e2298)
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429ff130)
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@426fe728)
E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429198b0)
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@428ba710)
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,D/dalvikvm( 4421): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42811230
D/dalvikvm( 4421): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42811230
,D/dalvikvm( 4421): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42811230, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/NativeLibraryUtils( 4421): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=238382676
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,W/Settings( 4421): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4421): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Choreographer( 4218): Skipped 324 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 4481): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4421): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4421): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 99ms
,I/Adreno-EGL( 4421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4421): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4421): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4421): Local Branch: 
I/Adreno-EGL( 4421): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4421): Local Patches: NONE
I/Adreno-EGL( 4421): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4421): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4421): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4421): Local Branch: 
I/Adreno-EGL( 4421): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4421): Local Patches: NONE
I/Adreno-EGL( 4421): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/AlarmManager( 1020): sending alarm Alarm{43a6b9f8 type 2 com.google.android.gms}
,I/Adreno-EGL( 4421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4421): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4421): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4421): Local Branch: 
I/Adreno-EGL( 4421): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4421): Local Patches: NONE
I/Adreno-EGL( 4421): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4421): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4421): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4421): Local Branch: 
I/Adreno-EGL( 4421): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4421): Local Patches: NONE
I/Adreno-EGL( 4421): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 10447 seconds from now (1452863140562)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/CheckinRequestBuilder( 1743): Classify the device as Phone.
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1222): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1222): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,I/dalvikvm( 1222): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1222): VFY: replacing opcode 0x6e at 0x003d
,I/CheckinTask( 1743): Sending checkin request (11632 bytes)
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/PollingManager( 1612): now: 337056 ,futureTime: 68884016
,D/PollingManager( 1612): Polling alarm set to expire at: 68884016 Current Time: 337056
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1612): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1612): [debug] > CusSM.onRadioUp
I/openssl ( 4331): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4331): Crypto mode 0 already enabled
D/OtaApp  ( 1612): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
D/PollingManager( 1612): now: 337081 ,futureTime: 68884016
,D/PollingManager( 1612): Polling alarm set to expire at: 68884016 Current Time: 337081
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4370): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4370): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1612): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1612): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: server told to :continue
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/OtaApp  ( 1612): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1612): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/CheckinService( 1743): Checkin interval check for package: unspecified last checkin: 1452862848261 min interval config: 0 actual interval: 292642
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1612): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: server told to :continue
D/DEBUG   ( 1612): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1612): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1612): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1612): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1612): onServiceConnected()
I/SundryService( 1612): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1612): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1612): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1612): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4331): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4331): Crypto mode 0 already enabled
D/MobileConnectivityChangeReceiver( 4370): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4370): onReceive CONNECTIVITY_CHANGE networkType=1
I/CheckinService( 1743): Checkin interval check for package: unspecified last checkin: 1452862848261 min interval config: 0 actual interval: 292701
D/DEBUG   ( 1612): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1612): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1612): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1612): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1612): onServiceConnected()
I/SundryService( 1612): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1612): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1612): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1612): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/GetNotificationsWS( 1612): unbindWebServices(): un-registering our AIDL callback...
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/OtaApp  ( 1612): [debug] > Received start id 2: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
D/OtaApp  ( 1612): [debug] > handle intent : null
I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1278): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1278): Inetcondition changed, white->blue
D/OtaApp  ( 1612): [debug] > supress duplicated intent, nextPompt: 1452949252124 and mNotificationInStatusBar: true
I/SBar.NetworkController( 1093): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,D/OtaApp  ( 1612): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/OtaApp  ( 1612): [debug] > Received start id 3: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1612): [debug] > handle intent : null
,D/OtaApp  ( 1612): [debug] > supress duplicated intent, nextPompt: 1452949252124 and mNotificationInStatusBar: true
,I/CheckinRequestBuilder( 1743): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1743): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1339): GC_EXPLICIT freed 1758K, 41% free 10305K/17224K, paused 2ms+5ms, total 34ms
,D/dalvikvm( 1339): null clazz in OP_INSTANCE_OF, single-stepping
,I/CheckinRequestBuilder( 1743): Classify the device as Phone.
,I/CheckinTask( 1743): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1743): Checking schedule, now: 1452863141329 next: 1452905195323
,I/CheckinService( 1743): active receiver: disabled
,I/CheckinService( 1743): Checking schedule, now: 1452863141355 next: 1452905195323
,I/CheckinService( 1743): active receiver: disabled
,D/dalvikvm( 1020): GC_EXPLICIT freed 842K, 66% free 18331K/53008K, paused 3ms+10ms, total 104ms
,D/CheckinService( 1743): Recording last checkin time for package unspecified as 1452863141369
,D/GCM     ( 1339): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1020): processMsg: ConnectedState
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1020): handleMessage: X
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4384): Thread[GAThread,5,main]: No campaign data found.
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
,I/ActivityManager( 1020): Killing 4150:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1020):   Scheme: "smsto"
I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4553 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 23ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/InternalIcingCorporaPro( 2362): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager( 1020): Killing 3574:com.android.vending/u0a38 (adj 15): empty #9
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1743): GC_CONCURRENT freed 1919K, 30% free 12060K/17224K, paused 4ms+5ms, total 49ms
,I/InternalIcingCorporaPro( 2362): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1020): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1020): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1020): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1020): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1020): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1020): sending alarm Alarm{42eac020 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider: pid=4586 uid=10038 gids={50038, 3003, 1028, 1015}
,I/dalvikvm( 4586): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4586): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4586): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4586): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4586): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4586): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4586): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4586): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4586): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4586): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4586): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4586): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4586): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4586): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4586): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 4586): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4586): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1020): Killing 4351:com.android.mms/u0a30 (adj 15): empty #9
,D/Ads     ( 4586): Skipping gmscore version check
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4586): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4586): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1743): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1743): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 4586): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 1743): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 4586): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1743): Indexing 08D2302403BBE76D1189E62A66162DB0256D4E65 from com.google.android.gms
,I/Icing   ( 1743): Indexing done 08D2302403BBE76D1189E62A66162DB0256D4E65
,I/Keyboard.Facilitator.LanguageModelFlusher( 1210): run()
,I/Keyboard.Facilitator( 1210): flushDynamicLanguageModels()
,I/ConfigService( 1222): onCreate
,I/ConfigService( 1222): onDestroy
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
,V/AlarmManager( 1020): sending alarm Alarm{4264c390 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44dc8e38 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
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
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7
,V/AlarmManager( 1020): sending alarm Alarm{44dd0340 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44dd35d0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44ddc4b0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44de0d38 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44de8398 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44deb3f0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44df2b38 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42eabf98 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{42ea79a0 type 1 com.android.deskclock}
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4663 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/ActivityManager( 1020): Killing 4370:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
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
,V/AlarmManager( 1020): sending alarm Alarm{44df89f0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e0b8f0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e11d80 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e17c58 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e1c240 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{42ea1ed8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1278): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=100
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44e27c48 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e2cdf0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e360e8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44e27d20 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{44e3b1e0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44e41548 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44e42818 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e45450 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e4b3f0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e52c90 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44e593c8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44e27ed0 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{44e28098 type 0 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{44e27df8 type 1 com.android.deskclock}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/EventLogService( 1743): Aggregate from 1452863138206 (log), 1452862494071 (data)
,D/dalvikvm( 1020): GC_CONCURRENT freed 2089K, 66% free 18490K/53008K, paused 5ms+8ms, total 99ms
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
,V/AlarmManager( 1020): sending alarm Alarm{44e6f0a8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44e6f180 type 3 com.google.android.gms}
,I/ProcessStatsService( 1020): Prepared write state in 21ms
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2016-01-14-19-22-37.bin
,W/dalvikvm( 1339): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1339): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1339): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1339): VFY: replacing opcode 0x1f at 0x0011
,I/dalvikvm( 1339): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1339): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1339): VFY: replacing opcode 0x6e at 0x003d
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
,V/AlarmManager( 1020): sending alarm Alarm{44e6efd0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{445c4880 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{445a93c0 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44545618 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{4453cf00 type 3 android}
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
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1020): sending alarm Alarm{44e6f1d0 type 2 com.motorola.ccc.cce}
D/CCE     ( 1612): Registering with Alarm Manager to restart CCE
V/AlarmManager( 1020): sending alarm Alarm{44e6f2a8 type 2 com.google.android.gms}
D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1278): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1278): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1278): onReceive() - done, currentInetCondition=100
D/AndroidRuntime( 4747): 
D/AndroidRuntime( 4747): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4747): CheckJNI is OFF
D/dalvikvm( 4747): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4747): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4747): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4747): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4747): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4747): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4747): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4747): failed to load memtrack module: -2
D/AndroidRuntime( 4747): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10113 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 4218:com.test.thalitest/u0a113 (adj 0): stop com.test.thalitest
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Killing 4421:com.google.android.gms.unstable/u0a22 (adj 15): empty for 1800s
I/ActivityManager( 1020): Killing 4441:com.android.chrome/u0a56 (adj 15): empty for 1805s
I/ActivityManager( 1020): Killing 4384:com.google.android.apps.magazines/u0a76 (adj 15): empty for 1805s
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{44fb1cd0 u0 com.test.thalitest/.MainActivity t2}
I/WindowState( 1020): WIN DEATH: Window{44fc5a10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1020): Client connection lost with reason: 4
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10113 user=0: pkg removed
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Keyboard.Facilitator( 1210): resetDictionaries() : en_GB
I/Keyboard.Facilitator.DecoderInitializer( 1210): run()
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1210): createOrResetDecoder
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
D/VoicemailCleanupService( 1190): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1298): GC_EXPLICIT freed 3523K, 33% free 11598K/17224K, paused 2ms+5ms, total 61ms
I/Launcher( 1298): Deferring update until onResume
D/dalvikvm( 2362): GC_EXPLICIT freed 2959K, 44% free 9783K/17224K, paused 10ms+4ms, total 66ms
D/dalvikvm( 2330): GC_EXPLICIT freed 5448K, 44% free 9652K/17224K, paused 5ms+6ms, total 60ms
D/dalvikvm( 1743): GC_EXPLICIT freed 1235K, 31% free 11931K/17224K, paused 21ms+5ms, total 117ms
W/SQLiteConnectionPool( 1743): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1020): GC_EXPLICIT freed 1134K, 66% free 18273K/53008K, paused 6ms+10ms, total 127ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/ConfigService( 1222): onCreate
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/Launcher( 1298): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/InternalIcingCorporaPro( 2362): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4782 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10113 #1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): run()
W/ContextImpl( 4782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1743): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1743): Clearing selected account for com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/ChimeraCfgMgr( 1743): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1743): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = contacts
I/dalvikvm( 4586): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4586): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4586): VFY: replacing opcode 0x6e at 0x0013
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = user
I/LocationSettingsChecker( 1743): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1210): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1210): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1210): run()
I/StatsUtilsManager( 1210): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1210): shouldRecordStats() = Too Soon
W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 4218 uid 10113
W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
I/Keyboard.Facilitator( 1210): onFinishInput()
E/NetworkScheduler.SchedulerReceiver( 1339): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1339): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1743): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1743): Module APK com.google.android.play.games already loaded
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4806 uid=10059 gids={50059, 1028, 3003, 1015}
I/InternalIcingCorporaPro( 2362): UpdateCorporaTask done [took 162 ms] updated apps [took 162 ms] 
D/gH_CompatibleDatabase( 1743): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1743): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1743): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1743): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Icing   ( 1743): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1743): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1743): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1743): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1743): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1743): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1743): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1743): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1743): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1743): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1020): GC_EXPLICIT freed 668K, 66% free 18451K/53008K, paused 7ms+22ms, total 308ms
D/AndroidRuntime( 4747): Shutting down VM
D/dalvikvm( 4747): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
I/dalvikvm( 4806): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 4806): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4806): VFY: replacing opcode 0x6e at 0x000f
I/GAv4    ( 4806): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4806):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4806):   adb logcat -s GAv4
W/GAv4    ( 4806): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/dalvikvm( 4806): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4806): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4806): VFY: replacing opcode 0x6e at 0x001b
W/GAv4    ( 4806): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4806): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4806): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
I/dalvikvm( 4806): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4806): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 4806): VFY: replacing opcode 0x71 at 0x0075
I/ActivityManager( 1020): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=4844 uid=10095 gids={50095, 3003, 1028, 1015}
E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4806): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
D/dalvikvm( 4806): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4806): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4806): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4806): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4806): VFY: unable to resolve instance field 36
D/dalvikvm( 4806): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4806): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4806): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4806): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4806): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4806): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 4806): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4295f6b8
D/dalvikvm( 4806): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4295f6b8
D/dalvikvm( 4806): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4295f6b8, skipping init
D/dalvikvm( 4806): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4295f6b8
D/dalvikvm( 4806): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4295f6b8
V/JNIHelp ( 4806): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/Quickoffice( 4844): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 4844): Loading recent documents list
D/Quickoffice( 4844): The number of lines present in  /proc/mount 24
D/Quickoffice( 4844): Parsing the storagedefinition.xml.
D/Quickoffice( 4844): # of Storagedefinitions - 35
D/Quickoffice( 4844): The # of storage definitions available - 35
D/Quickoffice( 4844): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 4844): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,size=428100k,nr_inodes=107025,mode=755 0 0
D/Quickoffice( 4844): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 4844): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 4844): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 4844): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 4844): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 4844): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 4844): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,size=428100k,nr_inodes=107025,mode=750,gid=1000 0 0
D/Quickoffice( 4844): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 4844): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,size=428100k,nr_inodes=107025,mode=755,gid=1000 0 0
D/Quickoffice( 4844): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,size=428100k,nr_inodes=107025,mode=755,gid=1000 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data f2fs ro,seclabel,nosuid,nodev,noatime,nodiratime,background_gc=off,discard,user_xattr,inline_xattr,acl,errors=recover,active_logs=6 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 ro,seclabel,nosuid,nodev,noatime,nodiratime,data=ordered 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,defcontext=u:object_r:persist_file:s0,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware ext4 ro,defcontext=u:object_r:modem_file:s0,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/pds /pds ext3 rw,defcontext=u:object_r:pds_file:s0,seclabel,nosuid,noexec,relatime,barrier=1,data=writeback 0 0
D/Quickoffice( 4844): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/fsg /fsg ext4 ro,defcontext=u:object_r:modem_file:s0,seclabel,nosuid,nodev,relatime 0 0
D/Quickoffice( 4844): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 4844): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/dalvikvm( 4806): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4295f6b8
D/dalvikvm( 4806): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4295f6b8
D/Quickoffice( 4844): Build properties are not configured for this storage definition.
D/dalvikvm( 4806): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4295f6b8
D/dalvikvm( 4806): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4295f6b8
D/Quickoffice( 4844): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 4844): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,size=428100k,nr_inodes=107025,mode=751,gid=1028 0 0
D/Quickoffice( 4844): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 4844): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 4844): Build properties are not configured for this storage definition.
D/Quickoffice( 4844): The # of mounts identified -  1
D/com.google.android.apps.docs.quickoffice.X( 4844): Checking validity of 0 items
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4864 uid=10058 gids={50058}
W/ActivityManager( 1020): No permission grants found for com.quickoffice.android
D/ContentResolverUtil( 4844): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 4844): 0 items were valid
D/Documents( 4864): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4864): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4864): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4864): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4864): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4864): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4864): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4864): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4864): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4864): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4864): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4864): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4864): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4864): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4864): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4864): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4864): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4864): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager( 1020): Killing 4663:com.android.deskclock/u0a15 (adj 15): empty #9
D/AndroidRuntime( 4864): Shutting down VM
W/dalvikvm( 4864): threadid=1: thread exiting with uncaught exception (group=0x41d2fd40)
W/ContextImpl( 1240): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/SQLiteLog( 2330): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/AndroidRuntime( 4864): FATAL EXCEPTION: main
E/AndroidRuntime( 4864): Process: com.android.documentsui, PID: 4864
E/AndroidRuntime( 4864): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4864): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4864): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4864): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4864): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4864): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4864): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4864): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4864): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4864): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4864): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4864): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4864): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4864): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4864): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4864): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4864): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4864): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4864): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4864): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4864): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4864): 	... 10 more

```
