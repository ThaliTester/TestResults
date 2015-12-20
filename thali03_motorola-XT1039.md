#### Test 506502785b2d2b2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4097): 
D/AndroidRuntime( 4097): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4097): CheckJNI is OFF
D/dalvikvm( 4097): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4097): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4097): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4097): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4097): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4097): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4097): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4097): failed to load memtrack module: -2
D/AndroidRuntime( 4097): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4097
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4113 uid=10498 gids={50498, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4097): Shutting down VM
D/dalvikvm( 4097): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4113): Binding Chromium to main looper Looper (main, tid 1) {42101c88}
I/LibraryLoader( 4113): Expected native library version number "",actual native library version number ""
I/chromium( 4113): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4113): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4388fa20:true
I/Adreno-EGL( 4113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4113): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4113): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4113): Local Branch: 
I/Adreno-EGL( 4113): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4113): Local Patches: NONE
I/Adreno-EGL( 4113): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4113): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4113): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4113): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4113): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4113): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4113): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4113): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4113): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4113): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4113): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4113): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4113): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4113): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4113): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4113): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4113): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4113): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4113): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4113): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4113): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4113): Enabling debug mode 0
,W/AwContents( 4113): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4113): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1022): Displayed com.test.thalitest/.MainActivity,cp,ca,383
I/ActivityManager( 1022): Displayed com.test.thalitest/.MainActivity: +355ms (total +383ms)
W/IInputConnectionWrapper( 4113): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4113): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4113): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42106138
,D/dalvikvm( 4113): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42106138
,D/jxcore_app_log( 4113): JniHelper::setJavaVM(0x4181cf78), pthread_self() = 1615124744
,D/JX-Cordova( 4113): jxcore cordova android initializing
,D/dalvikvm( 4113): GC_CONCURRENT freed 2795K, 17% free 14334K/17224K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 129K, 17% free 14336K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 129K, 17% free 14353K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 16.141MB for 96598-byte allocation
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 180K, 17% free 14388K/17320K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 16.221MB for 144892-byte allocation
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 254K, 18% free 14436K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 16.336MB for 217334-byte allocation
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 372K, 18% free 14510K/17680K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 16.513MB for 325996-byte allocation
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 573K, 19% free 14632K/18000K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 16.788MB for 488990-byte allocation
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 872K, 20% free 14809K/18480K, paused 27ms, total 27ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 1292K, 19% free 15066K/18480K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 17.794MB for 1100216-byte allocation
,D/dalvikvm( 4113): GC_CONCURRENT freed 1718K, 22% free 15443K/19556K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 344K, 22% free 15392K/19556K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 18.637MB for 1650320-byte allocation
,D/dalvikvm( 4113): GC_CONCURRENT freed 1567K, 25% free 15956K/21168K, paused 3ms+3ms, total 35ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 1500K, 25% free 16058K/21168K, paused 30ms, total 31ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 20.075MB for 2475476-byte allocation
,D/dalvikvm( 4113): GC_CONCURRENT freed 1921K, 30% free 16730K/23588K, paused 4ms+6ms, total 58ms
,D/dalvikvm( 4113): GC_CONCURRENT freed 2333K, 29% free 16975K/23588K, paused 2ms+7ms, total 45ms
,D/dalvikvm( 4113): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4113): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 503K, 29% free 16919K/23588K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 22.095MB for 3713210-byte allocation
,D/dalvikvm( 4113): GC_CONCURRENT freed 2840K, 34% free 17996K/27216K, paused 5ms+11ms, total 63ms
,D/dalvikvm( 4113): GC_FOR_ALLOC freed 519K, 34% free 17967K/27216K, paused 27ms, total 27ms
,W/jxcore-log( 4113): Initializing JXcore engine
,W/jxcore-log( 4113): JXcore engine is ready
,D/dalvikvm( 4113): GC_CONCURRENT freed 356K, 25% free 20600K/27216K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4113): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4113): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4113): Starting JXcore engine
,V/AlarmManager( 1022): sending alarm Alarm{442252e8 type 3 android}
,W/jxcore-log( 4113): Platform android
W/jxcore-log( 4113): 
,W/jxcore-log( 4113): Process ARCH arm
W/jxcore-log( 4113): 
,V/AlarmManager( 1022): sending alarm Alarm{42263b80 type 1 com.android.deskclock}
,I/ActivityManager( 1022): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4167 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1022): Killing 3869:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4113): JXcore Cordova bridge is ready!
I/jxcore-log( 4113): 
,W/jxcore-log( 4113): JXcore engine is started
,I/chromium( 4113): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4113): Toggling radios to true
I/jxcore-log( 4113): 
,D/BluetoothAdapter( 4113): enable(): BT is already enabled..!
D/WifiService( 1022): New client listening to asynchronous messages
D/WifiService( 1022): setWifiEnabled: true pid=4113, uid=10498
,E/WifiService( 1022): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1022): handleMessage: E msg.what=131145
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
I/jxcore-log( 4113): Radios toggled
I/jxcore-log( 4113): 
D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4113): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4113): 
I/jxcore-log( 4113): Perf Test app loaded loaded
I/jxcore-log( 4113): 
,I/jxcore-log( 4113): check test folder
I/jxcore-log( 4113): 
,I/jxcore-log( 4113): found test : ./testFindPeers.js
I/jxcore-log( 4113): 
,D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: ConnectedState
,D/Tethering( 1022): InitialState.processMessage what=4
,D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1022): WiFi NOT Tethered!
D/WifiStateMachine( 1022): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,I/jxcore-log( 4113): found test : ./testSendData.js
I/jxcore-log( 4113): 
D/WifiP2pService( 1022): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  473): NL - Read 60 bytes from update socket.
D/TCMD    (  473): NL - ignore NL message, type = 21
,D/TCMD    (  473): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1022): connected time updated 329802
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1022): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1022): Attempting to switch to ETHERNET
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1022): DisconnectingState
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1022): handleMessage: X
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): handleMessage: E msg.what=131146
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147460
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection lost
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/ConnectivityService( 1022): resetConnections(wlan0, 3)
,D/NetUtils( 1022): android_net_utils_resetConnections in env=0x615dd018 clazz=0x61600001 iface=wlan0 mask=0x3
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 1370): Read error: ssl=0x630f37b8: I/O error during system call, Connection timed out
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1022): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1022): Attempting to switch to ETHERNET
,I/chromium( 4113): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,D/dalvikvm( 1022): GC_EXPLICIT freed 22693K, 65% free 18110K/50764K, paused 4ms+11ms, total 171ms
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x630f37b8: I/O error during system call, Broken pipe
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,D/TCMD    (  473): NL - Read 56 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  473): NL - Read 312 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 88 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  473): NL - Read 80 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 80 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request,
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1207262472
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
,D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147459
,D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection established
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1022): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-48ms what=147462 obj=android.net.wifi.StateChangeResult@4215ba88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-43ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@421c2080 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=196612
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1022): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiP2pService( 1022): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42431888 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42431888 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c2
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c0
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 06,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 64,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE ,
,D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE ,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i,
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i,
D/TCMD    (  473): NL - Read 56 bytes from update socket.,
,D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState,
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiP2pService( 1022): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@424c8bd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@424c8bd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@424c8bd0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): handleMessage: X
,D/TCMD    (  473): NL - Read 60 bytes from update socket.
D/TCMD    (  473): NL - ignore NL message, type = 20
,D/TCMD    (  473): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): DHCP successful
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1022): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
,D/WifiStateMachine( 1022): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState enter
,D/WifiStateMachine( 1022): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=151572
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1022): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=135190
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1022): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1022): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState enter
,D/WifiStateMachine( 1022): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1022): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@421f40a0
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1022): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: ConnectedState
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@421f40a0
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1022): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/Tethering( 1022): MasterInitialState.processMessage what=3
D/CCE     ( 1575): Registering with Alarm Manager to restart CCE
D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
I/openssl ( 4014): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4014): Crypto mode 0 already enabled
D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1575): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 1575): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1575): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4287 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/dalvikvm(  280): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,V/MmsConfig( 4287): mnc/mcc: 
V/MmsConfig( 4287): tag: bool value: enabledMMS - true
,V/MmsConfig( 4287): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4287): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4287): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4287): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4287): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4287): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4287): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4287): tag: int value: recipientLimit - 20
V/MmsConfig( 4287): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4287): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4287): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4287): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4287): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4287): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4287): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4287): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4287): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/ActivityManager( 1022): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4307 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1022): Killing 3934:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4307): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4307): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4307): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4307): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4320 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3950:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1395): Checkin interval check for package: unspecified last checkin: 1450579188755 min interval config: 0 actual interval: 317755
,I/CheckinService( 1395): Checking schedule, now: 1450579506520 next: 1450579218733
,I/CheckinService( 1395): active receiver: enabled
,I/CheckinService( 1395): Preparing to send checkin request
,I/EventLogService( 1395): Accumulating logs since 1450579185405
,I/CheckinRequestBuilder( 1395): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1395): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4336 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3966:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4336): Binding Chromium to main looper Looper (main, tid 1) {420fbba8}
,I/LibraryLoader( 4336): Expected native library version number "",actual native library version number ""
,I/chromium( 4336): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4336): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4336): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4336): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4336): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4336): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4336): Local Branch: 
I/Adreno-EGL( 4336): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4336): Local Patches: NONE
I/Adreno-EGL( 4336): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1022): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4361 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/ConnectivityService( 1022): NetTransition Wakelock for ConnectedState released by timeout
,W/chromium( 4336): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4361): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4361): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4361): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4361): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4361): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4361): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4361): install
,I/MultiDex( 4361): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4361): loading existing secondary dex files
,I/MultiDex( 4361): load found 3 secondary dex files
,I/MultiDex( 4361): install done
,W/GAV2    ( 4336): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  265): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  265): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4336): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4361): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4361): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4361): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4361): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4361): VFY: unable to resolve instance field 36
,D/dalvikvm( 4361): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4361): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4361): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4361): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4361): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4361): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4361): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42101bb8
,D/dalvikvm( 4361): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42101bb8
,D/dalvikvm( 4361): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42101bb8, skipping init
,D/dalvikvm( 4361): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42101bb8
D/dalvikvm( 4361): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42101bb8
,V/JNIHelp ( 4361): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4361): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42101bb8
,D/dalvikvm( 4361): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42101bb8
D/dalvikvm( 4361): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42101bb8
,D/dalvikvm( 4361): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42101bb8
,I/NSApplication( 4336): Starting up...
,I/ImageResourceManager( 3993): ImageResourceManager: uninitalized
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1022): Killing 3912:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1575): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ProviderInstaller( 4361): Installed default security provider GmsCore_OpenSSL
,W/ContextImpl( 1575): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1575): bindWebServices(): registering our AIDL callback...
I/SundryService( 1575): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1575): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1575): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1575): onServiceConnected()
,D/GetNotificationsWS( 1575): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1575): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4014): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4014): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4307): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4307): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4361): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4361): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4361): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4361): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4361): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4361): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1395): Restart initialization of location
,D/WearableService( 1215): callingUid 10022, callindPid: 1215
,E/MDM     ( 1215): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4361): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4361): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4361): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4361): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4361): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4361): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4361): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4361): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4361): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4361): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4361): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,W/GCoreFlp( 1215): No location to return for getLastLocation()
,W/FusedLocationProvider( 1215): location=null
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  282): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  282): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  282): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5232000
,E/DrmWidevineDash(  282): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5232000
D/DrmWidevineDash(  282): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  282): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  282): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  282): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=3855159366
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
I/jxcore-log( 4113): Connected to the server!
I/jxcore-log( 4113): 
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/chromium( 4113): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/NativeLibraryUtils( 4361): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4361): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4230ca78
D/dalvikvm( 4361): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4230ca78
,D/dalvikvm( 4361): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4230ca78, skipping init
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,W/Settings( 4361): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4361): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4422): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 4361): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4361): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 106ms
,I/Adreno-EGL( 4361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4361): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4361): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4361): Local Branch: 
I/Adreno-EGL( 4361): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4361): Local Patches: NONE
I/Adreno-EGL( 4361): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4113): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4113): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4113): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4113): Shutting down VM
,W/dalvikvm( 4113): threadid=1: thread exiting with uncaught exception (group=0x4182ed40)
E/AndroidRuntime( 4113): FATAL EXCEPTION: main
E/AndroidRuntime( 4113): Process: com.test.thalitest, PID: 4113
E/AndroidRuntime( 4113): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4113): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4113): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4113): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4113): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4113): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4113): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4113): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4113): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4113): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4113): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4113): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4113): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4113): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4113): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4113): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4113): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager( 1022):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager( 1022): Killing 3554:com.android.vending/u0a38 (adj 15): empty #9
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 4113): Sending signal. PID: 4113 SIG: 9
,I/Adreno-EGL( 4361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4361): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4361): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4361): Local Branch: 
I/Adreno-EGL( 4361): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4361): Local Patches: NONE
I/Adreno-EGL( 4361): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
I/WindowState( 1022): WIN DEATH: Window{438abfc8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1022): Client connection lost with reason: 4
,I/ActivityManager( 1022): Process com.test.thalitest (pid 4113) has died.
D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1022): Got RemoteException sending setActive(false) notification to pid 4113 uid 10498
,W/Binder  ( 1201): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1201): java.lang.NullPointerException
W/Binder  ( 1201): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1201): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1201): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1201): 	at dalvik.system.NativeStart.run(Native Method)
,I/Adreno-EGL( 4361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4361): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4361): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4361): Local Branch: 
I/Adreno-EGL( 4361): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4361): Local Patches: NONE
I/Adreno-EGL( 4361): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4361): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4361): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4361): Local Branch: 
I/Adreno-EGL( 4361): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4361): Local Patches: NONE
I/Adreno-EGL( 4361): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=2499830890
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1395): Classify the device as Phone.
,V/NativeCrypto( 1395): SSL shutdown failed: ssl=0x6ce7d788: I/O error during system call, Connection timed out
,D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/PollingManager( 1575): now: 360579 ,futureTime: 61279984
,D/PollingManager( 1575): Polling alarm set to expire at: 61279984 Current Time: 360579
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Tethering( 1022): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1575): now: 360590 ,futureTime: 61279984
D/PollingManager( 1575): Polling alarm set to expire at: 61279984 Current Time: 360590
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1575): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1575): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4014): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4014): Crypto mode 0 already enabled
D/OtaApp  ( 1575): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MobileConnectivityChangeReceiver( 4307): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4307): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1575): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: server told to :continue
D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/CheckinService( 1395): Checkin interval check for package: unspecified last checkin: 1450579188755 min interval config: 0 actual interval: 320161
,D/dalvikvm( 3993): GC_FOR_ALLOC freed 606K, 5% free 16434K/17224K, paused 18ms, total 19ms
,D/OtaApp  ( 1575): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4014): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4014): Crypto mode 0 already enabled
,I/dalvikvm-heap( 3993): Grow heap (frag case) to 19.817MB for 1821008-byte allocation
,D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1575): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4307): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4307): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3993): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 13ms, total 14ms
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 1575): GC_CONCURRENT freed 1977K, 38% free 10732K/17224K, paused 4ms+4ms, total 43ms
,I/CheckinService( 1395): Checkin interval check for package: unspecified last checkin: 1450579188755 min interval config: 0 actual interval: 320233
,D/DEBUG   ( 1575): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1575): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1575): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1575): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1575): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1575): onServiceConnected()
,D/GetNotificationsWS( 1575): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1575): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1575): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1575): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1575): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1575): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1575): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1575): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1575): onServiceConnected()
,D/GetNotificationsWS( 1575): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1575): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1575): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1575): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1575
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1575): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/dalvikvm( 1022): GC_EXPLICIT freed 1481K, 65% free 18063K/50764K, paused 5ms+14ms, total 128ms
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1575): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1575): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1575
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/CheckinTask( 1395): Sending checkin request (11623 bytes)
I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1022): Activity reported stop, but no longer stopping: ActivityRecord{428f6d50 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WifiStateMachine( 1022): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1022): processMsg: ConnectedState
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,D/ConnectivityService( 1022): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1022):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1395): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1395): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1395): Classify the device as Phone.
,I/CheckinTask( 1395): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1395): Checking schedule, now: 1450579509761 next: 1451172579758
,I/CheckinService( 1395): active receiver: disabled
,I/CheckinService( 1395): Checking schedule, now: 1450579509781 next: 1451172579758
,I/CheckinService( 1395): active receiver: disabled
,D/CheckinService( 1395): Recording last checkin time for package unspecified as 1450579509787
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/PhenotypeConfigurator( 1215): Scheduling Phenotype for one-off execution 12187 seconds from now (1450579510314)
,D/GetConfigurationSnapshotOperation( 1215): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1215): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/dalvikvm( 1370): GC_EXPLICIT freed 1697K, 40% free 10366K/17224K, paused 2ms+4ms, total 34ms
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1215): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1215): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1215): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1215): GC_CONCURRENT freed 1598K, 35% free 11362K/17224K, paused 3ms+7ms, total 35ms
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1300): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1300): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/dalvikvm( 1215): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1215): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x003d
,I/GAV2    ( 4336): Thread[GAThread,5,main]: No campaign data found.
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1312): Deferring update until onResume
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4504 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/Launcher( 1312): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/GCoreNlp( 1215): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4504): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4504): MmsConfig.loadMmsSettings
,I/Babel   ( 4504): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4504): MmsConfig.loadFromDatabase
,E/Babel   ( 4504): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4504): MmsConfig.loadFromResources
,E/Babel   ( 4504): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4504): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4504): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1022): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4537 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1022): Killing 4167:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4555 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4014:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2334): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4577 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4287:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4577): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4577): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4537): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4577): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2334): UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
,I/dalvikvm( 4577): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4577): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4577): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4577): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4577): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4577): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4577): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4577): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4577): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4577): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4577): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4577): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4577): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4577): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4577): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1022): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4612 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4577): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4577): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4577): Skipping gmscore version check
,D/Finsky  ( 4577): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4577): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4577): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4577): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1022): Killing 4307:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1395): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1395): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1395): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4612): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x421081a8, skipping init
I/openssl ( 4612): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4612): Crypto mode 0 already enabled
,D/Finsky  ( 4577): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1022): Killing 4320:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4577): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1395): GC_CONCURRENT freed 1929K, 30% free 12060K/17224K, paused 3ms+5ms, total 38ms
,I/Icing   ( 1395): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1395): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450579518
,D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1022): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1022): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1022): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1022): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1022): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{425a9c60 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{442cd060 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{423bcf28 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{425164d8 type 2 android}
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 7
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{422b2d70 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42abbec0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{442576c0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43906698 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{424cc378 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{424a6768 type 0 com.google.android.gms}
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,I/EventLogService( 1395): Aggregate from 1450579506539 (log), 1450578103441 (data)
,D/dalvikvm( 1022): GC_EXPLICIT freed 1932K, 65% free 18110K/50764K, paused 4ms+10ms, total 99ms
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/WifiStateMachine( 1022): handleMessage: E msg.what=147460
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection lost
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
,D/Tethering( 1022): InitialState.processMessage what=4
,V/ConnectivityService( 1022): WiFi NOT Tethered!
D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  473): NL - Read 60 bytes from update socket.
D/TCMD    (  473): NL - ignore NL message, type = 21
,D/TCMD    (  473): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1022): connected time updated 792124
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1022): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1022): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/ConnectivityService( 1022): resetConnections(wlan0, 3)
D/NetUtils( 1022): android_net_utils_resetConnections in env=0x615dd018 clazz=0x9e200001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1022): invokeExitMethods: ConnectedState
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1370): Read error: ssl=0x62dcf4d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x62dcf4d8: I/O error during system call, Broken pipe
,D/WifiP2pService( 1022): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectedState
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1022): Attempting to switch to ETHERNET
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/TCMD    (  473): NL - Read 56 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
,D/WifiStateMachine( 1022): handleMessage: X
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1286): Active network info is not available
,D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1022): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1286): Active network info is not available
,E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1575): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1575): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1575): [debug] > CusSM.onRadioDown
,D/PollingManager( 1575): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,I/LaunchCheckinHandler( 1022): cleanup(): cleared. Last call was 453984 ms ago
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4686 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,V/MmsConfig( 4686): mnc/mcc: 
V/MmsConfig( 4686): tag: bool value: enabledMMS - true
,V/MmsConfig( 4686): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4686): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4686): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4686): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4686): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4686): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4686): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4686): tag: int value: recipientLimit - 20
V/MmsConfig( 4686): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4686): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4686): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4686): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4686): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4686): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4686): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4686): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4686): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1022): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4713 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1022): Killing 4336:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  280): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/MobileConnectivityChangeReceiver( 4713): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4713): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4713): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4713): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4727 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4361:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4740 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4504:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4740): Binding Chromium to main looper Looper (main, tid 1) {420fa850}
,I/LibraryLoader( 4740): Expected native library version number "",actual native library version number ""
,I/chromium( 4740): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4740): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4740): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4740): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4740): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4740): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4740): Local Branch: 
I/Adreno-EGL( 4740): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4740): Local Patches: NONE
I/Adreno-EGL( 4740): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4740): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4740): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  265): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  265): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4740): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4740): Starting up...
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager( 1022): Killing 4537:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.SyncManager( 3993): SYNC; picasa accounts
,I/iu.Environment( 1395): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/DEBUG   ( 1575): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1575): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,I/iu.UploadsManager( 1395): num queued entries: 0
,D/GetNotificationsWS( 1575): bindWebServices(): registering our AIDL callback...
,I/iu.UploadsManager( 1395): num updated entries: 0
,D/EmailService.MarketingOptInSetter( 1575): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1575): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1575): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1575): onServiceConnected()
D/GetNotificationsWS( 1575): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1575): unbindWebServices(): un-registering our AIDL callback...
,I/iu.SyncManager( 1395): NEXT; no task
,I/iu.UploadsManager( 3993): num queued entries: 0
,I/iu.UploadsManager( 3993): num updated entries: 0
,D/MobileConnectivityChangeReceiver( 4713): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4713): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.SyncManager( 3993): NEXT; no task
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/GAV2    ( 4740): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1022): sending alarm Alarm{4239eaf8 type 3 android}
,I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  473): NL - Read 56 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState,
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant( 1173): Retrying assoc: 1 
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-ASSOC-REJECT 
D/MDMCTBK (  277): Event received = CTRL-EVENT-ASSOC-REJECT 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147499
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/TCMD    (  473): NL - Read 56 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request,
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  473): NL - Read 312 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  473): NL - Read 88 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
,D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  473): NL - Read 80 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 80 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  277): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  473): NL - Read 1000 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1207262472
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
,D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147459
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection established
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1022): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-32ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42929f58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-31ms what=147462 obj=android.net.wifi.StateChangeResult@44244100 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196612
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1022): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiP2pService( 1022): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42431888 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42431888 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/TCMD    (  473): NL - Read 56 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/WifiP2pService( 1022): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): handleMessage: X
,D/TCMD    (  473): NL - Read 60 bytes from update socket.
D/TCMD    (  473): NL - ignore NL message, type = 20
,D/TCMD    (  473): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1022): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): DHCP successful
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1022): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1022): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState enter
,D/WifiStateMachine( 1022): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=151572
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=135190
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1022): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1022): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1022): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState enter
,D/WifiStateMachine( 1022): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1022): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@421f40a0
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1022): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
,I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1022): WiFi NOT Tethered!
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@421f40a0
,I/CheckinService( 1395): Checkin interval check for package: unspecified last checkin: 1450579509787 min interval config: 0 actual interval: 480537
D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
I/CheckinService( 1395): Checking schedule, now: 1450579990331 next: 1450579539758
I/CheckinService( 1395): active receiver: enabled
,I/CheckinService( 1395): Preparing to send checkin request
,I/EventLogService( 1395): Accumulating logs since 1450579957748
,I/CheckinRequestBuilder( 1395): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1395): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1022): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4853 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4853): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4853): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4853): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4853): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4853): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4853): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4853): install
,I/MultiDex( 4853): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4853): loading existing secondary dex files
,I/MultiDex( 4853): load found 3 secondary dex files
,I/MultiDex( 4853): install done
,D/dalvikvm( 4853): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4853): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4853): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4853): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4853): VFY: unable to resolve instance field 36
,D/dalvikvm( 4853): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4853): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4853): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4853): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4853): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4853): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4853): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42100ca0
,D/dalvikvm( 4853): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42100ca0
,D/dalvikvm( 4853): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42100ca0, skipping init
D/dalvikvm( 4853): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42100ca0
D/dalvikvm( 4853): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42100ca0
,V/JNIHelp ( 4853): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4853): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42100ca0
,D/dalvikvm( 4853): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42100ca0
D/dalvikvm( 4853): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42100ca0
,D/dalvikvm( 4853): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42100ca0
,I/ProviderInstaller( 4853): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1215): callingUid 10022, callindPid: 1215
,E/MDM     ( 1215): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,D/LocationInitializer( 1395): Restart initialization of location
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1215): No location to return for getLastLocation()
,W/FusedLocationProvider( 1215): location=null
,I/dalvikvm( 4853): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4853): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4853): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4853): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4853): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4853): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4853): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4853): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4853): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4853): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4853): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4853): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4853): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4853): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4853): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4853): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4853): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  282): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  282): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  282): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5232000
,E/DrmWidevineDash(  282): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5232000
D/DrmWidevineDash(  282): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  282): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  282): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  282): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=4196560635
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4853): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4853): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4234c1a0
D/dalvikvm( 4853): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4234c1a0
,D/dalvikvm( 4853): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4234c1a0, skipping init
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,W/Settings( 4853): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService( 1022): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4853): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4891): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4853): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4853): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 77ms
,I/Adreno-EGL( 4853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4853): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4853): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4853): Local Branch: 
I/Adreno-EGL( 4853): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4853): Local Patches: NONE
I/Adreno-EGL( 4853): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4853): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4853): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4853): Local Branch: 
I/Adreno-EGL( 4853): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4853): Local Patches: NONE
I/Adreno-EGL( 4853): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4853): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4853): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4853): Local Branch: 
I/Adreno-EGL( 4853): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4853): Local Patches: NONE
I/Adreno-EGL( 4853): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4853): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4853): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4853): Local Branch: 
I/Adreno-EGL( 4853): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4853): Local Patches: NONE
I/Adreno-EGL( 4853): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=3151337680
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1395): Classify the device as Phone.
,V/NativeCrypto( 1395): SSL shutdown failed: ssl=0x6ce7d788: I/O error during system call, Connection timed out
,I/CheckinTask( 1395): Sending checkin request (11629 bytes)
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4843
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4844
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4851
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 4900
,I/CheckinRequestBuilder( 1395): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1395): Failed to find provider info for com.google.android.wearable.settings
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/PollingManager( 1575): now: 845075 ,futureTime: 61279984
,D/PollingManager( 1575): Polling alarm set to expire at: 61279984 Current Time: 845076
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1286): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1575): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1575): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1575): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1575): now: 845106 ,futureTime: 61279984
,D/PollingManager( 1575): Polling alarm set to expire at: 61279984 Current Time: 845106
E/ActivityThread( 1575): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1575): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1575): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/Tethering( 1022): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
I/openssl ( 4612): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4612): Crypto mode 0 already enabled
D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1575): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4713): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4713): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1575): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1575): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/OtaApp  ( 1575): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1258): Column apn id key is 'apn_id'
,D/dalvikvm( 3993): GC_FOR_ALLOC freed 40K, 4% free 20559K/21204K, paused 16ms, total 16ms
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3993): num queued entries: 0
,I/iu.UploadsManager( 3993): num updated entries: 0
,I/iu.SyncManager( 3993): NEXT; no task
,D/dalvikvm( 1022): GC_EXPLICIT freed 1583K, 65% free 18011K/50764K, paused 4ms+9ms, total 93ms
,I/CheckinService( 1395): Checkin interval check for package: unspecified last checkin: 1450579509787 min interval config: 0 actual interval: 483776
,I/iu.Environment( 1395): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1395): num queued entries: 0
,I/iu.UploadsManager( 1395): num updated entries: 0
,D/DEBUG   ( 1575): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.SyncManager( 1395): NEXT; no task
,W/ContextImpl( 1575): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1575): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1575): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1575): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1575): onServiceConnected()
,D/GetNotificationsWS( 1575): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1575): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1575): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4612): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4612): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4713): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4713): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1395): Checkin interval check for package: unspecified last checkin: 1450579509787 min interval config: 0 actual interval: 483838
,D/DEBUG   ( 1575): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1575): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1575): bindWebServices(): registering our AIDL callback...
I/SundryService( 1575): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1575): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1575): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1575): onServiceConnected()
D/GetNotificationsWS( 1575): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1575): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1575): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1575
,D/GetNotificationsWS( 1575): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinRequestBuilder( 1395): Classify the device as Phone.
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1575): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1575): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1575
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/CheckinTask( 1395): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
I/CheckinService( 1395): Checking schedule, now: 1450579993722 next: 1451173063717
I/CheckinService( 1395): active receiver: disabled
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1575): [info] > Updatetime from metadata: 10
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for install later
I/CheckinService( 1395): Checking schedule, now: 1450579993746 next: 1451173063717
,I/CheckinService( 1395): active receiver: disabled
I/OtaApp  ( 1575): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/CheckinService( 1395): Recording last checkin time for package unspecified as 1450579993752
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1022): Activity reported stop, but no longer stopping: ActivityRecord{428f6d50 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1215): GC_CONCURRENT freed 1689K, 33% free 11611K/17224K, paused 4ms+7ms, total 34ms
,D/WifiStateMachine( 1022): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
D/ConnectivityService( 1022): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1022):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1300): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/ActivityManager( 1022): Killing 4555:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4951 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/Launcher( 1312): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/Launcher( 1312): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/GCoreNlp( 1215): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 1370): GC_EXPLICIT freed 652K, 40% free 10391K/17224K, paused 2ms+5ms, total 30ms
,I/Babel   ( 4951): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4951): MmsConfig.loadMmsSettings
I/Babel   ( 4951): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4951): MmsConfig.loadFromDatabase
,E/Babel   ( 4951): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4951): MmsConfig.loadFromResources
,E/Babel   ( 4951): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4951): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4951): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1022): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4988 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1022): Killing 4577:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Killing 4612:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5007 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2334): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5025 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4686:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 2334): GC_CONCURRENT freed 6507K, 39% free 10572K/17224K, paused 3ms+5ms, total 55ms
,I/dalvikvm( 5025): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 5025): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4988): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 1395): GC_CONCURRENT freed 2054K, 31% free 12015K/17224K, paused 4ms+6ms, total 44ms
,D/Finsky  ( 5025): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2334): UpdateCorporaTask done [took 235 ms] updated apps [took 235 ms] 
I/dalvikvm( 5025): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 5025): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 5025): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 5025): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x000a
D/Finsky  ( 5025): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 5025): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 5025): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x0032
W/Settings( 5025): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5025): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 5025): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5025): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 5025): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5025): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 5025): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5025): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1022): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5059 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 5025): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5025): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 5025): Skipping gmscore version check
D/Finsky  ( 5025): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5025): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 5025): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 5025): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5025): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1022): Killing 4713:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1395): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1395): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1395): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 5059): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x421071b0, skipping init
I/openssl ( 5059): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5059): Crypto mode 0 already enabled
,D/Finsky  ( 5025): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5025): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1022): Killing 4727:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1395): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1395): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450580002
,D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1022): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1022): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 1022): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1022): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1022): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1022): sending alarm Alarm{428f1c48 type 2 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{427f2d68 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{44261770 type 3 android}
,I/ClearcutLoggerApiImpl( 1370): disconnect managed GoogleApiClient
,V/AlarmManager( 1022): sending alarm Alarm{43f91150 type 3 android}
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4 
,V/AlarmManager( 1022): sending alarm Alarm{42abb458 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42265bf8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42989088 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42957980 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427868f8 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1022): cleanup(): cleared. Last call was 399840 ms ago
,I/ActivityManager( 1022): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5109 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1022): Killing 4740:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 ,
,V/AlarmManager( 1022): sending alarm Alarm{43f74fa8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42ac8638 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42929528 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43e6f098 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{442ace70 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43ec1fc0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42aa4350 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{442a8d50 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42457678 type 2 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{42a84c00 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1300): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42a84b28 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4388abc8 type 3 android}
,I/ProcessStatsService( 1022): Prepared write state in 49ms
,I/ProcessStatsService( 1022): Prepared write state in 16ms
,D/dalvikvm( 1022): GC_CONCURRENT freed 2007K, 65% free 18143K/50764K, paused 32ms+9ms, total 128ms
,I/ProcessStatsService( 1022): Pruning old procstats: /data/system/procstats/state-2015-12-19-03-05-33.bin
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43093258 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43093330 type 3 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{43093380 type 1 com.motorola.motocare}
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Checkin ( 2299): publish the event [tag = MOT_DEVICE_STATS_L3 event name = SystemLocale]
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43fbd8f0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4392d4a0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43906b30 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{438ea840 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4389ea48 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{430933d0 type 1 com.android.deskclock}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5167): 
D/AndroidRuntime( 5167): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5167): CheckJNI is OFF
D/dalvikvm( 5167): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5167): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5167): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5167): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5167): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5167): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5167): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5167): failed to load memtrack module: -2
D/AndroidRuntime( 5167): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10498 user=-1: uninstall pkg
W/PackageSettings( 1022): Skipping PackageSetting{423cbd70 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10498 user=0: pkg removed
D/dalvikvm( 2299): GC_EXPLICIT freed 5664K, 44% free 9654K/17224K, paused 5ms+5ms, total 54ms
D/dalvikvm( 1022): GC_EXPLICIT freed 838K, 65% free 17971K/50736K, paused 5ms+9ms, total 98ms
D/dalvikvm( 2334): GC_EXPLICIT freed 471K, 40% free 10342K/17224K, paused 2ms+4ms, total 108ms
W/GeofencerStateMachine( 1215): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1312): GC_EXPLICIT freed 3352K, 33% free 11597K/17224K, paused 2ms+8ms, total 156ms
D/VoicemailCleanupService( 4988): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/Launcher( 1312): Deferring update until onResume
D/dalvikvm( 1395): GC_EXPLICIT freed 1197K, 31% free 11937K/17224K, paused 3ms+11ms, total 124ms
W/SQLiteConnectionPool( 1395): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1022): GC_EXPLICIT freed 195K, 65% free 17971K/50736K, paused 4ms+11ms, total 137ms
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450581308
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2334): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/Launcher( 1312): Deferring update until onResume
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/ActivityManager( 1022): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5205 uid=10059 gids={50059, 3003, 1028, 1015}
D/AndroidRuntime( 5167): Shutting down VM
D/dalvikvm( 5167): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10498 #1
I/LatinIME:LogUtils( 1201): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450581308
I/InternalIcingCorporaPro( 2334): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
W/ActiveOrDefaultContextProvider( 5205): Missing scope.enter somewhere. Returning default context
E/SQLiteDatabase( 5205): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5205): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5205): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5205): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5205): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 5205): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 5205): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 5205): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 5205): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5205): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 5205): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 5205): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5205): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 5205): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5205): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 5205): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 5205): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 5205): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5205): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 5205): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5205): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5205): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 5205): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5205): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5205): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 5205): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 5205): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5205): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5205): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 5205): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 5205): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5205): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 5205): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 5205): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 5205): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5205): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 5205): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 5205): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 5205): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5205): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 5205): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 5205): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5205): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5205): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5205): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 5205): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 5205): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 5205): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5205): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 5205): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5205): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5205): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 5205): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5205): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5205): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 5205): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 5205): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5205): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5205): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5205): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5205): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5205): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5205): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5205): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 5205): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 5205): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 5205): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 5205): threadid=11: thread exiting with uncaught exception (group=0x4182ed40)
E/AndroidRuntime( 5205): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5205): Process: com.google.android.apps.docs, PID: 5205
E/AndroidRuntime( 5205): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5205): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5205): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5205): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5205): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5205): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 5205): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 5205): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 5205): 	at WT.run(AbstractDatabaseInstance.java:411)
I/Process ( 5205): Sending signal. PID: 5205 SIG: 9
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 5 more
I/ActivityManager( 1022): Process com.google.android.apps.docs (pid 5205) has died.

```
