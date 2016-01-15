#### Test 561510938d3c4f5_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1018): sending alarm Alarm{4342dec8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4416): 
D/AndroidRuntime( 4416): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4416): CheckJNI is OFF
D/dalvikvm( 4416): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4416): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4416): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4416): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4416): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4416): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4416): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4416): failed to load memtrack module: -2
D/AndroidRuntime( 4416): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4416
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4432 uid=10112 gids={50112, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4416): Shutting down VM
D/dalvikvm( 4416): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4432): Binding Chromium to main looper Looper (main, tid 1) {41f7a790}
I/LibraryLoader( 4432): Expected native library version number "",actual native library version number ""
I/chromium( 4432): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4432): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43bf9c50:true
I/Adreno-EGL( 4432): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4432): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4432): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4432): Local Branch: 
I/Adreno-EGL( 4432): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4432): Local Patches: NONE
I/Adreno-EGL( 4432): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4432): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4432): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4432): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4432): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4432): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4432): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4432): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4432): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4432): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4432): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4432): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4432): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4432): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4432): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4432): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4432): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4432): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4432): Enabling debug mode 0
,I/Keyboard.Facilitator( 1208): onFinishInput()
,W/AwContents( 4432): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4432): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,433
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +409ms (total +434ms)
,D/JsMessageQueue( 4432): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4432): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7ea60
,D/dalvikvm( 4432): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7ea60
,D/jxcore_app_log( 4432): JniHelper::setJavaVM(0x415d0fa8), pthread_self() = 1614784616
,D/JX-Cordova( 4432): jxcore cordova android initializing
,D/dalvikvm( 4432): GC_CONCURRENT freed 2701K, 16% free 14488K/17224K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 328K, 14% free 14849K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 16.574MB for 42652-byte allocation
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 104K, 14% free 14855K/17268K, paused 26ms, total 27ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 127K, 14% free 14876K/17268K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 16.651MB for 95956-byte allocation
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 179K, 15% free 14910K/17364K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 16.730MB for 143930-byte allocation
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 253K, 15% free 14957K/17508K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 16.845MB for 215890-byte allocation
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 368K, 16% free 15032K/17720K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 17.021MB for 323830-byte allocation
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 568K, 17% free 15152K/18040K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 17.292MB for 485740-byte allocation
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 865K, 18% free 15328K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 1204K, 16% free 15576K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 106K, 16% free 15557K/18516K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 18.266MB for 1092904-byte allocation
,D/dalvikvm( 4432): GC_CONCURRENT freed 1938K, 19% free 15993K/19584K, paused 1ms+7ms, total 66ms
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 19.214MB for 1639352-byte allocation
,D/dalvikvm( 4432): GC_CONCURRENT freed 2075K, 23% free 16517K/21188K, paused 1ms+6ms, total 55ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 941K, 23% free 16468K/21188K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 20.459MB for 2459024-byte allocation
,D/dalvikvm( 4432): GC_CONCURRENT freed 1935K, 27% free 17274K/23592K, paused 5ms+3ms, total 50ms
,D/dalvikvm( 4432): GC_CONCURRENT freed 2523K, 26% free 17509K/23592K, paused 1ms+7ms, total 50ms
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 88K, 26% free 17473K/23592K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 22.614MB for 3688532-byte allocation
,D/dalvikvm( 4432): GC_CONCURRENT freed 2746K, 32% free 18640K/27196K, paused 2ms+7ms, total 74ms
,D/dalvikvm( 4432): GC_FOR_ALLOC freed 1915K, 32% free 18609K/27196K, paused 33ms, total 33ms
,W/jxcore-log( 4432): Initializing JXcore engine
,W/jxcore-log( 4432): JXcore engine is ready
,D/dalvikvm( 4432): GC_CONCURRENT freed 392K, 22% free 21420K/27196K, paused 1ms+2ms, total 31ms
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 4432): Starting JXcore engine
,D/dalvikvm( 4432): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 4432): Platform android
W/jxcore-log( 4432): 
,W/jxcore-log( 4432): Process ARCH arm
W/jxcore-log( 4432): 
,I/jxcore-log( 4432): JXcore Cordova bridge is ready!
I/jxcore-log( 4432): 
,W/jxcore-log( 4432): JXcore engine is started
,I/chromium( 4432): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4432): Toggling radios to true
I/jxcore-log( 4432): 
,D/BluetoothAdapter( 4432): enable(): BT is already enabled..!
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=4432, uid=10112
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
I/jxcore-log( 4432): Radios toggled
I/jxcore-log( 4432): 
I/jxcore-log( 4432): My device name is: motorola-XT1039
I/jxcore-log( 4432): 
,D/TCMD    (  409): NL - Read 1000 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 68 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 68 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
,D/TCMD    (  409): Listening for incoming client connection request
,I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  272): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  272):  STA Disconnected !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
,I/MDMCTBK (  272): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  272): send SAR ctrl over QMI
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1018): InitialState.processMessage what=4
,V/ConnectivityService( 1018): WiFi NOT Tethered!
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  409): NL - Read 60 bytes from update socket.
D/TCMD    (  409): NL - ignore NL message, type = 21
,D/TCMD    (  409): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1018): connected time updated 307376
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1093): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1093): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1093): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1018): DisconnectingState
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/WifiStateMachine( 1018): handleMessage: X
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x61628ac0 clazz=0x64500001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection lost
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
V/NativeCrypto( 1374): Read error: ssl=0x630c0770: I/O error during system call, Connection timed out
V/NativeCrypto( 1374): SSL shutdown failed: ssl=0x630c0770: I/O error during system call, Broken pipe
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1018): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 1180): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  272): Event received = Trying to associate with
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1180): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  409): NL - Read 56 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
,D/TCMD    (  409): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 1180): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1180): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  409): NL - Read 312 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 192 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 68 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
,D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 1000 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  272): Event received = Associated with c0:ff:d4
D/TCMD    (  409): NL - Read 80 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 80 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/TCMD    (  409): NL - Read 68 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  272): Event received = WPA: Key negotiation com
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  272): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  272):  STA Connected !!
D/TCMD    (  409): NL - Read 1000 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/TCMD    (  409): Listening for incoming client connection request
E/MDMCTBK (  272): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  272): get_freq !!, resp=0
I/MDMCTBK (  272): get_freq !!, Strip data
I/MDMCTBK (  272): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  272): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  272): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  272): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1192144120
I/MDMCTBK (  272): return from set_get_from_wpa_supplicant
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
,I/MDMCTBK (  272): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/MDMCTBK (  272): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  272): send SAR ctrl over QMI
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
E/MDMCTBK (  272): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  272): , reply_len: 3, ret: 0
E/MDMCTBK (  272): MdmCutbackHndler, resp=OK
E/MDMCTBK (  272): 
D/MDMCTBK (  272): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@447e9108 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4278be58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4278be58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 6
D/TCMD    (  409): NL - Read 56 bytes from update socket.
D/TCMD    (  409): NL - message type is RTM_NEWLINK
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/TCMD    (  409): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44a2ea20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44a2ea20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44a2ea20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  409): NL - Read 60 bytes from update socket.
D/TCMD    (  409): NL - ignore NL message, type = 20
D/TCMD    (  409): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
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
D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1093): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
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
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1093): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@420341d0
I/SBar.NetworkController( 1093): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
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
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/SBar.NetworkController( 1093): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@420341d0
I/SBar.NetworkController( 1093): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1312): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=0
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1641): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1093): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/ActivityManager( 1018): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4562 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1641): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1641): Registering with Alarm Manager to restart CCE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1641): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1641): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
E/ActivityThread( 1641): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1641): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1641): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/dalvikvm( 4562): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f82f00, skipping init
I/openssl ( 4562): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4562): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4596 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4025:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4596): mnc/mcc: 
V/MmsConfig( 4596): tag: bool value: enabledMMS - true
,V/MmsConfig( 4596): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4596): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4596): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4596): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4596): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4596): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4596): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4596): tag: int value: recipientLimit - 20
V/MmsConfig( 4596): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4596): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4596): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4596): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4596): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4596): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4596): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4596): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4596): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4616 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 4200:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1018): GC_EXPLICIT freed 25583K, 66% free 18458K/52856K, paused 4ms+11ms, total 211ms
,D/MobileConnectivityChangeReceiver( 4616): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4616): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4616): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4616): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4630 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4236:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1765): Checkin interval check for package: unspecified last checkin: 1452860355889 min interval config: 0 actual interval: 293257
,I/CheckinService( 1765): Checking schedule, now: 1452860649157 next: 1452860385872
,I/CheckinService( 1765): active receiver: enabled
,I/CheckinService( 1765): Preparing to send checkin request
,I/EventLogService( 1765): Accumulating logs since 1452860351574
,D/dalvikvm( 1246): GC_CONCURRENT freed 1639K, 35% free 11362K/17224K, paused 4ms+8ms, total 53ms
,D/ConnectivityService( 1018): NetTransition Wakelock for ConnectedState released by timeout
,I/CheckinRequestBuilder( 1765): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1765): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4630): Binding Chromium to main looper Looper (main, tid 1) {41f7e338}
,I/LibraryLoader( 4630): Expected native library version number "",actual native library version number ""
,I/chromium( 4630): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4630): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4630): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4630): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4630): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4630): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4630): Local Branch: 
I/Adreno-EGL( 4630): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4630): Local Patches: NONE
I/Adreno-EGL( 4630): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4630): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4662 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/GAV2    ( 4630): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4662): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4662): VFY: replacing opcode 0x60 at 0x000b,
,I/dalvikvm( 4662): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4662): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4662): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4662): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4662): install
,I/MultiDex( 4662): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4662): loading existing secondary dex files
,I/MultiDex( 4662): load found 3 secondary dex files
,I/MultiDex( 4662): install done
,D/dalvikvm( 4662): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4662): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4662): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4662): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4662): VFY: unable to resolve instance field 36
,D/dalvikvm( 4662): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4662): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4662): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4662): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4662): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4662): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4662): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f84af0
,D/dalvikvm( 4662): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f84af0
,D/dalvikvm( 4662): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f84af0, skipping init
D/dalvikvm( 4662): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f84af0
,D/dalvikvm( 4662): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f84af0
,V/JNIHelp ( 4662): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4662): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f84af0
,D/dalvikvm( 4662): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f84af0
D/dalvikvm( 4662): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f84af0
,D/dalvikvm( 4662): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f84af0
,I/NSApplication( 4630): Starting up...
,I/ActivityManager( 1018): Killing 3969:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4686 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4662): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4662): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4662): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4662): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4662): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4662): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4662): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4662): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4662): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4662): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4662): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4662): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4662): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4662): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4662): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4662): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4662): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4662): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4686): VFY: unable to resolve instance field 68
,D/dalvikvm( 4686): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4686): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4686): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1641): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1641): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,I/ActivityManager( 1018): Killing 4274:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4686): VFY: unable to resolve instance field 68
,D/dalvikvm( 4686): VFY: replacing opcode 0x54 at 0x0011
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/GetNotificationsWS( 1641): bindWebServices(): registering our AIDL callback...
D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4686): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4686): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4686): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4686): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/EmailService.MarketingOptInSetter( 1641): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1641): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1641): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1641): onServiceConnected()
D/GetNotificationsWS( 1641): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1641): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4562): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4562): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4616): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4616): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5204000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5204000
,D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/WearableService( 1246): callingUid 10022, callindPid: 1246
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,E/MDM     ( 1246): [132] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/LocationInitializer( 1765): Restart initialization of location
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3540482655
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/GCoreFlp( 1246): No location to return for getLastLocation()
,W/FusedLocationProvider( 1246): location=null
,D/NativeLibraryUtils( 4662): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4662): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4217b3e8
,D/dalvikvm( 4662): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4217b3e8
,D/dalvikvm( 4662): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4217b3e8, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1141614980
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Settings( 4662): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/chromium( 4432): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 4662): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4729): DexOpt: load 10ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4662): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4662): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 104ms
,I/Adreno-EGL( 4662): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4662): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4662): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4662): Local Branch: 
I/Adreno-EGL( 4662): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4662): Local Patches: NONE
I/Adreno-EGL( 4662): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4662): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4662): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4662): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4662): Local Branch: 
I/Adreno-EGL( 4662): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4662): Local Patches: NONE
I/Adreno-EGL( 4662): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4662): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4662): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4662): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4662): Local Branch: 
I/Adreno-EGL( 4662): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4662): Local Patches: NONE
I/Adreno-EGL( 4662): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1641): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/PollingManager( 1641): now: 341201 ,futureTime: 71378645
D/PollingManager( 1641): Polling alarm set to expire at: 71378645 Current Time: 341201
E/ActivityThread( 1641): Failed to find provider info for com.motorola.blur.setupprovider
I/openssl ( 4562): Crypto mode not selected, openssl will run on its regular mode.
D/OtaApp  ( 1641): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1641): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1641): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4562): Crypto mode 0 already enabled
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/PollingManager( 1641): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1641): now: 341246 ,futureTime: 71378645
D/PollingManager( 1641): Polling alarm set to expire at: 71378645 Current Time: 341247
E/ActivityThread( 1641): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1641): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1641): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1641): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
D/Checkin ( 1641): publish the event [tag = MOT_OTA event name = LOG]
,I/Adreno-EGL( 4662): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4662): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4662): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4662): Local Branch: 
I/Adreno-EGL( 4662): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4662): Local Patches: NONE
I/Adreno-EGL( 4662): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/MobileConnectivityChangeReceiver( 4616): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4616): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1765): Checkin interval check for package: unspecified last checkin: 1452860355889 min interval config: 0 actual interval: 295455
,D/dalvikvm( 1641): GC_CONCURRENT freed 6397K, 38% free 10764K/17224K, paused 3ms+7ms, total 87ms
,D/OtaApp  ( 1641): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1641): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1641): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1641): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/DEBUG   ( 1641): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/OtaApp  ( 1641): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1641): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 1641): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1641): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1641): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1641): onServiceConnected()
D/GetNotificationsWS( 1641): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1641): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1641): [debug] > CusSM.runStateMachine: server told to :continue
,D/WaitableIntentService( 1641): ServiceHandler.handleMessage: mWaitCount=0
I/openssl ( 4562): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4562): Crypto mode 0 already enabled
D/GetNotificationsWS( 1641): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4616): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4616): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1765): Checkin interval check for package: unspecified last checkin: 1452860355889 min interval config: 0 actual interval: 295526
,D/DEBUG   ( 1641): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1641): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1641): bindWebServices(): registering our AIDL callback...
I/SundryService( 1641): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1641): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1641): onServiceConnected()
D/GetNotificationsWS( 1641): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1641): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1641): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/GetNotificationsWS( 1641): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1641): [debug] > Received start id 2: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/OtaApp  ( 1641): [debug] > handle intent : null
,D/OtaApp  ( 1641): [debug] > supress duplicated intent, nextPompt: 1452946758995 and mNotificationInStatusBar: true
,D/TelephonyProvider( 1273): Column apn id key is 'apn_id'
,D/OtaApp  ( 1641): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/OtaApp  ( 1641): [debug] > Received start id 3: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1641): [debug] > handle intent : null
,D/OtaApp  ( 1641): [debug] > supress duplicated intent, nextPompt: 1452946758995 and mNotificationInStatusBar: true
,I/CheckinRequestBuilder( 1765): Classify the device as Phone.
,I/CheckinTask( 1765): Sending checkin request (11682 bytes)
,V/AlarmManager( 1018): sending alarm Alarm{448e4b18 type 2 com.google.android.gms}
,D/dalvikvm( 1765): GC_CONCURRENT freed 1827K, 30% free 12109K/17224K, paused 5ms+8ms, total 46ms
,I/CheckinRequestBuilder( 1765): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1765): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1374): GC_EXPLICIT freed 1422K, 40% free 10358K/17224K, paused 2ms+4ms, total 42ms
,D/dalvikvm( 1018): GC_EXPLICIT freed 835K, 66% free 18251K/52856K, paused 4ms+11ms, total 102ms
,I/CheckinRequestBuilder( 1765): Classify the device as Phone.
,I/CheckinTask( 1765): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1765): Checking schedule, now: 1452860652648 next: 1452902706645
,I/CheckinService( 1765): active receiver: disabled
,I/CheckinService( 1765): Checking schedule, now: 1452860652667 next: 1452902706645
,I/CheckinService( 1765): active receiver: disabled
,D/CheckinService( 1765): Recording last checkin time for package unspecified as 1452860652672
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1093): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1312): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1312): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=100
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4630): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1018): Killing 4309:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/Launcher( 1322): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/Launcher( 1322): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4806 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/GCoreNlp( 1246): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/InternalIcingCorporaPro( 2373): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1018): Killing 4562:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1765): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1765): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1765): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2373): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
,I/Icing   ( 1765): Indexing 08D2302403BBE76D1189E62A66162DB0256D4E65 from com.google.android.gms
,I/Icing   ( 1765): Indexing done 08D2302403BBE76D1189E62A66162DB0256D4E65
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{425b1848 type 2 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{425a2af8 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1208): run()
,I/Keyboard.Facilitator( 1208): flushDynamicLanguageModels()
,I/ConfigService( 1246): onCreate
,I/ConfigService( 1246): onDestroy
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
,V/AlarmManager( 1018): sending alarm Alarm{42872290 type 3 android}
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
,I/ClearcutLoggerApiImpl( 1374): disconnect managed GoogleApiClient
,V/AlarmManager( 1018): sending alarm Alarm{44a04060 type 3 android}
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
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4,
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 5
,V/AlarmManager( 1018): sending alarm Alarm{433d5368 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42862c60 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{440eb8d0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42580508 type 1 com.android.deskclock}
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4886 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 4596:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1018): sending alarm Alarm{429f00c0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44327060 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42570d48 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/AlarmManager( 1018): sending alarm Alarm{433618d8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43322af0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43ec45a0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{448441a0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{443156c8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{44a1e690 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4330ea98 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4256ee50 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1312): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1312): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1312): onReceive() - done, currentInetCondition=100
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43f67458 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{427968d0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{429f9f70 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42807d98 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{449f1a38 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428ebbe8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43f67530 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{449156b8 type 1 com.android.deskclock}
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/AlarmManager( 1018): sending alarm Alarm{4488da48 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{448cca98 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43cc0ee0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44321198 type 3 android}
,I/ProcessStatsService( 1018): Prepared write state in 33ms
,I/ProcessStatsService( 1018): Prepared write state in 26ms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-22-31.bin
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
,V/AlarmManager( 1018): sending alarm Alarm{432178d8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{443694e8 type 3 android}
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
,D/dalvikvm( 1018): GC_CONCURRENT freed 2135K, 66% free 18317K/52856K, paused 31ms+9ms, total 141ms
,V/AlarmManager( 1018): sending alarm Alarm{43ee91e0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44a14e00 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{449eef88 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5011): 
D/AndroidRuntime( 5011): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5011): CheckJNI is OFF
D/dalvikvm( 5011): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5011): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5011): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5011): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5011): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5011): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5011): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5011): failed to load memtrack module: -2
D/AndroidRuntime( 5011): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10112 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 4432:com.test.thalitest/u0a112 (adj 0): stop com.test.thalitest
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1018): Killing 4686:com.android.chrome/u0a56 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 4630:com.google.android.apps.magazines/u0a76 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 4616:com.google.android.setupwizard/u0a41 (adj 15): empty for 1800s
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{44929c10 u0 com.test.thalitest/.MainActivity t2}
I/WindowState( 1018): WIN DEATH: Window{449354d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1018): Client connection lost with reason: 4
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10112 user=0: pkg removed
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1208): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1246): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1208): run()
D/VoicemailCleanupService( 1190): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2340): GC_EXPLICIT freed 5357K, 44% free 9653K/17224K, paused 2ms+7ms, total 67ms
D/dalvikvm( 1322): GC_EXPLICIT freed 3531K, 33% free 11601K/17224K, paused 2ms+18ms, total 82ms
I/Launcher( 1322): Deferring update until onResume
D/dalvikvm( 1765): GC_EXPLICIT freed 1715K, 31% free 11949K/17224K, paused 4ms+5ms, total 150ms
W/SQLiteConnectionPool( 1765): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1018): GC_EXPLICIT freed 643K, 66% free 18180K/52856K, paused 6ms+9ms, total 145ms
D/dalvikvm( 2373): GC_EXPLICIT freed 4026K, 42% free 10086K/17224K, paused 2ms+4ms, total 154ms
I/Decoder ( 1208): createOrResetDecoder
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2373): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5049 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/ConfigService( 1246): onCreate
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10112 #1
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
W/ContextImpl( 5049): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Launcher( 1322): Deferring update until onResume
W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 4432 uid 10112
I/InternalIcingCorporaPro( 2373): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
I/Keyboard.Facilitator( 1208): onFinishInput()
D/PackageBroadcastService( 1765): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1765): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1765): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1765): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): run()
I/dalvikvm( 3880): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3880): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3880): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1765): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1765): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1765): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1374): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1374): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
V/AlarmManager( 1018): sending alarm Alarm{427ea4e8 type 3 android}
I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
V/AlarmManager( 1018): sending alarm Alarm{427dbe80 type 3 com.google.android.gms}
V/AlarmManager( 1018): sending alarm Alarm{427d0c08 type 0 com.google.android.gms}
V/AlarmManager( 1018): sending alarm Alarm{427d3da0 type 2 com.motorola.ccc.cce}
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1208): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1208): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1208): run()
I/StatsUtilsManager( 1208): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1208): shouldRecordStats() = Too Soon
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5078 uid=10059 gids={50059, 1028, 3003, 1015}
I/Icing   ( 1765): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1765): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1765): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
D/gH_MetricsDatabase( 1765): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1765): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
D/gH_CompatibleDatabase( 1765): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1765): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1765): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
D/gH_CompatibleDatabase( 1765): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1765): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1765): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1765): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1765): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1765): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1018): GC_EXPLICIT freed 728K, 66% free 18317K/52856K, paused 5ms+16ms, total 334ms
D/AndroidRuntime( 5011): Shutting down VM
D/dalvikvm( 5011): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
I/dalvikvm( 5078): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 5078): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5078): VFY: replacing opcode 0x6e at 0x000f
I/GAv4    ( 5078): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5078):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5078):   adb logcat -s GAv4
W/GAv4    ( 5078): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/dalvikvm( 5078): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 5078): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 5078): VFY: replacing opcode 0x6e at 0x001b
W/GAv4    ( 5078): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5078): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5078): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
I/dalvikvm( 5078): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 5078): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 5078): VFY: replacing opcode 0x71 at 0x0075
V/AlarmManager( 1018): sending alarm Alarm{427d37c8 type 2 com.google.android.gms}
I/ActivityManager( 1018): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=5112 uid=10095 gids={50095, 3003, 1028, 1015}
E/SharedPreferencesImpl( 5078): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5078): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
E/SQLiteDatabase( 5112): Failed to open database '/data/data/com.quickoffice.android/databases/keyvaluedb.db'.
E/SQLiteDatabase( 5112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5112): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/SQLiteDatabase( 5112): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 5112): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 5112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5112): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5112): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 5112): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5112): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 5112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 5112): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 5112): Shutting down VM
W/dalvikvm( 5112): threadid=1: thread exiting with uncaught exception (group=0x416afd40)
E/AndroidRuntime( 5112): FATAL EXCEPTION: main
E/AndroidRuntime( 5112): Process: com.quickoffice.android, PID: 5112
E/AndroidRuntime( 5112): java.lang.RuntimeException: Unable to get provider com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5112): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 5112): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 5112): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 5112): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 5112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 5112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5112): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5112): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 5112): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5112): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 5112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 5112): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5112): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5112): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/AndroidRuntime( 5112): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 5112): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 5112): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 5112): 	... 12 more
I/Process ( 5112): Sending signal. PID: 5112 SIG: 9
D/dalvikvm( 5078): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5078): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5078): VFY: replacing opcode 0x62 at 0x000a
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
D/dalvikvm( 5078): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5078): VFY: unable to resolve instance field 36
D/dalvikvm( 5078): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5078): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5078): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5078): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5078): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 5078): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
I/ActivityManager( 1018): Process com.quickoffice.android (pid 5112) has died.
D/dalvikvm( 5078): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x422dfec0
D/dalvikvm( 5078): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x422dfec0
D/dalvikvm( 5078): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x422dfec0, skipping init
D/dalvikvm( 5078): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x422dfec0
D/dalvikvm( 5078): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x422dfec0
V/JNIHelp ( 5078): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...

```
