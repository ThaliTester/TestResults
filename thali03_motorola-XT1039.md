#### Test 5590220275263c8_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  280): NetlinkHandler, power_supply subsys
I/MDMCTBK (  280): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  280): checkDefaultInst, current pid is = 280
I/MDMCTBK (  280): checkDefaultInst, pid match
I/MDMCTBK (  280): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  280): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  280): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 4101): 
D/AndroidRuntime( 4101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4101): CheckJNI is OFF
D/dalvikvm( 4101): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4101): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4101): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4101): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4101): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4101): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4101): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4101): failed to load memtrack module: -2
D/AndroidRuntime( 4101): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  994): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4101
W/WindowManager(  994): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  994): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4124 uid=10107 gids={50107, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4101): Shutting down VM
D/dalvikvm( 4101): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4124): Binding Chromium to main looper Looper (main, tid 1) {41fdab20}
I/LibraryLoader( 4124): Expected native library version number "",actual native library version number ""
I/chromium( 4124): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4124): Initializing chromium process, renderers=0
D/BluetoothManagerService(  994): Message: 20
D/BluetoothManagerService(  994): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@436329d0:true
I/Adreno-EGL( 4124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4124): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4124): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4124): Local Branch: 
I/Adreno-EGL( 4124): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4124): Local Patches: NONE
I/Adreno-EGL( 4124): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4124): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4124): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4124): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4124): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4124): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4124): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4124): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4124): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4124): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4124): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4124): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4124): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4124): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4124): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4124): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4124): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4124): Enabling debug mode 0
,W/AwContents( 4124): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1204): onFinishInput()
,W/IInputConnectionWrapper( 4124): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  994): Displayed com.test.thalitest/.MainActivity,cp,ca,406
I/ActivityManager(  994): Displayed com.test.thalitest/.MainActivity: +380ms (total +406ms)
,D/JsMessageQueue( 4124): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4124): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdf408
,D/dalvikvm( 4124): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdf408
,D/jxcore_app_log( 4124): JniHelper::setJavaVM(0x4162ffa8), pthread_self() = 1614763400
,D/JX-Cordova( 4124): jxcore cordova android initializing
,D/dalvikvm( 4124): GC_CONCURRENT freed 2768K, 17% free 14420K/17224K, paused 2ms+2ms, total 53ms
,D/dalvikvm( 4124): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4124): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 155K, 17% free 14392K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 128K, 17% free 14410K/17224K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 16.197MB for 95956-byte allocation
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 179K, 17% free 14445K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 16.276MB for 143930-byte allocation
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 253K, 18% free 14492K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 16.391MB for 215890-byte allocation
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 368K, 18% free 14566K/17676K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 16.566MB for 323830-byte allocation
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 568K, 19% free 14687K/17996K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 16.838MB for 485740-byte allocation
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 866K, 20% free 14862K/18472K, paused 26ms, total 26ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 1285K, 19% free 15118K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 17.838MB for 1092904-byte allocation
,D/dalvikvm( 4124): GC_CONCURRENT freed 1734K, 21% free 15510K/19540K, paused 1ms+4ms, total 45ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 310K, 21% free 15447K/19540K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 18.681MB for 1639352-byte allocation
,D/dalvikvm( 4124): GC_CONCURRENT freed 1587K, 25% free 16002K/21144K, paused 1ms+3ms, total 31ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 1427K, 24% free 16084K/21144K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 20.085MB for 2459024-byte allocation
,D/dalvikvm( 4124): GC_CONCURRENT freed 343K, 22% free 18407K/23548K, paused 4ms+4ms, total 57ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 4312K, 28% free 17065K/23548K, paused 35ms, total 35ms
,I/dalvikvm-heap( 4124): Grow heap (frag case) to 22.215MB for 3688532-byte allocation
,D/dalvikvm( 4124): GC_CONCURRENT freed 276K, 25% free 20532K/27152K, paused 5ms+5ms, total 51ms
,D/dalvikvm( 4124): GC_FOR_ALLOC freed 3321K, 34% free 18023K/27152K, paused 28ms, total 29ms
,W/jxcore-log( 4124): Initializing JXcore engine
,W/jxcore-log( 4124): JXcore engine is ready
,D/dalvikvm( 4124): GC_CONCURRENT freed 380K, 24% free 20636K/27152K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 4124): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4124): Starting JXcore engine
,W/jxcore-log( 4124): Platform android
W/jxcore-log( 4124): 
,W/jxcore-log( 4124): Process ARCH arm
W/jxcore-log( 4124): 
,I/jxcore-log( 4124): JXcore Cordova bridge is ready!
I/jxcore-log( 4124): 
,W/jxcore-log( 4124): JXcore engine is started
,I/chromium( 4124): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4124): Toggling radios to true
I/jxcore-log( 4124): 
,D/BluetoothAdapter( 4124): enable(): BT is already enabled..!
D/WifiService(  994): New client listening to asynchronous messages
D/WifiService(  994): setWifiEnabled: true pid=4124, uid=10107
,E/WifiService(  994): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine(  994): handleMessage: E msg.what=131145
D/WifiStateMachine(  994): processMsg: ConnectedState
D/WifiStateMachine(  994): processMsg: L2ConnectedState
I/jxcore-log( 4124): Radios toggled
I/jxcore-log( 4124): 
I/jxcore-log( 4124): My device name is: motorola-XT1039
I/jxcore-log( 4124): 
,D/TCMD    (  453): NL - Read 1000 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  280): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  280): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  280):  STA Disconnected !!
I/MDMCTBK (  280): checkDefaultInst, current pid is = 280
I/MDMCTBK (  280): checkDefaultInst, pid match
I/MDMCTBK (  280): get_property_value, Enter
I/MDMCTBK (  280): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  280): get_property_value, Exit
I/MDMCTBK (  280): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  280): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  280): set_property_value, Enter
,I/MDMCTBK (  280): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  280): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  280): set_property_value, Exit
I/MDMCTBK (  280): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  280): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  280): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  280): set_property_value, Enter
I/MDMCTBK (  280): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  280): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  280): set_property_value, Exit
,I/MDMCTBK (  280): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,D/WifiStateMachine(  994): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  994): handleMessage: new destination call exit/enter
D/WifiStateMachine(  994): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  994): invokeExitMethods: ConnectedState
I/MDMCTBK (  280): send SAR ctrl over QMI
D/MDMCTBK (  280): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine(  994): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  994): Stopping DHCP and clearing IP
,D/WifiStateMachine(  994): setSuspendOptimizationsNative: 1 true
,D/Tethering(  994): InitialState.processMessage what=4
,D/Tethering(  994): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService(  994): WiFi NOT Tethered!
D/WifiP2pService(  994): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  994): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 21
,D/TCMD    (  453): Listening for incoming client connection request
,D/WifiStateMachine(  994): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  994): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  994): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics(  994): connected time updated 260838
D/ConnectivityService(  994): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  994): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1089): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  994): Attempting to switch to mobile
D/ConnectivityService(  994): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService(  994): Attempting to switch to ETHERNET
,D/ConnectivityService(  994): resetConnections(wlan0, 3)
I/SBar.NetworkController( 1089): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1089): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1089): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/NetUtils(  994): android_net_utils_resetConnections in env=0x6167f850 clazz=0x64b00001 iface=wlan0 mask=0x3
,D/WifiStateMachine(  994): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  994): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine(  994): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine(  994): DisconnectingState
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  994): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=131146
D/WifiStateMachine(  994): processMsg: DisconnectingState
,D/WifiStateMachine(  994): processMsg: ConnectModeState
D/MDMCTBK (  280): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=147460
D/WifiStateMachine(  994): processMsg: DisconnectingState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): Network connection lost
D/WifiStateMachine(  994): Stopping DHCP and clearing IP
,D/WifiStateMachine(  994): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1394): Read error: ssl=0x62feb830: I/O error during system call, Connection timed out
,D/WifiP2pService(  994): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  994): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1394): SSL shutdown failed: ssl=0x62feb830: I/O error during system call, Broken pipe
,D/WifiStateMachine(  994): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1089): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine(  994): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  994): handleMessage: new destination call exit/enter
D/WifiStateMachine(  994): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  994): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  994): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  994): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine(  994): invokeEnterMethods: DisconnectedState
,D/Checkin (  994): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): handleMessage: X
,D/WifiStateMachine(  994): handleMessage: E msg.what=131101
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
D/WifiStateMachine(  994): processMsg: SupplicantStartedState
D/WifiStateMachine(  994): processMsg: DefaultState
,D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=131216
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
D/WifiStateMachine(  994): processMsg: SupplicantStartedState
,D/WifiStateMachine(  994): processMsg: DefaultState
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=131216
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
,D/WifiStateMachine(  994): processMsg: SupplicantStartedState
D/WifiStateMachine(  994): processMsg: DefaultState
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: DisconnectedState
,D/WifiStateMachine(  994): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  994): processMsg: ConnectModeState
,D/WifiStateMachine(  994): handleMessage: X
D/Nat464Xlat(  994): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  994): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  994): Attempting to switch to mobile
D/ConnectivityService(  994): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService(  994): Attempting to switch to ETHERNET
,I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/Nat464Xlat(  994): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  994): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  280): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  280): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1185): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  280): Event received = Trying to associate with
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  994): handleMessage: E msg.what=147461
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
,D/WifiStateMachine(  994): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1185): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  994): processMsg: ConnectModeState
,D/WifiStateMachine(  994): handleMessage: X
,D/TCMD    (  453): NL - Read 312 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 192 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 1000 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
I/wpa_supplicant( 1185): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1185): WEXT: Custom wireless event: 'BEACONIEs='
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  280): Event received = Associated with c0:ff:d4
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 80 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
D/TCMD    (  453): Listening for incoming client connection request
D/TCMD    (  453): NL - Read 68 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
,D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  994): processMsg: ConnectModeState
,D/WifiStateMachine(  994): handleMessage: X
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  280): Event received = WPA: Key negotiation com
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  280): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  280):  STA Connected !!
D/TCMD    (  453): NL - Read 1000 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
E/MDMCTBK (  280): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  280): get_freq !!, resp=0
I/MDMCTBK (  280): get_freq !!, Strip data
I/MDMCTBK (  280): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  280): checkDefaultInst, current pid is = 280
I/MDMCTBK (  280): checkDefaultInst, pid match
I/MDMCTBK (  280): get_property_value, Enter
I/MDMCTBK (  280): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  280): get_property_value, Exit
I/MDMCTBK (  280): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  280): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  280): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  280): set_property_value, Enter
I/MDMCTBK (  280): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
I/MDMCTBK (  280): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  280): set_property_value, Exit
I/MDMCTBK (  280): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  280): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  280): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  280): checkDefaultInst, current pid is = 280
I/MDMCTBK (  280): checkDefaultInst, pid match
I/MDMCTBK (  280): get_property_value, Enter
I/MDMCTBK (  280): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  280): get_property_value, Exit
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): handleMessage: X
I/MDMCTBK (  280): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1196196952
I/MDMCTBK (  280): return from set_get_from_wpa_supplicant
I/MDMCTBK (  280): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  280): set_property_value, Enter
I/MDMCTBK (  280): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
,D/MDMCTBK (  280): wifi_set_tx_pwr: SETTXPOWER = 19
,I/MDMCTBK (  280): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  280): set_property_value, Exit
I/MDMCTBK (  280): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
E/MDMCTBK (  280): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  280): , reply_len: 3, ret: 0
E/MDMCTBK (  280): MdmCutbackHndler, resp=OK
E/MDMCTBK (  280): 
,D/MDMCTBK (  280): wifi_set_tx_pwr: Exit
I/MDMCTBK (  280): send SAR ctrl over QMI
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  994): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  994): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=147459
D/WifiStateMachine(  994): processMsg: DisconnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): Network connection established
,D/WifiStateMachine(  994): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  994): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  994): handleMessage: new destination call exit/enter
D/WifiStateMachine(  994): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  994): invokeExitMethods: DisconnectedState
D/WifiStateMachine(  994): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  994): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  994): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine(  994): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  994): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=147462
D/WifiStateMachine(  994): processMsg: ObtainingIpState
D/WifiStateMachine(  994): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@43b56a50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): processMsg: L2ConnectedState
,D/WifiStateMachine(  994): processMsg: ConnectModeState
,D/WifiStateMachine(  994): handleMessage: X
,I/SBar.NetworkController( 1089): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine(  994): handleMessage: E msg.what=131101
,D/WifiStateMachine(  994): processMsg: ObtainingIpState
D/WifiStateMachine(  994): ObtainingIpState{ when=-17ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43af9ce0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  994): processMsg: L2ConnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
,D/WifiStateMachine(  994): processMsg: DriverStartedState
,D/WifiStateMachine(  994): processMsg: SupplicantStartedState
,D/WifiStateMachine(  994): processMsg: DefaultState
,D/WifiStateMachine(  994): handleMessage: X
,D/WifiStateMachine(  994): handleMessage: E msg.what=196612
,D/WifiStateMachine(  994): processMsg: ObtainingIpState
D/WifiStateMachine(  994): ObtainingIpState{ when=-23ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  994): processMsg: L2ConnectedState
,D/WifiStateMachine(  994): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine(  994): Unexpected BatchedScanResults :OK
D/WifiP2pService(  994): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42220f90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  994): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42220f90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): handleMessage: X
,D/TCMD    (  453): NL - Read 56 bytes from update socket.
D/TCMD    (  453): NL - message type is RTM_NEWLINK
,D/TCMD    (  453): Listening for incoming client connection request
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 8 6
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  280): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  280): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  280): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  280): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  280): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  280): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService(  994): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  994): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  994): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  994): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43a072b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  994): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43a072b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  994): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43a072b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): handleMessage: E msg.what=147461
D/WifiStateMachine(  994): processMsg: ObtainingIpState
D/WifiStateMachine(  994): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): processMsg: L2ConnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
D/WifiStateMachine(  994): processMsg: SupplicantStartedState
D/WifiStateMachine(  994): handleMessage: X
,D/TCMD    (  453): NL - Read 60 bytes from update socket.
D/TCMD    (  453): NL - ignore NL message, type = 20
,D/TCMD    (  453): Listening for incoming client connection request
,D/WifiStateMachine(  994): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  994): handleMessage: E msg.what=131215
D/WifiStateMachine(  994): processMsg: ObtainingIpState
,D/WifiStateMachine(  994): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): processMsg: L2ConnectedState
,D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
D/WifiStateMachine(  994): processMsg: SupplicantStartedState
,D/WifiStateMachine(  994): processMsg: DefaultState
,D/WifiStateMachine(  994): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  994): handleMessage: X
,D/WifiStateMachine(  994): handleMessage: E msg.what=196613
,D/WifiStateMachine(  994): processMsg: ObtainingIpState
,D/WifiStateMachine(  994): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): processMsg: L2ConnectedState
,D/WifiStateMachine(  994): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  994): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  994): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  994): DHCP successful
D/WifiStateMachine(  994): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  994): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine(  994): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  994): handleMessage: new destination call exit/enter
D/WifiStateMachine(  994): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  994): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  994): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  994): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine(  994): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  994): VerifyingLinkState enter
D/WifiStateMachine(  994): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1089): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/dalvikvm(  994): Jit: resizing JitTable from 8192 to 16384
,D/WifiStateMachine(  994): handleMessage: X
,D/WifiStateMachine(  994): handleMessage: E msg.what=151572
D/WifiStateMachine(  994): processMsg: VerifyingLinkState
,D/WifiStateMachine(  994): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine(  994): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1089): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine(  994): handleMessage: X
,D/WifiStateMachine(  994): handleMessage: E msg.what=135190
D/WifiStateMachine(  994): processMsg: VerifyingLinkState
D/WifiStateMachine(  994): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  994): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  994): handleMessage: new destination call exit/enter
D/WifiStateMachine(  994): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  994): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  994): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  994): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine(  994): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  994): CaptivePortalCheckState enter
,D/WifiStateMachine(  994): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService(  994): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1089): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  994): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  994): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  994): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=131092
D/WifiStateMachine(  994): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  994): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  994): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService(  994): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1089): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService(  994): WiFi NOT Tethered!
E/ConnectivityService(  994): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ad528
,I/SBar.NetworkController( 1089): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat(  994): requiresClat: netType=1, hasIPv4Address=true
D/Checkin (  994): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
D/WifiStateMachine(  994): transitionTo: destState=ConnectedState
D/WifiStateMachine(  994): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  994): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  994): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  994): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  994): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine(  994): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  994): handleMessage: X
D/WifiStateMachine(  994): handleMessage: E msg.what=131092
,D/WifiStateMachine(  994): processMsg: ConnectedState
D/WifiStateMachine(  994): processMsg: L2ConnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
,D/WifiStateMachine(  994): processMsg: DriverStartedState
D/WifiStateMachine(  994): processMsg: SupplicantStartedState
D/WifiStateMachine(  994): processMsg: DefaultState
,D/WifiStateMachine(  994): handleMessage: X
,I/SBar.NetworkController( 1089): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1089): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService(  994): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService(  994): WiFi NOT Tethered!
,E/ConnectivityService(  994): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ad528
,D/ConnectivityService(  994): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  994): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1309): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=0
,W/XTWiFiOS( 1298): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1089): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering(  994): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1089): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1089): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker(  994): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  994): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PollingManager( 1602): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  994): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  994): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4263 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/Tethering(  994): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  994): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1089): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1298): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1089): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1602): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1602): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1602): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1602): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1602): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/ActivityManager(  994): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4292 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4263): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe2ea8, skipping init
I/openssl ( 4263): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4263): Crypto mode 0 already enabled
,I/ActivityManager(  994): Killing 3270:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4292): mnc/mcc: 
V/MmsConfig( 4292): tag: bool value: enabledMMS - true
V/MmsConfig( 4292): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4292): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4292): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4292): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4292): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4292): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4292): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4292): tag: int value: recipientLimit - 20
V/MmsConfig( 4292): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4292): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4292): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4292): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4292): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4292): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4292): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4292): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4292): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager(  994): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4313 uid=10041 gids={50041, 3003}
,I/ActivityManager(  994): Killing 3953:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4313): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4313): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4313): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4313): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  994): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4327 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager(  994): Killing 3977:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1730): Checkin interval check for package: unspecified last checkin: 1452695550188 min interval config: 0 actual interval: 247479
,I/CheckinService( 1730): Checking schedule, now: 1452695797679 next: 1452695580162
,I/CheckinService( 1730): active receiver: enabled
,I/CheckinService( 1730): Preparing to send checkin request
,I/EventLogService( 1730): Accumulating logs since 1452695546434
,I/CheckinRequestBuilder( 1730): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1730): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4327): Binding Chromium to main looper Looper (main, tid 1) {41fdea88}
,I/LibraryLoader( 4327): Expected native library version number "",actual native library version number ""
,I/chromium( 4327): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4327): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4327): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4327): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4327): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4327): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4327): Local Branch: 
I/Adreno-EGL( 4327): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4327): Local Patches: NONE
I/Adreno-EGL( 4327): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm(  994): GC_EXPLICIT freed 23344K, 65% free 18317K/51356K, paused 4ms+10ms, total 150ms
,V/GLSActivity( 1394): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1394): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4327): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager(  994): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4360 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
W/GAV2    ( 4327): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4327): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4360): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4360): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4360): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4360): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4360): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4360): install
,I/MultiDex( 4360): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4360): loading existing secondary dex files
,I/MultiDex( 4360): load found 3 secondary dex files
,I/MultiDex( 4360): install done
,D/dalvikvm( 4360): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4360): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4360): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4360): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4360): VFY: unable to resolve instance field 36
,D/dalvikvm( 4360): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4360): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4360): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4360): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4360): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4360): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4360): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe4a98
D/dalvikvm( 4360): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe4a98
,D/dalvikvm( 4360): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe4a98, skipping init
,D/dalvikvm( 4360): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe4a98
D/dalvikvm( 4360): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe4a98
,V/JNIHelp ( 4360): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4360): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fe4a98
,D/dalvikvm( 4360): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fe4a98
D/dalvikvm( 4360): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fe4a98
,D/dalvikvm( 4360): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe4a98
,I/NSApplication( 4327): Starting up...
,I/ActivityManager(  994): Killing 3747:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  994): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4385 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4360): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4385): VFY: unable to resolve instance field 68
D/dalvikvm( 4385): VFY: replacing opcode 0x54 at 0x000c
,D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4385): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4385): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,I/dalvikvm( 4360): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4360): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x00ce
,D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4360): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4385): VFY: unable to resolve instance field 68
W/dalvikvm( 4360): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 4385): VFY: replacing opcode 0x54 at 0x0011
I/openssl ( 4263): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4263): Crypto mode 0 already enabled
D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4385): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4385): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4385): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4385): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/MobileConnectivityChangeReceiver( 4313): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4313): onReceive CONNECTIVITY_CHANGE networkType=1
I/dalvikvm( 4360): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4360): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4360): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4360): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4360): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4360): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4360): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4360): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4360): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4360): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/ActivityManager(  994): Killing 4017:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1602): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1602): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1602): bindWebServices(): registering our AIDL callback...
I/SundryService( 1602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1602): onServiceConnected()
,D/GetNotificationsWS( 1602): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1602): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1602): unbindWebServices(): un-registering our AIDL callback...
,D/WVCdm   (  284): Instantiating CDM.
,I/WVCdm   (  284): Level3 Library Nov 20 2013 18:09:31
,D/WearableService( 1235): callingUid 10022, callindPid: 1235
,D/DrmWidevineDash(  284): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  284): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  284): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb520c000
,E/DrmWidevineDash(  284): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb520c000
,E/MDM     ( 1235): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DrmWidevineDash(  284): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  284): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  284): calling OEMCrypto_IsKeyboxValid...
,D/LocationInitializer( 1730): Restart initialization of location
,D/DrmWidevineDash(  284): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  284): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  284): CdmEngine::OpenSession
,D/DrmWidevineDash(  284): calling OEMCrypto_OpenSession...
,D/AuthorizationBluetoothService( 1394): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1394): Proximity feature is not enabled.
,D/DrmWidevineDash(  284): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetRandom...
,V/GLSActivity( 1394): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  284): OEMCrypto_GetRandom returns 0
I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/GCoreFlp( 1235): No location to return for getLastLocation()
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  284): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,W/FusedLocationProvider( 1235): location=null
,D/DrmWidevineDash(  284): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  284): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  284): PrepareKeyRequest: nonce=120762065
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4360): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4360): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421be3d8
D/dalvikvm( 4360): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421be3d8
,D/dalvikvm( 4360): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421be3d8, skipping init
,D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  284): CdmEngine::CloseSession
,D/DrmWidevineDash(  284): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4360): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4416): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 4360): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4360): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 75ms
,I/Adreno-EGL( 4360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4360): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4360): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4360): Local Branch: 
I/Adreno-EGL( 4360): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4360): Local Patches: NONE
I/Adreno-EGL( 4360): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4360): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4360): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4360): Local Branch: 
I/Adreno-EGL( 4360): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4360): Local Patches: NONE
I/Adreno-EGL( 4360): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/AlarmManager(  994): sending alarm Alarm{4327bfe0 type 2 com.google.android.gms}
,W/Settings( 4360): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Tethering(  994): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1089): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1298): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1602): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1089): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1602): now: 293647 ,futureTime: 63375543
D/PollingManager( 1602): Polling alarm set to expire at: 63375543 Current Time: 293648
,D/CaptivePortalTracker(  994): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1089): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1089): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
E/ActivityThread( 1602): Failed to find provider info for com.motorola.blur.setupprovider
I/openssl ( 4263): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4263): Crypto mode 0 already enabled
D/PollingManager( 1602): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1602): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1602): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1602): now: 293683 ,futureTime: 63375543
D/PollingManager( 1602): Polling alarm set to expire at: 63375543 Current Time: 293683
,E/ActivityThread( 1602): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1602): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1602): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
D/Checkin ( 1602): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1602): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1602): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1602): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/Tethering(  994): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  994): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
W/XTWiFiOS( 1298): No entry in secure settings for enhanced location services: false
,D/OtaApp  ( 1602): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1602): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
D/Checkin ( 1602): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4313): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4313): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1602): [debug] > CusSM.runStateMachine: server told to :continue
D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
I/CheckinService( 1730): Checkin interval check for package: unspecified last checkin: 1452695550188 min interval config: 0 actual interval: 249300
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/DEBUG   ( 1602): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1602): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1602): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1602): onServiceConnected()
,D/GetNotificationsWS( 1602): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1602): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1602): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4263): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4263): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4313): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4313): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1730): Checkin interval check for package: unspecified last checkin: 1452695550188 min interval config: 0 actual interval: 249376
,D/DEBUG   ( 1602): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1602): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1602): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1602): onServiceConnected()
D/GetNotificationsWS( 1602): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1602): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/WaitableIntentService( 1602): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1602): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1602): [debug] > Received start id 2: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1602): [debug] > handle intent : null
,D/OtaApp  ( 1602): [debug] > supress duplicated intent, nextPompt: 1452781953718 and mNotificationInStatusBar: true
,D/OtaApp  ( 1602): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/OtaApp  ( 1602): [debug] > Received start id 3: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1602): [debug] > handle intent : null
,D/OtaApp  ( 1602): [debug] > supress duplicated intent, nextPompt: 1452781953718 and mNotificationInStatusBar: true
,I/Adreno-EGL( 4360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4360): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4360): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4360): Local Branch: 
I/Adreno-EGL( 4360): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4360): Local Patches: NONE
I/Adreno-EGL( 4360): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4360): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4360): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4360): Local Branch: 
I/Adreno-EGL( 4360): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4360): Local Patches: NONE
I/Adreno-EGL( 4360): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/ConnectivityService(  994): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1309): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1089): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1089): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1089): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1309): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1309): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1309): onReceive() - done, currentInetCondition=100
,I/WVCdm   (  284): CdmEngine::OpenSession
,D/DrmWidevineDash(  284): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  284): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  284): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  284): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  284): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  284): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  284): PrepareKeyRequest: nonce=2850479982
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  284): CdmEngine::CloseSession
,D/DrmWidevineDash(  284): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1730): Classify the device as Phone.
,D/dalvikvm( 1730): GC_CONCURRENT freed 1864K, 30% free 12106K/17224K, paused 4ms+5ms, total 50ms
,D/dalvikvm( 1730): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/CheckinTask( 1730): Sending checkin request (11902 bytes)
,I/CheckinRequestBuilder( 1730): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1730): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1730): Classify the device as Phone.
,I/CheckinTask( 1730): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1730): Checking schedule, now: 1452695801457 next: 1452737855437
,I/CheckinService( 1730): active receiver: disabled
,I/CheckinService( 1730): Checking schedule, now: 1452695801473 next: 1452737855437
,I/CheckinService( 1730): active receiver: disabled
,D/CheckinService( 1730): Recording last checkin time for package unspecified as 1452695801478
,D/GCM     ( 1394): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  994): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  994): handleMessage: E msg.what=131215
D/WifiStateMachine(  994): processMsg: ConnectedState
D/WifiStateMachine(  994): processMsg: L2ConnectedState
D/WifiStateMachine(  994): processMsg: ConnectModeState
D/WifiStateMachine(  994): processMsg: DriverStartedState
D/WifiStateMachine(  994): processMsg: SupplicantStartedState
,D/WifiStateMachine(  994): processMsg: DefaultState
,D/WifiStateMachine(  994): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  994): handleMessage: X
D/ConnectivityService(  994): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  994):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat(  994): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  994): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  994): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4327): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  994): Killing 4049:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4124): Test app app.js loaded
I/jxcore-log( 4124): 
,I/chromium( 4124): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4124): --= Surplus to requirements =--
I/jxcore-log( 4124): 
I/jxcore-log( 4124): ****TEST TOOK:  ms ****
I/jxcore-log( 4124): 
,I/jxcore-log( 4124): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4124): 
,D/AndroidRuntime( 4467): 
D/AndroidRuntime( 4467): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4467): CheckJNI is OFF
,D/dalvikvm( 4467): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4467): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4467): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4467): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4467): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4467): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4467): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4467): failed to load memtrack module: -2
,D/AndroidRuntime( 4467): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  994): Force stopping com.test.thalitest appid=10107 user=-1: uninstall pkg
,I/ActivityManager(  994): Killing 4124:com.test.thalitest/u0a107 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  994):   Force finishing activity ActivityRecord{444c8ce0 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState(  994): WIN DEATH: Window{444b3430 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  994): Client connection lost with reason: 4
,I/ActivityManager(  994): Force stopping com.test.thalitest appid=10107 user=0: pkg removed
,I/Keyboard.Facilitator( 1204): resetDictionaries() : en_GB
,W/GeofencerStateMachine( 1235): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "sms"
,D/dalvikvm( 1323): GC_EXPLICIT freed 3431K, 33% free 11596K/17224K, paused 3ms+4ms, total 61ms
,I/Keyboard.Facilitator.DecoderInitializer( 1204): run()
,I/InputReader(  994): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1204): createOrResetDecoder
,I/Launcher( 1323): Deferring update until onResume
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "smsto"
,D/VoicemailCleanupService( 1187): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "mms"
,D/dalvikvm( 2298): GC_EXPLICIT freed 5100K, 44% free 9646K/17224K, paused 2ms+11ms, total 70ms
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "mmsto"
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "sms"
,D/dalvikvm( 2331): GC_EXPLICIT freed 2689K, 44% free 9773K/17224K, paused 2ms+79ms, total 165ms
I/ActivityManager(  994): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4488 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm( 1730): GC_EXPLICIT freed 583K, 31% free 11897K/17224K, paused 6ms+19ms, total 185ms
,W/SQLiteConnectionPool( 1730): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm(  994): GC_EXPLICIT freed 1420K, 65% free 18234K/51356K, paused 4ms+14ms, total 157ms
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "smsto"
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "mms"
I/Launcher( 1323): Deferring update until onResume
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "mmsto"
,I/ConfigService( 1235): onCreate
,W/InputMethodManagerService(  994): Got RemoteException sending setActive(false) notification to pid 4124 uid 10107
D/BackupManagerService(  994): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  994): removePackageParticipantsLocked: uid=10107 #1
W/Binder  ( 1204): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1204): java.lang.NullPointerException
W/Binder  ( 1204): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1204): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1204): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1204): 	at dalvik.system.NativeStart.run(Native Method)
I/Keyboard.Facilitator( 1204): onFinishInput()
,I/InternalIcingCorporaPro( 2331): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1204): run()
,I/ActivityManager(  994): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4507 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager(  994): Killing 3495:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 4507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1204): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1204): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1204): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1204): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1204): run()
I/StatsUtilsManager( 1204): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1204): shouldRecordStats() = Too Soon
,W/BroadcastQueue(  994): Exception when sending broadcast to ComponentInfo{com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver}
W/BroadcastQueue(  994): android.os.DeadObjectException
W/BroadcastQueue(  994): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  994): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:822)
W/BroadcastQueue(  994): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:236)
W/BroadcastQueue(  994): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:879)
W/BroadcastQueue(  994): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:14032)
W/BroadcastQueue(  994): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:394)
W/BroadcastQueue(  994): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2140)
W/BroadcastQueue(  994): 	at android.os.Binder.execTransact(Binder.java:404)
W/BroadcastQueue(  994): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  994): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4522 uid=10038 gids={50038, 3003, 1028, 1015}
I/ActivityManager(  994): Process com.android.vending (pid 3495) has died and restarted (pid 4522).
,D/dalvikvm(  282): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  282): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
,I/ActivityManager(  994): Killing 4263:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  282): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
I/InternalIcingCorporaPro( 2331): UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
D/dalvikvm(  994): GC_EXPLICIT freed 548K, 65% free 18276K/51356K, paused 5ms+17ms, total 233ms
,I/dalvikvm( 4522): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4522): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x000e
,D/AndroidRuntime( 4467): Shutting down VM
,D/Finsky  ( 4522): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 4467): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/dalvikvm( 4522): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4522): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4522): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4522): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4522): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4522): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4522): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4522): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4522): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4522): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4522): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4522): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4522): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x037f
,I/dalvikvm( 4522): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4522): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager(  994): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4558 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4522): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4522): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4522): Skipping gmscore version check
,D/Finsky  ( 4522): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4522): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1730): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1730): Clearing selected account for com.test.thalitest
I/dalvikvm( 4522): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4522): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 4522): VFY: replacing opcode 0x6e at 0x0013
,D/ChimeraCfgMgr( 1730): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1730): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1730): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1730): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1730): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1394): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1394): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  994): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4582 uid=10059 gids={50059, 1028, 3003, 1015}
,I/Icing   ( 1730): doRemovePackageData com.test.thalitest
,I/InputReader(  994): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "sms"
I/Launcher( 1323): Deferring update until onResume
,D/gH_CompatibleDatabase( 1730): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1730): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 1730): (3850) statement aborts at 26: [DELETE FROM raw_events_metadata WHERE app_id=?] disk I/O error
E/SQLiteLog( 1730): (3850) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 1730): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/dalvikvm( 1730): threadid=51: thread exiting with uncaught exception (group=0x4170ed40)
,E/SQLiteLog( 1323): (3850) statement aborts at 30: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
W/FileUtils( 1730): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/FileUtils( 4558): Failed to chmod(/data/data/com.android.providers.media/databases/external.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1730): Failed to open Apps corpus file.
E/Icing   ( 1730): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1730): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
E/GMPM-SVC( 1730): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1779)
F/PackageManager(  994): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  994): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  994): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  994): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  994): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  994): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  994): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  994): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  994): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:119)
F/PackageManager(  994): 	at com.android.internal.util.FastXmlSerializer.endTag(FastXmlSerializer.java:205)
F/PackageManager(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1116)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
F/PackageManager(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
F/PackageManager(  994): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager(  994): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  994): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  994): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  994): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  994): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  994): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  994): 	... 14 more
E/SharedPreferencesImpl( 1730): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SharedPreferencesImpl( 1730): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/AndroidRuntime( 1730): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1730): Process: com.google.android.gms, PID: 1730
E/AndroidRuntime( 1730): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1730): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1730): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1730): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1730): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1730): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1730): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1730): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1730): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1730): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1730): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/MediaProvider( 4558): failed to open database external.db
E/MediaProvider( 4558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquireNonPrimaryConnectionLocked(SQLiteConnectionPool.java:899)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:609)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:650)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/MediaProvider( 4558): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/MediaProvider( 4558): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/MediaProvider( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/MediaProvider( 4558): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:441)
E/MediaProvider( 4558): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5400)
E/MediaProvider( 4558): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/MediaProvider( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/MediaProvider( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/MediaProvider( 4558): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/MediaProvider( 4558): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/MediaProvider( 4558): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/MediaProvider( 4558): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/MediaProvider( 4558): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/MediaProvider( 4558): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/MediaProvider( 4558): 	at android.os.Looper.loop(Looper.java:136)
E/MediaProvider( 4558): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/MediaProvider( 4558): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/MediaProvider( 4558): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/MediaProvider( 4558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/MediaProvider( 4558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/MediaProvider( 4558): 	at dalvik.system.NativeStart.main(Native Method)
E/DropBoxManagerService(  994): Can't write: system_server_wtf
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop68.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService(  994): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  994): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService(  994): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService(  994): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 19 more
I/PackageManager(  994): Failed to clean up mangled file: /data/system/packages-stopped.xml
I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "smsto"
W/PackageManager(  994): Preserving older stopped packages backup
E/DropBoxManagerService(  994): Can't write: system_app_crash
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 5 more
I/Launcher( 1323): Deferring update until onResume
F/PackageManager(  994): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  994): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1057)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
F/PackageManager(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
F/PackageManager(  994): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager(  994): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  994): 	... 9 more
I/Process ( 1730): Sending signal. PID: 1730 SIG: 9
E/SQLiteDatabase( 4558): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4558): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteDatabase( 4558): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteDatabase( 4558): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteDatabase( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4558): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4558): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4558): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4558): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4558): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4558): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4558): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4558): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4558): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4558): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4558): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4558): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4558): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteOpenHelper( 4558): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteOpenHelper( 4558): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteOpenHelper( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4558): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteOpenHelper( 4558): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteOpenHelper( 4558): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteOpenHelper( 4558): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4558): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4558): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4558): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4558): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4558): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4558): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4558): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4558): (14) cannot open file at line 28970 of [00bb9c9ce4]
E/SQLiteLog( 4558): (14) os_unix.c:28970: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4558): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
D/AndroidRuntime( 4558): Shutting down VM
W/dalvikvm( 4558): threadid=1: thread exiting with uncaught exception (group=0x4170ed40)
E/DropBoxManagerService(  994): Can't write: system_server_wtf
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop74.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService(  994): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  994): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService(  994): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService(  994): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 19 more
,E/AndroidRuntime( 4558): FATAL EXCEPTION: main
E/AndroidRuntime( 4558): Process: android.process.media, PID: 4558
E/AndroidRuntime( 4558): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 4558): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4558): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4558): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4558): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4558): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4558): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:598)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/AndroidRuntime( 4558): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/AndroidRuntime( 4558): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/AndroidRuntime( 4558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 4558): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/AndroidRuntime( 4558): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/AndroidRuntime( 4558): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/AndroidRuntime( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 4558): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 4558): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 4558): 	... 12 more
I/PackageManager(  994): Failed to clean up mangled file: /data/system/packages-stopped.xml
I/Process ( 4558): Sending signal. PID: 4558 SIG: 9
I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "mms"
W/PackageManager(  994): Preserving older stopped packages backup
E/DropBoxManagerService(  994): Can't write: system_app_crash
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 5 more
F/PackageManager(  994): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  994): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1057)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
F/PackageManager(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
F/PackageManager(  994): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager(  994): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  994): 	... 9 more
I/ActivityManager(  994): Process android.process.media (pid 4558) has died.
W/ActivityManager(  994): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 1000ms
E/DropBoxManagerService(  994): Can't write: system_server_wtf
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop13.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService(  994): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  994): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService(  994): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService(  994): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 19 more
I/PackageManager(  994): Failed to clean up mangled file: /data/system/packages-stopped.xml
I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "mmsto"
W/PackageManager(  994): Preserving older stopped packages backup
F/PackageManager(  994): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  994): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1057)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
F/PackageManager(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
F/PackageManager(  994): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager(  994): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  994): 	... 9 more
D/WifiService(  994): Client connection lost with reason: 4
E/DropBoxManagerService(  994): Can't write: system_server_wtf
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop69.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService(  994): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  994): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService(  994): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService(  994): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 19 more
I/PackageManager(  994): Failed to clean up mangled file: /data/system/packages-stopped.xml
I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  994):   Scheme: "sms"
W/PackageManager(  994): Preserving older stopped packages backup
I/ActivityManager(  994): Start proc android.process.media for restart android.process.media: pid=4611 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager(  994): Process com.google.android.gms (pid 1730) has died.
F/PackageManager(  994): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  994): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1057)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
F/PackageManager(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
F/PackageManager(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
F/PackageManager(  994): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager(  994): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  994): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  994): 	... 9 more
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10976ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10976ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10976ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10976ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10975ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20975ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 30975ms
W/ActivityManager(  994): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 40975ms
,E/DropBoxManagerService(  994): Can't write: system_server_wtf
E/DropBoxManagerService(  994): java.io.FileNotFoundException: /data/system/dropbox/drop74.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  994): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  994): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  994): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService(  994): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService(  994): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  994): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService(  994): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService(  994): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService(  994): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService(  994): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService(  994): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService(  994): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  994): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  994): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  994): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  994): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  994): 	... 19 more
I/PackageManager(  994): Failed to clean up mangled file: /data/system/packages-stopped.xml
,I/PackageManager(  994): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  994):   Action: "android.intent.action.SENDTO"
I/PackageManager(  994):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  994):   Scheme: "smsto"

```
