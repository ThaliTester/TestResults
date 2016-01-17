#### Test 56151093914d164_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
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
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4234): 
D/AndroidRuntime( 4234): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4234): CheckJNI is OFF
D/dalvikvm( 4234): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4234): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4234): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4234): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4234): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4234): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4234): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4234): failed to load memtrack module: -2
D/AndroidRuntime( 4234): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  988): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4234
W/WindowManager(  988): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  988): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4250 uid=10118 gids={50118, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4234): Shutting down VM
D/dalvikvm( 4234): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4250): Binding Chromium to main looper Looper (main, tid 1) {41f2be18}
I/LibraryLoader( 4250): Expected native library version number "",actual native library version number ""
I/chromium( 4250): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4250): Initializing chromium process, renderers=0
D/BluetoothManagerService(  988): Message: 20
D/BluetoothManagerService(  988): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43acb5c8:true
I/Adreno-EGL( 4250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4250): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4250): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4250): Local Branch: 
I/Adreno-EGL( 4250): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4250): Local Patches: NONE
I/Adreno-EGL( 4250): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4250): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4250): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4250): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4250): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4250): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4250): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4250): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4250): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4250): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4250): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4250): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4250): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4250): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4250): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4250): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4250): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4250): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4250): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4250): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4250): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4250): Enabling debug mode 0
,W/AwContents( 4250): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1208): onFinishInput()
,I/LaunchCheckinHandler(  988): Displayed com.test.thalitest/.MainActivity,cp,ca,406
I/ActivityManager(  988): Displayed com.test.thalitest/.MainActivity: +370ms (total +406ms)
W/AwContents( 4250): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4250): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4250): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4250): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f300e8
,D/dalvikvm( 4250): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f300e8
,D/jxcore_app_log( 4250): JniHelper::setJavaVM(0x4157afa8), pthread_self() = 1614466184
,D/JX-Cordova( 4250): jxcore cordova android initializing
,D/dalvikvm( 4250): GC_CONCURRENT freed 2691K, 16% free 14498K/17224K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 4250): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4250): GC_FOR_ALLOC freed 420K, 14% free 14913K/17224K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4250): Grow heap (frag case) to 16.657MB for 63974-byte allocation
,D/dalvikvm( 4250): GC_FOR_ALLOC freed 142K, 14% free 14916K/17288K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4250): Grow heap (frag case) to 16.690MB for 95956-byte allocation
,D/dalvikvm( 4250): GC_FOR_ALLOC freed 178K, 14% free 14950K/17384K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4250): Grow heap (frag case) to 16.769MB for 143930-byte allocation
,D/dalvikvm( 4250): GC_FOR_ALLOC freed 251K, 15% free 14998K/17528K, paused 26ms, total 26ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 16.884MB for 215890-byte allocation
D/dalvikvm( 4250): GC_FOR_ALLOC freed 366K, 16% free 15071K/17740K, paused 25ms, total 26ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 17.059MB for 323830-byte allocation
D/dalvikvm( 4250): GC_FOR_ALLOC freed 565K, 16% free 15192K/18060K, paused 27ms, total 27ms
D/dalvikvm( 4250): GC_FOR_ALLOC freed 858K, 15% free 15368K/18060K, paused 27ms, total 27ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 17.735MB for 728606-byte allocation
D/dalvikvm( 4250): GC_FOR_ALLOC freed 1274K, 17% free 15624K/18772K, paused 27ms, total 28ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 18.333MB for 1092904-byte allocation
D/dalvikvm( 4250): GC_CONCURRENT freed 1858K, 20% free 16022K/19840K, paused 2ms+4ms, total 35ms
D/dalvikvm( 4250): GC_FOR_ALLOC freed 121K, 20% free 15999K/19840K, paused 26ms, total 26ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 19.219MB for 1639352-byte allocation
D/dalvikvm( 4250): GC_CONCURRENT freed 1921K, 23% free 16540K/21444K, paused 2ms+4ms, total 35ms
D/dalvikvm( 4250): GC_FOR_ALLOC freed 1039K, 23% free 16518K/21444K, paused 28ms, total 28ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 20.508MB for 2459024-byte allocation
D/dalvikvm( 4250): GC_CONCURRENT freed 303K, 21% free 18871K/23848K, paused 4ms+5ms, total 37ms
D/dalvikvm( 4250): GC_FOR_ALLOC freed 4173K, 27% free 17555K/23848K, paused 36ms, total 43ms
I/dalvikvm-heap( 4250): Grow heap (frag case) to 22.694MB for 3688532-byte allocation
D/dalvikvm( 4250): GC_CONCURRENT freed 352K, 24% free 21014K/27452K, paused 4ms+6ms, total 49ms
,D/dalvikvm( 4250): GC_FOR_ALLOC freed 4392K, 33% free 18664K/27452K, paused 33ms, total 33ms
,W/jxcore-log( 4250): Initializing JXcore engine
,W/jxcore-log( 4250): JXcore engine is ready
,D/dalvikvm( 4250): GC_CONCURRENT freed 403K, 22% free 21482K/27452K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 4250): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/jxcore-log( 4250): Starting JXcore engine
,W/jxcore-log( 4250): Platform android
W/jxcore-log( 4250): 
,W/jxcore-log( 4250): Process ARCH arm
W/jxcore-log( 4250): 
,I/jxcore-log( 4250): JXcore Cordova bridge is ready!
I/jxcore-log( 4250): 
,W/jxcore-log( 4250): JXcore engine is started
,I/chromium( 4250): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4250): Toggling radios to true
I/jxcore-log( 4250): 
,D/BluetoothAdapter( 4250): enable(): BT is already enabled..!
D/WifiService(  988): New client listening to asynchronous messages
D/WifiService(  988): setWifiEnabled: true pid=4250, uid=10118
,E/WifiService(  988): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine(  988): handleMessage: E msg.what=131145
D/WifiStateMachine(  988): processMsg: ConnectedState
D/WifiStateMachine(  988): processMsg: L2ConnectedState
I/jxcore-log( 4250): Radios toggled
I/jxcore-log( 4250): 
I/jxcore-log( 4250): My device name is: motorola-XT1039
I/jxcore-log( 4250): 
,I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
D/TCMD    (  389): NL - Read 1000 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
,D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 1000 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 68 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 68 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
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
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering(  988): InitialState.processMessage what=4
,D/Tethering(  988): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService(  988): WiFi NOT Tethered!,
D/WifiStateMachine(  988): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  988): handleMessage: new destination call exit/enter
D/WifiStateMachine(  988): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  988): invokeExitMethods: ConnectedState
D/WifiStateMachine(  988): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  988): Stopping DHCP and clearing IP
D/WifiStateMachine(  988): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  988): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  988): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  389): NL - Read 60 bytes from update socket.
D/TCMD    (  389): NL - ignore NL message, type = 21
,D/TCMD    (  389): Listening for incoming client connection request
,D/WifiStateMachine(  988): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  988): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  988): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics(  988): connected time updated 308528
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  988): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  988): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService(  988): Attempting to switch to mobile
D/ConnectivityService(  988): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  988): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService(  988): resetConnections(wlan0, 3)
D/NetUtils(  988): android_net_utils_resetConnections in env=0x615ccaa0 clazz=0x64c00001 iface=wlan0 mask=0x3
D/WifiStateMachine(  988): moveTempStackToStateStack: i=0,j=4
D/Checkin (  988): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine(  988): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine(  988): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  988): DisconnectingState
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=131146
D/WifiStateMachine(  988): processMsg: DisconnectingState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=147460
D/WifiStateMachine(  988): processMsg: DisconnectingState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): Network connection lost
D/WifiStateMachine(  988): Stopping DHCP and clearing IP
D/WifiStateMachine(  988): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1382): Read error: ssl=0x62e0bdc8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1382): SSL shutdown failed: ssl=0x62e0bdc8: I/O error during system call, Broken pipe
,D/WifiP2pService(  988): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  988): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine(  988): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine(  988): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  988): handleMessage: new destination call exit/enter
D/WifiStateMachine(  988): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/Checkin (  988): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine(  988): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  988): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  988): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  988): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=131101
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
D/WifiStateMachine(  988): processMsg: DefaultState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=131216
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
D/WifiStateMachine(  988): processMsg: DefaultState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=131216
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
D/WifiStateMachine(  988): processMsg: DefaultState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  988): processMsg: ConnectModeState
,D/WifiStateMachine(  988): handleMessage: X
,D/Nat464Xlat(  988): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  988): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  988): Attempting to switch to mobile
D/ConnectivityService(  988): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService(  988): Attempting to switch to ETHERNET
,D/Nat464Xlat(  988): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  988): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1191): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  988): handleMessage: E msg.what=147461
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
D/TCMD    (  389): NL - Read 56 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
,D/TCMD    (  389): Listening for incoming client connection request
,E/wpa_supplicant( 1191): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine(  988): handleMessage: X
,D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  988): processMsg: ConnectModeState
,D/WifiStateMachine(  988): handleMessage: X
,I/wpa_supplicant( 1191): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1191): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  389): NL - Read 312 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 88 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 68 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 1000 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
,D/TCMD    (  389): Listening for incoming client connection request
I/wpa_supplicant( 1191): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): handleMessage: X
D/Tethering(  988): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  988): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  389): NL - Read 80 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 80 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
D/TCMD    (  389): Listening for incoming client connection request
D/TCMD    (  389): NL - Read 68 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
,D/TCMD    (  389): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1191): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  389): NL - Read 1000 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
,D/TCMD    (  389): Listening for incoming client connection request
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1205779704
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1,
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: DisconnectedState
,D/WifiStateMachine(  988): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  988): processMsg: ConnectModeState
,D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=147459
D/WifiStateMachine(  988): processMsg: DisconnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): Network connection established
,D/WifiStateMachine(  988): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine(  988): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  988): handleMessage: new destination call exit/enter
D/WifiStateMachine(  988): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  988): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  988): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  988): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  988): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine(  988): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  988): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  988): handleMessage: X
,D/WifiStateMachine(  988): handleMessage: E msg.what=131101
D/WifiStateMachine(  988): processMsg: ObtainingIpState
D/WifiStateMachine(  988): ObtainingIpState{ when=-21ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4463c8c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): processMsg: L2ConnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
,D/WifiStateMachine(  988): processMsg: SupplicantStartedState
D/WifiStateMachine(  988): processMsg: DefaultState
,D/WifiStateMachine(  988): handleMessage: X
,D/WifiStateMachine(  988): handleMessage: E msg.what=147462
D/WifiStateMachine(  988): processMsg: ObtainingIpState
D/WifiStateMachine(  988): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@43c27f70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): processMsg: L2ConnectedState
,D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=196612
D/WifiStateMachine(  988): processMsg: ObtainingIpState
D/WifiStateMachine(  988): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  988): processMsg: L2ConnectedState
,D/WifiStateMachine(  988): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine(  988): Unexpected BatchedScanResults :OK
D/WifiP2pService(  988): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42778d40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  988): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42778d40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/TCMD    (  389): NL - Read 56 bytes from update socket.
D/TCMD    (  389): NL - message type is RTM_NEWLINK
,D/TCMD    (  389): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiP2pService(  988): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): InactiveState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43b782c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  988): P2pEnabledState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43b782c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  988): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43b782c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): handleMessage: E msg.what=147461
D/WifiStateMachine(  988): processMsg: ObtainingIpState
D/WifiStateMachine(  988): ObtainingIpState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): processMsg: L2ConnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
,D/WifiStateMachine(  988): handleMessage: X
,D/TCMD    (  389): NL - Read 60 bytes from update socket.
D/TCMD    (  389): NL - ignore NL message, type = 20
,D/TCMD    (  389): Listening for incoming client connection request
,D/WifiStateMachine(  988): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  988): handleMessage: E msg.what=131215
D/WifiStateMachine(  988): processMsg: ObtainingIpState
D/WifiStateMachine(  988): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  988): processMsg: L2ConnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
,D/WifiStateMachine(  988): processMsg: DefaultState
,D/WifiStateMachine(  988): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  988): handleMessage: X
,D/WifiStateMachine(  988): handleMessage: E msg.what=196613
,D/WifiStateMachine(  988): processMsg: ObtainingIpState
D/WifiStateMachine(  988): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): processMsg: L2ConnectedState
D/WifiStateMachine(  988): setSuspendOptimizationsNative: 1 true
D/WifiP2pService(  988): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  988): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  988): DHCP successful
D/WifiStateMachine(  988): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  988): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine(  988): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  988): handleMessage: new destination call exit/enter
D/WifiStateMachine(  988): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  988): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  988): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  988): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine(  988): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  988): VerifyingLinkState enter
D/WifiStateMachine(  988): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine(  988): handleMessage: X
,D/WifiStateMachine(  988): handleMessage: E msg.what=151572
D/WifiStateMachine(  988): processMsg: VerifyingLinkState
D/WifiStateMachine(  988): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine(  988): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine(  988): handleMessage: X
,D/WifiStateMachine(  988): handleMessage: E msg.what=135190
D/WifiStateMachine(  988): processMsg: VerifyingLinkState
D/WifiStateMachine(  988): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  988): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  988): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  988): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  988): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  988): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  988): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine(  988): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  988): CaptivePortalCheckState enter
,D/WifiStateMachine(  988): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService(  988): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  988): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  988): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  988): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=131092
D/WifiStateMachine(  988): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  988): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  988): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService(  988): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService(  988): WiFi NOT Tethered!
,E/ConnectivityService(  988): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff7c60
I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine(  988): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  988): handleMessage: new destination call exit/enter
D/WifiStateMachine(  988): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  988): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  988): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  988): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine(  988): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  988): handleMessage: X
D/WifiStateMachine(  988): handleMessage: E msg.what=131092
D/WifiStateMachine(  988): processMsg: ConnectedState
,D/WifiStateMachine(  988): processMsg: L2ConnectedState
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat(  988): requiresClat: netType=1, hasIPv4Address=true
D/Checkin (  988): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
D/WifiStateMachine(  988): processMsg: DefaultState
D/WifiStateMachine(  988): handleMessage: X
,I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService(  988): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService(  988): WiFi NOT Tethered!
E/ConnectivityService(  988): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff7c60
,D/ConnectivityService(  988): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  988): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
D/Tethering(  988): MasterInitialState.processMessage what=3
,D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  988): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  988): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager(  988): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4379 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/SBar.NetworkController( 1092): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1612): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1612): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/OtaApp  ( 1612): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1612): [debug] > CusSM.onRadioDown
,D/Tethering(  988): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  988): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/dalvikvm( 4379): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f33b88, skipping init
I/openssl ( 4379): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4379): Crypto mode 0 already enabled
,I/ActivityManager(  988): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4411 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager(  988): Killing 3941:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4411): mnc/mcc: 
,V/MmsConfig( 4411): tag: bool value: enabledMMS - true
V/MmsConfig( 4411): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4411): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4411): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4411): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4411): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4411): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4411): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4411): tag: int value: recipientLimit - 20
,V/MmsConfig( 4411): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4411): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4411): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4411): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4411): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4411): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4411): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4411): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4411): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager(  988): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4430 uid=10041 gids={50041, 3003}
,I/ActivityManager(  988): Killing 4059:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/MobileConnectivityChangeReceiver( 4430): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4430): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4430): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4430): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  988): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4444 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager(  988): Killing 4103:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1719): Checkin interval check for package: unspecified last checkin: 1453042895613 min interval config: 0 actual interval: 294751
,I/CheckinService( 1719): Checking schedule, now: 1453043190370 next: 1453042925593
,I/CheckinService( 1719): active receiver: enabled
,I/CheckinService( 1719): Preparing to send checkin request
,I/EventLogService( 1719): Accumulating logs since 1453042890978
,D/ConnectivityService(  988): NetTransition Wakelock for ConnectedState released by timeout
,I/CheckinRequestBuilder( 1719): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1719): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4444): Binding Chromium to main looper Looper (main, tid 1) {41f247f8}
,I/LibraryLoader( 4444): Expected native library version number "",actual native library version number ""
,I/chromium( 4444): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4444): Initializing chromium process, renderers=0
,D/dalvikvm(  988): GC_EXPLICIT freed 25306K, 65% free 18810K/53632K, paused 4ms+12ms, total 149ms
,E/AudioManagerAndroid( 4444): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4444): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4444): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4444): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4444): Local Branch: 
I/Adreno-EGL( 4444): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4444): Local Patches: NONE
I/Adreno-EGL( 4444): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4444): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager(  988): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4475 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
W/GAV2    ( 4444): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4444): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4475): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4475): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4475): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4475): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4475): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4475): install
,I/MultiDex( 4475): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4475): loading existing secondary dex files
,I/MultiDex( 4475): load found 3 secondary dex files
,I/MultiDex( 4475): install done
,D/dalvikvm( 4475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4475): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4475): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4475): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4475): VFY: unable to resolve instance field 36
,D/dalvikvm( 4475): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4475): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4475): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4475): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4475): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4475): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2ae90
,D/dalvikvm( 4475): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2ae90
,D/dalvikvm( 4475): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2ae90, skipping init
,D/dalvikvm( 4475): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2ae90
,D/dalvikvm( 4475): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2ae90
,V/JNIHelp ( 4475): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4475): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2ae90
,D/dalvikvm( 4475): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f2ae90
D/dalvikvm( 4475): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2ae90
,D/dalvikvm( 4475): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f2ae90
,I/NSApplication( 4444): Starting up...
,I/ActivityManager(  988): Killing 3780:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  988): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4499 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4475): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4499): VFY: unable to resolve instance field 68
,D/dalvikvm( 4499): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4499): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4499): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,I/dalvikvm( 4475): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4475): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4475): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4475): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x000d
,D/DEBUG   ( 1612): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4499): VFY: unable to resolve instance field 68
,D/dalvikvm( 4499): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4499): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4499): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4499): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4499): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,W/ContextImpl( 1612): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,I/ActivityManager(  988): Killing 4143:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,D/GetNotificationsWS( 1612): bindWebServices(): registering our AIDL callback...
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/SundryService( 1612): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1612): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1612): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1612): onServiceConnected()
D/GetNotificationsWS( 1612): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1612): unbindWebServices(): un-registering our AIDL callback...
,I/dalvikvm( 4475): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4475): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4475): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4475): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4475): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4475): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4475): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4475): VFY: replacing opcode 0x6e at 0x0036
I/openssl ( 4379): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4379): Crypto mode 0 already enabled
I/dalvikvm( 4475): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4475): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/dalvikvm( 4475): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
D/MobileConnectivityChangeReceiver( 4430): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4430): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52fb000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52fb000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/WearableService( 1240): callingUid 10022, callindPid: 1240
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3773153410
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4250): 
,E/MDM     ( 1240): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/LocationInitializer( 1719): Restart initialization of location
,D/AuthorizationBluetoothService( 1382): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1382): Proximity feature is not enabled.
,W/GCoreFlp( 1240): No location to return for getLastLocation()
,W/FusedLocationProvider( 1240): location=null
,V/GLSActivity( 1382): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4475): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4475): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4210eb80
,D/dalvikvm( 4475): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4210eb80
D/dalvikvm( 4475): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4210eb80, skipping init
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,W/Settings( 4475): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4475): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4533): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4475): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4475): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 81ms
,I/Adreno-EGL( 4475): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4475): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4475): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4475): Local Branch: 
I/Adreno-EGL( 4475): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4475): Local Patches: NONE
I/Adreno-EGL( 4475): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4250): 
,I/Adreno-EGL( 4475): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4475): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4475): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4475): Local Branch: 
I/Adreno-EGL( 4475): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4475): Local Patches: NONE
I/Adreno-EGL( 4475): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4250): 
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4250): 
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4250): 
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4250): 
,I/jxcore-log( 4250): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4250): 
,D/Tethering(  988): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  988): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/PollingManager( 1612): now: 342442 ,futureTime: 53513021
,D/PollingManager( 1612): Polling alarm set to expire at: 53513021 Current Time: 342442
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1612): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1612): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1612): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1612): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
D/Tethering(  988): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  988): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/PollingManager( 1612): now: 342472 ,futureTime: 53513021
,D/PollingManager( 1612): Polling alarm set to expire at: 53513021 Current Time: 342473
,E/ActivityThread( 1612): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1612): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1612): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
I/openssl ( 4379): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4379): Crypto mode 0 already enabled
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MobileConnectivityChangeReceiver( 4430): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4430): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1612): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Adreno-EGL( 4475): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4475): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4475): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4475): Local Branch: 
I/Adreno-EGL( 4475): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4475): Local Patches: NONE
I/Adreno-EGL( 4475): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinService( 1719): Checkin interval check for package: unspecified last checkin: 1453042895613 min interval config: 0 actual interval: 296943
,D/DEBUG   ( 1612): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/Adreno-EGL( 4475): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4475): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4475): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4475): Local Branch: 
I/Adreno-EGL( 4475): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4475): Local Patches: NONE
I/Adreno-EGL( 4475): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/ContextImpl( 1612): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1612): bindWebServices(): registering our AIDL callback...
,D/OtaApp  ( 1612): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1612): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/EmailService.MarketingOptInSetter( 1612): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1612): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1612): onServiceConnected()
,D/GetNotificationsWS( 1612): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1612): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1612): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4379): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4379): Crypto mode 0 already enabled
D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1612): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1612): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MobileConnectivityChangeReceiver( 4430): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4430): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1612): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1719): Checkin interval check for package: unspecified last checkin: 1453042895613 min interval config: 0 actual interval: 297048
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DEBUG   ( 1612): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,W/ContextImpl( 1612): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1612): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1612): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1612): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/GetNotificationsWS( 1612): onServiceConnected()
D/GetNotificationsWS( 1612): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1612): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1612): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1612): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager(  988): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1612
D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=4085799546
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1612): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1612): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1612): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1612): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1612): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1612): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1612): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1612): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1612): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  988): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1612
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1612): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1612): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1612): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1612): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1612): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1612): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1208): onFinishInput()
,I/jxcore-log( 4250): Test app app.js loaded
I/jxcore-log( 4250): 
,I/Choreographer( 4250): Skipped 372 frames!  The application may be doing too much work on its main thread.
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,W/IInputConnectionWrapper( 4250): showStatusIcon on inactive InputConnection
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/chromium( 4250): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  988): Activity reported stop, but no longer stopping: ActivityRecord{428495d0 u0 com.motorola.ccc.ota/.ui.DownloadActivity t2}
,I/CheckinRequestBuilder( 1719): Classify the device as Phone.
,I/LaunchCheckinHandler(  988): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,273
,I/jxcore-log( 4250): --= Surplus to requirements =--
I/jxcore-log( 4250): 
I/jxcore-log( 4250): ****TEST TOOK:  ms ****
I/jxcore-log( 4250): 
,I/jxcore-log( 4250): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4250): 
,I/CheckinTask( 1719): Sending checkin request (11756 bytes)
,D/AndroidRuntime( 4577): 
D/AndroidRuntime( 4577): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4577): CheckJNI is OFF
,D/dalvikvm( 4577): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4577): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4577): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4577): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4577): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4577): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4577): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4577): failed to load memtrack module: -2
,D/AndroidRuntime( 4577): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  988): Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,I/ActivityManager(  988): Killing 4250:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  988):   Force finishing activity ActivityRecord{447ce218 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState(  988): WIN DEATH: Window{44a08488 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  988): Client connection lost with reason: 4
,I/CheckinRequestBuilder( 1719): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  988): Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,E/ActivityThread( 1719): Failed to find provider info for com.google.android.wearable.settings
,W/GeofencerStateMachine( 1240): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1208): resetDictionaries() : en_GB
,I/InputReader(  988): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1208): run()
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "sms"
,I/Decoder ( 1208): createOrResetDecoder
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "smsto"
,D/WifiStateMachine(  988): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  988): handleMessage: E msg.what=131215
,D/WifiStateMachine(  988): processMsg: ConnectedState
,D/WifiStateMachine(  988): processMsg: L2ConnectedState
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiStateMachine(  988): processMsg: ConnectModeState
D/WifiStateMachine(  988): processMsg: DriverStartedState
D/WifiStateMachine(  988): processMsg: SupplicantStartedState
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "mms"
,D/WifiStateMachine(  988): processMsg: DefaultState
,D/WifiStateMachine(  988): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "mmsto"
D/VoicemailCleanupService( 1192): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1719): GC_EXPLICIT freed 1736K, 31% free 12041K/17224K, paused 5ms+7ms, total 93ms
,D/WifiStateMachine(  988): handleMessage: X
,D/dalvikvm( 2317): GC_EXPLICIT freed 5214K, 44% free 9651K/17224K, paused 10ms+12ms, total 92ms
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "sms"
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "smsto"
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "mms"
,D/dalvikvm( 1326): GC_EXPLICIT freed 3260K, 33% free 11643K/17224K, paused 72ms+9ms, total 162ms
,I/Launcher( 1326): Deferring update until onResume
D/BackupManagerService(  988): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  988): removePackageParticipantsLocked: uid=10118 #1
I/ConfigService( 1240): onCreate
,D/dalvikvm( 2349): GC_EXPLICIT freed 4088K, 42% free 10093K/17224K, paused 8ms+5ms, total 96ms
,I/PackageManager(  988): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  988):   Action: "android.intent.action.SENDTO"
I/PackageManager(  988):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  988):   Scheme: "mmsto"
,I/ActivityManager(  988): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4607 uid=10033 gids={50033, 3003, 1028, 1015}
,D/ConnectivityService(  988): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  988):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat(  988): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  988): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  988): requiresClat: netType=1, hasIPv4Address=true
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): run()
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/Launcher( 1326): Deferring update until onResume
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1208): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1208): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1208): run()
I/StatsUtilsManager( 1208): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1208): shouldRecordStats() = Too Soon
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/InternalIcingCorporaPro( 2349): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  988): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4626 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager(  988): Killing 4171:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  988): GC_EXPLICIT freed 1845K, 65% free 18778K/53632K, paused 20ms+19ms, total 299ms
,D/dalvikvm( 1382): GC_EXPLICIT freed 1496K, 40% free 10387K/17224K, paused 2ms+12ms, total 53ms
,D/AndroidRuntime( 4577): Shutting down VM
,D/dalvikvm( 4577): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ContextImpl( 4626): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/dalvikvm(  988): GC_EXPLICIT freed 129K, 66% free 18663K/53632K, paused 8ms+9ms, total 100ms
,I/InternalIcingCorporaPro( 2349): UpdateCorporaTask done [took 188 ms] updated apps [took 188 ms] 
,I/dalvikvm( 3539): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3539): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3539): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1719): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1719): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1719): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1719): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1719): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1719): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1719): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1382): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1382): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1719): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1719): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1719): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1719): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1719): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,I/Icing   ( 1719): doRemovePackageData com.test.thalitest
,D/gH_CompatibleDatabase( 1719): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1719): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  988): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4654 uid=10059 gids={50059, 1028, 3003, 1015}
,D/gH_CompatibleDatabase( 1719): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1719): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1719): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1719): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1719): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1719): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  988): Killing 4379:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinRequestBuilder( 1719): Classify the device as Phone.
,I/CheckinTask( 1719): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1719): Checking schedule, now: 1453043194534 next: 1453592848529
,I/CheckinService( 1719): active receiver: disabled
,I/CheckinService( 1719): Checking schedule, now: 1453043194554 next: 1453592848529
,I/CheckinService( 1719): active receiver: disabled
,D/CheckinService( 1719): Recording last checkin time for package unspecified as 1453043194559
,I/dalvikvm( 4654): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 4654): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4654): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4654): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4654):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4654):   adb logcat -s GAv4
,W/GAv4    ( 4654): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.

```
