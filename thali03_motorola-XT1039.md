#### Test 54970261fc259e9_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4032): 
D/AndroidRuntime( 4032): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4032): CheckJNI is OFF
D/dalvikvm( 4032): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4032): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4032): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4032): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4032): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4032): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4032): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4032): failed to load memtrack module: -2
D/AndroidRuntime( 4032): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1005): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4032
W/WindowManager( 1005): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1005): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4048 uid=10515 gids={50515, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4032): Shutting down VM
D/dalvikvm( 4032): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4048): Binding Chromium to main looper Looper (main, tid 1) {41fe1a90}
I/LibraryLoader( 4048): Expected native library version number "",actual native library version number ""
I/chromium( 4048): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4048): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1005): Message: 20
D/BluetoothManagerService( 1005): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43591ca0:true
I/Adreno-EGL( 4048): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4048): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4048): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4048): Local Branch: 
I/Adreno-EGL( 4048): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4048): Local Patches: NONE
I/Adreno-EGL( 4048): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4048): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4048): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4048): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4048): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4048): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4048): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4048): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4048): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4048): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4048): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4048): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4048): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4048): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4048): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4048): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4048): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4048): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4048): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4048): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4048): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4048): Enabling debug mode 0
,W/AwContents( 4048): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4048): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1005): Displayed com.test.thalitest/.MainActivity,cp,ca,425
I/ActivityManager( 1005): Displayed com.test.thalitest/.MainActivity: +398ms (total +425ms)
,D/JsMessageQueue( 4048): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4048): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe6288
,D/dalvikvm( 4048): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe6288
D/jxcore_app_log( 4048): JniHelper::setJavaVM(0x4163cf78), pthread_self() = 1615063800
D/JX-Cordova( 4048): jxcore cordova android initializing
,D/dalvikvm( 4048): GC_CONCURRENT freed 2754K, 17% free 14434K/17224K, paused 3ms+3ms, total 57ms
,D/dalvikvm( 4048): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4048): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 191K, 17% free 14447K/17224K, paused 27ms, total 28ms
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 135K, 17% free 14459K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 16.244MB for 95956-byte allocation
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 179K, 17% free 14493K/17320K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 16.323MB for 143930-byte allocation
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 253K, 17% free 14540K/17464K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 16.438MB for 215890-byte allocation
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 368K, 18% free 14614K/17676K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 16.613MB for 323830-byte allocation
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 568K, 19% free 14735K/17996K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 16.886MB for 485740-byte allocation
,V/AlarmManager( 1005): sending alarm Alarm{438af2f8 type 3 android}
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 866K, 20% free 14911K/18472K, paused 29ms, total 29ms
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 1282K, 18% free 15167K/18472K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 17.886MB for 1092904-byte allocation
,D/dalvikvm( 4048): GC_CONCURRENT freed 1842K, 20% free 15665K/19540K, paused 2ms+5ms, total 63ms
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 132K, 21% free 15564K/19540K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 18.795MB for 1639352-byte allocation
,D/dalvikvm( 4048): GC_CONCURRENT freed 1789K, 25% free 16067K/21144K, paused 3ms+4ms, total 41ms
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 1296K, 24% free 16122K/21144K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 20.122MB for 2459024-byte allocation
,D/dalvikvm( 4048): GC_CONCURRENT freed 286K, 22% free 18419K/23548K, paused 4ms+4ms, total 56ms
,V/AlarmManager( 1005): sending alarm Alarm{429070b0 type 1 com.android.deskclock}
,I/ActivityManager( 1005): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4094 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1005): Killing 3759:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4048): GC_CONCURRENT freed 4343K, 28% free 17115K/23548K, paused 3ms+7ms, total 50ms
,D/dalvikvm( 4048): WAIT_FOR_CONCURRENT_GC blocked 37ms
,I/dalvikvm-heap( 4048): Grow heap (frag case) to 22.264MB for 3688532-byte allocation
,D/dalvikvm( 4048): GC_CONCURRENT freed 2638K, 33% free 18287K/27152K, paused 2ms+6ms, total 48ms
,D/dalvikvm( 4048): GC_FOR_ALLOC freed 1091K, 34% free 18077K/27152K, paused 29ms, total 29ms
,W/jxcore-log( 4048): Initializing JXcore engine
,W/jxcore-log( 4048): JXcore engine is ready
,D/dalvikvm( 4048): GC_CONCURRENT freed 348K, 24% free 20753K/27152K, paused 1ms+2ms, total 33ms
D/dalvikvm( 4048): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4048): Starting JXcore engine
,W/jxcore-log( 4048): Platform android
W/jxcore-log( 4048): 
,W/jxcore-log( 4048): Process ARCH arm
W/jxcore-log( 4048): 
,I/jxcore-log( 4048): JXcore Cordova bridge is ready!
I/jxcore-log( 4048): 
,W/jxcore-log( 4048): JXcore engine is started
,I/chromium( 4048): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4048): Toggling radios to true
I/jxcore-log( 4048): 
,D/BluetoothAdapter( 4048): enable(): BT is already enabled..!
D/WifiService( 1005): New client listening to asynchronous messages
D/WifiService( 1005): setWifiEnabled: true pid=4048, uid=10515
,E/WifiService( 1005): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1005): handleMessage: E msg.what=131145
D/WifiStateMachine( 1005): processMsg: ConnectedState
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
I/jxcore-log( 4048): Radios toggled
I/jxcore-log( 4048): 
,D/TCMD    (  466): NL - Read 1000 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,I/wpa_supplicant( 1153): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273):  STA Disconnected !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1005): InitialState.processMessage what=4
,D/Tethering( 1005): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1005): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1005): handleMessage: new destination call exit/enter
,V/ConnectivityService( 1005): WiFi NOT Tethered!
D/WifiStateMachine( 1005): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1005): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1005): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1005): Stopping DHCP and clearing IP
D/WifiStateMachine( 1005): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1005): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1005): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1153): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1153): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  466): NL - Read 60 bytes from update socket.
D/TCMD    (  466): NL - ignore NL message, type = 21
,D/TCMD    (  466): Listening for incoming client connection request
,D/WifiStateMachine( 1005): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1005): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1005): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1005): connected time updated 289976
D/ConnectivityService( 1005): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1005): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1005): Attempting to switch to mobile
D/ConnectivityService( 1005): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1005): Attempting to switch to ETHERNET
,D/ConnectivityService( 1005): resetConnections(wlan0, 3)
D/NetUtils( 1005): android_net_utils_resetConnections in env=0x611be430 clazz=0x62100001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1005): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1005): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1005): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1005): DisconnectingState
E/wpa_supplicant( 1153): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1153): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1005): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1005): handleMessage: X
,D/WifiStateMachine( 1005): handleMessage: E msg.what=131146
D/WifiStateMachine( 1005): processMsg: DisconnectingState
,D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1005): processMsg: DisconnectingState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): Network connection lost
D/WifiStateMachine( 1005): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1005): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1374): Read error: ssl=0x63077388: I/O error during system call, Connection timed out
D/WifiP2pService( 1005): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1005): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1153): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1153): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1005): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1005): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1005): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1005): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1005): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1005): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1005): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1005): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1005): handleMessage: X
,D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/Checkin ( 1005): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiStateMachine( 1005): processMsg: DefaultState
D/WifiStateMachine( 1005): handleMessage: X
,D/WifiStateMachine( 1005): handleMessage: E msg.what=131216
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiStateMachine( 1005): processMsg: DefaultState
,D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=131216
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiStateMachine( 1005): processMsg: DefaultState
D/WifiStateMachine( 1005): handleMessage: X
,D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1005): processMsg: ConnectModeState
,D/WifiStateMachine( 1005): handleMessage: X
,V/NativeCrypto( 1374): SSL shutdown failed: ssl=0x63077388: I/O error during system call, Broken pipe
,D/Nat464Xlat( 1005): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1203): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1005): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1005): Attempting to switch to mobile
D/ConnectivityService( 1005): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1005): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1005): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1005): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1203): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1153): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1005): handleMessage: E msg.what=147461
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
E/wpa_supplicant( 1153): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  466): NL - Read 56 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,D/WifiStateMachine( 1005): processMsg: DriverStartedState
,D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1005): processMsg: ConnectModeState
,D/WifiStateMachine( 1005): handleMessage: X
,I/wpa_supplicant( 1153): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1153): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  466): NL - Read 312 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 192 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 1000 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
,D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 80 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 80 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
,D/TCMD    (  466): Listening for incoming client connection request
I/wpa_supplicant( 1153): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: DisconnectedState
,D/WifiStateMachine( 1005): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): handleMessage: X
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1153): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1153): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  466): NL - Read 1000 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
,D/TCMD    (  466): Listening for incoming client connection request
D/Tethering( 1005): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1192213752
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
,I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=147459
D/WifiStateMachine( 1005): processMsg: DisconnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): Network connection established
,D/WifiStateMachine( 1005): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1005): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1005): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1005): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1005): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1005): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1005): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1005): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1005): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1005): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1005): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=147462
D/WifiStateMachine( 1005): processMsg: ObtainingIpState
,D/WifiStateMachine( 1005): ObtainingIpState{ when=-27ms what=147462 obj=android.net.wifi.StateChangeResult@447e1c98 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1005): processMsg: L2ConnectedState
,D/WifiStateMachine( 1005): processMsg: ConnectModeState
,D/WifiStateMachine( 1005): handleMessage: X
,D/WifiStateMachine( 1005): handleMessage: E msg.what=131101
D/WifiStateMachine( 1005): processMsg: ObtainingIpState
D/WifiStateMachine( 1005): ObtainingIpState{ when=-29ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4380bd00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
,D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiStateMachine( 1005): processMsg: DefaultState
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=196612
D/WifiStateMachine( 1005): processMsg: ObtainingIpState
D/WifiStateMachine( 1005): ObtainingIpState{ when=-9ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1005): processMsg: L2ConnectedState
,D/WifiStateMachine( 1005): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1005): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1005): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427f6e78 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1005): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427f6e78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1005): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 9
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 94
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 94
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 0c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 0c
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 10
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 10
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1005): handleMessage: E msg.what=147461
D/WifiStateMachine( 1005): processMsg: ObtainingIpState
D/WifiStateMachine( 1005): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
,D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiP2pService( 1005): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1005): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1005): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1005): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@437b0b18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1005): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@437b0b18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1005): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@437b0b18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1005): handleMessage: X
D/TCMD    (  466): NL - Read 56 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,D/TCMD    (  466): NL - Read 60 bytes from update socket.
D/TCMD    (  466): NL - ignore NL message, type = 20
,D/TCMD    (  466): Listening for incoming client connection request
,D/WifiStateMachine( 1005): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1005): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1005): processMsg: ObtainingIpState
D/WifiStateMachine( 1005): ObtainingIpState{ when=-6ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1005): processMsg: L2ConnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
,D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1005): processMsg: DefaultState
D/WifiStateMachine( 1005): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1005): handleMessage: X
,D/WifiStateMachine( 1005): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1005): processMsg: ObtainingIpState
D/WifiStateMachine( 1005): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
,D/WifiStateMachine( 1005): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1005): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1005): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1005): DHCP successful
D/WifiStateMachine( 1005): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1005): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1005): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1005): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1005): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1005): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1005): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1005): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1005): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1005): VerifyingLinkState enter
D/WifiStateMachine( 1005): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=151572
D/WifiStateMachine( 1005): processMsg: VerifyingLinkState
D/WifiStateMachine( 1005): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=135190
D/WifiStateMachine( 1005): processMsg: VerifyingLinkState
D/WifiStateMachine( 1005): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1005): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1005): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1005): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1005): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1005): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1005): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1005): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1005): CaptivePortalCheckState enter
,D/WifiStateMachine( 1005): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1005): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1005): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1005): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1005): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=131092
D/WifiStateMachine( 1005): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1005): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1005): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1005): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1005): WiFi NOT Tethered!
,E/ConnectivityService( 1005): Unexpected mtu value: android.net.wifi.WifiStateTracker@420e7288
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1005): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1203): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1005): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/Checkin ( 1005): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
V/ConnectivityService( 1005): WiFi NOT Tethered!
,E/ConnectivityService( 1005): Unexpected mtu value: android.net.wifi.WifiStateTracker@420e7288
D/WifiStateMachine( 1005): transitionTo: destState=ConnectedState
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1005): handleMessage: new destination call exit/enter
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1005): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1005): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1005): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1005): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1005): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1005): handleMessage: X
D/WifiStateMachine( 1005): handleMessage: E msg.what=131092
D/WifiStateMachine( 1005): processMsg: ConnectedState
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
D/WifiStateMachine( 1005): processMsg: DefaultState
D/WifiStateMachine( 1005): handleMessage: X
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1005): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1005): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1203): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=0
,D/Tethering( 1005): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1005): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1005): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1582): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1005): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4176 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1005): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1005): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,E/ActivityThread( 1582): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1582): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1582): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1582): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1582): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1582): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1582): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,I/ActivityManager( 1005): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4204 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4176): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41feac88, skipping init
I/openssl ( 4176): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4176): Crypto mode 0 already enabled
,I/ActivityManager( 1005): Killing 3899:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4204): mnc/mcc: 
V/MmsConfig( 4204): tag: bool value: enabledMMS - true
,V/MmsConfig( 4204): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4204): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4204): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4204): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4204): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4204): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4204): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4204): tag: int value: recipientLimit - 20
V/MmsConfig( 4204): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4204): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4204): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4204): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4204): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4204): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4204): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4204): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4204): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1005): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4226 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1005): Killing 3463:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4226): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4226): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4226): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4226): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1005): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4240 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1005): Killing 3930:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1452011128617 min interval config: 0 actual interval: 277746
,I/CheckinService( 1408): Checking schedule, now: 1452011406368 next: 1452011158581
,I/CheckinService( 1408): active receiver: enabled
,I/CheckinService( 1408): Preparing to send checkin request
,I/EventLogService( 1408): Accumulating logs since 1452011124727
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1005): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4254 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1005): Killing 3486:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4254): Binding Chromium to main looper Looper (main, tid 1) {41fe7c98}
,I/LibraryLoader( 4254): Expected native library version number "",actual native library version number ""
,I/chromium( 4254): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4254): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4254): BLUETOOTH permission is missing!
,D/ConnectivityService( 1005): NetTransition Wakelock for ConnectedState released by timeout
D/dalvikvm( 1005): GC_EXPLICIT freed 23655K, 65% free 18085K/51008K, paused 4ms+10ms, total 145ms
,I/Adreno-EGL( 4254): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4254): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4254): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4254): Local Branch: 
I/Adreno-EGL( 4254): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4254): Local Patches: NONE
I/Adreno-EGL( 4254): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4254): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4254): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4254): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1005): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4289 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,W/dalvikvm( 4289): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4289): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/dalvikvm(  275): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/dalvikvm( 4289): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4289): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4289): VFY: replacing opcode 0x6e at 0x00cd
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
I/MultiDex( 4289): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4289): install
,I/MultiDex( 4289): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4289): loading existing secondary dex files
,I/MultiDex( 4289): load found 3 secondary dex files
,I/MultiDex( 4289): install done
,D/dalvikvm( 4289): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4289): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4289): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4289): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4289): VFY: unable to resolve instance field 36
,D/dalvikvm( 4289): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4289): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4289): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4289): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4289): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4289): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4289): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed870
D/dalvikvm( 4289): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed870
,D/dalvikvm( 4289): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed870, skipping init
,D/dalvikvm( 4289): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fed870
D/dalvikvm( 4289): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fed870
,V/JNIHelp ( 4289): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4254): Starting up...
D/dalvikvm( 4289): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fed870
,D/dalvikvm( 4289): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fed870
D/dalvikvm( 4289): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fed870
,D/dalvikvm( 4289): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fed870
,I/ImageResourceManager( 3503): ImageResourceManager: uninitalized
,I/iu.Environment( 3503): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1005): Killing 3948:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4176): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4176): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4226): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4226): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3503): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 1408): GC_CONCURRENT freed 1813K, 31% free 12039K/17224K, paused 7ms+12ms, total 69ms
,D/DEBUG   ( 1582): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1582): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1582): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1582): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1582): onServiceConnected()
D/GetNotificationsWS( 1582): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1582): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1582): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1582): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 3503): GC_CONCURRENT freed 628K, 5% free 16441K/17224K, paused 3ms+3ms, total 28ms
,I/ProviderInstaller( 4289): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1237): callingUid 10022, callindPid: 1237
,D/LocationInitializer( 1408): Restart initialization of location
,E/MDM     ( 1237): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1237): No location to return for getLastLocation()
,W/FusedLocationProvider( 1237): location=null
,I/dalvikvm( 4289): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4289): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4289): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4289): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4289): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4289): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4289): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4289): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4289): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4289): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4289): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4289): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4289): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4289): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4289): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4289): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4289): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52a0000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52a0000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=2860554491
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4289): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4289): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e0528
,D/dalvikvm( 4289): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e0528
,D/dalvikvm( 4289): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421e0528, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine( 1005): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1005): handleMessage: E msg.what=131215
D/WifiStateMachine( 1005): processMsg: ConnectedState
D/WifiStateMachine( 1005): processMsg: L2ConnectedState
D/WifiStateMachine( 1005): processMsg: ConnectModeState
D/WifiStateMachine( 1005): processMsg: DriverStartedState
D/WifiStateMachine( 1005): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1005): processMsg: DefaultState
,D/WifiStateMachine( 1005): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1005): handleMessage: X
,D/ConnectivityService( 1005): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1005):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1005): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1005): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1005): requiresClat: netType=1, hasIPv4Address=true
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=27616901
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4289): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4329): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4289): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4289): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 78ms
,I/Adreno-EGL( 4289): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4289): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4289): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4289): Local Branch: 
I/Adreno-EGL( 4289): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4289): Local Patches: NONE
I/Adreno-EGL( 4289): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4289): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4289): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4289): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4289): Local Branch: 
I/Adreno-EGL( 4289): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4289): Local Patches: NONE
I/Adreno-EGL( 4289): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4289): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4289): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4289): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4289): Local Branch: 
I/Adreno-EGL( 4289): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4289): Local Patches: NONE
I/Adreno-EGL( 4289): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4289): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4289): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4289): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4289): Local Branch: 
I/Adreno-EGL( 4289): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4289): Local Patches: NONE
I/Adreno-EGL( 4289): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/Tethering( 1005): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/CaptivePortalTracker( 1005): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,W/Settings( 4289): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/PollingManager( 1582): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
D/PollingManager( 1582): now: 320763 ,futureTime: 20482949
,D/PollingManager( 1582): Polling alarm set to expire at: 20482949 Current Time: 320764
,E/ActivityThread( 1582): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1582): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Tethering( 1005): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1005): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1582): now: 320774 ,futureTime: 20482949
D/PollingManager( 1582): Polling alarm set to expire at: 20482949 Current Time: 320774
D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/openssl ( 4176): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4176): Crypto mode 0 already enabled
E/ActivityThread( 1582): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1582): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1582): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1582): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1582): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1582): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1582): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4226): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4226): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1582): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1582): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1582): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/CheckinRequestBuilder( 1408): Classify the device as Phone.
D/dalvikvm( 3503): GC_FOR_ALLOC freed 38K, 5% free 16405K/17224K, paused 13ms, total 13ms
I/dalvikvm-heap( 3503): Grow heap (frag case) to 19.791MB for 1821008-byte allocation
I/iu.Environment( 3503): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/OtaApp  ( 1582): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1582): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1452011128617 min interval config: 0 actual interval: 280200
,D/dalvikvm( 3503): GC_FOR_ALLOC freed 4K, 5% free 18184K/19004K, paused 19ms, total 19ms
,D/OtaApp  ( 1582): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1582): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/OtaApp  ( 1582): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1582): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1582): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/openssl ( 4176): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4176): Crypto mode 0 already enabled
,D/TelephonyProvider( 1279): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4226): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4226): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3503): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1452011128617 min interval config: 0 actual interval: 280259
,D/DEBUG   ( 1582): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1582): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1582): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1582): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1582): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1582): onServiceConnected()
,D/GetNotificationsWS( 1582): onServiceConnected(): Registered for remote service callbacks...
,D/DEBUG   ( 1582): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1582): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1582): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1582): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1582): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1582): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1582): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1582): onServiceConnected()
,D/GetNotificationsWS( 1582): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1582): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1582): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1582): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1005): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1582
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1582): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1582): [info] > Updatetime from metadata: 10
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1582): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1582): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1582): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1582): [info] > Updatetime from metadata: 10
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1582): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1582): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1582): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1582): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1005): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1582
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1582): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1582): [info] > Updatetime from metadata: 10
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1582): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1582): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinTask( 1408): Sending checkin request (11629 bytes)
,I/OtaApp  ( 1582): [info] > Updatetime from metadata: 10
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1582): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1582): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1582): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1005): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,112
D/OtaApp  ( 1582): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1582): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1005): Activity reported stop, but no longer stopping: ActivityRecord{428c7e90 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,I/CheckinTask( 1408): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1408): Checking schedule, now: 1452011409661 next: 1452604479641
,I/CheckinService( 1408): active receiver: disabled
,I/CheckinService( 1408): Checking schedule, now: 1452011409686 next: 1452604479641
,I/CheckinService( 1408): active receiver: disabled
,D/CheckinService( 1408): Recording last checkin time for package unspecified as 1452011409691
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1005): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1203): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1203): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4254): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1005): Killing 3524:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4048): Test app app.js loaded
I/jxcore-log( 4048): 
,W/IInputConnectionWrapper( 4048): showStatusIcon on inactive InputConnection
,I/chromium( 4048): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/InputReader( 1005): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "sms"
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "smsto"
,I/ActivityManager( 1005): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4379 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mms"
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mmsto"
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "sms"
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "smsto"
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mms"
I/Launcher( 1304): Deferring update until onResume
,I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mmsto"
,I/Launcher( 1304): Deferring update until onResume
,I/Babel   ( 4379): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4379): MmsConfig.loadMmsSettings
I/Babel   ( 4379): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4379): MmsConfig.loadFromDatabase
,E/Babel   ( 4379): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4379): MmsConfig.loadFromResources
,E/Babel   ( 4379): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4379): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4379): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1237): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager( 1005): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4416 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm( 1005): GC_EXPLICIT freed 1481K, 65% free 18097K/51008K, paused 4ms+10ms, total 104ms
I/ActivityManager( 1005): Killing 4094:com.android.deskclock/u0a15 (adj 15): empty #9
I/ActivityManager( 1005): Killing 4176:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1005): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4435 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ContactLocale( 4416): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2268): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1005): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4453 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1005): Killing 4204:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4453): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4453): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4453): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2268): UpdateCorporaTask done [took 214 ms] updated apps [took 214 ms] 
,I/dalvikvm( 4453): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4453): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4453): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4453): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4453): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4453): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4453): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4453): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4453): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4453): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4453): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4453): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4453): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4453): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4453): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1005): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4491 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4453): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4453): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4453): Skipping gmscore version check
,D/Finsky  ( 4453): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4453): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4453): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4453): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1005): Killing 4226:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1408): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1408): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4491): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe9328, skipping init
I/openssl ( 4491): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4491): Crypto mode 0 already enabled
,I/ActivityManager( 1005): Killing 4240:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4453): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4453): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1408): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1408): GC_CONCURRENT freed 2015K, 31% free 11991K/17224K, paused 5ms+6ms, total 48ms
,I/Icing   ( 1408): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,D/CaptivePortalTracker( 1005): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1005): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/LatinIME:LogUtils( 1218): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452011418
,D/CaptivePortalTracker( 1005): Checking http://216.58.209.46/generate_204
,D/dalvikvm( 1237): GC_CONCURRENT freed 1765K, 33% free 11577K/17224K, paused 3ms+7ms, total 43ms
,D/CaptivePortalTracker( 1005): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 1005): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1005): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1005): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1005): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{4294f430 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{42924698 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{421b4b58 type 3 android}
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{435a1db8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{428cfe18 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{44783160 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{42889f48 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{43e67028 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{429798e8 type 2 android}
,D/ConnectivityService( 1005): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1005): sending alarm Alarm{437b2e68 type 0 com.google.android.gms}
,D/ConnectivityService( 1005): Done.
,D/ConnectivityService( 1005): Setting timer for 720seconds
,I/EventLogService( 1408): Aggregate from 1452011406389 (log), 1452009601083 (data)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{42866158 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{42999390 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{43db2e68 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{428672b0 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{43d41528 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{44779178 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{42800500 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{42866230 type 1 com.android.deskclock}
,I/ActivityManager( 1005): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4622 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1005): Killing 4254:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1005): sending alarm Alarm{4286d088 type 2 com.google.android.gms}
,D/ConnectivityService( 1005): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1203): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1005): sending alarm Alarm{43ed5338 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{429c16e0 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{43ef6e00 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{44195c48 type 2 android}
,V/AlarmManager( 1005): sending alarm Alarm{4296b2a8 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{428c6950 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{44195cf8 type 2 android}
,D/ConnectivityService( 1005): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1005): Done.
,D/ConnectivityService( 1005): Setting timer for 720seconds
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{4295e0b0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{4298ad40 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{429c3018 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{4391df98 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{43f18230 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1005): sending alarm Alarm{435a2068 type 3 android}
,I/ProcessStatsService( 1005): Prepared write state in 30ms
,I/ProcessStatsService( 1005): Prepared write state in 32ms
,I/ProcessStatsService( 1005): Pruning old procstats: /data/system/procstats/state-2016-01-05-01-37-59.bin
,V/AlarmManager( 1005): sending alarm Alarm{441b2078 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{4380d048 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{427ffc98 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{441ae890 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{44195dd0 type 3 android}
,V/AlarmManager( 1005): sending alarm Alarm{4210e350 type 3 com.google.android.gms}
,V/AlarmManager( 1005): sending alarm Alarm{4210e3a0 type 1 com.motorola.motocare}
,V/AlarmManager( 1005): sending alarm Alarm{4210e3f0 type 1 com.android.deskclock}
,D/dalvikvm( 1374): GC_EXPLICIT freed 508K, 41% free 10329K/17224K, paused 2ms+5ms, total 39ms
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Checkin ( 2235): publish the event [tag = MOT_DEVICE_STATS_L3 event name = SystemLocale]
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1005): sending alarm Alarm{43ef8fb8 type 2 com.google.android.gms}
V/AlarmManager( 1005): sending alarm Alarm{435cb950 type 2 com.motorola.ccc.cce}
D/CCE     ( 1582): Registering with Alarm Manager to restart CCE
D/ConnectivityService( 1005): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1203): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1203): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1203): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/AndroidRuntime( 4694): 
D/AndroidRuntime( 4694): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4694): CheckJNI is OFF
D/dalvikvm( 4694): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4694): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4694): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4694): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4694): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4694): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4694): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4694): failed to load memtrack module: -2
D/AndroidRuntime( 4694): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1005): Force stopping com.test.thalitest appid=10515 user=-1: uninstall pkg
I/ActivityManager( 1005): Killing 4048:com.test.thalitest/u0a515 (adj 9): stop com.test.thalitest
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1005): Killing 4289:com.google.android.gms.unstable/u0a22 (adj 15): empty for 1801s
I/ActivityManager( 1005):   Force finishing activity ActivityRecord{4388fcc0 u0 com.test.thalitest/.MainActivity t3}
I/dalvikvm( 1005): Total arena pages for JIT: 15
I/WindowState( 1005): WIN DEATH: Window{4384e800 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1005): Client connection lost with reason: 4
W/PackageSettings( 1005): Skipping PackageSetting{422a9410 com.example.hello/10509} due to missing metadata
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1005): Force stopping com.test.thalitest appid=10515 user=0: pkg removed
I/InputReader( 1005): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "sms"
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "smsto"
I/LatinIME:LogUtils( 1218): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1218): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/VoicemailCleanupService( 4416): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mms"
D/dalvikvm( 1408): GC_EXPLICIT freed 583K, 31% free 11910K/17224K, paused 5ms+6ms, total 111ms
W/SQLiteConnectionPool( 1408): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2235): GC_EXPLICIT freed 5430K, 44% free 9652K/17224K, paused 2ms+17ms, total 69ms
W/GeofencerStateMachine( 1237): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2268): GC_EXPLICIT freed 2936K, 44% free 9783K/17224K, paused 3ms+4ms, total 137ms
D/dalvikvm( 1304): GC_EXPLICIT freed 3336K, 33% free 11598K/17224K, paused 10ms+4ms, total 144ms
I/Launcher( 1304): Deferring update until onResume
D/dalvikvm( 1005): GC_EXPLICIT freed 2268K, 65% free 18108K/51008K, paused 35ms+11ms, total 181ms
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 31ms
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 31ms
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 51ms
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mmsto"
D/dalvikvm( 1005): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "sms"
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "smsto"
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mms"
I/InternalIcingCorporaPro( 2268): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1005): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1005):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1005):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1005):   Scheme: "mmsto"
I/ActivityManager( 1005): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4724 uid=10059 gids={50059, 3003, 1028, 1015}
I/Launcher( 1304): Deferring update until onResume
D/BackupManagerService( 1005): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1005): removePackageParticipantsLocked: uid=10515 #1
I/LatinIME:LogUtils( 1218): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452013215
D/dalvikvm( 1005): GC_EXPLICIT freed 598K, 65% free 18038K/51008K, paused 4ms+14ms, total 184ms
I/InternalIcingCorporaPro( 2268): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
I/LatinIME:LogUtils( 1218): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452013215
D/AndroidRuntime( 4694): Shutting down VM
D/dalvikvm( 4694): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 4724): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1005): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4752 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4724): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1408): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1408): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1408): Module APK com.google.android.play.games already loaded
I/dalvikvm( 4453): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4453): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4453): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1408): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1408): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1408): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1408): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1408): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1408): threadid=48: thread exiting with uncaught exception (group=0x41713d40)
E/SQLiteLog( 1374): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/DriveAsyncService( 1408): disk I/O error (code 3850)
E/DriveAsyncService( 1408): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1408): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1408): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1408): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1408): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1408): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1408): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1408): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1408): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1408): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1408): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1408): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1408): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1408): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1408): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1408): 	at java.lang.Thread.run(Thread.java:841)
D/AndroidRuntime( 1374): Shutting down VM
W/dalvikvm( 1374): threadid=1: thread exiting with uncaught exception (group=0x41713d40)
E/SQLiteDatabase( 1408): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1408): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1408): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1408): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1408): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1408): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1408): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1408): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1408): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 1408): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 1408): Process: com.google.android.gms, PID: 1408
E/AndroidRuntime( 1408): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1408): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1408): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1408): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1408): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1408): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 1408): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/AndroidRuntime( 1408): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1408): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1408): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1408): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1408): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1408): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1408): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 1408): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1408): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1408): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1408): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1408): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1408): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1408): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1408): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1408): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1408): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1408): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1408): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1408): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1408): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1408): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1408): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1408): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1408): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1408): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1408): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1408): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1408): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1408): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1408): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1408): Sending signal. PID: 1408 SIG: 9
E/DropBoxManagerService( 1005): Can't write: system_app_crash
E/DropBoxManagerService( 1005): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1005): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1005): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1005): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1005): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1005): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1005): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1005): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1005): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1005): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1005): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1005): 	... 5 more
E/AndroidRuntime( 1374): FATAL EXCEPTION: main
E/AndroidRuntime( 1374): Process: com.google.process.gapps, PID: 1374
E/AndroidRuntime( 1374): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1374): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1374): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1374): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1374): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1374): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1374): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1374): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1374): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1374): 	... 10 more
I/Process ( 1374): Sending signal. PID: 1374 SIG: 9
E/DropBoxManagerService( 1005): Can't write: system_app_crash
E/DropBoxManagerService( 1005): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1005): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1005): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1005): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1005): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1005): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1005): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1005): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1005): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1005): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1005): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1005): 	... 5 more
D/dalvikvm( 3503): GC_FOR_ALLOC freed 27K, 4% free 20544K/21204K, paused 70ms, total 71ms
I/ActivityManager( 1005): Process com.google.android.gms (pid 1408) has died.
D/WifiService( 1005): Client connection lost with reason: 4
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10998ms
D/WifiService( 1005): Client connection lost with reason: 4
I/ActivityManager( 1005): Process com.google.process.gapps (pid 1374) has died.
W/ActivityManager( 1005): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20995ms
E/SQLiteDatabase( 4752): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4752): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4752): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4752): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4752): threadid=10: thread exiting with uncaught exception (group=0x41713d40)
E/AndroidRuntime( 4752): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4752): Process: com.android.keychain, PID: 4752
E/AndroidRuntime( 4752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4752): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4752): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4752): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4752): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4752): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4752): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
