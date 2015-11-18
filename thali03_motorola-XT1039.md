#### Test 5107482134e3b48_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{43d60240 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3521): 
D/AndroidRuntime( 3521): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3521): CheckJNI is OFF
D/dalvikvm( 3521): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3521): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3521): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3521): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3521): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3521): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3521): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3521): failed to load memtrack module: -2
D/AndroidRuntime( 3521): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3521
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3537 uid=10382 gids={50382, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3521): Shutting down VM
D/dalvikvm( 3521): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 3ms
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3537): Binding Chromium to main looper Looper (main, tid 1) {41fcf688}
I/LibraryLoader( 3537): Expected native library version number "",actual native library version number ""
I/chromium( 3537): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3537): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43aae2d0:true
D/BluetoothAdapter( 3537): 1107183064: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3537): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3537): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3537): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3537): Local Branch: 
I/Adreno-EGL( 3537): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3537): Local Patches: NONE
I/Adreno-EGL( 3537): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3537): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3537): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3537): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3537): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3537): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3537): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3537): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3537): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3537): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3537): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3537): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3537): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3537): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3537): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3537): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3537): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3537): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3537): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3537): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3537): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3537): Enabling debug mode 0
,W/AwContents( 3537): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3537): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,394
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +369ms (total +394ms)
,D/JsMessageQueue( 3537): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3537): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fd3958
,D/dalvikvm( 3537): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fd3958
,D/jxcore_app_log( 3537): JniHelper::setJavaVM(0x41625fa8), pthread_self() = 1615324192
,D/JX-Cordova( 3537): jxcore cordova android initializing
,I/dalvikvm( 3537): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
,W/dalvikvm( 3537): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3537): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3537): GC_CONCURRENT freed 2810K, 17% free 14379K/17224K, paused 2ms+3ms, total 59ms
,D/dalvikvm( 3537): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 3537): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 221K, 17% free 14358K/17224K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 16.148MB for 98002-byte allocation
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 189K, 17% free 14386K/17320K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 16.222MB for 146998-byte allocation
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 258K, 18% free 14435K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 16.339MB for 220492-byte allocation
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 376K, 18% free 14511K/17680K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 16.519MB for 330734-byte allocation
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 584K, 19% free 14635K/18004K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 16.798MB for 496096-byte allocation
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 885K, 20% free 14813K/18492K, paused 27ms, total 27ms
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 1310K, 19% free 15075K/18492K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 17.819MB for 1116206-byte allocation
,D/dalvikvm( 3537): GC_CONCURRENT freed 1809K, 21% free 15513K/19584K, paused 2ms+10ms, total 66ms
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 272K, 22% free 15427K/19584K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 18.695MB for 1674304-byte allocation
,D/dalvikvm( 3537): GC_CONCURRENT freed 1649K, 25% free 15978K/21220K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 3537): GC_FOR_ALLOC freed 1485K, 25% free 16084K/21220K, paused 31ms, total 32ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 20.135MB for 2511452-byte allocation
,D/dalvikvm( 3537): GC_CONCURRENT freed 226K, 23% free 18424K/23676K, paused 4ms+6ms, total 40ms
,D/dalvikvm( 3537): GC_CONCURRENT freed 4480K, 28% free 17062K/23676K, paused 2ms+7ms, total 46ms
,D/dalvikvm( 3537): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm-heap( 3537): Grow heap (frag case) to 22.288MB for 3767174-byte allocation
,D/dalvikvm( 3537): GC_CONCURRENT freed 2860K, 34% free 18168K/27356K, paused 4ms+6ms, total 69ms
,W/jxcore-log( 3537): Initializing JXcore engine
,W/jxcore-log( 3537): JXcore engine is ready
,D/dalvikvm( 3537): GC_CONCURRENT freed 503K, 25% free 20616K/27356K, paused 5ms+7ms, total 41ms
,W/jxcore-log( 3537): Starting JXcore engine
,W/jxcore-log( 3537): Platform android
W/jxcore-log( 3537): 
,W/jxcore-log( 3537): Process ARCH arm
W/jxcore-log( 3537): 
,I/jxcore-log( 3537): JXcore Cordova bridge is ready!
I/jxcore-log( 3537): 
,W/jxcore-log( 3537): JXcore engine is started
,I/chromium( 3537): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3537): Turning radios to true
I/jxcore-log( 3537): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,W/Settings( 1251): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService( 1019): Message: 1
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1268): Active network info is not available
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,D/WifiService( 1019): New client listening to asynchronous messages
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3583 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
D/WifiService( 1019): setWifiEnabled: true pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1251): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1251): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1268): Active network info is not available
,W/Settings( 1251): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): setting operational mode to 1
,D/AdapterServiceConfig( 3583): Adding HeadsetService
D/AdapterServiceConfig( 3583): Adding A2dpService
D/AdapterServiceConfig( 3583): Adding HidService
D/AdapterServiceConfig( 3583): Adding HealthService
D/AdapterServiceConfig( 3583): Adding PanService
D/AdapterServiceConfig( 3583): Adding GattService
,D/AdapterServiceConfig( 3583): Adding BluetoothMapService
,D/BluetoothAdapterService( 3583): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43118f70:true
,D/BluetoothAdapterState( 3583): make
,I/BluetoothAdapterState( 3583): Entering OffState
,I/bluedroid( 3583): init
,I/bte_conf( 3583): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3583): get_profile_interface socket
,I/GKI_LINUX( 3583): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3583): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,I/bluedroid( 3583): config_hci_snoop_log
D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterProperties( 3583): Name is: XT1039
,D/BluetoothAdapterState( 3583): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3583): Setting state to 11
I/BluetoothAdapterState( 3583): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3583): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothBondStateMachine( 3583): make
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3583): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3622 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1019): Proxy object connected
D/BluetoothHeadset( 1238): Proxy object connected
,D/BluetoothHeadset( 1238): Proxy object connected
,D/BluetoothHeadset( 1238): Proxy object connected
D/HeadsetService( 3583): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3583): classInitNative: succeeds
D/HeadsetStateMachine( 3583): Version 1.6
,D/HeadsetStateMachine( 3583): make
,I/bluedroid( 3583): get_profile_interface handsfree
,I/BluetoothAdapterState( 3583): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothA2dp( 1019): Proxy object connected
,D/A2dpService( 3583): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3583): classInitNative: succeeds
V/Avrcp   ( 3583): make
,I/bluedroid( 3583): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3583): classInitNative: succeeds
D/A2dpStateMachine( 3583): make
,I/bluedroid( 3583): get_profile_interface a2dp
I/GKI_LINUX( 3583): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3583): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3583): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3583): classInitNative: succeeds
,D/HidService( 3583): Received start request. Starting profile...
I/bluedroid( 3583): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3583): classInitNative: succeeds
,D/HealthService( 3583): Received start request. Starting profile...
I/bluedroid( 3583): get_profile_interface health
,I/BluetoothPanServiceJni( 3583): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
D/PanService( 3583): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3583): initializeNative(L110): pan
,I/bluedroid( 3583): get_profile_interface pan
,D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43a2fd80
,I/BtGatt.JNI( 3583): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3583): handleDebugAction() action=null
,D/BtGatt.GattService( 3583): Received start request. Starting profile...
D/BtGatt.GattService( 3583): start()
,I/bluedroid( 3583): get_profile_interface gatt
,I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  274): NetlinkHandler, interfaceAdded
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
E/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  274): , Wifi = 0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  594): NL - Read 1004 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/Tethering( 1019): InitialState.processMessage what=4
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  274): NetlinkHandler, interfaceAdded
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
E/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  274): , Wifi = 0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  594): NL - Read 1004 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
D/BluetoothMapService( 3583): Received start request. Starting profile...
,D/BluetoothMapService( 3583): start()
,D/HeadsetPhoneState( 3583): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3583): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3583): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3583): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3583): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3583): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3583): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/QsoftapCmd(  272): Got softap fwreload command we are passing on
,D/SoftapController(  272): Softap fwReload - Ok
,D/HeadsetPhoneState( 3583): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3583): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3583): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3583): enable
,I/bt_hci_bdroid( 3583): init
,I/bt_vendor( 3583): bt-vendor : init
I/bt_hci_bdroid( 3583): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3583): userial_init
I/bt_hwcfg( 3583): Starting hciattach daemon
I/bt_hwcfg( 3583): try to set false
,I/bt_hwcfg( 3583): Starting hciattach daemon
I/bt_hwcfg( 3583): try to set true
,I/bt_hci_bdroid( 3583): bt_hc_worker_thread started
D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring down wlan0
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/qcom-bluetooth( 3648): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/WifiStateMachine( 1019): setWifiState: enabling
,D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
I/SBar.NetworkController( 1083): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): Active network info is not available
,I/qcom-bluetooth( 3656): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3657): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/ActivityManager( 1019): Killing 3359:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/wpa_supplicant( 3653): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3653): rfkill: Cannot open RFKILL control device
I/qcom-bluetooth( 3659): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
I/qcom-bluetooth( 3660): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3661): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
D/WifiService( 1019): New client listening to asynchronous messages
,E/Diag_Lib( 3664): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3664): Setting internal use port to rmnet0
E/Diag_Lib( 3664):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3664): Failed on DIAG init
E/Diag_Lib( 3664): linux_qmi_qmux_if_client_get_proc_name: pid=3664, proc_name=hci_qcomm_init
E/Diag_Lib( 3664): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3664): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3664): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3664): qmi_client [3664]: successfully connected to server, attempt=1
E/Diag_Lib( 3664): linux_qmi_qmux_if_client_get_client_id [3664]: qmux_client_id=13
E/Diag_Lib( 3664): qmi_client [3664] 13: qmux_client ID is initialized
E/Diag_Lib( 3664): qmi_client [3664] 13: pipe() system call, fd[0]=10, fd[1]=11
E/Diag_Lib( 3664): qmi_client [3664] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3664): qmi_client [3664] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3664): Sending signal ...... to read cmd data 
E/Diag_Lib( 3664): qmi error code.........:0
E/Diag_Lib( 3664): qmi sys error code.........:0
E/Diag_Lib( 3664): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3664): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3664): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3664): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3664): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3664): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3664): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3664): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3664): qmi_init:  Created client handle b761e788
,E/Diag_Lib( 3664): qmi_client [3664] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3664): qmi_client [3664] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3664): Sending signal ...... to read cmd data 
E/Diag_Lib( 3664): qmi error code.........:0
,E/Diag_Lib( 3664): qmi sys error code.........:0
E/Diag_Lib( 3664): Setting the api flag to : 1
,E/Diag_Lib( 3664): qmi_client [3664] 13: sending 54 bytes on fd = 8
,E/Diag_Lib( 3653): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3653): Setting internal use port to rmnet0
,E/wpa_supplicant( 3653): baseband property is set to [msm]
,I/rmt_storage(  408): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73e11d0
I/rmt_storage(  408): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  408): wakelock acquired: 1, error no: 42
,I/rmt_storage(  408): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1220669720)
E/Diag_Lib( 3664): qmi_client [3664] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3664):  API Flag .............. 1 
,E/Diag_Lib( 3664):  Message ID ............... 92 
,E/wpa_supplicant( 3653):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3653): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3653): card_info[i].card_state: 0x2
E/wpa_supplicant( 3653): card_info[i].error_code: 0x3
E/wpa_supplicant( 3653): SIM/USIM not ready
,E/wpa_supplicant( 3653): Error while reading SIM card status
,E/wpa_supplicant( 3653): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3653): card_info[i].card_state: 0x2
E/wpa_supplicant( 3653): card_info[i].error_code: 0x3
E/wpa_supplicant( 3653): SIM/USIM not ready
,I/wpa_supplicant( 3653): eap_proxy: Card not ready
,E/Diag_Lib( 3664): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3664): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3664): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3664): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3664): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3664): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3664): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3664): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3664): qmi_client [3664] 13: sending 880 bytes on fd = 8
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
E/Diag_Lib( 3664): qmi_client [3664] 13: Received 880 bytes on fd = 8
,E/Diag_Lib( 3664): Sending signal ...... to read cmd data 
E/Diag_Lib( 3664): qmi error code.........:0
E/Diag_Lib( 3664): qmi sys error code.........:0
E/Diag_Lib( 3664): qmi_release: Released client handle ff
E/Diag_Lib( 3664): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/,Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3664): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3664): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3664): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3664): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3664): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3664): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3664): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3664): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3664): qmi_client [3664] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3664): qmi_client [3664] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3664): Sending signal ...... to read cmd data 
E/Diag_Lib( 3664): qmi error code.........:0
E/Diag_Lib( 3664): qmi sys error code.........:0
E/Diag_Lib( 3664): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3664] 13
E/Diag_Lib( 3664): qmi_client [3664] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3664): qmi_client [3664] 13: failed to locate client data
E/Diag_Lib( 3664): qmi_client [3664] 13: calling release of fd=8
E/Diag_Lib( 3664): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/dalvikvm( 1019): GC_EXPLICIT freed 22338K, 65% free 17912K/50324K, paused 5ms+11ms, total 192ms
,I/rmt_storage(  408): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  408): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  408): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1220669720) wakelock released: 1, error no: 0
I/rmt_storage(  408): 
,I/rmt_storage(  408): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb73e11d0
,V/BluetoothFtpReceiver( 3583): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3653): Long line in configuration file truncated
,I/wpa_supplicant( 3653): rfkill: Cannot open RFKILL control device
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,I/qcom-bluetooth( 3668): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3669): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 3653): COUNTRY Code Recived
,E/wpa_supplicant( 3653): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3653): baseband property is set to [msm]
,E/wpa_supplicant( 3653):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3653): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3653): card_info[i].card_state: 0x2
E/wpa_supplicant( 3653): card_info[i].error_code: 0x3
E/wpa_supplicant( 3653): SIM/USIM not ready
,E/wpa_supplicant( 3653): Error while reading SIM card status
E/wpa_supplicant( 3653): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3653): card_info[i].card_state: 0x2
E/wpa_supplicant( 3653): card_info[i].error_code: 0x3
E/wpa_supplicant( 3653): SIM/USIM not ready
,I/wpa_supplicant( 3653): eap_proxy: Card not ready
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/SBar.NetworkController( 1083): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): Active network info is not available
I/bt_hwcfg( 3583): bluetooth satus is on
,D/bt_userial_mct( 3583): userial_open(port:0)
,I/bt_userial_vendor( 3583): Done intiailizing UART
I/bt_userial_vendor( 3583): Done intiailizing UART
I/bt_userial_mct( 3583): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3583): Bluetooth Firmware and smd is initialized
,D/WifiConfigStore( 1019): Loading config and enabling all networks
D/bt_userial_mct( 3583): Entering userial_read_thread()
I/GKI_LINUX( 3583): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3583): btu_task pending for preload complete event
,I/bt-btu  ( 3583): btu_task received preload complete event
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/        ( 3583): BTE_InitTraceLevels -- TRC_HCI
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
I/        ( 3583): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3583): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3583): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3583): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3583): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3583): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3583): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 3583): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3583): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3583): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3583): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3583): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3583): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3583): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3653): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3653): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3653): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/CommandListener(  272): Setting iface cfg
D/CommandListener(  272): Trying to bring up p2p0
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
E/bt-btm  ( 3583): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f167049 
E/bt-btm  ( 3583): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f167049 
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set country code PL
E/bt-btif ( 3583): Calling BTA_HhEnable
E/bt-btif ( 3583): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3583): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:1 len:6
,D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
E/wpa_supplicant( 3653): COUNTRY Code Recived
E/wpa_supplicant( 3653): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
D/BluetoothAdapterProperties( 3583): Name is: XT1039
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3583): Scan Mode:21
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3583): Discoverable Timeout:120
,D/WifiP2pService( 1019): MCC mode enabled 0
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:8 len:6
,D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/BluetoothAdapterProperties( 3583): Adding bonded device:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:3 len:48
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
E/BluetoothRemoteDevices( 3583): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1019): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
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
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1019): InactiveState
I/bte_conf( 3583): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/WifiP2pService( 1019): InactiveState{ when=-15ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-15ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
E/bt_mct  ( 3583): hci lib postload completed
D/WifiP2pService( 1019): InactiveState{ when=-16ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
I/bte_conf( 3583): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
,D/WifiP2pService( 1019): P2pEnabledState{ when=-16ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
I/bte_conf( 3583): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/wpa_supplicant( 3653): COUNTRY Code Recived
E/wpa_supplicant( 3653): COUNTRY Code Recived
,I/bte_conf( 3583): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/WifiP2pService( 1019): InactiveState{ when=-16ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-16ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterState( 3583): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 3583): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 3583): ScanMode =  21
D/BluetoothAdapterProperties( 3583): State =  11
D/BluetoothAdapterProperties( 3583): Setting state to 12
I/BluetoothAdapterState( 3583): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3583): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
D/BluetoothPan( 1019): onBluetoothStateChange on: true
I/BluetoothAdapterState( 3583): Entering On State
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3583): Discoverable Timeout:120
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(1107170760)( 3583): Get Bonded Devices being called
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterProperties( 3583): getBondedDevices: length=1
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3583): onReceive
D/BluetoothMapService( 3583): STATE_ON
D/BluetoothMapService( 3583): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1107170760)( 3583): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3583): getBondedDevices: length=1
D/BluetoothMapService( 3583): Map Service initSocket
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(1107170760)( 3583): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3583): getBondedDevices: length=1
W/BluetoothAdapter( 3583): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3583): SOCK FLAG = 1 ***********************
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3583): Scan Mode:21
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothMapService( 3583): Accepting socket connection...
,I/qcom-bt-wlan-coex( 3685): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothAdapterService(1107170760)( 3583): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3583): getBondedDevices: length=1
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424dd468:true
,D/LocalBluetoothProfileManager( 3622): Adding local A2DP profile
,D/BluetoothPbapService( 3583): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3583): Handler(): got msg=1
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3583): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 3622): Adding local HEADSET profile
E/BluetoothServiceJni( 3583): SOCK FLAG = 1 ***********************
D/BluetoothAdapterService(1107170760)( 3583): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3583): getBondedDevices: length=1
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3622): Adding local MAP profile
D/BluetoothMap( 3622): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3622): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3622): finishStartingService: stopping service
,D/BluetoothAdapterService(1107170760)( 3583): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3583): getBondedDevices: length=1
,D/BluetoothA2dp( 3622): Proxy object connected
,D/A2dpProfile( 3622): Bluetooth service connected
,D/BluetoothHeadset( 3622): Proxy object connected
,D/HeadsetProfile( 3622): Bluetooth service connected
,D/BluetoothInputDevice( 3622): Proxy object connected
,D/HidProfile( 3622): Bluetooth service connected
,D/BluetoothPan( 3622): BluetoothPAN Proxy object connected
D/PanProfile( 3622): Bluetooth service connected
,D/BluetoothMap( 3622): Proxy object connected
D/MapProfile( 3622): Bluetooth service connected
,D/BluetoothMap( 3622): getConnectedDevices()
,D/BluetoothPbap( 3622): Proxy object connected
,D/PbapServerProfile( 3622): Bluetooth service connected
,V/BluetoothFtpReceiver( 3583): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3583): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3583): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3583): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3583): Accept thread started.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
V/BluetoothFtpService( 3583): Ftp Service onCreate
I/BluetoothFtpService( 3583): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3583): Starting FTP service
,V/BluetoothFtpService( 3583): Ftp Service onStartCommand
,V/BluetoothFtpService( 3583): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3583): Handler(): got msg=1
,V/BluetoothFtpService( 3583): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3583): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3583): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3583): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3583): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3583): Run Accept thread
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): wifi_connect_to_supplicant, current pid is = 274
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  274): wifi_close_sockets: Exit
,E/MDMCTBK (  274): Attach monitor thread
,I/MDMCTBK (  274): createWifiMonitorThread: Started the wifi monitor thread -1216166952
,D/MDMCTBK (  274): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3653): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3651): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3651): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/TCMD    (  594): NL - Read 56 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,E/wpa_supplicant( 3653): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 3653): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 3653): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  594): NL - Read 312 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 88 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 68 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,I/wpa_supplicant( 3653): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  594): NL - Read 80 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 80 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 68 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3653): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3653): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1216171288
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-53ms what=147462 obj=android.net.wifi.StateChangeResult@420698c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-30ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@423c0610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42124560 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42124560 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 8e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 8e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  594): NL - Read 56 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42052e90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42052e90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42052e90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,D/TCMD    (  594): NL - Read 60 bytes from update socket.
D/TCMD    (  594): NL - ignore NL message, type = 20
,D/TCMD    (  594): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4214c6e8
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4214c6e8
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
,D/        ( 1019): Setting time of day to sec=1447848614
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
W/        ( 1019): Unable to set rtc to 1447848614: Invalid argument
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1537): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/PollingManager( 1537): now: 302495 ,futureTime: 76263123
,D/PollingManager( 1537): Polling alarm set to expire at: 76263123 Current Time: 302502
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1537): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
D/PollingManager( 1537): registerApp(): CCE
I/CCE     ( 1537): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1537): Registering with Alarm Manager to restart CCE
I/openssl ( 3036): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3036): Crypto mode 0 already enabled
D/MMApiWebService( 1537): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1537): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1537): isRequestAllowed(): already have outstanding request ... ignoring request
D/PollingManager( 1537): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1537): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1537): [debug] > CusSM.onRadioUp
D/PollingManager( 1537): now: 302556 ,futureTime: 76263123
D/PollingManager( 1537): Polling alarm set to expire at: 76263123 Current Time: 302556
D/OtaApp  ( 1537): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,E/ActivityThread( 1537): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1537): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1537): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1537): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MMApiWebService( 1537): generating token using payload instead of using session token
,D/OtaApp  ( 1537): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1537): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1537): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/OtaApp  ( 1537): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1537): [debug] > CusSM.onRadioUp
I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3786 uid=10056 gids={50056, 3003, 1028, 1015}
,D/OtaApp  ( 1537): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1537): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1537): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1537): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1537): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1537): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1537): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3803 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/dalvikvm( 1537): GC_CONCURRENT freed 3025K, 38% free 10704K/17224K, paused 3ms+3ms, total 31ms
,V/MmsConfig( 3803): mnc/mcc: 
V/MmsConfig( 3803): tag: bool value: enabledMMS - true
,V/MmsConfig( 3803): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3803): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 3803): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3803): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3803): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3803): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3803): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3803): tag: int value: recipientLimit - 20
V/MmsConfig( 3803): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3803): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3803): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3803): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3803): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3803): tag: bool value: smsForceShowEncodingMenu - true
I/VacuumService( 1355): Vacuum at: now=1447848615072 tag=VacuumService
V/MmsConfig( 3803): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3803): tag: bool value: enableGroupMms - false
E/MmsConfig( 3803): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/dalvikvm( 1341): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1341): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1341): VFY: replacing opcode 0x6e at 0x0033
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3829 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3389:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DelayedSyncController( 3786): Delaying sync.
,D/GpsLocationProvider( 1019): NTP server returned: 1447848611782 (Wed Nov 18 13:10:11 CET 2015) reference: 299524 certainty: 17 system time offset: -3340
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/dalvikvm( 1203): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1203): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1203): VFY: replacing opcode 0x6e at 0x0033
,I/ActivityManager( 1019): Killing 3104:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1238): GC_EXPLICIT freed 1388K, 45% free 9516K/17224K, paused 6ms+4ms, total 74ms
,E/Auth.Api.Credentials( 1341): [CredentialSyncAdapter] Unknown sync event.
,D/MobileConnectivityChangeReceiver( 3829): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3829): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3829): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3829): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3848 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3415:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1341): Checkin interval check for package: unspecified last checkin: 1447844538720 min interval config: 0 actual interval: 4076519
,I/CheckinService( 1341): Checking schedule, now: 1447848615263 next: 1447844568700
,I/CheckinService( 1341): active receiver: enabled
,I/CheckinService( 1341): Preparing to send checkin request
,I/EventLogService( 1341): Accumulating logs since 1447848346330
,D/dalvikvm( 1203): GC_EXPLICIT freed 1496K, 40% free 10336K/17224K, paused 2ms+20ms, total 55ms
,E/DataBuffer( 1203): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41fdff48)
,I/CheckinRequestBuilder( 1341): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1019): New client listening to asynchronous messages
V/WebViewChromiumFactoryProvider( 3848): Binding Chromium to main looper Looper (main, tid 1) {41fd6060}
I/LibraryLoader( 3848): Expected native library version number "",actual native library version number ""
I/chromium( 3848): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3848): Initializing chromium process, renderers=0
E/ActivityThread( 1341): Failed to find provider info for com.google.android.wearable.settings
,E/AudioManagerAndroid( 3848): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3848): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3848): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3848): Local Branch: 
I/Adreno-EGL( 3848): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3848): Local Patches: NONE
I/Adreno-EGL( 3848): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1019): GC_EXPLICIT freed 1773K, 65% free 17907K/50324K, paused 4ms+10ms, total 109ms
,W/chromium( 3848): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/DelayedSyncController( 3786): Delaying sync.
,W/GAV2    ( 3848): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3848): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3889 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 3889): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3889): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3889): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3889): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 3889): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3889): install
,I/MultiDex( 3889): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/NSApplication( 3848): Starting up...
,I/MultiDex( 3889): loading existing secondary dex files
,I/MultiDex( 3889): load found 3 secondary dex files
,I/MultiDex( 3889): install done
,I/ImageResourceManager( 3439): ImageResourceManager: uninitalized
,I/iu.Environment( 3439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3439): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3083:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3889): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3889): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3889): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3889): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3889): VFY: unable to resolve instance field 46
,D/dalvikvm( 3889): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3889): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3889): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3889): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3889): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3889): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fdbe10
D/dalvikvm( 3889): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fdbe10
,D/dalvikvm( 3889): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fdbe10, skipping init
,D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fdbe10
D/dalvikvm( 3889): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fdbe10
,V/JNIHelp ( 3889): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/iu.UploadsManager( 3439): num queued entries: 0
,I/iu.UploadsManager( 3439): num updated entries: 0
,I/iu.SyncManager( 3439): NEXT; no task
,I/iu.SyncManager( 1341): SYNC; picasa accounts
,D/NetworkLogImpl( 1341): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1341): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1341): num queued entries: 0
,I/iu.UploadsManager( 1341): num updated entries: 0
,I/iu.SyncManager( 1341): NEXT; no task
,D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fdbe10
,D/dalvikvm( 3889): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41fdbe10
D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fdbe10
,D/dalvikvm( 3889): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fdbe10
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3914 uid=10007 gids={50007, 3003}
,D/ExtensionsFactory( 3914): No custom extensions.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3933 uid=10015 gids={50015, 1028}
I/ActivityManager( 1019): Killing 3142:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3938 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3622:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/WifiService( 1019): Client connection lost with reason: 4
I/ProviderInstaller( 3889): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,V/AlarmClock( 3933): AlarmInitReceiver android.intent.action.TIME_SET
,I/dalvikvm( 3889): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 3889): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3889): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 3889): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x0220
,I/GCM     ( 1355): GCM config loaded
,I/CalendarProvider2( 3938): Created com.android.providers.calendar.CalendarAlarmManager@41ff2f68(com.android.providers.calendar.CalendarProvider2@41feab20)
I/dalvikvm( 3889): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3889): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,E/dalvikvm( 3889): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 3889): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 3889): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 3889): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
,W/dalvikvm( 3889): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 3889): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3889): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 3889): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,I/AlarmClock( 3933): Displaying next alarm time: ''
,V/AlarmClock( 3933): AlarmInitReceiver finished
,I/ActivityManager( 1019): Killing 3036:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3965 uid=10098 gids={50098}
,D/MMApiProvisionService( 1537): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"162302","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1537): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1537): doRequest(): /v1/dp/devices.json resp length: 138
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/dalvikvm( 3965): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41fd3348, skipping init
D/TimeService( 3965): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1447848616140
D/        ( 3965): TimeServiceNative: User Time to be set is 1447848616140
D/QC-time-services( 3965): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3965): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3965): Lib:time_genoff_operation: pargs->ts_val = 1447848616140
D/QC-time-services(  398): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3965): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  398): Daemon:Received base = 2, unit = 1, operation = 0,value = 1447848616140
D/QC-time-services(  398): Daemon:genoff_opr: Base = 2, val = 1447848616140, operation = 0
D/QC-time-services(  398): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/18/115 12:4:26
D/QC-time-services(  398): Daemon:Value read from RTC seconds = 1447848266000
D/QC-time-services(  398): Daemon:new time 1447848616140 
D/QC-time-services(  398): Daemon: delta 350140 genoff 350140 
D/QC-time-services(  398): Daemon:genoff_persistent_update: Writing genoff = 350140 to memory
D/QC-time-services(  398): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  398): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  398): Updating the TOD offset
D/QC-time-services(  398): Daemon:genoff_persistent_update: Writing genoff = 350140 to memory
D/QC-time-services(  398): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  398): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/MMApiProvisionService( 1537): MMApiProvisionService.handleResponse (update_device) : true (None)
E/QC-time-services(  398): Daemon:Update to modem bit set
D/QC-time-services(  398): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  398): Daemon: Base = 2, Value being sent to MODEM = 18446743757745101756
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
E/QC-time-services(  398): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  398): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  279): App is not loaded in QSEE
,E/QC-time-services( 3965): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/MMApiProvisionService( 1537): handleResponse(): Session Expiration alarm set to expire at: Fri Nov 20 10:15:18 CET 2015
,D/MMApiProvisionService( 1537): _setMMApiCredInfo: storing credential info 
,D/MMApiWSBase( 1537): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1537): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1537): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/QSEECOMAPI: (  279): Loaded image: APP id = 3
,D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5344000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5344000
,D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,I/CheckinService( 1341): Checkin interval check for package: unspecified last checkin: 1447844538720 min interval config: 0 actual interval: 4077507
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,E/MMApiProvisionService( 1537): handleResponse(): no settings sent by the server:
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1537): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=4203733327
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/Checkin ( 1537): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1537): handleGetNotificationsResponse(): got 0; more=false
,D/UdcCache:FPQuery( 1341): Bootstrapping UDC settings cache for all accounts
,D/DEBUG   ( 1537): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1537): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1537): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1537): ServiceHandler.handleMessage: mWaitCount=1
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3985 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm( 3889): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42189e90
,D/dalvikvm( 3889): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42189e90
,D/dalvikvm( 3889): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42189e90, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/NativeLibraryUtils( 3889): Install completed successfully. count=13 extracted=0
,D/MobileConnectivityChangeReceiver( 3829): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3829): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/dalvikvm( 3985): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fd7e20, skipping init
I/openssl ( 3985): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3985): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Killing 3914:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3889): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
,D/DEBUG   ( 1537): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SundryService( 1537): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/EmailService.MarketingOptInSetter( 1537): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1537): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1537): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1537): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1537
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1537): [info] > Updatetime from metadata: 10
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1537): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1537): [info] > Updatetime from metadata: 10
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1537): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1537): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1537
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/dalvikvm( 4004): DexOpt: load 5ms, verify+opt 9ms, 128132 bytes
,D/dalvikvm( 3889): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3889): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 136ms
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/OtaApp  ( 1537): [info] > Updatetime from metadata: 10
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1537): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,139
I/OtaApp  ( 1537): [info] > Updatetime from metadata: 10
D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > cancelling the previous pending intent set for install later
,D/WearableService( 1203): callingUid 10022, callindPid: 1203
I/OtaApp  ( 1537): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{420ca1f0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/LocationInitializer( 1341): Restart initialization of location
D/AuthorizationBluetoothService( 1355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
,E/MDM     ( 1203): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1341): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=4014 uid=10007 gids={50007, 3003}
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1355): location=null
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/ExtensionsFactory( 4014): No custom extensions.
,D/GetConfigurationSnapshotOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/ActivityManager( 1019): Killing 3965:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/DEBUG   ( 1537): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1537): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1537): Received shoulder tap
D/DEBUG   ( 1537): Received intent : com.motorola.ccc.notification.action.NOTIFY
,D/WaitableIntentService( 1537): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,D/GetNotificationsWS( 1537): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1537): sendAidlRequest(): was sent by CCE successfully!
D/WaitableIntentService( 1537): ServiceHandler.handleMessage: mWaitCount=2
I/SundryService( 1537): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1537): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1537): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1537): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1537): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/CalendarProvider2( 3938): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3938): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4014): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/dalvikvm( 1355): GC_CONCURRENT freed 1833K, 39% free 10666K/17224K, paused 5ms+4ms, total 80ms
,I/PhenotypeFlagCommitter( 1355): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,I/GoogleURLConnFactory( 1355): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
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
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=4224469864
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
D/dalvikvm( 1019): GC_EXPLICIT freed 800K, 65% free 17924K/50324K, paused 4ms+11ms, total 102ms
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/AlertService( 4014): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/MMApiWSBase( 1537): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1537): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1537): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1537): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1537): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1537): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1537): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1537): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1537): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 1537): ServiceHandler.handleMessage: mWaitCount=0
,I/dalvikvm( 1537): Jit: resizing JitTable from 4096 to 8192
,D/GetNotificationsWS( 1537): unbindWebServices(): un-registering our AIDL callback...
,W/Uploader( 1355):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Settings( 3889): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1341): Classify the device as Phone.
,D/dalvikvm( 1341): GC_CONCURRENT freed 1780K, 33% free 11708K/17224K, paused 3ms+4ms, total 35ms
,I/CheckinTask( 1341): Sending checkin request (11771 bytes)
,I/CheckinRequestBuilder( 1341): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1341): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1341): Classify the device as Phone.
,I/CheckinTask( 1341): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1341): Checking schedule, now: 1447848618778 next: 1448441688770
,I/CheckinService( 1341): active receiver: disabled
,D/CheckinService( 1341): Recording last checkin time for package unspecified as 1447848618790
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3848): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 4014): no sender configured
,D/AlertService( 4014): Beginning updateAlertNotification
,D/AlertService( 4014): No fired or scheduled alerts
,D/AlertService( 4014): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4014): No events found starting within 1 week.
I/ActivityManager( 1019): Killing 3938:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 3985:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1298): Deferring update until onResume
I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4071 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
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
,I/Launcher( 1298): Deferring update until onResume
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
,I/Babel   ( 4071): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4071): MmsConfig.loadMmsSettings
I/Babel   ( 4071): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4071): MmsConfig.loadFromDatabase
,E/Babel   ( 4071): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4071): MmsConfig.loadFromResources
,E/Babel   ( 4071): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4071): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4071): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GmsNetworkLocationProvi( 1203): DISABLE
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4103 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Attempting to connect to the test coordinator server
I/jxcore-log( 3537): 
,I/ActivityManager( 1019): Killing 3803:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4123 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3829:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/jxcore  ( 3537): Error!: Cannot find module '../../lib/thali-tape'
E/jxcore  ( 3537): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1604","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1604:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"10","_columnNumber":"12","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js:10:12"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"9","_columnNumber":"9","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:9:9"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"6","_columnNumber":"1","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:6:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"63","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:63:3"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at, Module.pr
I/jxcore-log( 3537): {"type":"test","name":"setup","id":0}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
W/IInputConnectionWrapper( 3537): showStatusIcon on inactive InputConnection
I/ActivityManager( 1019): Killing 3786:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2179): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/chromium( 3537): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../../lib/thali-tape'\nError: Cannot find module '../../lib/thali-tape'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1604:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js:10:12\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:9:9\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:6:1\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:63:3\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:253:5\n    at JXMobile.executeJSON@main.js:272:7\n    at @JX_Evaluate:1:1\n    "", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4140 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3848:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3439): GC_CONCURRENT freed 630K, 5% free 16453K/17224K, paused 3ms+1ms, total 39ms
,D/dalvikvm( 3439): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dalvikvm-heap( 3439): Grow heap (frag case) to 19.836MB for 1821008-byte allocation
,I/ContactLocale( 4103): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4140): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4140): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x000d
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect called
I/jxcore-log( 3537): 
,D/Finsky  ( 4140): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4140): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4140): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4140): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4140): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2179): UpdateCorporaTask done [took 287 ms] updated apps [took 287 ms] 
,D/Finsky  ( 4140): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4140): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4140): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4140): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4140): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4140): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4140): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4140): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4140): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x0392
I/dalvikvm( 4140): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4140): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x0398
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4182 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4140): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4140): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4140): Skipping gmscore version check
,D/Finsky  ( 4140): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4140): [1] 2.run: Finished loading 1 libraries.
,I/dalvikvm( 4140): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4140): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4140): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1019): Killing 3933:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1341): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1341): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1341): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4182): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fdd168, skipping init
I/openssl ( 4182): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4182): Crypto mode 0 already enabled
,D/Finsky  ( 4140): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4140): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1019): Killing 4014:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{421ba928 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{4218c270 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d0c420 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43dc0318 type 3 android}
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43e0e6e8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): got start_tests event with data : {"data":{"devices":{"ios":3,"android":16}}}
I/jxcore-log( 3537): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): {"type":"end","test":0}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1447848880681},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":1}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":2}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":3}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":3}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":4}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":5}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":6},
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":6}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":7}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":8}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":9}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":9}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: 4sO6s8lriSftpNlITD6OgA==;Matt
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":32957,"expected":32957,"test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"4sO6s8lriSftpNlITD6OgA==;Matt","expected":"4sO6s8lriSftpNlITD6OgA==;Matt","test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":10}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":11}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":12}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":12}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":13}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: 4gmc0sfjERtfz8K1wgEm2A==;Toby
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":40609,"expected":40609,"test":13,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"4gmc0sfjERtfz8K1wgEm2A==;Toby","expected":"4gmc0sfjERtfz8K1wgEm2A==;Toby","test":13,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,V/AlarmManager( 1019): sending alarm Alarm{42840f68 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42187fe8 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4236 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3889:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3537): {"type":"end","test":14}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":15}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":15}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: PfOQ+ncv/bGIlVUXCRbw2A==;Luke
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":60206,"expected":60206,"test":16,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"PfOQ+ncv/bGIlVUXCRbw2A==;Luke","expected":"PfOQ+ncv/bGIlVUXCRbw2A==;Luke","test":16,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":16}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":17}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":18}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":18}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: AcC10/BVng3/uc8uBYR/4Q==;Jukka
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":55042,"expected":55042,"test":19,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"AcC10/BVng3/uc8uBYR/4Q==;Jukka","expected":"AcC10/BVng3/uc8uBYR/4Q==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":19}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":20}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":21}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":21}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: geljZXSwJlgE6TAxEG7sRw==;Doug
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":49121,"expected":49121,"test":22,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"geljZXSwJlgE6TAxEG7sRw==;Doug","expected":"geljZXSwJlgE6TAxEG7sRw==;Doug","test":22,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":22}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":23}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":24}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":24}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: ootbHK0++nW49/B8qtZxww==;David
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":58864,"expected":58864,"test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"ootbHK0++nW49/B8qtZxww==;David","expected":"ootbHK0++nW49/B8qtZxww==;David","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: ootbHK0++nW49/B8qtZxww==;David
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":58864,"expected":58864,"test":25,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"ootbHK0++nW49/B8qtZxww==;David","expected":"ootbHK0++nW49/B8qtZxww==;David","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":25}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): {"type":"end","test":26}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":27}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): {"type":"end","test":27}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":395392,"expected":395392,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":587392,"expected":587392,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":172032,"expected":172032,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":932032,"expected":932032,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==,
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":852096,"expected":852096,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":802176,"expected":802176,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":654336,"expected":654336,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":52992,"expected":52992,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":174464,"expected":174464,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":436096,"expected":436096,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: sOura5m1WEPz8fAmwslRdA==;John
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":45785,"expected":45785,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"sOura5m1WEPz8fAmwslRdA==;John","expected":"sOura5m1WEPz8fAmwslRdA==;John","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO identityExchange We will advertise the following device name as we start: v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":56280,"expected":56280,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","expected":"v1oXfaiKHXjn9OxFrAnrbQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/cb request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3537): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO smallerHash Making /identity/rnmine request to pkOther value v1oXfaiKHXjn9OxFrAnrbQ==
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":447040,"expected":447040,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":28}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":29}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":30}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":30}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":31}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":32}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":33}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":33}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":34}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":35}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":36}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":36}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,E/jxcore-log( 3537): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3537): 
,E/jxcore-log( 3537): Trace: 
E/jxcore-log( 3537):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 3537):     at addListener@events.js:140:7
E/jxcore-log( 3537):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 3537):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3537):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3537):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3537):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3537):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 3537): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3537): 
,E/jxcore-log( 3537): Trace: 
E/jxcore-log( 3537):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 3537):     at addListener@events.js:140:7
E/jxcore-log( 3537):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 3537):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3537):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3537):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3537):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3537):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
I/jxcore-log( 3537): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":37}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":38}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":39}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":39}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"qN0eOkSDq3QM+oiCXP0H1Q==","expected":"qN0eOkSDq3QM+oiCXP0H1Q==","test":40,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":40}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":41}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":42}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":42}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"I28NGYnUdLIpNmfFSKJB0A==","expected":"I28NGYnUdLIpNmfFSKJB0A==","test":43,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":43}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":44}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":44}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":45}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,V/AlarmManager( 1019): sending alarm Alarm{4323e2c8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): {"type":"end","test":45}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"zjGpZD/3N3TXqTB+Ptq0ZA==","expected":"zjGpZD/3N3TXqTB+Ptq0ZA==","test":46,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":46}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":47}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":48}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":48}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"s3LKSLZ8Uyv54rzi+HTaDQ==","expected":"s3LKSLZ8Uyv54rzi+HTaDQ==","test":49,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":49}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): {"type":"end","test":50}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":51}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":51}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"uecxMylw7Kk4Yj6Yy0WmoA==","expected":"uecxMylw7Kk4Yj6Yy0WmoA==","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:36328/identity/cb","data":{"cbValue":"JSobYciQy81JaSyBKbtorv5I6+zg0V402S8st7NTUrw=","pkMine":"obblIQE61fGHxyEeOlqH/A=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-jpHpQ85Q6D7U2o60fMd6xw\"","date":"Wed, 18 Nov 2015 12:16:14 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"uecxMylw7Kk4Yj6Yy0WmoA==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"uecxMylw7Kk4Yj6Yy0WmoA==","expected":"uecxMylw7Kk4Yj6Yy0WmoA==","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:35126/identity/rnmine","data":{"rnMine":"1mbseAWutDJTuxHFh1LSuQ==","pkOther":"0cZBVvYw85x2QuvPw1/52A=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-jpHpQ85Q6D7U2o60fMd6xw\"","date":"Wed, 18 Nov 2015 12:16:14 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"uecxMylw7Kk4Yj6Yy0WmoA==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"uecxMylw7Kk4Yj6Yy0WmoA==","expected":"uecxMylw7Kk4Yj6Yy0WmoA==","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:49811/identity/cb","data":{"cbValue":"xh8qf4rqlBbQYztMsuIw9eoW38gftaJxBZwUjuZOWBs=","pkMine":"ULNLP1pMuusNELUaLsPYrA=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-jpHpQ85Q6D7U2o60fMd6xw\"","date":"Wed, 18 Nov 2015 12:16:14 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"uecxMylw7Kk4Yj6Yy0WmoA==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"uecxMylw7Kk4Yj6Yy0WmoA==","expected":"uecxMylw7Kk4Yj6Yy0WmoA==","test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":52}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":53}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":54}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":54}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"jBGsHjTl30mFcjg4GTLx9g=="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"4ig+BNNs0yk6X7MNSclqig=="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"ZEmxveliFF1TB+Y5c7WVzbyDHLuVyeU68dsYcI/dQ6GT","pkMine":"nt5dFcO/nkbjIOdk97vv+A=="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"GUlKd7HZrhK79d9sEb2KMlfElMBemGxXxOE5ijF4DA==","pkMine":"x3RtQK++GeZpiErAlLpH7A=="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"EsbcgLNm1R7MULySq3w3/lFFLAYUK4nnQSgc601lhx8=","pkMine":" "}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"rQXV2aQJ6Bp04X693h5UIZZYT/+h55OsDaEmni4YW3s=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"taO/Wmca+IQXu3486UMcE2rK3JJqNhmC09f0KYYCDrk=","pkMine":"ZBl9SdJkxKfupK+uF2w8HJw="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"UxnO8AniRcGmr+DfYWvCVsfYNJvcdZ8jXg/cKlpYTkA=","pkMine":"Tc9jLMCQ0lZzkbdyH7Fh"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"ZBl9SdJkxKfupK+uF2w8HJw="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"Tc9jLMCQ0lZzkbdyH7Fh"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"ZBl9SdJkxKfupK+uF2w8HJw="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"Tc9jLMCQ0lZzkbdyH7Fh"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ZEmxveliFF1TB+Y5c7WVzbyDHLuVyeU68dsYcI/dQ6GT","pkMine":" "}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ZEmxveliFF1TB+Y5c7WVzbyDHLuVyeU68dsYcI/dQ6GT","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ZEmxveliFF1TB+Y5c7WVzbyDHLuVyeU68dsYcI/dQ6GT","pkMine":"ZBl9SdJkxKfupK+uF2w8HJw="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ZEmxveliFF1TB+Y5c7WVzbyDHLuVyeU68dsYcI/dQ6GT","pkMine":"Tc9jLMCQ0lZzkbdyH7Fh"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"GUlKd7HZrhK79d9sEb2KMlfElMBemGxXxOE5ijF4DA==","pkMine":" "}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"GUlKd7HZrhK79d9sEb2KMlfElMBemGxXxOE5ijF4DA==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"GUlKd7HZrhK79d9sEb2KMlfElMBemGxXxOE5ijF4DA==","pkMine":"ZBl9SdJkxKfupK+uF2w8HJw="}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"GUlKd7HZrhK79d9sEb2KMlfElMBemGxXxOE5ijF4DA==","pkMine":"Tc9jLMCQ0lZzkbdyH7Fh"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): INFO largerHash Got a /identity/cb request with a bum pkMine - {}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): ,
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!,
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"18AahBHjedtf8nu/MGGRug==","expected":"18AahBHjedtf8nu/MGGRug==","test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":55}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":56}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":57}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":57}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"TdWRlSg+HcOVrRU94j6qog==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"o96hB9vZji/GXraevOnXZQ==","expected":"o96hB9vZji/GXraevOnXZQ==","test":58,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"TdWRlSg+HcOVrRU94j6qog==","test":58,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"o96hB9vZji/GXraevOnXZQ==","expected":"o96hB9vZji/GXraevOnXZQ==","test":58,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"o96hB9vZji/GXraevOnXZQ==","expected":"o96hB9vZji/GXraevOnXZQ==","test":58,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":58}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":59}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":60}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":60}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther","id":61}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"jVU+ZrPuOiNnDF2DAc0gPA==","expected":true,"test":61,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"WZSf9Abmsf37Nq0Cuw9TGw==","test":61,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[89,148,159,244,6,230,177,253,251,54,173,2,187,15,83,27],"expected":true,"test":61,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":381184,"expected":381184,"test":61,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":61}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":62}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":62}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":63}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":63}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"do a successful cb and successful rnmine and then repeat the rnmine","id":64}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"eiZvCAXhB6YrIJA3U6hEaA==","expected":true,"test":64,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[122,38,111,8,5,225,7,166,43,32,144,55,83,168,68,104],"expected":true,"test":64,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":827968,"expected":827968,"test":64,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":64}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"teardown","id":65}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":65}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":66}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":66}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"do a rnmine without a cb","id":67}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":67,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"Mw8QPJlgaSfOFDxhlxEm4w==","expected":"Mw8QPJlgaSfOFDxhlxEm4w==","test":67,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":67,"type":"assert"}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"end","test":67}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): {"type":"test","name":"teardown","id":68}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"end","test":68}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): {"type":"test","name":"setup","id":69}
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{432590a0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{436aa790 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4217cf68 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1019): GC_CONCURRENT freed 1986K, 65% free 18062K/50324K, paused 26ms+10ms, total 121ms
,V/AlarmManager( 1019): sending alarm Alarm{43ddd4e8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{443bf1d8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{443ac290 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4435ca48 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44355f70 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44101518 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{440e4c18 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42808f18 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4211adb8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42644780 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42114110 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{422094c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{433e01d0 type 1 com.android.deskclock}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1355): GC_CONCURRENT freed 1609K, 37% free 10986K/17224K, paused 3ms+6ms, total 57ms
,D/UdcCache:FPQuery( 1341): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1019): sending alarm Alarm{43a4f1c0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/AlarmManager( 1019): sending alarm Alarm{435d1500 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42337250 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43ceca68 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42337cb8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43e4a028 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{433cd928 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4318be80 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{4316adf8 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{4316ae48 type 0 com.google.android.gms}
,I/ProcessStatsService( 1019): Prepared write state in 13ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-11-17-18-44-01.bin
I/EventLogService( 1341): Aggregate from 1447848615286 (log), 1447848346330 (data)
V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1341): GC_CONCURRENT freed 1986K, 33% free 11680K/17224K, paused 3ms+4ms, total 41ms
,V/AlarmManager( 1019): sending alarm Alarm{436727b0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d18c90 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4310b1d0 mBinding = false
,W/Settings( 1251): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1019): Message: 2
D/BluetoothManagerService( 1019): Sending off request.
D/BluetoothAdapterState( 3583): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3583): Setting state to 13
I/BluetoothAdapterState( 3583): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3583): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3583): onBluetoothDisable()
I/BluetoothAdapterState( 3583): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3583): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3583): Scan Mode:21
D/BluetoothAdapterState( 3583): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3583): bta_jv_rfcomm_stop_server
D/btif_config_util( 3583): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 3583): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3583): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3583): bta_jv_rfcomm_stop_server
E/bt-btif ( 3583): bta_jv_rfcomm_stop_server
E/bt-btif ( 3583): bta_jv_rfcomm_stop_server
W/bt-btif ( 3583): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3583): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3583): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3583): onReceive
,D/BluetoothMapService( 3583): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 3583): MAP Service closeService in
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4421 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,W/Settings( 1251): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/BtOppRfcommListener( 3583): stopping Accept Thread
,I/BtOppRfcommListener( 3583): BluetoothSocket listen thread finished
,W/Settings( 1251): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,W/Settings( 1251): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  594): NL - Read 60 bytes from update socket.
D/TCMD    (  594): NL - ignore NL message, type = 21
D/TCMD    (  594): Listening for incoming client connection request
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1019): connected time updated 1633402
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
I/jxcore-log( 3537): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":69,"type":"assert"}
I/jxcore-log( 3537): 
I/jxcore-log( 3537): LogCallback not set !!!!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x61269ff8 clazz=0x97100001 iface=wlan0 mask=0x3
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,V/NativeCrypto( 1355): Read error: ssl=0x62da5800: I/O error during system call, Connection timed out
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothPbapService( 3583): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42096260:true
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
V/NativeCrypto( 1355): SSL shutdown failed: ssl=0x62da5800: I/O error during system call, Broken pipe
D/CommandListener(  272): Clearing all IP addresses on wlan0
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): stopping supplicant
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): setWifiState: disabling
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
I/SBar.NetworkController( 1083): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/bt-btif ( 3583): ag scb idx 1 not allocated
E/bt-btif ( 3583): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3583): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3583): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3583): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3583): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3583): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3583): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_hwcfg( 3583): hw_epilog_process
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): Active network info is not available
E/XTCC-3.0.0.2(  596): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  596): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  596): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  596): [CSMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): Message: 30
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): Message: 30
I/bt_hwcfg( 3583): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3583): bt_hc_worker_thread exiting
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/bt_userial_mct( 3583): userial_close
I/bt_userial_mct( 3583): exiting userial_read_thread
D/bt_userial_mct( 3583): Leaving userial_evt_read_thread()
,I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=null
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
,W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/LocalBluetoothProfileManager( 4421): Adding local MAP profile
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,D/BluetoothMap( 4421): Create BluetoothMap proxy object
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1019): Message: 30
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
,D/BluetoothManagerService( 1019): Message: 30
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
,W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/LocalBluetoothProfileManager( 4421): LocalBluetoothProfileManager construction complete
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/DockEventReceiver( 4421): finishStartingService: stopping service
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 68 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
D/TCMD    (  594): NL - Read 68 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
I/wpa_supplicant( 3653): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/Tethering( 1019): InitialState.processMessage what=4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: X
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/wpa_supplicant( 3653): eap_proxy Deinitialzed
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
D/TCMD    (  594): Listening for incoming client connection request
I/wpa_supplicant( 3653): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  274): wifi_close_sockets: Exit
I/wpa_supplicant( 3653): CTRL_IFACE monitor[0]: 2 - No such file or directory
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): Supplicant connection lost
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
D/BluetoothInputDevice( 4421): Proxy object connected
D/HidProfile( 4421): Bluetooth service connected
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothPan( 4421): BluetoothPAN Proxy object connected
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
V/BluetoothFtpReceiver( 3583): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/PanProfile( 4421): Bluetooth service connected
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMap( 4421): Proxy object connected
D/MapProfile( 4421): Bluetooth service connected
D/BluetoothMap( 4421): getConnectedDevices()
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
D/BluetoothMap( 4421): Bluetooth is Not enabled
I/ActivityManager( 1019): Killing 4071:com.google.android.talk/u0a70 (adj 15): empty #9
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BTSNOOP-DISP( 3583): btsnoop_close
I/bt_vendor( 3583): cleanup
I/bt_hwcfg( 3583): Starting hciattach daemon
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/bt_hwcfg( 3583): try to set false
I/GKI_LINUX( 3583): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
I/GKI_LINUX( 3583): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 3583): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 3583): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetService( 3583): Received stop request...Stopping profile...
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothHeadset( 1019): Proxy object disconnected
D/BluetoothHeadset( 1238): Proxy object disconnected
D/BluetoothHeadset( 1238): Proxy object disconnected
D/BluetoothHeadset( 1238): Proxy object disconnected
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/A2dpService( 3583): Received stop request...Stopping profile...
D/A2dpStateMachine( 3583): Exit Disconnected: -1
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
D/BluetoothA2dp( 1019): Proxy object disconnected
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3583): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidService( 3583): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4421): Proxy object disconnected
D/HidProfile( 4421): Bluetooth service disconnected
D/BluetoothAdapterState( 3583): Stopping profile services that were post enabled
W/BluetoothHeadsetServiceJni( 3583): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3583): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3583): Received stop request...Stopping profile...
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
D/BluetoothAdapterService( 3583): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanService( 3583): Received stop request...Stopping profile...
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 1019): BluetoothPAN Proxy object disconnected
E/BluetoothTethering( 1019): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1019): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43a2fd80
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 4421): BluetoothPAN Proxy object disconnected
D/PanProfile( 4421): Bluetooth service disconnected
I/GKI_LINUX( 3583): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3583): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3583): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BtGatt.DebugUtils( 3583): handleDebugAction() action=null
D/BtGatt.GattService( 3583): Received stop request...Stopping profile...
D/BtGatt.GattService( 3583): stop()
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothAdapterService( 3583): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 3583): Received stop request...Stopping profile...
D/BluetoothMapService( 3583): stop()
D/BluetoothMapService( 3583): MAP Service closeService in
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/BluetoothMap( 4421): Proxy object disconnected
D/MapProfile( 4421): Bluetooth service disconnected
W/BluetoothHidServiceJni( 3583): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3583): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3583): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3583): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
W/BluetoothHealthServiceJni( 3583): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3583): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3583): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3583): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3583): Cleaning up Bluetooth PAN callback object
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
D/BluetoothAdapterService( 3583): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3583): cleanup()
D/BluetoothMapService( 3583): MAP Service closeService in
D/BluetoothAdapterState( 3583): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3583): Setting state to 10
I/BluetoothAdapterState( 3583): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3583): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3583): Entering OffState
D/BluetoothManagerService( 1019): Message: 60
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=false
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothPan( 1019): onBluetoothStateChange on: false
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothPbap( 4421): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothInputDevice( 4421): onBluetoothStateChange: up=false
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/BluetoothMap( 4421): onBluetoothStateChange: up=false
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothPan( 4421): onBluetoothStateChange on: false
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 9 receivers.
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4310b1d0 mBinding = false
D/BluetoothManagerService( 1019): Sending unbind request.
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3583): Cleaning up adapter native....
I/GKI_LINUX( 3583): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3583): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3583): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3583): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3583): Done cleaning up adapter native....
D/BluetoothAdapterService(1107170760)( 3583): ****onDestroy()********
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
I/jxcore-log( 3537): The client has disconnected!
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 13 -> 10
I/jxcore-log( 3537): Turning radios to false
I/jxcore-log( 3537): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3537): toggleBluetooth - 
I/jxcore-log( 3537): 
D/WifiService( 1019): setWifiEnabled: false pid=3537, uid=10382
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapter( 1083): 1108641560: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 3537): toggleWiFi
I/jxcore-log( 3537): 
D/BtGatt.GattService( 3583): cleanup()
W/bt-btif ( 3583): GATTC Module not enabled/already disabled
W/bt-btif ( 3583): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1203): 1110304312: getState() :  mService = null. Returning STATE_OFF
D/WifiStateMachine( 1019): setWifiState: disabled
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1268): Active network info is not available
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
E/XTCC-3.0.0.2(  596): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  596): [WwanPosMgr] handleConnectivtyStatusChange failed
W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothAdapter( 1203): 1110304312: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
I/SBar.NetworkController( 1083): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/Settings( 1203): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DockEventReceiver( 4421): finishStartingService: stopping service
D/BluetoothAdapter( 4421): 1107218136: getState() :  mService = null. Returning STATE_OFF
E/XTCC-3.0.0.2(  596): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  596): [CSMgr] handleConnectivtyStatusChange failed
V/BluetoothFtpReceiver( 3583): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3583): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3583): Ftp Service onDestroy
V/BluetoothFtpService( 3583): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3583): Shutdown
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1019): Killing 4103:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothAdapter( 4421): 1107218136: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4463 uid=10016 gids={50016, 3002}
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,D/Checkin ( 4463): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager( 1019): Killing 4123:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
D/TCMD    (  594): NL - Read 444 bytes from update socket.
D/TCMD    (  594): NL - ignore NL message, type = 17
D/TCMD    (  594): Listening for incoming client connection request
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  274): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  594): NL - Read 1000 bytes from update socket.
D/TCMD    (  594): NL - message type is RTM_NEWLINK
,D/TCMD    (  594): Listening for incoming client connection request
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
D/TCMD    (  594): NL - Read 444 bytes from update socket.
D/TCMD    (  594): NL - ignore NL message, type = 17
D/TCMD    (  594): Listening for incoming client connection request
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  274): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  274): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  274): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
I/jxcore-log( 3537): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3537): 
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,D/PollingManager( 1537): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1537): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1537): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/PollingManager( 1537): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1537): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1537): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1537): [debug] > CusSM.onRadioDown
,E/ActivityThread( 1537): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4497 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,V/MmsConfig( 4497): mnc/mcc: 
V/MmsConfig( 4497): tag: bool value: enabledMMS - true
V/MmsConfig( 4497): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4497): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4497): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4497): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4497): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4497): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4497): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4497): tag: int value: recipientLimit - 20
V/MmsConfig( 4497): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4497): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4497): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4497): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4497): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4497): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4497): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4497): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4497): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4520 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3537:com.test.thalitest/u0a382 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4520): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4520): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4520): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4520): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4534 uid=10056 gids={50056, 3003, 1028, 1015}
I/ActivityManager( 1019): Killing 3439:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4548 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4140:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4548): Binding Chromium to main looper Looper (main, tid 1) {41fd29d8}
,I/LibraryLoader( 4548): Expected native library version number "",actual native library version number ""
,I/chromium( 4548): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4548): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4548): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4548): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4548): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4548): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4548): Local Branch: 
I/Adreno-EGL( 4548): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4548): Local Patches: NONE
I/Adreno-EGL( 4548): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4548): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4548): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4548): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4548): Starting up...
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4593 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4236:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1019): GC_EXPLICIT freed 2014K, 65% free 18035K/50324K, paused 10ms+10ms, total 97ms
,I/ImageResourceManager( 4593): ImageResourceManager: uninitalized
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4611 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/iu.Environment( 4593): update battery state; isPlugged? true*
I/iu.Environment( 4593): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 4593): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1019): Killing 3583:com.android.bluetooth/1002 (adj 15): empty #9
W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4421:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1251): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1341): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/WifiService( 1019): Client connection lost with reason: 4
I/iu.UploadsManager( 1341): num queued entries: 0
D/DEBUG   ( 1537): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/iu.UploadsManager( 1341): num updated entries: 0
W/ContextImpl( 1537): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1537): bindWebServices(): registering our AIDL callback...
I/iu.SyncManager( 1341): NEXT; no task
D/EmailService.MarketingOptInSetter( 1537): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1537): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1537): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1537): onServiceConnected()
D/GetNotificationsWS( 1537): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1537): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4520): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4520): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4593): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/dalvikvm( 4593): GC_FOR_ALLOC freed 388K, 5% free 16403K/17224K, paused 16ms, total 16ms
,I/dalvikvm-heap( 4593): Grow heap (frag case) to 19.788MB for 1821008-byte allocation
,I/iu.UploadsManager( 4593): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 4593): GC_FOR_ALLOC freed 13K, 5% free 18182K/19004K, paused 11ms, total 12ms
,I/iu.UploadsManager( 4593): End new media; added: 0, uploading: 0, time: 56 ms
,I/iu.FingerprintManager( 4593): Start processing all media
,I/iu.FingerprintManager( 4593): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4593): Start processing media store URI: content://media/external/video/media
,I/ContactLocale( 4611): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/iu.FingerprintManager( 4593): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4593): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 4593): Finished generating fingerprints; 0.024 seconds
,I/iu.FingerprintManager( 4593):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/WifiP2pService( 1019): P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{43e91770 type 2 com.android.keyguard}

```
