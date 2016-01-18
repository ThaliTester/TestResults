#### Test 56151093b6ab50f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1021): sending alarm Alarm{448cdb68 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4307): 
D/AndroidRuntime( 4307): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4307): CheckJNI is OFF
D/dalvikvm( 4307): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4307): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4307): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4307): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4307): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4307): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4307): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4307): failed to load memtrack module: -2
D/AndroidRuntime( 4307): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4307
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4323 uid=10120 gids={50120, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4307): Shutting down VM
D/dalvikvm( 4307): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4323): Binding Chromium to main looper Looper (main, tid 1) {41f79bc8}
I/LibraryLoader( 4323): Expected native library version number "",actual native library version number ""
I/chromium( 4323): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4323): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44127848:true
I/Adreno-EGL( 4323): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4323): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4323): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4323): Local Branch: 
I/Adreno-EGL( 4323): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4323): Local Patches: NONE
I/Adreno-EGL( 4323): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4323): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4323): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4323): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4323): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4323): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4323): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4323): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4323): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4323): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4323): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4323): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4323): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4323): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4323): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4323): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4323): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4323): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4323): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4323): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4323): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4323): Enabling debug mode 0
,W/AwContents( 4323): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1208): onFinishInput()
,W/IInputConnectionWrapper( 4323): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,455
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +427ms (total +455ms)
,D/JsMessageQueue( 4323): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4323): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7e078
,D/dalvikvm( 4323): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7e078
,D/jxcore_app_log( 4323): JniHelper::setJavaVM(0x415c7fa8), pthread_self() = 1614776752
,D/JX-Cordova( 4323): jxcore cordova android initializing
,D/dalvikvm( 4323): GC_CONCURRENT freed 2694K, 16% free 14495K/17224K, paused 2ms+4ms, total 40ms
,D/dalvikvm( 4323): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 421K, 14% free 14912K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 16.657MB for 63974-byte allocation
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 115K, 14% free 14943K/17288K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 16.716MB for 95956-byte allocation
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 194K, 14% free 14962K/17384K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 16.781MB for 143930-byte allocation
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 263K, 15% free 14997K/17528K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 16.884MB for 215890-byte allocation
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 366K, 16% free 15071K/17740K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 17.059MB for 323830-byte allocation
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 565K, 16% free 15192K/18060K, paused 26ms, total 26ms
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 858K, 15% free 15367K/18060K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 17.735MB for 728606-byte allocation
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 1274K, 17% free 15624K/18772K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 18.333MB for 1092904-byte allocation
,D/dalvikvm( 4323): GC_CONCURRENT freed 1928K, 20% free 16031K/19840K, paused 1ms+5ms, total 50ms
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 30K, 20% free 16020K/19840K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 19.241MB for 1639352-byte allocation
,D/dalvikvm( 4323): GC_CONCURRENT freed 1927K, 23% free 16538K/21444K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 1053K, 23% free 16520K/21444K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 20.510MB for 2459024-byte allocation
,D/dalvikvm( 4323): GC_CONCURRENT freed 1958K, 28% free 17333K/23848K, paused 2ms+4ms, total 48ms
,D/dalvikvm( 4323): GC_CONCURRENT freed 2528K, 27% free 17546K/23848K, paused 2ms+6ms, total 52ms
,D/dalvikvm( 4323): WAIT_FOR_CONCURRENT_GC blocked 35ms
,I/dalvikvm-heap( 4323): Grow heap (frag case) to 22.685MB for 3688532-byte allocation
,D/dalvikvm( 4323): GC_CONCURRENT freed 505K, 24% free 20967K/27452K, paused 4ms+7ms, total 75ms
,D/dalvikvm( 4323): GC_FOR_ALLOC freed 4242K, 33% free 18650K/27452K, paused 32ms, total 35ms
,W/jxcore-log( 4323): Initializing JXcore engine
,W/jxcore-log( 4323): JXcore engine is ready
,D/dalvikvm( 4323): GC_CONCURRENT freed 394K, 22% free 21473K/27452K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 4323): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4323): Starting JXcore engine
,W/jxcore-log( 4323): Platform android
W/jxcore-log( 4323): 
,W/jxcore-log( 4323): Process ARCH arm
W/jxcore-log( 4323): 
,I/jxcore-log( 4323): JXcore Cordova bridge is ready!
I/jxcore-log( 4323): 
,W/jxcore-log( 4323): JXcore engine is started
,I/chromium( 4323): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4323): Toggling radios to true
I/jxcore-log( 4323): 
,D/BluetoothAdapter( 4323): enable(): BT is already enabled..!
D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=4323, uid=10120
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4323): Radios toggled
I/jxcore-log( 4323): 
I/jxcore-log( 4323): My device name is: motorola-XT1039
I/jxcore-log( 4323): 
,I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  274): send SAR ctrl over QMI
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1021): InitialState.processMessage what=4
,D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1021): WiFi NOT Tethered!
D/TCMD    (  441): NL - Read 1000 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 1000 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 68 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 68 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/dalvikvm( 1021): Jit: resizing JitTable from 8192 to 16384
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  441): NL - Read 60 bytes from update socket.
D/TCMD    (  441): NL - ignore NL message, type = 21
,D/TCMD    (  441): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 313855
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectingState
I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1021): DisconnectingState
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/ConnectivityService( 1021): Attempting to switch to mobile
,D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection lost
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x61621078 clazz=0x61a00001 iface=wlan0 mask=0x3
D/CommandListener(  272): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1391): Read error: ssl=0x62fee0b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1391): SSL shutdown failed: ssl=0x62fee0b0: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1021): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1165): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
E/wpa_supplicant( 1165): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1165): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1165): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  441): NL - Read 312 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 192 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 68 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 1000 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1165): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  441): NL - Read 80 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 80 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 68 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274):  STA Connected !!
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): Network connection established
D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/TCMD    (  441): NL - Read 1000 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193727152
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  274): send SAR ctrl over QMI
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
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
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-24ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@448f4870 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@43c51df0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4279f0d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4279f0d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 f
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 f
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 f
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 f
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 fe
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 fe
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 fc
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 fc
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 10
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 10
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@437c8ff8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@437c8ff8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@437c8ff8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
,D/TCMD    (  441): NL - Read 60 bytes from update socket.
D/TCMD    (  441): NL - ignore NL message, type = 20
,D/TCMD    (  441): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
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
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1021): WiFi NOT Tethered!
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@420359a0
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
,D/WifiStateMachine( 1021): processMsg: ConnectedState
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1021): WiFi NOT Tethered!
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@420359a0
I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1304): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1092): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1627): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager( 1021): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4447 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1627): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1627): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1627): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1627): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1627): Registering with Alarm Manager to restart CCE
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/OtaApp  ( 1627): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1627): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4474 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4447): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f81b18, skipping init
I/openssl ( 4447): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4447): Crypto mode 0 already enabled
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
I/ActivityManager( 1021): Killing 3997:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,V/MmsConfig( 4474): mnc/mcc: 
V/MmsConfig( 4474): tag: bool value: enabledMMS - true
,V/MmsConfig( 4474): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4474): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4474): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 4474): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4474): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4474): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4474): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4474): tag: int value: recipientLimit - 20
,V/MmsConfig( 4474): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4474): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4474): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4474): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4474): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4474): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4474): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4474): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4474): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4496 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 4122:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4496): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4496): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4509 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4175:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1774): Checkin interval check for package: unspecified last checkin: 1453102449471 min interval config: 0 actual interval: 299431
,I/CheckinService( 1774): Checking schedule, now: 1453102748912 next: 1453102479423
,I/CheckinService( 1774): active receiver: enabled
,I/CheckinService( 1774): Preparing to send checkin request
,I/EventLogService( 1774): Accumulating logs since 1453102444825
,I/CheckinRequestBuilder( 1774): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1774): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4509): Binding Chromium to main looper Looper (main, tid 1) {41f72910}
,I/LibraryLoader( 4509): Expected native library version number "",actual native library version number ""
,I/chromium( 4509): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4509): Initializing chromium process, renderers=0
,D/dalvikvm( 1021): GC_EXPLICIT freed 25216K, 65% free 18745K/53432K, paused 4ms+10ms, total 148ms
,E/AudioManagerAndroid( 4509): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4509): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4509): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4509): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4509): Local Branch: 
I/Adreno-EGL( 4509): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4509): Local Patches: NONE
I/Adreno-EGL( 4509): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1391): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1391): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4509): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4509): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4509): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4545 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4545): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4545): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4545): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4545): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4545): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4545): install
,I/MultiDex( 4545): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4545): loading existing secondary dex files
,I/MultiDex( 4545): load found 3 secondary dex files
,I/MultiDex( 4545): install done
,D/dalvikvm( 4545): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4545): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4545): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4545): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4545): VFY: unable to resolve instance field 36
,D/dalvikvm( 4545): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4545): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4545): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4545): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4545): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4545): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f78e10
D/dalvikvm( 4545): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f78e10
,D/dalvikvm( 4545): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f78e10, skipping init
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f78e10
D/dalvikvm( 4545): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f78e10
,V/JNIHelp ( 4545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f78e10
D/dalvikvm( 4545): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f78e10
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f78e10
,D/dalvikvm( 4545): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f78e10
,I/NSApplication( 4509): Starting up...
,I/ActivityManager( 1021): Killing 3859:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4565 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4545): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4545): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4545): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4545): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4565): VFY: unable to resolve instance field 68
,D/dalvikvm( 4565): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4565): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4565): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
I/dalvikvm( 4545): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4545): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4545): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4545): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4545): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4545): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4545): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4545): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4545): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4545): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/openssl ( 4447): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4447): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4565): VFY: unable to resolve instance field 68
,D/dalvikvm( 4565): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4565): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4565): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/dalvikvm( 4565): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4565): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager( 1021): Killing 4215:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb518e000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb518e000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DEBUG   ( 1627): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,W/ContextImpl( 1627): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/GetNotificationsWS( 1627): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1627): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1627): onServiceConnected()
I/SundryService( 1627): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1627): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1627): onServiceConnected(): Registered for remote service callbacks...
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/GetNotificationsWS( 1627): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1235): callingUid 10022, callindPid: 1235
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4323): 
D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,E/MDM     ( 1235): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3394804314
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/LocationInitializer( 1774): Restart initialization of location
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/AuthorizationBluetoothService( 1391): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1391): Proximity feature is not enabled.
,V/GLSActivity( 1391): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1235): No location to return for getLastLocation()
,W/FusedLocationProvider( 1235): location=null
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1627): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1627): now: 346852 ,futureTime: 70586839
,D/PollingManager( 1627): Polling alarm set to expire at: 70586839 Current Time: 346852
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1627): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1627): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1627): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1627): [debug] > CusSM.onRadioUp
D/PollingManager( 1627): now: 346867 ,futureTime: 70586839
D/PollingManager( 1627): Polling alarm set to expire at: 70586839 Current Time: 346867
D/OtaApp  ( 1627): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/NativeLibraryUtils( 4545): Install completed successfully. count=14 extracted=0
,E/ActivityThread( 1627): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1627): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1627): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 4545): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42151ef0
D/dalvikvm( 4545): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42151ef0
,D/dalvikvm( 4545): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42151ef0, skipping init
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/OtaApp  ( 1627): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
I/openssl ( 4447): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4447): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1627): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1627): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/CheckinService( 1774): Checkin interval check for package: unspecified last checkin: 1453102449471 min interval config: 0 actual interval: 300561
,I/OtaApp  ( 1627): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1267): Column apn id key is 'apn_id'
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1627): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 1627): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DEBUG   ( 1627): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1627): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1627): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1627): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1627): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1627): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1627): onServiceConnected()
,D/GetNotificationsWS( 1627): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1627): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4447): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4447): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1774): Checkin interval check for package: unspecified last checkin: 1453102449471 min interval config: 0 actual interval: 300632
,D/DEBUG   ( 1627): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1627): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1627): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1627): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1627): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1627): onServiceConnected()
D/GetNotificationsWS( 1627): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1627): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1627): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1627): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1627
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1627): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1627): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1627): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1627): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1627): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1627): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1627): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1627): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1627): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1627): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1627): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1627): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1627): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1627
W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Keyboard.Facilitator( 1208): onFinishInput()
,D/OtaApp  ( 1627): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1627): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1627): [debug] > cancelling the previous pending intent set for download later
,I/WVCdm   (  278): CdmEngine::OpenSession
D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,I/OtaApp  ( 1627): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,D/OtaApp  ( 1627): [debug] > DownloadActivity, FormattedText
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/LaunchCheckinHandler( 1021): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,120
I/OtaApp  ( 1627): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
D/OtaApp  ( 1627): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 1627): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1627): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1627): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1627): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1164732264
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager( 1021): Activity reported stop, but no longer stopping: ActivityRecord{427eeec8 u0 com.motorola.ccc.ota/.ui.DownloadActivity t2}
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4323): 
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4323): 
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,W/Settings( 4545): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4323): 
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4323): 
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4323): 
,I/jxcore-log( 4323): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4323): 
,D/dalvikvm( 4545): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4616): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 4545): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4545): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 91ms
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4323): Test app app.js loaded
I/jxcore-log( 4323): 
,I/dalvikvm( 4323): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4323): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4323): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4323): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4323): BLE advertisement is supported
I/jxcore-log( 4323): 
,I/Choreographer( 4323): Skipped 371 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4323): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/IInputConnectionWrapper( 4323): showStatusIcon on inactive InputConnection
,I/CheckinRequestBuilder( 1774): Classify the device as Phone.
,V/NativeCrypto( 1774): SSL shutdown failed: ssl=0x6c15dc78: I/O error during system call, Connection timed out
,I/jxcore-log( 4323): --= Surplus to requirements =--
I/jxcore-log( 4323): 
I/jxcore-log( 4323): ****TEST TOOK:  ms ****
I/jxcore-log( 4323): 
,I/jxcore-log( 4323): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4323): 
,I/CheckinTask( 1774): Sending checkin request (11633 bytes)
,D/WifiStateMachine( 1021): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/ConnectivityService( 1021): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1021):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,D/AndroidRuntime( 4630): 
D/AndroidRuntime( 4630): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4630): CheckJNI is OFF
,D/dalvikvm( 4630): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4630): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4630): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4630): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4630): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4630): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4630): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4630): failed to load memtrack module: -2
,V/AlarmManager( 1021): sending alarm Alarm{42127e98 type 2 com.google.android.gms}
,D/AndroidRuntime( 4630): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10120 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 4323:com.test.thalitest/u0a120 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{431f8a38 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1021): WIN DEATH: Window{431ce6b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1021): Client connection lost with reason: 4
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10120 user=0: pkg removed
,D/dalvikvm( 1774): GC_EXPLICIT freed 1547K, 30% free 12096K/17224K, paused 4ms+6ms, total 44ms
,W/SQLiteConnectionPool( 1774): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 2343): GC_EXPLICIT freed 5199K, 44% free 9647K/17224K, paused 2ms+5ms, total 43ms
,I/Keyboard.Facilitator( 1208): resetDictionaries() : en_GB
D/dalvikvm( 2374): GC_EXPLICIT freed 4461K, 42% free 10103K/17224K, paused 3ms+9ms, total 113ms
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1208): run()
,W/GeofencerStateMachine( 1235): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1208): createOrResetDecoder
,D/VoicemailCleanupService( 1191): Cleaning up data for package: com.test.thalitest
,I/CheckinRequestBuilder( 1774): Checkin reason type: 8 attempt count: 1
,D/dalvikvm( 1319): GC_EXPLICIT freed 3257K, 33% free 11598K/17224K, paused 2ms+10ms, total 48ms
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1021):   Scheme: "sms"
,E/ActivityThread( 1774): Failed to find provider info for com.google.android.wearable.settings
I/ConfigService( 1235): onCreate
,I/Launcher( 1319): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1021):   Scheme: "smsto"
I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4656 uid=10033 gids={50033, 3003, 1028, 1015}
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
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10120 #1
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/Launcher( 1319): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/GoogleURLConnFactory( 1235): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): run()
,I/InternalIcingCorporaPro( 2374): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4674 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1021): Killing 4244:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1021): GC_EXPLICIT freed 1811K, 65% free 18799K/53432K, paused 11ms+19ms, total 284ms
,D/dalvikvm( 1021): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = contacts
,D/AndroidRuntime( 4630): Shutting down VM
,D/dalvikvm( 4630): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,D/dalvikvm( 1021): GC_EXPLICIT freed 223K, 66% free 18619K/53432K, paused 10ms+10ms, total 103ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1208): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1208): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1208): run()
,I/StatsUtilsManager( 1208): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1208): shouldRecordStats() = Too Soon
,I/PhenotypeConfigurator( 1235): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/ContextImpl( 4674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/InternalIcingCorporaPro( 2374): UpdateCorporaTask done [took 197 ms] updated apps [took 197 ms] 
,D/dalvikvm( 1235): GC_CONCURRENT freed 1557K, 34% free 11499K/17224K, paused 3ms+6ms, total 37ms
,D/PackageBroadcastService( 1774): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1774): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1774): Removing dialog suppression flag for package com.test.thalitest
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423550a8)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41fa7370)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4212b6b0)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4207a808)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4216af28)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42071ef8)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421115b0)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42187d28)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4228be10)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41f926a8)
,E/DataBuffer( 1235): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42035578)
,E/NetworkScheduler.SchedulerReceiver( 1391): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1391): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/dalvikvm( 3594): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3594): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3594): VFY: replacing opcode 0x6e at 0x0013
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
,I/CheckinRequestBuilder( 1774): Classify the device as Phone.
,D/gH_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1774): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Icing   ( 1774): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1774): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1774): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1774): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4707 uid=10059 gids={50059, 1028, 3003, 1015}
,I/ActivityManager( 1021): Killing 4447:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinTask( 1774): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1774): Checking schedule, now: 1453102752994 next: 1453652406989
,I/CheckinService( 1774): active receiver: disabled
,D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1304): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1304): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1304): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1304): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1092): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/CheckinService( 1774): Checking schedule, now: 1453102753098 next: 1453652406989
I/CheckinService( 1774): active receiver: disabled
,D/CheckinService( 1774): Recording last checkin time for package unspecified as 1453102753106
E/SharedPreferencesImpl( 1774): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak

```
