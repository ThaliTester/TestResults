#### Test 54970261ac9928f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{427d54f8 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4059): 
D/AndroidRuntime( 4059): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4059): CheckJNI is OFF
D/dalvikvm( 4059): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4059): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4059): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4059): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4059): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4059): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4059): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4059): failed to load memtrack module: -2
D/AndroidRuntime( 4059): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4059
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4075 uid=10526 gids={50526, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4059): Shutting down VM
D/dalvikvm( 4059): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4075): Binding Chromium to main looper Looper (main, tid 1) {41f2ec58}
I/LibraryLoader( 4075): Expected native library version number "",actual native library version number ""
I/chromium( 4075): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4075): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42271288:true
I/Adreno-EGL( 4075): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4075): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4075): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4075): Local Branch: 
I/Adreno-EGL( 4075): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4075): Local Patches: NONE
I/Adreno-EGL( 4075): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
D/dalvikvm( 1019): GC_EXPLICIT freed 1187K, 65% free 18124K/51076K, paused 4ms+11ms, total 99ms
,W/chromium( 4075): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4075): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4075): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4075): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4075): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4075): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4075): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4075): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4075): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4075): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4075): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4075): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4075): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4075): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4075): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4075): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4075): Enabling debug mode 0
,W/AwContents( 4075): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,463
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +435ms (total +463ms)
,D/JsMessageQueue( 4075): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4075): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f32f28
,D/dalvikvm( 4075): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f32f28
,D/jxcore_app_log( 4075): JniHelper::setJavaVM(0x4157cfa8), pthread_self() = 1614756064
,D/JX-Cordova( 4075): jxcore cordova android initializing
,D/dalvikvm( 4075): GC_CONCURRENT freed 2769K, 17% free 14414K/17224K, paused 3ms+2ms, total 58ms
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 136K, 17% free 14394K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 126K, 17% free 14414K/17224K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 16.200MB for 95956-byte allocation
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 177K, 17% free 14448K/17320K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 16.279MB for 143930-byte allocation
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 251K, 17% free 14495K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 16.394MB for 215890-byte allocation
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 366K, 18% free 14569K/17676K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 16.569MB for 323830-byte allocation
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 565K, 19% free 14690K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 16.841MB for 485740-byte allocation
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 860K, 20% free 14866K/18472K, paused 27ms, total 27ms
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 1277K, 19% free 15121K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 17.841MB for 1092904-byte allocation
,D/dalvikvm( 4075): GC_CONCURRENT freed 1769K, 21% free 15575K/19540K, paused 1ms+3ms, total 41ms
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 274K, 21% free 15437K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 18.670MB for 1639352-byte allocation
,D/dalvikvm( 4075): GC_CONCURRENT freed 1709K, 25% free 16018K/21144K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 1269K, 24% free 16075K/21144K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 20.076MB for 2459024-byte allocation
,D/dalvikvm( 4075): GC_CONCURRENT freed 232K, 23% free 18366K/23548K, paused 4ms+3ms, total 33ms
,D/dalvikvm( 4075): GC_CONCURRENT freed 4363K, 28% free 17082K/23548K, paused 3ms+7ms, total 43ms
,D/dalvikvm( 4075): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/dalvikvm-heap( 4075): Grow heap (frag case) to 22.232MB for 3688532-byte allocation
,D/dalvikvm( 4075): GC_CONCURRENT freed 188K, 25% free 20612K/27152K, paused 4ms+5ms, total 48ms
,D/dalvikvm( 4075): GC_FOR_ALLOC freed 3426K, 34% free 18029K/27152K, paused 30ms, total 30ms
,W/jxcore-log( 4075): Initializing JXcore engine
,W/jxcore-log( 4075): JXcore engine is ready
,D/dalvikvm( 4075): GC_CONCURRENT freed 341K, 24% free 20679K/27152K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 4075): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/jxcore-log( 4075): Starting JXcore engine
,W/jxcore-log( 4075): Platform android
W/jxcore-log( 4075): 
,W/jxcore-log( 4075): Process ARCH arm
W/jxcore-log( 4075): 
,I/jxcore-log( 4075): JXcore Cordova bridge is ready!
I/jxcore-log( 4075): 
,W/jxcore-log( 4075): JXcore engine is started
,I/chromium( 4075): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4075): Toggling radios to true
I/jxcore-log( 4075): 
,D/BluetoothAdapter( 4075): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4075, uid=10526
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4075): Radios toggled
I/jxcore-log( 4075): 
,I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  272): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
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
D/Tethering( 1019): InitialState.processMessage what=4
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
,E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  393): NL - Read 60 bytes from update socket.
D/TCMD    (  393): NL - ignore NL message, type = 21
,D/TCMD    (  393): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 267627
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1019): DisconnectingState
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x61171490 clazz=0x62300001 iface=wlan0 mask=0x3
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1367): Read error: ssl=0x62c79520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x62c79520: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
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
,D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1209): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1209): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1151): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  272): Event received = Trying to associate with
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  393): NL - Read 56 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
E/wpa_supplicant( 1151): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1151): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  393): NL - Read 312 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 192 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
,I/wpa_supplicant( 1151): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 80 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 80 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
I/wpa_supplicant( 1151): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  272): Event received = Associated with c0:ff:d4
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1151): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  272): Event received = WPA: Key negotiation com
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  272): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  272):  STA Connected !!
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
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  272): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1211163824
I/MDMCTBK (  272): return from set_get_from_wpa_supplicant
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/MDMCTBK (  272): wifi_set_tx_pwr: SETTXPOWER = 19
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
E/MDMCTBK (  272): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  272): , reply_len: 3, ret: 0
E/MDMCTBK (  272): MdmCutbackHndler, resp=OK
E/MDMCTBK (  272): 
,D/MDMCTBK (  272): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-27ms what=147462 obj=android.net.wifi.StateChangeResult@42044fc8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-26ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42292000 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4204a2d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4204a2d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  393): NL - Read 56 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 9
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 6 9
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 b
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 7 b
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 b8
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 b8
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 fe
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 fe
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428f5018 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428f5018 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428f5018 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  393): NL - Read 60 bytes from update socket.
D/TCMD    (  393): NL - ignore NL message, type = 20
,D/TCMD    (  393): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,W/BroadcastQueue( 1019): Skipping deliver [background] BroadcastRecord{427328a0 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{42075ed8 1403 com.google.android.gms/10022/u0 remote:4276f5b0}: process crashing
D/Tethering( 1019): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1296): Active network info is not available
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1586): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,W/BroadcastQueue( 1019): Skipping deliver [background] BroadcastRecord{42770798 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{42075ed8 1403 com.google.android.gms/10022/u0 remote:4276f5b0}: process crashing
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1296): Active network info is not available
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
E/ActivityThread( 1586): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1586): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1586): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1586): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1586): Registering with Alarm Manager to restart CCE
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1586): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1586): [debug] > CusSM.onRadioDown
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4184 uid=10030 gids={50030, 3003, 1028, 1015}
D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): DHCP successful
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
V/MmsConfig( 4184): mnc/mcc: 
,V/MmsConfig( 4184): tag: bool value: enabledMMS - true
V/MmsConfig( 4184): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4184): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4184): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4184): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4184): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4184): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4184): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4184): tag: int value: recipientLimit - 20
V/MmsConfig( 4184): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4184): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4184): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4184): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4184): tag: int value: maxSubjectLength - 80
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
V/MmsConfig( 4184): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4184): tag: bool value: smsForce7BitEncoding - false
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
V/MmsConfig( 4184): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4184): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4207 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3872:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 24ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+5ms, total 24ms
,D/MobileConnectivityChangeReceiver( 4207): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4207): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4207): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4207): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4224 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3889:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42020ee8
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1209): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42020ee8
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1209): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1403): Checkin interval check for package: unspecified last checkin: 1452269513108 min interval config: 0 actual interval: 255358
,I/CheckinService( 1403): Checking schedule, now: 1452269768475 next: 1452269543074
,I/CheckinService( 1403): active receiver: enabled
,I/CheckinService( 1403): Preparing to send checkin request
,I/EventLogService( 1403): Accumulating logs since 1452269509600
,I/CheckinRequestBuilder( 1403): Checkin reason type: 8 attempt count: 1
I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4241 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1019): Killing 3903:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/ActivityThread( 1403): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4241): Binding Chromium to main looper Looper (main, tid 1) {41f27c00}
,I/LibraryLoader( 4241): Expected native library version number "",actual native library version number ""
,I/chromium( 4241): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4241): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4241): BLUETOOTH permission is missing!
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno-EGL( 4241): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4241): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4241): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4241): Local Branch: 
I/Adreno-EGL( 4241): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4241): Local Patches: NONE
I/Adreno-EGL( 4241): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/NativeCrypto( 1367): Read error: ssl=0x62c04818: I/O error during system call, Connection timed out
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x62c04818: I/O error during system call, Broken pipe
,W/chromium( 4241): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4241): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/GAV2    ( 4241): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/NSApplication( 4241): Starting up...
,I/ImageResourceManager( 3925): ImageResourceManager: uninitalized
,I/iu.Environment( 3925): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 3849:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 3948): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3948): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4207): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4207): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3925): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1586): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1586): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1586): bindWebServices(): registering our AIDL callback...
I/SundryService( 1586): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1586): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1586): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1586): onServiceConnected()
D/GetNotificationsWS( 1586): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1586): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4285 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4285): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4285): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4285): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4285): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4285): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4285): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4285): install
,I/MultiDex( 4285): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4285): loading existing secondary dex files
,I/MultiDex( 4285): load found 3 secondary dex files
,I/MultiDex( 4285): install done
,D/dalvikvm( 4285): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4285): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4285): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4285): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4285): VFY: unable to resolve instance field 36
,D/dalvikvm( 4285): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4285): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4285): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4285): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4285): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4285): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4285): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2dd60
D/dalvikvm( 4285): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2dd60
,D/dalvikvm( 4285): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2dd60, skipping init
D/dalvikvm( 4285): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2dd60
,D/dalvikvm( 4285): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2dd60
,V/JNIHelp ( 4285): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4285): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2dd60
D/dalvikvm( 4285): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f2dd60
,D/dalvikvm( 4285): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2dd60
,D/dalvikvm( 4285): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f2dd60
,I/ProviderInstaller( 4285): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1236): callingUid 10022, callindPid: 1236
,E/MDM     ( 1236): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,D/LocationInitializer( 1403): Restart initialization of location
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1236): No location to return for getLastLocation()
,W/FusedLocationProvider( 1236): location=null
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
I/dalvikvm( 4285): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4285): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4285): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4285): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4285): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4285): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4285): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4285): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4285): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4285): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4285): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 4285): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4285): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4285): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4285): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4285): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4285): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb532c000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb532c000
D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=2855306830
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4285): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4285): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42136d70
D/dalvikvm( 4285): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42136d70
,D/dalvikvm( 4285): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42136d70, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4285): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4322): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4285): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4285): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 67ms
,I/Adreno-EGL( 4285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4285): Local Branch: 
I/Adreno-EGL( 4285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4285): Local Patches: NONE
I/Adreno-EGL( 4285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4285): Local Branch: 
I/Adreno-EGL( 4285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4285): Local Patches: NONE
I/Adreno-EGL( 4285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=2472064312
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4285): Local Branch: 
I/Adreno-EGL( 4285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4285): Local Patches: NONE
I/Adreno-EGL( 4285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4285): Local Branch: 
I/Adreno-EGL( 4285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4285): Local Patches: NONE
I/Adreno-EGL( 4285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4285): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1403): Classify the device as Phone.
,I/CheckinTask( 1403): Sending checkin request (11748 bytes)
,W/BroadcastQueue( 1019): Skipping deliver [background] BroadcastRecord{4289ecf0 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{42075ed8 1403 com.google.android.gms/10022/u0 remote:4276f5b0}: process crashing
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
D/Tethering( 1019): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1586): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/PollingManager( 1586): now: 299138 ,futureTime: 20301364
,D/PollingManager( 1586): Polling alarm set to expire at: 20301364 Current Time: 299139
E/ActivityThread( 1586): Failed to find provider info for com.motorola.blur.setupprovider
,W/BroadcastQueue( 1019): Skipping deliver [background] BroadcastRecord{43e57898 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{42075ed8 1403 com.google.android.gms/10022/u0 remote:4276f5b0}: process crashing
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1586): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
W/XTWiFiOS( 1296): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1586): now: 299184 ,futureTime: 20301364
,D/PollingManager( 1586): Polling alarm set to expire at: 20301364 Current Time: 299185
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,E/ActivityThread( 1586): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1586): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1586): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1586): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1586): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 3948): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3948): Crypto mode 0 already enabled
,D/TelephonyProvider( 1265): Column apn id key is 'apn_id'
,D/OtaApp  ( 1586): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1586): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/MobileConnectivityChangeReceiver( 4207): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4207): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1586): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1586): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1586): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1586): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1586): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3925): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1586): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1586): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1586): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/dalvikvm( 3925): GC_FOR_ALLOC freed 599K, 5% free 16433K/17224K, paused 16ms, total 20ms
,I/dalvikvm-heap( 3925): Grow heap (frag case) to 19.817MB for 1821008-byte allocation
,D/dalvikvm( 1019): GC_EXPLICIT freed 1606K, 65% free 18043K/51076K, paused 4ms+9ms, total 106ms
,D/OtaApp  ( 1586): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1403): Checkin interval check for package: unspecified last checkin: 1452269513108 min interval config: 0 actual interval: 258577
,I/openssl ( 3948): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3948): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4207): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4207): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3925): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 11ms, total 11ms
,I/iu.Environment( 3925): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1403): Checkin interval check for package: unspecified last checkin: 1452269513108 min interval config: 0 actual interval: 258638
,D/DEBUG   ( 1586): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1586): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1586): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1586): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1586): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1586): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1586): onServiceConnected()
D/GetNotificationsWS( 1586): onServiceConnected(): Registered for remote service callbacks...
,D/DEBUG   ( 1586): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1586): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1586): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1586): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1586): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1586): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1586): onServiceConnected()
D/WaitableIntentService( 1586): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1586): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1586): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1586): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1586
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1586): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1586): [info] > Updatetime from metadata: 10
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1586): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1586): [info] > Updatetime from metadata: 10
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1586): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1586): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1586
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1586): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1586): [info] > Updatetime from metadata: 10
D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1586): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1586): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1586): [info] > Updatetime from metadata: 10
D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1586): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1586): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1586): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{4290b6c8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,120
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
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1403): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1403): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1403): Classify the device as Phone.
,I/CheckinTask( 1403): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1403): Checking schedule, now: 1452269772040 next: 1452862842026
,I/CheckinService( 1403): active receiver: disabled
,I/CheckinService( 1403): Checking schedule, now: 1452269772058 next: 1452862842026
,I/CheckinService( 1403): active receiver: disabled
,D/CheckinService( 1403): Recording last checkin time for package unspecified as 1452269772064
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1209): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1209): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4241): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1019): Killing 3491:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4075): Test app app.js loaded
I/jxcore-log( 4075): 
,I/Choreographer( 4075): Skipped 709 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4075): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4075): TAP version 13
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # multiplex can send data
I/jxcore-log( 4075): 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4391 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
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
,I/Launcher( 1308): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/Launcher( 1308): Deferring update until onResume
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
,I/Babel   ( 4391): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4391): MmsConfig.loadMmsSettings
I/Babel   ( 4391): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4391): MmsConfig.loadFromDatabase
,I/GCoreNlp( 1236): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel   ( 4391): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4391): MmsConfig.loadFromResources
,E/Babel   ( 4391): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4391): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4391): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4424 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm( 1236): GC_CONCURRENT freed 1791K, 34% free 11519K/17224K, paused 5ms+9ms, total 56ms
,I/ActivityManager( 1019): Killing 4043:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4448 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3948:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2319): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4465 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4184:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4465): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4465): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4424): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4465): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2319): UpdateCorporaTask done [took 202 ms] updated apps [took 202 ms] 
,I/dalvikvm( 4465): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4465): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4465): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4465): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4465): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4465): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4465): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4465): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4465): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4465): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4465): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4465): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4465): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4465): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4465): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4500 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4465): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4465): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4465): Skipping gmscore version check
,D/Finsky  ( 4465): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4465): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4465): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4465): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1019): Killing 4207:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1403): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1403): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1403): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4500): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f34278, skipping init
I/openssl ( 4500): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4500): Crypto mode 0 already enabled
,D/Finsky  ( 4465): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1019): Killing 4224:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4465): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1403): GC_CONCURRENT freed 1974K, 31% free 11988K/17224K, paused 3ms+4ms, total 36ms
,I/Icing   ( 1403): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1403): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452269780
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): ok 1 String should be length:200
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # basic
I/jxcore-log( 4075): 
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
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
,I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,W/IInputConnectionWrapper( 1586): showStatusIcon on inactive InputConnection
,I/Process ( 1403): Sending signal. PID: 1403 SIG: 9
,I/ActivityManager( 1019): Process com.google.android.gms (pid 1403) has died.
,D/WifiService( 1019): Client connection lost with reason: 4
,W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
,I/jxcore-log( 4075): ok 2 sane
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # another
I/jxcore-log( 4075): 
,I/ActivityManager( 1019): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=4552 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4552): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4552): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4552): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4552): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4552): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4552): install
,I/MultiDex( 4552): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4552): loading existing secondary dex files
,I/MultiDex( 4552): load found 3 secondary dex files
,I/MultiDex( 4552): install done
,D/dalvikvm( 1019): GC_EXPLICIT freed 1548K, 65% free 18121K/51076K, paused 4ms+11ms, total 92ms
,D/dalvikvm( 4552): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4552): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4552): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4552): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4552): VFY: unable to resolve instance field 36
,D/dalvikvm( 4552): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4552): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4552): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4552): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4552): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4552): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4552): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f406b8
D/dalvikvm( 4552): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f406b8
,D/dalvikvm( 4552): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f406b8, skipping init
,D/dalvikvm( 4552): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f406b8
D/dalvikvm( 4552): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f406b8
,V/JNIHelp ( 4552): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4552): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f406b8
,D/dalvikvm( 4552): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f406b8
D/dalvikvm( 4552): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f406b8
,D/dalvikvm( 4552): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f406b8
,I/ProviderInstaller( 4552): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4552): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4552): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x000d
,I/GAv4-SVC( 4552): Google Analytics 8.4.89 is starting up.
,D/dalvikvm( 1367): GC_EXPLICIT freed 1429K, 41% free 10331K/17224K, paused 2ms+4ms, total 28ms
,I/dalvikvm( 4552): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 4552): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x002b
,D/dalvikvm( 4552): Trying to load lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x41f406b8
,I/dalvikvm( 4552): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 4552): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x0010
,D/dalvikvm( 4552): Added shared lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x41f406b8
,D/dalvikvm( 4552): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x41f406b8, skipping init
,I/dalvikvm( 4552): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4552): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4552): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4552): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4552): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4552): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4552): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4552): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4552): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/NativeLibraryUtils( 4552): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4552): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/dalvikvm( 4552): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4552): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x003e
,I/dalvikvm( 4552): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4552): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x00ce
,I/Icing   ( 4552): Storage manager: low false usage 2.08MB avail 4.38GB capacity 5.52GB
,D/WearableService( 1236): callingUid 10022, callindPid: 1236
,E/MDM     ( 1236): [70] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 4552): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
,W/dalvikvm( 4552): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x0029
,D/LocationInitializer( 4552): Restart initialization of location
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/dalvikvm( 4552): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
,W/dalvikvm( 4552): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
,D/dalvikvm( 4552): VFY: replacing opcode 0x1f at 0x0035
,W/GCoreFlp( 1236): No location to return for getLastLocation()
,W/FusedLocationProvider( 1236): location=null
,W/IcingInternalCorpora( 4552): getNumBytesRead when not calculated.
,I/dalvikvm( 4552): Total arena pages for JIT: 11
,I/dalvikvm( 4552): Total arena pages for JIT: 12
I/dalvikvm( 4552): Total arena pages for JIT: 13
,I/dalvikvm( 4552): Total arena pages for JIT: 14
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/Icing   ( 4552): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4552): Internal init done: storage state 0
,I/Icing   ( 4552): Post-init done
,W/ContextImpl( 1913): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:517 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/jxcore-log( 4075): ok 3 sane
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 4 should be equal
I/jxcore-log( 4075): 
,V/AlarmManager( 1019): sending alarm Alarm{44126120 type 3 android}
,I/jxcore-log( 4075): ok 5 null
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 6 (unnamed assert)
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 7 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 8 should not throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): ok 9 (unnamed assert)
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 10 (unnamed assert)
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 11 should not throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 12 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 13 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
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
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 14 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # failed to get mobile documents path
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 15 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 16 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 17 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 18 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #init should register the networkChanged event
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 19 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should throw on null device name
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 20 should throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 21 should throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 22 should throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 23 should throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should throw on negative port
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 24 should throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should throw on too large port
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 25 should throw
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 26 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 27 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 28 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): ok 29 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 30 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 31 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
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
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4075): 
,V/AlarmManager( 1019): sending alarm Alarm{42779eb0 type 3 android}
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 32 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 33 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 34 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 35 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 36 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 37 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 38 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
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
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): ok 39 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 40 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 41 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 42 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 43 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): ok 44 should be equal
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): # setup
I/jxcore-log( 4075): 
,V/AlarmManager( 1019): sending alarm Alarm{427766e0 type 3 android}
,I/jxcore-log( 4075): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4075): 
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 9
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4075): # teardown
I/jxcore-log( 4075): 
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
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/dalvikvm( 4075): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4075): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4075): Shutting down VM
,W/dalvikvm( 4075): threadid=1: thread exiting with uncaught exception (group=0x4165bd40)
,E/AndroidRuntime( 4075): FATAL EXCEPTION: main
E/AndroidRuntime( 4075): Process: com.test.thalitest, PID: 4075
E/AndroidRuntime( 4075): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4075): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4075): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4075): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4075): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4075): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4075): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/AndroidRuntime( 4075): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4075): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4075): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4075): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4075): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4075): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4075): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4075): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4075): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4075): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4075): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4075): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 4075): Sending signal. PID: 4075 SIG: 9
,I/ActivityManager( 1019): Process com.test.thalitest (pid 4075) has died.
,I/WindowState( 1019): WIN DEATH: Window{42177bb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,V/AlarmManager( 1019): sending alarm Alarm{42522a80 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42349fa0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42226da8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42011440 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42105638 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4208efc0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42bc5180 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{428e40b8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{427d0908 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4207ea78 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42329a80 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43e05430 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{43c6df30 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4650 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ActivityManager( 1019): Killing 4241:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1019): sending alarm Alarm{4275a798 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c5fb98 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1209): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
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
,V/AlarmManager( 1019): sending alarm Alarm{4289dff0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42013188 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42105c00 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42874a80 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4276a2d0 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{428a1240 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43aeb960 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4294cc38 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43e54ae0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4277f448 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{428ad020 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 22ms
,I/ProcessStatsService( 1019): Prepared write state in 31ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2016-01-07-23-18-41.bin
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
,V/AlarmManager( 1019): sending alarm Alarm{4415f158 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43dc25f8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{44155d78 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4289e188 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428ca780 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1019): sending alarm Alarm{428ca7d0 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{428ca820 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{42970f58 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{4289e0b0 type 1 com.android.deskclock}
,D/MMApiProvisionService( 1586): Got session expired event.. obtaining new session
,D/MMApiProvisionService( 1586): createDeviceIdOrLogin(): Got request to login .. processing now
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1586): generating token using payload instead of using session token
,I/MMApiWSBase( 1586): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 4552): Aggregate from 1452269768493 (log), 1452269177382 (data)
,D/MMApiProvisionService( 1586): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1586): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1586): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1586): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1586): handleResponse(): Session Expiration alarm set to expire at: Sun Jan 10 17:44:05 CET 2016
,D/MMApiProvisionService( 1586): _setMMApiCredInfo: storing credential info 
,E/MMApiProvisionService( 1586): handleResponse(): no settings sent by the server:
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/DEBUG   ( 1586): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,W/ContextImpl( 1586): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1586): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1586): onServiceConnected()
D/GetNotificationsWS( 1586): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1586): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1586): Received shoulder tap
,D/WaitableIntentService( 1586): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1586): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1586): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1586): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1586): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1586): GC_CONCURRENT freed 1961K, 39% free 10665K/17224K, paused 8ms+3ms, total 50ms
,D/MMApiWSBase( 1586): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1586): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1586): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1586): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1586): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1586): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1586): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1586): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1586): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1586): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1586): unbindWebServices(): un-registering our AIDL callback...
,V/AlarmManager( 1019): sending alarm Alarm{43c6eea8 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1019): sending alarm Alarm{43c6f058 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1019): sending alarm Alarm{43c6ef80 type 2 com.google.android.gms}
D/CCE     ( 1586): Registering with Alarm Manager to restart CCE
D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1209): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/AndroidRuntime( 4723): 
D/AndroidRuntime( 4723): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4723): CheckJNI is OFF
D/dalvikvm( 4723): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4723): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4723): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4723): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4723): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4723): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4723): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4723): failed to load memtrack module: -2
D/AndroidRuntime( 4723): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10526 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 4285:com.google.android.gms.unstable/u0a22 (adj 15): empty for 1801s
W/ContextImpl( 1277): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{443f7c58 u0 com.test.thalitest/.MainActivity t3}
I/dalvikvm( 1019): Total arena pages for JIT: 15
W/PackageSettings( 1019): Skipping PackageSetting{421f2ed8 com.example.hello/10523} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10526 user=0: pkg removed
D/dalvikvm( 2287): GC_EXPLICIT freed 5544K, 44% free 9652K/17224K, paused 2ms+6ms, total 45ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2319): GC_EXPLICIT freed 2678K, 44% free 9777K/17224K, paused 9ms+37ms, total 111ms
W/GeofencerStateMachine( 1236): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/VoicemailCleanupService( 4424): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1308): GC_EXPLICIT freed 3237K, 33% free 11594K/17224K, paused 2ms+4ms, total 132ms
I/Launcher( 1308): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 2171K, 65% free 18159K/51076K, paused 5ms+11ms, total 131ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452271577
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/Launcher( 1308): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2319): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4754 uid=10059 gids={50059, 3003, 1028, 1015}
D/dalvikvm(  274): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
D/dalvikvm( 4552): GC_EXPLICIT freed 4573K, 36% free 11149K/17224K, paused 4ms+11ms, total 70ms
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10526 #1
I/LatinIME:LogUtils( 1220): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452271577
I/InternalIcingCorporaPro( 2319): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
D/dalvikvm( 1019): GC_EXPLICIT freed 611K, 65% free 18075K/51076K, paused 4ms+15ms, total 206ms
D/AndroidRuntime( 4723): Shutting down VM
D/dalvikvm( 4723): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4754): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4778 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4754): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4465): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4465): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4465): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 4552): Reading stored module config
D/PackageBroadcastService( 4552): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4552): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4552): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4552): Loading module APK com.google.android.play.games
I/dalvikvm( 4552): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4552): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 4552): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 4552): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 4552): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 4552): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4552): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 4552): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
I/LocationSettingsChecker( 4552): Removing dialog suppression flag for package com.test.thalitest
I/dalvikvm( 4552): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 4552): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 4552): VFY: replacing opcode 0x6e at 0x0053
E/SQLiteDatabase( 4552): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4552): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4552): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4552): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4552): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4552): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4552): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4552): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4552): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 4552): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 4552): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 4552): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 4552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 4552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 4552): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 4552): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4552): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4552): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4552): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 4552): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1367): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1367): Shutting down VM
W/dalvikvm( 1367): threadid=1: thread exiting with uncaught exception (group=0x4165bd40)
E/AndroidRuntime( 1367): FATAL EXCEPTION: main
E/AndroidRuntime( 1367): Process: com.google.process.gapps, PID: 1367
E/AndroidRuntime( 1367): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1367): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1367): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1367): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1367): 	... 10 more
D/ChimeraCfgMgr( 4552): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4552): Module APK com.google.android.play.games already loaded
I/Process ( 1367): Sending signal. PID: 1367 SIG: 9

```
