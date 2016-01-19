#### Test 564317025f150b2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4362): 
D/AndroidRuntime( 4362): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4362): CheckJNI is OFF
D/dalvikvm( 4362): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4362): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4362): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4362): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4362): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4362): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4362): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4362): failed to load memtrack module: -2
D/AndroidRuntime( 4362): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4362
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4378 uid=10125 gids={50125, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4362): Shutting down VM
D/dalvikvm( 4362): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4378): Binding Chromium to main looper Looper (main, tid 1) {42013b58}
I/LibraryLoader( 4378): Expected native library version number "",actual native library version number ""
I/chromium( 4378): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4378): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425c3a68:true
I/Adreno-EGL( 4378): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4378): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4378): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4378): Local Branch: 
I/Adreno-EGL( 4378): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4378): Local Patches: NONE
I/Adreno-EGL( 4378): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4378): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4378): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4378): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4378): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4378): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4378): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4378): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4378): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4378): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4378): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4378): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4378): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4378): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4378): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4378): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4378): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4378): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4378): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4378): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4378): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4378): Enabling debug mode 0
W/AwContents( 4378): nativeOnDraw failed; clearing to background color.
I/Keyboard.Facilitator( 1206): onFinishInput()
W/AwContents( 4378): nativeOnDraw failed; clearing to background color.
I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,398
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +374ms (total +398ms)
W/IInputConnectionWrapper( 4378): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 4378): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4378): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42017f18
D/dalvikvm( 4378): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42017f18
D/jxcore_app_log( 4378): JniHelper::setJavaVM(0x41668f78), pthread_self() = 1614876504
D/JX-Cordova( 4378): jxcore cordova android initializing
I/io.jxcore.node.ConnectionHelper( 4378): Build version SDK_INT: 19
D/dalvikvm( 4378): GC_CONCURRENT freed 2696K, 16% free 14492K/17224K, paused 3ms+3ms, total 44ms
D/dalvikvm( 4378): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/dalvikvm( 4378): GC_FOR_ALLOC freed 421K, 14% free 14910K/17224K, paused 27ms, total 28ms
I/dalvikvm-heap( 4378): Grow heap (frag case) to 16.655MB for 63974-byte allocation
D/dalvikvm( 4378): GC_FOR_ALLOC freed 142K, 14% free 14914K/17288K, paused 27ms, total 27ms
I/dalvikvm-heap( 4378): Grow heap (frag case) to 16.688MB for 95956-byte allocation
D/dalvikvm( 4378): GC_FOR_ALLOC freed 178K, 15% free 14948K/17384K, paused 26ms, total 27ms
I/dalvikvm-heap( 4378): Grow heap (frag case) to 16.767MB for 143930-byte allocation
D/dalvikvm( 4378): GC_FOR_ALLOC freed 251K, 15% free 14995K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 16.882MB for 215890-byte allocation
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 366K, 16% free 15069K/17740K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 17.057MB for 323830-byte allocation
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 565K, 16% free 15190K/18060K, paused 27ms, total 27ms
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 858K, 15% free 15365K/18060K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 17.732MB for 728606-byte allocation
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 1274K, 17% free 15621K/18772K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 18.331MB for 1092904-byte allocation
,D/dalvikvm( 4378): GC_CONCURRENT freed 1877K, 20% free 16022K/19840K, paused 1ms+4ms, total 35ms
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 88K, 20% free 16010K/19840K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 19.231MB for 1639352-byte allocation
,D/dalvikvm( 4378): GC_CONCURRENT freed 1898K, 23% free 16533K/21444K, paused 3ms+4ms, total 37ms
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 1071K, 23% free 16520K/21444K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 20.510MB for 2459024-byte allocation
,D/dalvikvm( 4378): GC_CONCURRENT freed 355K, 21% free 18872K/23848K, paused 5ms+3ms, total 35ms
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 4129K, 27% free 17549K/23848K, paused 37ms, total 37ms
,I/dalvikvm-heap( 4378): Grow heap (frag case) to 22.688MB for 3688532-byte allocation
,D/dalvikvm( 4378): GC_CONCURRENT freed 2863K, 33% free 18597K/27452K, paused 2ms+6ms, total 67ms
,D/dalvikvm( 4378): GC_FOR_ALLOC freed 1884K, 33% free 18649K/27452K, paused 33ms, total 36ms
,W/jxcore-log( 4378): Initializing JXcore engine
,W/jxcore-log( 4378): JXcore engine is ready
,D/dalvikvm( 4378): GC_CONCURRENT freed 386K, 22% free 21478K/27452K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 4378): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4378): Starting JXcore engine
,W/jxcore-log( 4378): Platform android
W/jxcore-log( 4378): 
,W/jxcore-log( 4378): Process ARCH arm
W/jxcore-log( 4378): 
,I/jxcore-log( 4378): JXcore Cordova bridge is ready!
I/jxcore-log( 4378): 
,W/jxcore-log( 4378): JXcore engine is started
,I/chromium( 4378): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4378): Toggling radios to true
I/jxcore-log( 4378): 
,D/BluetoothAdapter( 4378): enable(): BT is already enabled..!
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=4378, uid=10125
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
I/jxcore-log( 4378): Radios toggled
I/jxcore-log( 4378): 
I/jxcore-log( 4378): My device name is: motorola-XT1039
I/jxcore-log( 4378): 
,I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
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
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
,D/Tethering( 1018): InitialState.processMessage what=4
D/TCMD    (  572): NL - Read 1000 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/TCMD    (  572): NL - Read 68 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/TCMD    (  572): NL - Read 68 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
,D/TCMD    (  572): Listening for incoming client connection request
,V/ConnectivityService( 1018): WiFi NOT Tethered!
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  572): NL - Read 60 bytes from update socket.
D/TCMD    (  572): NL - ignore NL message, type = 21
,D/TCMD    (  572): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1018): connected time updated 294782
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1092): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x6163f610 clazz=0x64000001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1018): DisconnectingState
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1018): processMsg: DisconnectingState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
,D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection lost
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1340): Read error: ssl=0x63015bf0: I/O error during system call, Connection timed out
,D/WifiP2pService( 1018): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
V/NativeCrypto( 1340): SSL shutdown failed: ssl=0x63015bf0: I/O error during system call, Broken pipe
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1280): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1280): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1280): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1280): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1280): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1280): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1180): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/TCMD    (  572): NL - Read 56 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
,D/TCMD    (  572): Listening for incoming client connection request
,E/wpa_supplicant( 1180): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  572): NL - Read 312 bytes from update socket.
I/wpa_supplicant( 1180): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/TCMD    (  572): NL - Read 88 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
I/wpa_supplicant( 1180): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  572): NL - Read 68 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/TCMD    (  572): NL - Read 1000 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  572): NL - Read 80 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/TCMD    (  572): NL - Read 80 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/TCMD    (  572): NL - Read 68 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
,D/TCMD    (  572): Listening for incoming client connection request
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  572): NL - Read 1000 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195088560
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  275): send SAR ctrl over QMI
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection established
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@439f33f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-28ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42b22780 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-11ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42145a18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42145a18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 8c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 8c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 8e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 8e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  572): NL - Read 56 bytes from update socket.
D/TCMD    (  572): NL - message type is RTM_NEWLINK
D/TCMD    (  572): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428adad8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@428adad8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@428adad8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  572): NL - Read 60 bytes from update socket.
D/TCMD    (  572): NL - ignore NL message, type = 20
,D/TCMD    (  572): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
,D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: null, inetCondition= 0
D/PollingManager( 1598): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1018): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4463 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 33ms
,W/XTWiFiOS( 1264): Active network info is not available
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 5ms+7ms, total 34ms
,E/ActivityThread( 1598): Failed to find provider info for com.motorola.blur.setupprovider
W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
D/CCE     ( 1598): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1264): Active network info is not available
D/PollingManager( 1598): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1598): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1598): Failed to find provider info for com.motorola.blur.setupprovider
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
D/OtaApp  ( 1598): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1598): [debug] > CusSM.onRadioDown
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/dalvikvm( 4463): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4201b9a8, skipping init
I/openssl ( 4463): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4463): Crypto mode 0 already enabled
D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4504 uid=10030 gids={50030, 3003, 1028, 1015}
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): DHCP successful
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1018): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1018): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState enter
,D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/ActivityManager( 1018): Killing 4034:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiStateMachine( 1018): handleMessage: X
,I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,V/MmsConfig( 4504): mnc/mcc: 
V/MmsConfig( 4504): tag: bool value: enabledMMS - true
,V/MmsConfig( 4504): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4504): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4504): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4504): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4504): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4504): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4504): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4504): tag: int value: recipientLimit - 20
V/MmsConfig( 4504): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4504): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4504): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 4504): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4504): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4504): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4504): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4504): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4504): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4522 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 4183:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ddf58
I/SBar.NetworkController( 1092): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1280): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1280): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1280): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@420ddf58
I/SBar.NetworkController( 1092): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1092): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1280): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1280): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1280): onReceive() - done, currentInetCondition=0
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4522): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4522): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4540 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4232:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1712): Checkin interval check for package: unspecified last checkin: 1453190682707 min interval config: 0 actual interval: 281477
,I/CheckinService( 1712): Checking schedule, now: 1453190964193 next: 1453190712668
,I/CheckinService( 1712): active receiver: enabled
,I/CheckinService( 1712): Preparing to send checkin request
,I/EventLogService( 1712): Accumulating logs since 1453190679347
,I/CheckinRequestBuilder( 1712): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1712): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4540): Binding Chromium to main looper Looper (main, tid 1) {4200cf68}
,I/LibraryLoader( 4540): Expected native library version number "",actual native library version number ""
,I/chromium( 4540): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4540): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4540): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4540): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4540): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4540): Local Branch: 
I/Adreno-EGL( 4540): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4540): Local Patches: NONE
I/Adreno-EGL( 4540): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1018): GC_EXPLICIT freed 1815K, 65% free 18778K/53452K, paused 3ms+12ms, total 106ms
,W/chromium( 4540): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4540): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4540): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4575 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4575): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4575): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4575): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4575): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4575): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4575): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4575): install
,I/MultiDex( 4575): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4575): loading existing secondary dex files
,I/MultiDex( 4575): load found 3 secondary dex files
,I/MultiDex( 4575): install done
,D/dalvikvm( 4575): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4575): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4575): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4575): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4575): VFY: unable to resolve instance field 36
,D/dalvikvm( 4575): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4575): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4575): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4575): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4575): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4575): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4575): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42012b90
,D/dalvikvm( 4575): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42012b90
,D/dalvikvm( 4575): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42012b90, skipping init
,D/dalvikvm( 4575): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42012b90
,D/dalvikvm( 4575): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42012b90
,V/JNIHelp ( 4575): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4540): Starting up...
,I/ActivityManager( 1018): Killing 3916:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4595 uid=10056 gids={50056, 3003, 1028, 1015}
,D/dalvikvm( 4575): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42012b90
,D/dalvikvm( 4575): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42012b90
D/dalvikvm( 4575): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42012b90
,D/dalvikvm( 4575): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42012b90
,D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4595): VFY: unable to resolve instance field 68
D/dalvikvm( 4595): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4595): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4595): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1598): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager( 1018): Killing 4269:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1598): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/GetNotificationsWS( 1598): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1598): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1598): onServiceConnected()
I/SundryService( 1598): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1598): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1598): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1598): unbindWebServices(): un-registering our AIDL callback...
D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4595): VFY: unable to resolve instance field 68
,D/dalvikvm( 4595): VFY: replacing opcode 0x54 at 0x0011
I/openssl ( 4463): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4463): Crypto mode 0 already enabled
D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4595): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4595): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4595): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4595): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ProviderInstaller( 4575): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,E/MDM     ( 1222): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1712): Restart initialization of location
D/AuthorizationBluetoothService( 1340): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1340): Proximity feature is not enabled.
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
,I/dalvikvm( 4575): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4575): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4575): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4575): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4575): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4575): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4575): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4575): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4575): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4575): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4575): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4575): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4575): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4575): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4575): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4575): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4575): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 1222): GC_CONCURRENT freed 1676K, 34% free 11405K/17224K, paused 3ms+6ms, total 38ms
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422bd7e8)
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422c2d28)
E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422c5f18)
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422c9108)
,E/DataBuffer( 1222): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42353840)
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50fc000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50fc000
,D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
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
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4378): 
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2085249175
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4575): Install completed successfully. count=14 extracted=0
,D/ConnectivityService( 1018): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4575): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42261fd0
D/dalvikvm( 4575): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42261fd0
,D/dalvikvm( 4575): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42261fd0, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=362466723
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4378): 
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4378): 
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4378): 
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4378): 
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4378): 
,I/jxcore-log( 4378): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4378): 
,W/Settings( 4575): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4575): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4633): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4575): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4575): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4575): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4575): Local Patches: NONE
I/Adreno-EGL( 4575): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4575): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4575): Local Patches: NONE
I/Adreno-EGL( 4575): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4575): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4575): Local Patches: NONE
I/Adreno-EGL( 4575): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4378): Test app app.js loaded
I/jxcore-log( 4378): 
I/dalvikvm( 4378): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4378): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4378): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4378): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4378): BLE advertisement is supported
I/jxcore-log( 4378): 
,I/chromium( 4378): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4575): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4575): Local Patches: NONE
I/Adreno-EGL( 4575): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1712): Classify the device as Phone.
,I/jxcore-log( 4378): --= Surplus to requirements =--
I/jxcore-log( 4378): 
,I/jxcore-log( 4378): ****TEST TOOK:  ms ****
I/jxcore-log( 4378): 
,I/jxcore-log( 4378): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4378): 
,I/CheckinTask( 1712): Sending checkin request (11748 bytes)
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1598): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-15ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/PollingManager( 1598): now: 329577 ,futureTime: 68752754
,D/PollingManager( 1598): Polling alarm set to expire at: 68752754 Current Time: 329577
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,E/ActivityThread( 1598): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1598): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/PollingManager( 1598): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1598): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1598): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4463): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4463): Crypto mode 0 already enabled
D/PollingManager( 1598): now: 329638 ,futureTime: 68752754
D/PollingManager( 1598): Polling alarm set to expire at: 68752754 Current Time: 329638
,D/AndroidRuntime( 4648): 
D/AndroidRuntime( 4648): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,E/ActivityThread( 1598): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1598): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/AndroidRuntime( 4648): CheckJNI is OFF
D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1598): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
I/CheckinService( 1712): Checkin interval check for package: unspecified last checkin: 1453190682707 min interval config: 0 actual interval: 284536
D/dalvikvm( 4648): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4648): Added shared lib libjavacore.so 0x0
D/OtaApp  ( 1598): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/dalvikvm( 4648): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4648): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4648): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/OtaApp  ( 1598): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1598): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/DEBUG   ( 1598): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1598): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
W/ContextImpl( 1598): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1598): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1598): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1598): onServiceConnected()
D/GetNotificationsWS( 1598): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1598): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 4648): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/WaitableIntentService( 1598): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/GetNotificationsWS( 1598): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1598): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/openssl ( 4463): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4463): Crypto mode 0 already enabled
,D/OtaApp  ( 1598): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1712): Checkin interval check for package: unspecified last checkin: 1453190682707 min interval config: 0 actual interval: 284615
,D/DEBUG   ( 1598): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1598): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1598): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1598): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1598): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1598): onServiceConnected()
,D/GetNotificationsWS( 1598): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1598): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1598): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1598): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1598
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1598): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1598): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1598): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1598): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1598): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1598): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1598): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1598): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1598): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1598): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1598): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1598): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1598): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1598
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/Keyboard.Facilitator( 1206): onFinishInput()
,W/IInputConnectionWrapper( 4378): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1598): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1598): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
E/memtrack( 4648): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4648): failed to load memtrack module: -2
,D/OtaApp  ( 1598): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1598): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1598): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1598): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1018): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,125
D/OtaApp  ( 1598): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 1598): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1598): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1598): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1598): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{4290b068 u0 com.motorola.ccc.ota/.ui.DownloadActivity t2}
,D/AndroidRuntime( 4648): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10125 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 4378:com.test.thalitest/u0a125 (adj 9): stop com.test.thalitest
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{43226630 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1018): WIN DEATH: Window{42942ff8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1018): Client connection lost with reason: 4
,I/CheckinRequestBuilder( 1712): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1712): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10125 user=0: pkg removed
,I/Keyboard.Facilitator( 1206): resetDictionaries() : en_GB
,W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 2336): GC_EXPLICIT freed 5148K, 44% free 9647K/17224K, paused 2ms+5ms, total 39ms
,I/Keyboard.Facilitator.DecoderInitializer( 1206): run()
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/Decoder ( 1206): createOrResetDecoder
,D/dalvikvm( 1712): GC_EXPLICIT freed 1535K, 31% free 12006K/17224K, paused 5ms+7ms, total 69ms
,D/dalvikvm( 2368): GC_EXPLICIT freed 4470K, 42% free 10105K/17224K, paused 3ms+24ms, total 68ms
,W/SQLiteConnectionPool( 1712): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/VoicemailCleanupService( 1190): Cleaning up data for package: com.test.thalitest
,D/dalvikvm( 1297): GC_EXPLICIT freed 3248K, 33% free 11596K/17224K, paused 2ms+34ms, total 69ms
,I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4682 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/ConfigService( 1222): onCreate
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10125 #1
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1206): run()
,I/Launcher( 1297): Deferring update until onResume
,I/InternalIcingCorporaPro( 2368): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1206): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1206): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1206): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1206): run()
I/StatsUtilsManager( 1206): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1206): shouldRecordStats() = Too Soon
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4700 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1018): Killing 4302:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1018): sending alarm Alarm{4283dfd8 type 2 com.google.android.gms}
,D/dalvikvm( 1018): GC_EXPLICIT freed 1681K, 62% free 18842K/48384K, paused 10ms+15ms, total 203ms
W/ContextImpl( 4700): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3848): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 3848): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3848): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1712): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1712): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1712): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1712): Module APK com.google.android.play.games already loaded
,D/AndroidRuntime( 4648): Shutting down VM
,D/dalvikvm( 4648): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/dalvikvm( 1018): GC_EXPLICIT freed 282K, 62% free 18612K/48384K, paused 7ms+10ms, total 96ms
,I/LocationSettingsChecker( 1712): Removing dialog suppression flag for package com.test.thalitest
,D/WifiStateMachine( 1018): handleMessage: X
D/ChimeraCfgMgr( 1712): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1712): Module APK com.google.android.play.games already loaded
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
E/NetworkScheduler.SchedulerReceiver( 1340): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1340): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1712): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1712): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1712): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1712): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
D/gH_CompatibleDatabase( 1712): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1712): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1712): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1712): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1712): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1712): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1712): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1712): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1712): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4725 uid=10059 gids={50059, 1028, 3003, 1015}
,I/ActivityManager( 1018): Killing 4463:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1712): doRemovePackageData com.test.thalitest
,I/InternalIcingCorporaPro( 2368): UpdateCorporaTask done [took 273 ms] updated apps [took 273 ms] 
,I/CheckinRequestBuilder( 1712): Classify the device as Phone.
,I/CheckinTask( 1712): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1712): Checking schedule, now: 1453190968218 next: 1453740622200
,I/CheckinService( 1712): active receiver: disabled
,I/dalvikvm( 4725): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4725): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4725):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4725):   adb logcat -s GAv4
I/CheckinService( 1712): Checking schedule, now: 1453190968285 next: 1453740622200
,I/CheckinService( 1712): active receiver: disabled
,D/CheckinService( 1712): Recording last checkin time for package unspecified as 1453190968292
,E/SharedPreferencesImpl( 1712): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
,W/GAv4    ( 4725): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4725): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x001b
,E/SQLiteDatabase( 4725): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4725): 	at avm.getWritableDatabase(PG:244)
E/SQLiteDatabase( 4725): 	at avc.a(PG:1573)
E/SQLiteDatabase( 4725): 	at jep$b.a(PG:131)
E/SQLiteDatabase( 4725): 	at ave.run(PG:588)
,W/dalvikvm( 4725): threadid=11: thread exiting with uncaught exception (group=0x4173fd40)
I/dalvikvm( 4725): Could not find method android.app.Activity.finishAfterTransition, referenced from method ce.onBackPressed
W/dalvikvm( 4725): VFY: unable to resolve virtual method 1245: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0012
,W/GAv4    ( 4725): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4725): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/CAKEMIX_CRASHED( 4725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/CAKEMIX_CRASHED( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/CAKEMIX_CRASHED( 4725): 	at avm.getWritableDatabase(PG:244)
E/CAKEMIX_CRASHED( 4725): 	at avc.a(PG:1573)
E/CAKEMIX_CRASHED( 4725): 	at jep$b.a(PG:131)
E/CAKEMIX_CRASHED( 4725): 	at ave.run(PG:588)
E/SQLiteDatabase( 4725): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4725): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4725): 	at java.util.con,current.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4725): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4725): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4725): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4725): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4725): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4725): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4725): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4725): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4725): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4725): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4725): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4725): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4725): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
,I/dalvikvm( 4725): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4725): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 4725): VFY: replacing opcode 0x71 at 0x0075
I/ActivityManager( 1018): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from pid 4725

```
