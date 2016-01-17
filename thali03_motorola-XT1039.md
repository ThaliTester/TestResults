#### Test 5615109389cecbd_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1021): sending alarm Alarm{4336c8b0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4394): 
D/AndroidRuntime( 4394): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4394): CheckJNI is OFF
D/dalvikvm( 4394): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4394): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4394): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4394): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4394): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4394): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4394): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4394): failed to load memtrack module: -2
D/AndroidRuntime( 4394): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4394
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4410 uid=10115 gids={50115, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4394): Shutting down VM
D/dalvikvm( 4394): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4410): Binding Chromium to main looper Looper (main, tid 1) {41f4a308}
I/LibraryLoader( 4410): Expected native library version number "",actual native library version number ""
I/chromium( 4410): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4410): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43b0ee70:true
I/Adreno-EGL( 4410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4410): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4410): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4410): Local Branch: 
I/Adreno-EGL( 4410): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4410): Local Patches: NONE
I/Adreno-EGL( 4410): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4410): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4410): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4410): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4410): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4410): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4410): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4410): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4410): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4410): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4410): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4410): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4410): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4410): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4410): Enabling debug mode 0
,W/AwContents( 4410): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1209): onFinishInput()
,W/IInputConnectionWrapper( 4410): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,410
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +374ms (total +410ms)
,D/JsMessageQueue( 4410): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4410): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f4e7b8
,D/dalvikvm( 4410): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f4e7b8
,D/jxcore_app_log( 4410): JniHelper::setJavaVM(0x415a0fa8), pthread_self() = 1614640600
,D/JX-Cordova( 4410): jxcore cordova android initializing
,D/dalvikvm( 4410): GC_CONCURRENT freed 2673K, 16% free 14516K/17224K, paused 3ms+3ms, total 36ms
,D/dalvikvm( 4410): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 326K, 14% free 14889K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 16.614MB for 42652-byte allocation
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 102K, 14% free 14896K/17268K, paused 26ms, total 26ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 125K, 14% free 14916K/17268K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 16.691MB for 95956-byte allocation
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 177K, 14% free 14951K/17364K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 16.770MB for 143930-byte allocation
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 251K, 15% free 14998K/17508K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 16.884MB for 215890-byte allocation
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 366K, 15% free 15072K/17720K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 17.060MB for 323830-byte allocation
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 565K, 16% free 15192K/18040K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 17.332MB for 485740-byte allocation
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 859K, 17% free 15369K/18516K, paused 28ms, total 29ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 1120K, 16% free 15609K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 195K, 16% free 15584K/18516K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 18.293MB for 1092904-byte allocation
,D/dalvikvm( 4410): GC_CONCURRENT freed 1810K, 19% free 16021K/19584K, paused 1ms+5ms, total 37ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 182K, 19% free 15947K/19584K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 19.169MB for 1639352-byte allocation
,D/dalvikvm( 4410): GC_CONCURRENT freed 1851K, 22% free 16538K/21188K, paused 1ms+3ms, total 35ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 1055K, 23% free 16521K/21188K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 20.511MB for 2459024-byte allocation
,D/dalvikvm( 4410): GC_CONCURRENT freed 1965K, 27% free 17295K/23592K, paused 4ms+4ms, total 44ms
,D/dalvikvm( 4410): GC_CONCURRENT freed 2511K, 26% free 17548K/23592K, paused 3ms+6ms, total 48ms
,D/dalvikvm( 4410): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 14K, 26% free 17543K/23592K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 22.682MB for 3688532-byte allocation
,D/dalvikvm( 4410): GC_CONCURRENT freed 351K, 24% free 20915K/27196K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 4368K, 32% free 18673K/27196K, paused 35ms, total 35ms
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 4410): Initializing JXcore engine
,W/jxcore-log( 4410): JXcore engine is ready
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
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
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4410): GC_CONCURRENT freed 414K, 22% free 21483K/27196K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 4410): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 4410): Starting JXcore engine
,W/jxcore-log( 4410): Platform android
W/jxcore-log( 4410): 
,W/jxcore-log( 4410): Process ARCH arm
W/jxcore-log( 4410): 
,I/jxcore-log( 4410): JXcore Cordova bridge is ready!
I/jxcore-log( 4410): 
,W/jxcore-log( 4410): JXcore engine is started
,I/chromium( 4410): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4410): Toggling radios to true
I/jxcore-log( 4410): 
,D/BluetoothAdapter( 4410): enable(): BT is already enabled..!
D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=4410, uid=10115
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4410): Radios toggled
I/jxcore-log( 4410): 
I/jxcore-log( 4410): My device name is: motorola-XT1039
I/jxcore-log( 4410): 
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
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
D/TCMD    (  491): NL - Read 1000 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
,D/TCMD    (  491): Listening for incoming client connection request
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/TCMD    (  491): NL - Read 1000 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
I/MDMCTBK (  276): send SAR ctrl over QMI
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  491): Listening for incoming client connection request
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
,D/TCMD    (  491): Listening for incoming client connection request
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1021): InitialState.processMessage what=4
,D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1021): WiFi NOT Tethered!
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  491): NL - Read 60 bytes from update socket.
D/TCMD    (  491): NL - ignore NL message, type = 21
,D/TCMD    (  491): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 320916
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1021): DisconnectingState
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: DisconnectingState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x615fa9b8 clazz=0x61c00001 iface=wlan0 mask=0x3
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection lost
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1371): Read error: ssl=0x63ea4008: I/O error during system call, Connection timed out
,V/NativeCrypto( 1371): SSL shutdown failed: ssl=0x63ea4008: I/O error during system call, Broken pipe
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1191): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1021): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1191): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1191): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  491): NL - Read 56 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
,D/TCMD    (  491): Listening for incoming client connection request
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1191): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1191): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  491): NL - Read 312 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 88 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 1000 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1191): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  491): NL - Read 80 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 80 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
,D/TCMD    (  491): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1191): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  276): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  491): NL - Read 1000 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
,D/TCMD    (  491): Listening for incoming client connection request
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
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1222823960
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection established
D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1021): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@44a240d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-38ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@44a2df80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-15ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42282ea0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42282ea0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 3
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 8
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 8
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/TCMD    (  491): NL - Read 56 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 80
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 80
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@449e0328 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@449e0328 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@449e0328 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1289): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1289): Active network info is not available
,D/PollingManager( 1608): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1021): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4496 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1289): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1289): Active network info is not available
,E/ActivityThread( 1608): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1608): Registering with Alarm Manager to restart CCE
D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/PollingManager( 1608): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1608): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
E/ActivityThread( 1608): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1608): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1608): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/dalvikvm( 4496): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f52ff8, skipping init
I/openssl ( 4496): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4496): Crypto mode 0 already enabled
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4523 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4089:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4523): mnc/mcc: 
,V/MmsConfig( 4523): tag: bool value: enabledMMS - true
V/MmsConfig( 4523): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4523): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4523): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 4523): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4523): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4523): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4523): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4523): tag: int value: recipientLimit - 20
,V/MmsConfig( 4523): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4523): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4523): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4523): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4523): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4523): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4523): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4523): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4523): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4542 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 4208:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TCMD    (  491): NL - Read 60 bytes from update socket.
D/TCMD    (  491): NL - ignore NL message, type = 20
,D/TCMD    (  491): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/MobileConnectivityChangeReceiver( 4542): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4542): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4542): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4542): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4561 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4257:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4561): Binding Chromium to main looper Looper (main, tid 1) {41f4e098}
,I/LibraryLoader( 4561): Expected native library version number "",actual native library version number ""
,I/chromium( 4561): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4561): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4561): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4561): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4561): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4561): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4561): Local Branch: 
I/Adreno-EGL( 4561): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4561): Local Patches: NONE
I/Adreno-EGL( 4561): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
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
D/WifiStateMachine( 1021): handleMessage: X
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/dalvikvm( 1021): GC_EXPLICIT freed 25392K, 66% free 18786K/53684K, paused 4ms+12ms, total 173ms
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): handleMessage: X
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1021): WiFi NOT Tethered!
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@4201ec48
,D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,W/chromium( 4561): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1021): WiFi NOT Tethered!
E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@4201ec48
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/CheckinService( 1725): Checkin interval check for package: unspecified last checkin: 1453023902298 min interval config: 0 actual interval: 306940
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1725): Checking schedule, now: 1453024209246 next: 1453023932208
,I/CheckinService( 1725): active receiver: enabled
,I/CheckinService( 1725): Preparing to send checkin request
,I/EventLogService( 1725): Accumulating logs since 1453023898144
,W/GAV2    ( 4561): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4561): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/CheckinRequestBuilder( 1725): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1725): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4623 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/NSApplication( 4561): Starting up...
,I/ActivityManager( 1021): Killing 3935:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/dalvikvm( 4623): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4623): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4623): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4623): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4623): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4623): install
,I/MultiDex( 4623): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4641 uid=10056 gids={50056, 3003, 1028, 1015}
I/MultiDex( 4623): loading existing secondary dex files
,I/MultiDex( 4623): load found 3 secondary dex files
,I/MultiDex( 4623): install done
,D/dalvikvm( 4623): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4623): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4623): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4623): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4623): VFY: unable to resolve instance field 36
,D/dalvikvm( 4623): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4623): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4623): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4623): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4623): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4623): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f54c90
,D/dalvikvm( 4623): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f54c90
,D/dalvikvm( 4623): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f54c90, skipping init
D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f54c90
,D/dalvikvm( 4623): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f54c90
,V/JNIHelp ( 4623): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4641): VFY: unable to resolve instance field 68
D/dalvikvm( 4641): VFY: replacing opcode 0x54 at 0x000c
,D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4641): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4641): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1608): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager( 1021): Killing 4295:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4641): VFY: unable to resolve instance field 68
,D/dalvikvm( 4641): VFY: replacing opcode 0x54 at 0x0011
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1608): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1608): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1608): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1608): onServiceConnected()
D/GetNotificationsWS( 1608): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1608): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1608): ServiceHandler.handleMessage: mWaitCount=0
I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4410): 
D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4641): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4641): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4641): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4641): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/GetNotificationsWS( 1608): unbindWebServices(): un-registering our AIDL callback...
D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f54c90
D/dalvikvm( 4623): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f54c90
D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f54c90
,D/dalvikvm( 4623): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f54c90
I/openssl ( 4496): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4496): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4542): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4542): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ProviderInstaller( 4623): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1243): callingUid 10022, callindPid: 1243
,E/MDM     ( 1243): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1371): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1371): Proximity feature is not enabled.
,D/LocationInitializer( 1725): Restart initialization of location
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1243): No location to return for getLastLocation()
,W/FusedLocationProvider( 1243): location=null
,I/dalvikvm( 4623): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4623): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4623): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4623): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4623): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4623): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4623): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4623): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4623): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4623): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4623): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4623): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4623): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4623): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51e8000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51e8000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=2812554981
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4623): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4623): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421a45f0
D/dalvikvm( 4623): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421a45f0
,D/dalvikvm( 4623): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421a45f0, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4623): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4609
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4612
,I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4410): 
,I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4410): 
,D/dalvikvm( 4674): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4623): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4623): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 92ms
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4410): 
,I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4410): 
,I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4410): 
,I/jxcore-log( 4410): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4410): 
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiStateMachine( 1021): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/ConnectivityService( 1021): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1021):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4623): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4623): Local Patches: NONE
I/Adreno-EGL( 4623): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=532016318
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/jxcore-log( 4410): Test app app.js loaded
I/jxcore-log( 4410): 
,I/Choreographer( 4410): Skipped 358 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4410): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4410): --= Surplus to requirements =--
I/jxcore-log( 4410): 
,I/jxcore-log( 4410): ****TEST TOOK:  ms ****
I/jxcore-log( 4410): 
,I/jxcore-log( 4410): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4410): 
,W/Settings( 4623): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1725): Classify the device as Phone.
,V/NativeCrypto( 1725): SSL shutdown failed: ssl=0x6bfcf3d0: I/O error during system call, Connection timed out
,D/AndroidRuntime( 4692): 
D/AndroidRuntime( 4692): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4692): CheckJNI is OFF
,D/dalvikvm( 4692): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4692): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4692): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4692): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4692): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4692): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,I/CheckinTask( 1725): Sending checkin request (11760 bytes)
,E/memtrack( 4692): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4692): failed to load memtrack module: -2
,D/AndroidRuntime( 4692): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10115 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 4410:com.test.thalitest/u0a115 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{449fbe00 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1021): WIN DEATH: Window{44ad03a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1021): Client connection lost with reason: 4
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10115 user=0: pkg removed
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/dalvikvm( 2344): GC_EXPLICIT freed 5186K, 44% free 9646K/17224K, paused 2ms+6ms, total 38ms
,D/dalvikvm( 1725): GC_EXPLICIT freed 1361K, 31% free 12028K/17224K, paused 3ms+6ms, total 60ms
,W/SQLiteConnectionPool( 1725): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/GeofencerStateMachine( 1243): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1209): resetDictionaries() : en_GB
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1209): run()
I/Decoder ( 1209): createOrResetDecoder
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
D/dalvikvm( 2377): GC_EXPLICIT freed 4705K, 42% free 10146K/17224K, paused 3ms+9ms, total 102ms
,D/OtaApp  ( 1608): [debug] > DownloadActivity, FormattedText
,D/VoicemailCleanupService( 1192): Cleaning up data for package: com.test.thalitest
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,D/dalvikvm( 1315): GC_EXPLICIT freed 3252K, 33% free 11596K/17224K, paused 2ms+20ms, total 94ms
,I/OtaApp  ( 1608): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,I/CheckinRequestBuilder( 1725): Checkin reason type: 8 attempt count: 1
,I/Launcher( 1315): Deferring update until onResume
,D/Checkin ( 1608): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1021):   Scheme: "sms"
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10115 #1
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4725 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
D/OtaApp  ( 1608): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 1608): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1608): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
E/ActivityThread( 1725): Failed to find provider info for com.google.android.wearable.settings
D/Tethering( 1021): MasterInitialState.processMessage what=3
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
W/XTWiFiOS( 1289): No entry in secure settings for enhanced location services: false
D/Tethering( 1021): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1289): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/ConfigService( 1243): onCreate
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
D/OtaApp  ( 1608): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/OtaApp  ( 1608): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/PollingManager( 1608): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1608): now: 355717 ,futureTime: 72506060
,D/PollingManager( 1608): Polling alarm set to expire at: 72506060 Current Time: 355719
,E/ActivityThread( 1608): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1608): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1608): now: 355723 ,futureTime: 72506060
D/PollingManager( 1608): Polling alarm set to expire at: 72506060 Current Time: 355723
,E/ActivityThread( 1608): Failed to find provider info for com.motorola.blur.setupprovider
,W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 4410 uid 10115
,I/Launcher( 1315): Deferring update until onResume
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
D/OtaApp  ( 1608): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/Keyboard.Facilitator( 1209): onFinishInput()
,D/OtaApp  ( 1608): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1608): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1608): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): run()
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1608): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1608): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 1608): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1608): [debug] > CusSM.onRadioUp
,I/InternalIcingCorporaPro( 2377): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/OtaApp  ( 1608): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/dalvikvm( 1021): GC_EXPLICIT freed 1868K, 65% free 18826K/53684K, paused 6ms+16ms, total 299ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1209): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1209): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1209): run()
,I/StatsUtilsManager( 1209): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1209): shouldRecordStats() = Too Soon
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4750 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1608): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 1608): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1608): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/ActivityManager( 1021): Killing 4329:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 4692): Shutting down VM
D/OtaApp  ( 1608): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/dalvikvm( 4692): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,W/ContextImpl( 4750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1725): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1725): Clearing selected account for com.test.thalitest
I/dalvikvm( 3863): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3863): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3863): VFY: replacing opcode 0x6e at 0x0013
,I/LocationSettingsChecker( 1725): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1725): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1725): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1725): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1725): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1371): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1371): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1725): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Icing   ( 1725): doRemovePackageData com.test.thalitest
,D/dalvikvm( 1371): GC_EXPLICIT freed 1863K, 40% free 10392K/17224K, paused 2ms+13ms, total 86ms
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,D/gH_CompatibleDatabase( 1725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4778 uid=10059 gids={50059, 1028, 3003, 1015}
D/gH_CompatibleDatabase( 1725): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1725): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1725): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/TelephonyProvider( 1275): Column apn id key is 'apn_id'
,I/ActivityManager( 1021): Killing 4496:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2377): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
,I/CheckinRequestBuilder( 1725): Classify the device as Phone.
,I/CheckinTask( 1725): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1725): Checking schedule, now: 1453024212694 next: 1453573866689
,I/CheckinService( 1725): active receiver: disabled
,D/CheckinService( 1725): Recording last checkin time for package unspecified as 1453024212717
,I/dalvikvm( 4778): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 4778): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4778): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4778): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4778):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4778):   adb logcat -s GAv4
,W/GAv4    ( 4778): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4778): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4778): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4778): VFY: replacing opcode 0x6e at 0x001b
,E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4778): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4778): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4778): 	at avm.getWritableDatabase(PG:244)
E/SQLiteDatabase( 4778): 	at avc.a(PG:1573)
E/SQLiteDatabase( 4778): 	at jep$b.a(PG:131)
E/SQLiteDatabase( 4778): 	at ave.run(PG:588)
,W/dalvikvm( 4778): threadid=11: thread exiting with uncaught exception (group=0x4167fd40)
W/GAv4    ( 4778): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/dalvikvm( 4778): Could not find method android.app.Activity.finishAfterTransition, referenced from method ce.onBackPressed
W/dalvikvm( 4778): VFY: unable to resolve virtual method 1245: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4778): VFY: replacing opcode 0x6e at 0x0012
E/SQLiteDatabase( 4778): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4778): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4778): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4778): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4778): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/CAKEMIX_CRASHED( 4778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/CAKEMIX_CRASHED( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/CAKEMIX_CRASHED( 4778): 	at avm.getWritableDatabase(PG:244)
E/CAKEMIX_CRASHED( 4778): 	at avc.a(PG:1573)
E/CAKEMIX_CRASHED( 4778): 	at jep$b.a(PG:131)
E/CAKEMIX_CRASHED( 4778): 	at ave.run(PG:588)
W/AnalyticsTrackerProxyImpl( 4778): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
E/SQLiteDatabase( 4778): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4778): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4778): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4778): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4778): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4778): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4778): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4    ( 4778): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4778): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/dalvikvm( 4778): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4778): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 4778): VFY: replacing opcode 0x71 at 0x0075
I/ActivityManager( 1021): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from pid 4778

```
