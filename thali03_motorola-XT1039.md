#### Test 56151093c886730_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1020): sending alarm Alarm{440ed890 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4352): 
D/AndroidRuntime( 4352): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4352): CheckJNI is OFF
D/dalvikvm( 4352): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4352): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4352): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4352): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4352): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4352): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4352): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4352): failed to load memtrack module: -2
D/AndroidRuntime( 4352): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4352
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4369 uid=10117 gids={50117, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4352): Shutting down VM
D/dalvikvm( 4352): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4369): Binding Chromium to main looper Looper (main, tid 1) {41f70aa0}
I/LibraryLoader( 4369): Expected native library version number "",actual native library version number ""
I/chromium( 4369): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4369): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ac6648:true
I/Adreno-EGL( 4369): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4369): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4369): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4369): Local Branch: 
I/Adreno-EGL( 4369): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4369): Local Patches: NONE
I/Adreno-EGL( 4369): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4369): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4369): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4369): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4369): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4369): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4369): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4369): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4369): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4369): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4369): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4369): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4369): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4369): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4369): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4369): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4369): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4369): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4369): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4369): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4369): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4369): Enabling debug mode 0
,W/AwContents( 4369): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1220): onFinishInput()
,W/AwContents( 4369): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,473
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +445ms (total +473ms)
W/IInputConnectionWrapper( 4369): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4369): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4369): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f75278
,D/dalvikvm( 4369): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f75278
,D/jxcore_app_log( 4369): JniHelper::setJavaVM(0x415c3fa8), pthread_self() = 1614783896
,D/JX-Cordova( 4369): jxcore cordova android initializing
,D/dalvikvm( 4369): GC_CONCURRENT freed 2644K, 16% free 14545K/17224K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 4369): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4369): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 355K, 14% free 14874K/17224K, paused 27ms, total 27ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 69K, 14% free 14878K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 16.602MB for 42652-byte allocation
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 93K, 14% free 14897K/17268K, paused 28ms, total 28ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 127K, 14% free 14917K/17268K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 16.691MB for 95956-byte allocation
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 179K, 14% free 14952K/17364K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 16.771MB for 143930-byte allocation
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 253K, 15% free 14998K/17508K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 16.885MB for 215890-byte allocation
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 367K, 15% free 15073K/17720K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 17.061MB for 323830-byte allocation
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 569K, 16% free 15193K/18040K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 17.333MB for 485740-byte allocation
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 863K, 17% free 15369K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 1178K, 16% free 15614K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 161K, 16% free 15569K/18516K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 18.278MB for 1092904-byte allocation
,D/dalvikvm( 4369): GC_CONCURRENT freed 1889K, 19% free 16048K/19584K, paused 1ms+4ms, total 63ms
,D/dalvikvm( 4369): WAIT_FOR_CONCURRENT_GC blocked 3ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 19.268MB for 1639352-byte allocation
,D/dalvikvm( 4369): GC_CONCURRENT freed 2074K, 22% free 16573K/21188K, paused 1ms+8ms, total 54ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 966K, 23% free 16510K/21188K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 20.500MB for 2459024-byte allocation
,D/dalvikvm( 4369): GC_CONCURRENT freed 362K, 20% free 18891K/23592K, paused 5ms+7ms, total 62ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 4143K, 26% free 17551K/23592K, paused 39ms, total 39ms
,I/dalvikvm-heap( 4369): Grow heap (frag case) to 22.690MB for 3688532-byte allocation
,D/dalvikvm( 4369): GC_CONCURRENT freed 293K, 23% free 21071K/27196K, paused 5ms+5ms, total 58ms
,D/dalvikvm( 4369): GC_FOR_ALLOC freed 4475K, 32% free 18666K/27196K, paused 34ms, total 35ms
,W/jxcore-log( 4369): Initializing JXcore engine
,W/jxcore-log( 4369): JXcore engine is ready
,D/dalvikvm( 4369): GC_CONCURRENT freed 414K, 22% free 21474K/27196K, paused 1ms+2ms, total 32ms
,D/dalvikvm( 4369): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4369): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 4369): Starting JXcore engine
,W/jxcore-log( 4369): Platform android
W/jxcore-log( 4369): 
,W/jxcore-log( 4369): Process ARCH arm
W/jxcore-log( 4369): 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4369): JXcore Cordova bridge is ready!
I/jxcore-log( 4369): 
,W/jxcore-log( 4369): JXcore engine is started
,I/chromium( 4369): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4369): Toggling radios to true
I/jxcore-log( 4369): 
,D/BluetoothAdapter( 4369): enable(): BT is already enabled..!
D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=4369, uid=10117
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 4369): Radios toggled
I/jxcore-log( 4369): 
I/jxcore-log( 4369): My device name is: motorola-XT1039
I/jxcore-log( 4369): 
,I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,I/MDMCTBK (  275): send SAR ctrl over QMI
D/TCMD    (  465): NL - Read 1000 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1000 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1020): WiFi NOT Tethered!
,D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 21
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1020): connected time updated 300988
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1020): DisconnectingState
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x6160eb70 clazz=0x62600001 iface=wlan0 mask=0x3
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1349): Read error: ssl=0x631a2d58: I/O error during system call, Connection timed out
,V/NativeCrypto( 1349): SSL shutdown failed: ssl=0x631a2d58: I/O error during system call, Broken pipe
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
I/dalvikvm( 1020): Jit: resizing JitTable from 8192 to 16384
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1168): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1168): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
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
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1168): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  465): NL - Read 312 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 88 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1000 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  465): NL - Read 1000 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275):  STA Connected !!
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
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1212196016
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
I/MDMCTBK (  275): send SAR ctrl over QMI
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@43f50f00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-14ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43f49718 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4254f238 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4254f238 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,V/AlarmManager( 1020): sending alarm Alarm{4342c0d0 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiP2pService( 1020): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiP2pService( 1020): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43c9cfa8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43c9cfa8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43c9cfa8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 20
,D/TCMD    (  465): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,V/AlarmManager( 1020): sending alarm Alarm{441366c8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): DHCP successful
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState enter
D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
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
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1020): WiFi NOT Tethered!
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@420418a8
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1020): WiFi NOT Tethered!
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@420418a8
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1614): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1094): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1020): MasterInitialState.processMessage what=3
D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager( 1020): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4490 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1614): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1614): Registering with Alarm Manager to restart CCE
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
,D/PollingManager( 1614): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1614): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1614): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1614): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1614): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4517 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4490): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f78d18, skipping init
I/openssl ( 4490): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4490): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Killing 4068:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4517): mnc/mcc: 
V/MmsConfig( 4517): tag: bool value: enabledMMS - true
,V/MmsConfig( 4517): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4517): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4517): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4517): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4517): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4517): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4517): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4517): tag: int value: recipientLimit - 20
V/MmsConfig( 4517): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4517): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4517): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4517): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4517): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4517): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4517): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4517): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4517): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4539 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 4178:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4539): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4539): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4539): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4539): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4552 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1020): Killing 4231:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1745): Checkin interval check for package: unspecified last checkin: 1453034244818 min interval config: 0 actual interval: 285761
,I/CheckinService( 1745): Checking schedule, now: 1453034530585 next: 1453034274792
,I/CheckinService( 1745): active receiver: enabled
,I/CheckinService( 1745): Preparing to send checkin request
,I/EventLogService( 1745): Accumulating logs since 1453034241244
,I/CheckinRequestBuilder( 1745): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1745): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4552): Binding Chromium to main looper Looper (main, tid 1) {41f74c40}
,I/LibraryLoader( 4552): Expected native library version number "",actual native library version number ""
,I/chromium( 4552): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4552): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4552): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4552): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4552): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4552): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4552): Local Branch: 
I/Adreno-EGL( 4552): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4552): Local Patches: NONE
I/Adreno-EGL( 4552): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4552): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4552): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  264): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4552): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1020): GC_EXPLICIT freed 25283K, 66% free 18781K/53688K, paused 4ms+12ms, total 170ms
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4587 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4587): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4587): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4587): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4587): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4587): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4587): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4587): install
,I/MultiDex( 4587): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4587): loading existing secondary dex files
,I/MultiDex( 4587): load found 3 secondary dex files
,I/NSApplication( 4552): Starting up...
,I/MultiDex( 4587): install done
,I/ActivityManager( 1020): Killing 3933:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4587): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4587): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4587): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4587): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4587): VFY: unable to resolve instance field 36
,D/dalvikvm( 4587): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4587): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4587): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4587): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4587): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4587): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4607 uid=10056 gids={50056, 3003, 1028, 1015}
D/dalvikvm( 4587): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f7a908
D/dalvikvm( 4587): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f7a908
D/dalvikvm( 4587): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f7a908, skipping init
D/dalvikvm( 4587): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f7a908
D/dalvikvm( 4587): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f7a908
V/JNIHelp ( 4587): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4587): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f7a908
,D/dalvikvm( 4587): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f7a908
D/dalvikvm( 4587): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f7a908
,D/dalvikvm( 4587): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f7a908
,D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4607): VFY: unable to resolve instance field 68
,D/dalvikvm( 4607): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4607): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4607): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1614): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1614): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4607): VFY: unable to resolve instance field 68
D/dalvikvm( 4607): VFY: replacing opcode 0x54 at 0x0011
,D/GetNotificationsWS( 1614): bindWebServices(): registering our AIDL callback...
D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,D/EmailService.MarketingOptInSetter( 1614): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/dalvikvm( 4607): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4607): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4607): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4607): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/GetNotificationsWS( 1614): onServiceConnected()
D/GetNotificationsWS( 1614): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1614): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1614): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1614): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4490): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4490): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4539): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4539): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager( 1020): Killing 4268:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ProviderInstaller( 4587): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1252): callingUid 10022, callindPid: 1252
,E/MDM     ( 1252): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1349): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1349): Proximity feature is not enabled.
,D/LocationInitializer( 1745): Restart initialization of location
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1252): No location to return for getLastLocation()
,W/FusedLocationProvider( 1252): location=null
,I/dalvikvm( 4587): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4587): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4587): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4587): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4587): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4587): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4587): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4587): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4587): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4587): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4587): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4587): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4587): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4587): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4587): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4587): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4587): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51f7000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51f7000
,D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
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
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2327563686
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4369): 
,D/NativeLibraryUtils( 4587): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4587): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421ca2f0
,D/dalvikvm( 4587): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421ca2f0
,D/dalvikvm( 4587): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421ca2f0, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,W/Settings( 4587): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4587): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4643): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4587): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4587): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 86ms
,I/Adreno-EGL( 4587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4587): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4587): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4587): Local Branch: 
I/Adreno-EGL( 4587): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4587): Local Patches: NONE
I/Adreno-EGL( 4587): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4587): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4587): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4587): Local Branch: 
I/Adreno-EGL( 4587): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4587): Local Patches: NONE
I/Adreno-EGL( 4587): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4369): 
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4369): 
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4369): 
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4369): 
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4369): 
,I/jxcore-log( 4369): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4369): 
,I/Adreno-EGL( 4587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4587): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4587): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4587): Local Branch: 
I/Adreno-EGL( 4587): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4587): Local Patches: NONE
I/Adreno-EGL( 4587): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4587): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4587): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4587): Local Branch: 
I/Adreno-EGL( 4587): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4587): Local Patches: NONE
I/Adreno-EGL( 4587): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=3083771427
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1614): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1614): now: 333633 ,futureTime: 62164019
,D/PollingManager( 1614): Polling alarm set to expire at: 62164019 Current Time: 333633
,E/ActivityThread( 1614): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1614): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1614): [debug] > CusSM.onRadioUp
D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/PollingManager( 1614): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1614): now: 333646 ,futureTime: 62164019
D/PollingManager( 1614): Polling alarm set to expire at: 62164019 Current Time: 333646
D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
D/OtaApp  ( 1614): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
W/XTWiFiOS( 1295): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1614): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
E/ActivityThread( 1614): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1614): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
I/openssl ( 4490): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4490): Crypto mode 0 already enabled
,V/AlarmManager( 1020): sending alarm Alarm{427de8c8 type 2 com.google.android.gms}
D/OtaApp  ( 1614): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1614): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1614): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4539): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4539): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1614): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,I/jxcore-log( 4369): Test app app.js loaded
I/jxcore-log( 4369): 
,I/CheckinService( 1745): Checkin interval check for package: unspecified last checkin: 1453034244818 min interval config: 0 actual interval: 288228
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1614): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/chromium( 4369): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/OtaApp  ( 1614): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1280): Column apn id key is 'apn_id'
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DEBUG   ( 1614): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,W/ContextImpl( 1614): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1614): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1614): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1614): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1614): onServiceConnected()
D/GetNotificationsWS( 1614): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1614): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1614): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4490): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4490): Crypto mode 0 already enabled
,I/CheckinRequestBuilder( 1745): Classify the device as Phone.
,D/MobileConnectivityChangeReceiver( 4539): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4539): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1745): Checkin interval check for package: unspecified last checkin: 1453034244818 min interval config: 0 actual interval: 288308
,D/dalvikvm( 1614): GC_CONCURRENT freed 6374K, 38% free 10712K/17224K, paused 2ms+5ms, total 55ms
,D/DEBUG   ( 1614): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1614): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1614): bindWebServices(): registering our AIDL callback...
I/SundryService( 1614): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1614): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1614): onServiceConnected()
,D/GetNotificationsWS( 1614): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1614): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1614): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1614): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1614
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1614): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1614): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1614): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1614): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1614): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1614): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1614): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1614): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1614): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1614): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1614): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1614): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1614): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1614
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Keyboard.Facilitator( 1220): onFinishInput()
W/IInputConnectionWrapper( 4369): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1614): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1614): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1614): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1614): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1614): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1614): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1020): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,120
D/OtaApp  ( 1614): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 1614): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1614): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1614): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1614): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1020): Activity reported stop, but no longer stopping: ActivityRecord{42865040 u0 com.motorola.ccc.ota/.ui.DownloadActivity t2}
,I/CheckinTask( 1745): Sending checkin request (11757 bytes)
,I/jxcore-log( 4369): --= Surplus to requirements =--
I/jxcore-log( 4369): 
I/jxcore-log( 4369): ****TEST TOOK:  ms ****
I/jxcore-log( 4369): 
,I/jxcore-log( 4369): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4369): 
,D/AndroidRuntime( 4688): 
D/AndroidRuntime( 4688): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4688): CheckJNI is OFF
,D/dalvikvm( 4688): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4688): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4688): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4688): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4688): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4688): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4688): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4688): failed to load memtrack module: -2
,D/AndroidRuntime( 4688): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10117 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 4369:com.test.thalitest/u0a117 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{44a555c0 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1020): WIN DEATH: Window{446a30d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10117 user=0: pkg removed
,D/dalvikvm( 1745): GC_EXPLICIT freed 1073K, 30% free 12058K/17224K, paused 4ms+6ms, total 45ms
,W/SQLiteConnectionPool( 1745): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 2326): GC_EXPLICIT freed 5213K, 44% free 9649K/17224K, paused 2ms+10ms, total 48ms
,D/dalvikvm( 2359): GC_EXPLICIT freed 3027K, 43% free 9840K/17224K, paused 3ms+3ms, total 69ms
,W/GeofencerStateMachine( 1252): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1220): resetDictionaries() : en_GB
,I/Keyboard.Facilitator.DecoderInitializer( 1220): run()
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
D/VoicemailCleanupService( 1194): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1220): createOrResetDecoder
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1308): GC_EXPLICIT freed 3253K, 33% free 11598K/17224K, paused 2ms+4ms, total 62ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/Launcher( 1308): Deferring update until onResume
,I/CheckinRequestBuilder( 1745): Checkin reason type: 8 attempt count: 1
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1020):   Scheme: "mmsto"
I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4717 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1020):   Scheme: "sms"
E/ActivityThread( 1745): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,I/ConfigService( 1252): onCreate
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10117 #1
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1220): run()
,I/Launcher( 1308): Deferring update until onResume
,I/InternalIcingCorporaPro( 2359): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1020): Killing 4300:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1349): null clazz in OP_INSTANCE_OF, single-stepping
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4734 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1220): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1220): run() : Missing File = Personal.en_GB.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1220): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1220): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1220): run()
I/StatsUtilsManager( 1220): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1220): shouldRecordStats() = Too Soon
,W/ContextImpl( 4734): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1745): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1745): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1745): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1745): Module APK com.google.android.play.games already loaded
I/dalvikvm( 3682): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3682): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3682): VFY: replacing opcode 0x6e at 0x0013
,I/LocationSettingsChecker( 1745): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1745): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1745): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1349): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1349): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1745): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1745): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1745): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1745): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1745): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1745): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1745): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1745): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1745): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1745): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1745): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1745): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1745): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/dalvikvm( 1020): GC_EXPLICIT freed 1791K, 65% free 18798K/53688K, paused 8ms+13ms, total 308ms
,D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/AndroidRuntime( 4688): Shutting down VM
,D/dalvikvm( 4688): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,D/dalvikvm( 1020): GC_EXPLICIT freed 153K, 66% free 18646K/53688K, paused 4ms+10ms, total 96ms
,I/Icing   ( 1745): doRemovePackageData com.test.thalitest
,I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4763 uid=10059 gids={50059, 1028, 3003, 1015}
,I/ActivityManager( 1020): Killing 4490:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2359): UpdateCorporaTask done [took 302 ms] updated apps [took 302 ms] 
,I/CheckinRequestBuilder( 1745): Classify the device as Phone.
,I/CheckinTask( 1745): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1745): Checking schedule, now: 1453034534970 next: 1453584188967
,I/CheckinService( 1745): active receiver: disabled
,I/CheckinService( 1745): Checking schedule, now: 1453034534984 next: 1453584188967
,I/CheckinService( 1745): active receiver: disabled
,D/CheckinService( 1745): Recording last checkin time for package unspecified as 1453034534990
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/dalvikvm( 4763): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
,W/dalvikvm( 4763): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4763): VFY: replacing opcode 0x6e at 0x001b
,I/dalvikvm( 4763): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 4763): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4763): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4763): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4763):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4763):   adb logcat -s GAv4
,W/GAv4    ( 4763): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SQLiteDatabase( 4763): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4763): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4763): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4763): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4763): 	at avm.getWritableDatabase(PG:244)
E/SQLiteDatabase( 4763): 	at avc.a(PG:1573)
E/SQLiteDatabase( 4763): 	at jep$b.a(PG:131)
E/SQLiteDatabase( 4763): 	at ave.run(PG:588)
,W/dalvikvm( 4763): threadid=11: thread exiting with uncaught exception (group=0x416a2d40)
I/dalvikvm( 4763): Could not find method android.app.Activity.finishAfterTransition, referenced from method ce.onBackPressed
W/dalvikvm( 4763): VFY: unable to resolve virtual method 1245: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4763): VFY: replacing opcode 0x6e at 0x0012
E/CAKEMIX_CRASHED( 4763): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4763): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/CAKEMIX_CRASHED( 4763): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/CAKEMIX_CRASHED( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/CAKEMIX_CRASHED( 4763): 	at avm.getWritableDatabase(PG:244)
E/CAKEMIX_CRASHED( 4763): 	at avc.a(PG:1573)
E/CAKEMIX_CRASHED( 4763): 	at jep$b.a(PG:131)
E/CAKEMIX_CRASHED( 4763): 	at ave.run(PG:588)
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
W/GAv4    ( 4763): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1094): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1208): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1208): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=100
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4763): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4763): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4763): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4763): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4763): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4763): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4763): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4763): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4763): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4763): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4763): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4763): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4763): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4763): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4763): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4763): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4763): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4763): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4763): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4763): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4763): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4763): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4763): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4763): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
I/ActivityManager( 1020): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from pid 4763
,W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/dalvikvm( 4763): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4763): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 4763): VFY: replacing opcode 0x71 at 0x0075
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/FileUtils( 4763): Failed to chmod(/data/data/com.google.android.apps.docs/app_filecache2): libcore.io.ErrnoException: chmod failed: ENOENT (No such file or directory)
I/Process ( 4763): Sending signal. PID: 4763 SIG: 9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
E/SQLiteLog( 2326): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
I/ActivityManager( 1020): Process com.google.android.apps.docs (pid 4763) has died.
E/SQLiteDatabase( 2326): Error inserting state=component=com.google.android.apps.docs/.app.ErrorNotificationActivity event=am_restart_activity timestamp=1453034535194 timezone=3600 name=PauseResumeTrigger
E/SQLiteDatabase( 2326): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2326): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2326): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2326): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2326): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2326): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2326): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2326): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2326): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2326): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2326): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2326): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2326): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2326): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2326): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2326): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
E/SQLiteLog( 2326): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error

```
